---
unique-page-id: 45417125
description: 네이티브 Salesforce 통합을 위한 Sales Insight - Marketing To Docs - 제품 설명서
title: 네이티브 Salesforce 통합을 위한 세일즈 인사이트
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '1270'
ht-degree: 0%

---


# 네이티브 Salesforce 통합을 위한 세일즈 인사이트 {#sales-insight-for-non-native-salesforce-integrations}

Marketing To 계정이 사용자 지정 또는 비기본 통합을 통해 Salesforce에 연결된 경우 이 문서를 사용하여 Sales Insight를 구성합니다.

>[!NOTE]
>
>**사전 요구 사항**
>
>* Marketing To 인스턴스에 대해 &quot;MSI Non-Native&quot; 기능을 활성화하려면 고객 성공 관리자에게 문의하십시오.
>* MSI 패키지 설정이 있는 Salesforce 계정.
>* Marketing REST API를 [설정했습니다](http://developers.marketo.com/rest-api/). 노출된 CRUD API는 비기본 동기화를 수행하는 기반이 됩니다.
>* 개체 및 관계를 이해하려면 [이 블로그 게시물을](http://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/) 읽어 보십시오.
>* 대/소문자를 구분하는 15자의 전역 고유 식별자가 아니라 18자의 대/소문자를 구분하지 않는 전역 고유 식별자를 표시하도록 Salesforce 개체를 설정합니다.

>



>[!NOTE]
>
>Marketing MSI 관리 패널의 REST API 구성은 기본 동기화가 아닌 동기화에 사용할 수 없습니다.

## MSI에 대한 비기본 동기화에 성공하려면 다음이 필요합니다. {#successful-non-native-sync-for-msi-requires-the-following}

1. Salesforce 세일즈 사용자를 Marketing Cloud에 동기화합니다.

   Salesforce 영업 사용자는 Salesforce의 리드/연락처를 소유한 외부 사용자입니다. Salesforce 세일즈 사용자를 위해 영업 담당자를 업데이트해야 합니다. 영업 담당자의 *업사이드에 대해 externalSalesPersonId* 필드가 필수적입니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>마케팅 영업 사원 필드</strong></td> 
   <td><strong>Salesforce 영업 사용자 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce 세일즈 사용자 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td><p>외부 Salesforce Sales User 개체에 대한 Marketing To Sales Person 레코드를 식별합니다.</p><p>다른 개체를 동기화하기 전에 영업 담당자가 먼저 동기화되어야 적절한 관계가 생성됩니다.</p></td> 
  </tr> 
 </tbody> 
</table>

영업 담당자를 위한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](http://developers.marketo.com/rest-api/lead-database/sales-persons/)\
영업 사원 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsPOST 사용](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsPOST 사용)

1. Salesforce 계정을 Marketing Cloud에 동기화합니다.

   Salesforce 계정을 사용하려면 Marketing Company를 업데이트해야 합니다. 회사 *업사이드에 대해* externalCompanyId *및* externalSalesPersonId필드가 필수적입니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>마케팅 회사 필드</strong></td> 
   <td><strong>Salesforce 계정 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>외부 Salesforce 계정 개체에 대한 마케팅 회사 레코드를 식별합니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce 세일즈 사용자 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>계정 소유자인 외부 Salesforce 세일즈 사용자 개체에 대한 마케팅 회사 레코드를 식별합니다.<br><br>또한 Marketing To 내에서 회사를 회사 레코드를 소유한 영업자와 연관시키는 데 사용됩니다. 이 필드를 설정하기 전에 먼저 영업 담당자를 동기화해야 합니다.</td> 
  </tr> 
 </tbody> 
</table>

기업을 위한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/companies/](http://developers.marketo.com/rest-api/lead-database/companies/)\
`API documentation for syncing Companies:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST)`

1. Salesforce 리드/연락처를 Marketing Cloud에 동기화합니다.

   Salesforce 리드/연락처에 대한 마케팅 리드를 업데이트해야 합니다. 리드 *업사이드에 대해* externalPersonId *,* externalSalesPersonId *및* externalCompanyId필드는 필수 항목입니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>마케팅 리드 필드</strong></td> 
   <td><strong>Salesforce 리드/연락처 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalPersonId</td> 
   <td>Salesforce 리드/연락처 대/대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>외부 Salesforce 리드/연락처 개체에 대한 마케팅 리드 레코드를 식별합니다.<br><br>MSI Non-Native에 도입된 새로운 필드입니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce 세일즈 사용자 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>이 리드/연락처를 소유한 외부 Salesforce 영업 사용자 개체를 식별합니다.<br><br>또한 Marketing의 영업 담당자와 리드를 연관시킵니다. 영업 담당자가 먼저 올바로 동기화되어야 합니다.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>리드/연락처가 속하는 외부 Salesforce 계정 개체를 식별합니다.<br><br>또한 리드 레코드를 Marketing의 회사와 연관시킵니다. 먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
  </tr> 
 </tbody> 
</table>

리드에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/leads/`](http://developers.marketo.com/rest-api/lead-database/leads/)\
리드 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST)

1. Salesforce 기회를 Marketing Cloud와 동기화

   Salesforce Opportunity에 대한 Marketing To Opportunity를 업데이트해야 합니다. Opportunity를 업데이트하려면 *externalOpportunityId*, *externalCompanyId*&#x200B;및 *externalSalesPersonId* 필드가 필수항목입니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketing To Opportunity 객체 필드</strong></td> 
   <td><strong>Salesforce Opportunity 개체 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce 리드/연락처 대/대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>외부 Salesforce Opportunity 개체에 대한 Marketing To Opportunity 레코드를 식별합니다.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>이 Opportunity 가 속한 외부 Salesforce 계정 개체를 식별합니다. <br><br>먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce 세일즈 사용자 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>이 영업 기회를 소유한 외부 Salesforce 영업 사용자 개체를 식별합니다. </td> 
  </tr> 
 </tbody> 
</table>

기회에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](http://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Salesforce 연락처 역할을 Marketing Cloud에 동기화할 수 있습니다.

   그런 다음 Salesforce Opportunity의 Salesforce 연락처 역할을 Marketing to Opportunity 역할을 통해 동기화할 수 있습니다. [기회 역할] 레코드는 *externalOpportunityId*, *역할*&#x200B;및 *leadId* 필드를지정합니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>마케팅 기회 역할 필드</strong></td> 
   <td><strong>Salesforce 연락처 역할 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce Opportunity는 대/소문자를 구분하지 않는 전역 고유 식별자입니다.</td> 
   <td>외부 Salesforce 기회 개체에 대한 Marketing to Opportunity 역할을 식별합니다.<br><br>Salesforce Opportunity가 먼저 올바로 동기화되어야 합니다.</td> 
  </tr> 
  <tr> 
   <td>leadId</td> 
   <td>해당 사항 없음, 마케팅 대상 리드 ID일 수 있습니다.</td> 
   <td>동기화된 Salesforce 연락처의 마케팅 리드 ID입니다.<br><br>연락처가 Marketing To에 동기화되면 Salesforce 연락처 대/소문자를 구분하지 않는 고유 식별자를 externalPersonId로 사용하고 Marketing to REST API를 사용하여 Marketing To Lead에 대해 쿼리할 수 있습니다.</td> 
  </tr> 
  <tr> 
   <td>역할</td> 
   <td>Salesforce 연락처의 역할 필드</td> 
   <td>이 기회의 담당자 역할을 설명합니다.</td> 
  </tr> 
 </tbody> 
</table>

기회에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](http://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. 마지막 관심 모멘트/MSI 점수 필드 동기화를 SFDC에 연결합니다.

   Salesforce 개체가 Marketing To에 올바르게 동기화되면 MSI 기능을 활용할 수 있습니다. MSI 마지막 관심 영역/점수 필드가 리드에 대한 REST API에 표시됩니다. 이러한 필드는 MSI로 계산되며 읽기 전용입니다.

   마케팅 리드의 마지막 관심 영역/점수 필드는 REST API 리드 끝점을 사용하여 Salesforce에 정기적으로 동기화되어야 합니다. filterType으로 *externalPersonId* 를 사용하여 마케팅 리드에 대해 이 끝점을 쿼리하고 Salesforce 리드 GUID를 filterValue로 전달합니다.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=salesforceLeadId1,salesforceLeadId2 |
   |---|

   그런 다음 이러한 필드 값을 사용하여 Salesforce 리드/연락처 개체에 동기화할 수 있습니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>마케팅 리드 필드</strong></td> 
   <td><strong>Salesforce 리드/연락처 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentType</td> 
   <td>레이블:마지막 관심 모멘트<br>유형:Last_Interest_Moment_Type__c</td> 
   <td>리드에 대한 마지막 관심 부분 유형</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentDate</td> 
   <td><p>레이블:마지막 흥미로운 순간 날짜</p><p>이름:Last_Interest_Moment_Date__c</p></td> 
   <td>리드에 대한 마지막 흥미로운 날짜</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentDesc</td> 
   <td><p>레이블:마지막 흥미로운 순간 설명</p><p>이름:Last_Interest_Moment_Desc__c</p></td> 
   <td>리드의 마지막 흥미로운 순간에 대한 설명</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentSource</td> 
   <td><p>레이블:마지막 흥미로운 순간 출처</p><p>이름:Last_Interest_Moment_Source__c</p></td> 
   <td>리드의 마지막 흥미로운 순간의 출처</td> 
  </tr> 
  <tr> 
   <td>우선 순위</td> 
   <td><p>레이블:참여</p><p>이름:우선 순위__c</p></td> 
   <td>리드의 우선 순위</td> 
  </tr> 
  <tr> 
   <td>relativeImmedium</td> 
   <td><p>레이블:상대적 긴급성 값</p><p>이름:Immedium_Value__c</p></td> 
   <td>리드의 상대적 긴급성</td> 
  </tr> 
  <tr> 
   <td>relativeScoring</td> 
   <td><p>레이블:상대 점수 값</p><p>이름:Relative_Score_Value__c</p></td> 
   <td>리드의 상대 점수</td> 
  </tr> 
 </tbody> 
</table>

리드 REST API에 대한 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](http://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET).

외부 필드를 올바르게 사용하는 것이 비기본 동기화에 중요합니다. 일부 보기에서 데이터를 볼 수 없는 경우 특정 필드가 올바로 동기화되지 않았을 수 있습니다. 예를 들어, 리드의 활동과 관심 있는 순간이 계정 아래의 MSI 위젯을 볼 때 표시되지 않는 경우 리드의 회사나 계정이 올바르게 동기화되지 않았을 수 있습니다. 외부 필드를 지정하는 동안 이 리드에 대한 GET 요청을 수행하면 리드가 올바르게 동기화되었는지 확인하는 데 도움이 됩니다. 또한 Marketing의 외부 영업 담당자의 이메일은 Salesforce의 해당 사용자의 이메일과 일치해야 합니다. 이메일이 일치하지 않는 경우 Salesforce의 마케팅 탭에 데이터가 표시되지 않을 수 있습니다.


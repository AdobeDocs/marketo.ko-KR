---
unique-page-id: 45417125
description: 비기본 Salesforce 통합을 위한 Sales Insight - Marketo 문서 - 제품 설명서
title: 비기본 Salesforce 통합을 위한 Sales Insight
exl-id: a771ecdf-c610-44e4-9e93-7fdcc9d79f4b
source-git-commit: 73c5375c6e2ec3b2dce09595be1f61f302ff4c25
workflow-type: tm+mt
source-wordcount: '1300'
ht-degree: 0%

---

# 비기본 Salesforce 통합을 위한 Sales Insight {#sales-insight-for-non-native-salesforce-integrations}

사용자 지정 또는 비기본 통합을 통해 Marketo 계정이 Salesforce에 연결된 경우 이 문서를 사용하여 Sales Insight를 구성합니다.

>[!PREREQUISITES]
>
>* MSI 설정을 시작하기 전에 Marketo 인스턴스에 대해 &quot;MSI Non-Native&quot; 기능이 활성화되었습니다(MSI가 아닌 경우 해당 기능을 이미 구입한 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support)에 문의하십시오. 이 기능을 아직 구입하지 않은 경우 고객 성공 관리자에게 문의하십시오.).
>* [MSI 패키지가 설정된 Salesforce 계정입니다](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md).
>* Marketo REST API [를 성공적으로 설정했습니다. ](https://developers.marketo.com/rest-api/) 노출된 CRUD API는 비기본 동기화를 수행하는 기반이 됩니다.
>* 개체 및 관계를 이해하려면 [이 블로그 게시물](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/)을 읽어 보십시오.
>* Salesforce 개체를 설정하여 15자의 대/소문자를 구분하는 전역 고유 식별자가 아니라 18자의 대/소문자를 구분하지 않는 전역 고유 식별자를 표시합니다.


>[!NOTE]
>
>Marketo MSI 관리 패널의 REST API 구성은 비네이티브 동기화에 사용할 수 없습니다.

## MSI에 대해 네이티브 동기화가 실패하면 다음 항목이 필요합니다 {#successful-non-native-sync-for-msi-requires-the-following}

1. Salesforce 영업 사용자를 Marketo에 동기화합니다.

   Salesforce Sales User는 Salesforce의 Lead/Contact를 소유하는 외부 사용자입니다. Salesforce 판매 사용자를 위해 Marketo 영업 담당자를 업데이트해야 합니다. Sales Person의 업사이드에 대해 *externalSalesPersonId* 필드가 지정됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 영업 담당자 필드</strong></td> 
   <td><strong>Salesforce 영업 사용자 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User 대/소문자를 구분하지 않는 globally Unique Identifier</td> 
   <td><p>외부 Salesforce Sales User 개체에 대해 Marketo Sales Person 레코드를 식별합니다.</p><p>적절한 관계가 생성되도록 다른 객체를 동기화하기 전에 먼저 영업 담당자를 동기화해야 합니다.</p></td> 
  </tr> 
 </tbody> 
</table>

영업 사원에 대한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/)\
영업 담당자 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST)

1. Salesforce 계정을 Marketo에 동기화합니다.

   Salesforce 계정에 대해 Marketo 회사를 업그레이드해야 합니다. _externalCompanyId_ 및 _externalSalesPersonId_ 필드는 회사 업데이트에 대해 지정됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 회사 필드</strong></td> 
   <td><strong>Salesforce 계정 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>외부 Salesforce 계정 개체에 Marketo 회사 레코드를 식별합니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User 대/소문자를 구분하지 않는 globally Unique Identifier</td> 
   <td>계정 소유자인 외부 Salesforce 영업 사용자 개체에 Marketo 회사 레코드를 식별합니다.<br><br>또한 Marketo 내에서 회사를 회사 레코드를 소유한 영업 사원과 연결하는 데 사용됩니다. 이 필드를 설정하기 전에 영업 담당자를 먼저 동기화해야 합니다.</td> 
  </tr> 
 </tbody> 
</table>

회사를 위한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/)\
`API documentation for syncing Companies:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST)`

1. Salesforce 리드/연락처를 Marketo에 동기화합니다.

   Salesforce 리드/연락처에 대한 Marketo 리드를 업데이트해야 합니다. _externalPersonId_, _externalSalesPersonId_ 및 _externalCompanyId_ 필드는 리드의 업데이트에 대해 지정됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 리드 필드</strong></td> 
   <td><strong>Salesforce 리드/연락처 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalPersonId</td> 
   <td>Salesforce Lead/Contact 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>외부 Salesforce 리드/연락처 개체에 Marketo 리드 레코드를 식별합니다.<br><br>MSI Non-Native에 대해 도입된 새 필드입니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User 대/소문자를 구분하지 않는 globally Unique Identifier</td> 
   <td>이 Lead/Contact를 담당하는 외부 Salesforce Sales User 개체를 식별합니다.<br><br>Marketo의 영업 담당자와 가망 고객도 연관됩니다. 먼저 영업 담당자를 올바르게 동기화해야 합니다.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>Lead/Contact가 속한 외부 Salesforce 계정 개체를 식별합니다.<br><br>Marketo의 회사에 대한 리드 레코드도 관련이 있습니다. 먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
  </tr> 
 </tbody> 
</table>

리드에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/leads/`](https://developers.marketo.com/rest-api/lead-database/leads/)\
리드 동기화를 위한 API 설명서:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST)

1. Salesforce 기회를 Marketo에 동기화합니다.

   Salesforce Opportunity에 대한 Marketo Opportunity 를 업데이트해야 합니다. _externalOpportunityId_, _externalCompanyId_ 및 _externalSalesPersonId_ 필드는 Opportunity 업데이트에 대해 지정됩니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 기회 객체 필드</strong></td> 
   <td><strong>Salesforce 기회 객체 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce Lead/Contact 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
   <td>외부 Salesforce Opportunity 객체에 대한 Marketo Opportunity 레코드를 식별합니다.</td> 
  </tr> 
  <tr> 
   <td>externalCompanyId</td> 
   <td>Salesforce 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
   <td>이 Opportunity가 속한 외부 Salesforce 계정 개체를 식별합니다. <br><br>먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
  </tr> 
  <tr> 
   <td>externalSalesPersonId</td> 
   <td>Salesforce Sales User 대/소문자를 구분하지 않는 globally Unique Identifier</td> 
   <td>이 Opportunity 를 소유한 외부 Salesforce Sales User 개체를 식별합니다. </td> 
  </tr> 
 </tbody> 
</table>

Opportunity에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. Salesforce 연락처 역할을 Marketo에 동기화합니다.

   그런 다음 Salesforce Opportunity에 대한 Salesforce 연락처 역할을 Marketo Opportunity 역할을 통해 동기화할 수 있습니다. Opportunity Role 레코드는 _externalOpportunityId_, _role_ 및 _leadId_ 필드를 지정합니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 기회 역할 필드</strong></td> 
   <td><strong>Salesforce 연락처 역할 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>externalOpportunityId</td> 
   <td>Salesforce Opportunity 대/소문자를 구분하지 않는 전역적 고유 식별자</td> 
   <td>외부 Salesforce Opportunity 객체에 대한 Marketo Opportunity 역할을 식별합니다.<br><br>먼저 Salesforce Opportunity 를 올바르게 동기화해야 합니다.</td> 
  </tr> 
  <tr> 
   <td>leadId</td> 
   <td>N/A, Marketo 리드 ID입니다</td> 
   <td>동기화된 Salesforce 연락처의 Marketo 리드 ID입니다.<br><br>연락처가 Marketo에서 동기화되면 Salesforce 연락처 대/소문자를 구분하지 않는 전역 고유 식별자를 externalPersonId로 사용하고 Marketo REST API를 사용하여 Marketo 리드를 쿼리할 수 있습니다.</td> 
  </tr> 
  <tr> 
   <td>역할</td> 
   <td>Salesforce 연락처의 역할 필드</td> 
   <td>이 기회에 대한 연락처의 역할을 설명합니다.</td> 
  </tr> 
 </tbody> 
</table>

Opportunity에 대한 API 설명서: [`https://developers.marketo.com/rest-api/lead-database/opportunities/`](https://developers.marketo.com/rest-api/lead-database/opportunities/)\
`API documentation for syncing Opportunities:  [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunities/syncOpportunitiesUsingPOST)`

1. 마지막 흥미로운 모멘트/MSI 점수 필드를 SFDC에 동기화합니다.

   Salesforce 개체가 Marketo에 올바르게 동기화되면 MSI 기능을 활용할 수 있습니다. MSI Last Interest Moment/Scoring 필드는 Leads를 위한 REST API에 표시됩니다. 이러한 필드는 MSI에 의해 계산되며 읽기 전용입니다.

   Marketo 리드의 마지막 관심사 모멘트/점수 필드는 REST API 리드 엔드포인트를 사용하여 Salesforce에 정기적으로 동기화해야 합니다. FilterType으로 _externalPersonId_&#x200B;을 사용하고 Salesforce 리드 GUID를 filterValue로 전달하여 Marketo 리드에 대해 이 끝점을 쿼리합니다.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=salesforceLeadId1,salesforceLeadId2 |
   |---|

   그런 다음 이러한 필드의 값을 사용하여 Salesforce 리드/연락처 개체에 동기화할 수 있습니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Marketo 리드 필드</strong></td> 
   <td><strong>Salesforce 리드/연락처 필드</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentType</td> 
   <td>레이블: 마지막 흥미로운 모멘트 유형<br>이름: Last_Interest_Moment_Type__c</td> 
   <td>리드에 대한 마지막 흥미로운 순간 유형</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentDate</td> 
   <td><p>레이블: 마지막 흥미로운 모멘트 날짜</p><p>이름: Last_Interest_Moment_Date__c</p></td> 
   <td>리드에 대한 마지막 흥미로운 날짜</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentDesc</td> 
   <td><p>레이블: 마지막 흥미로운 순간 설명</p><p>이름: Last_Interest_Moment_Desc__c</p></td> 
   <td>리드에 대한 마지막 흥미로운 순간에 대한 설명</td> 
  </tr> 
  <tr> 
   <td>msiLastInterestMomentSource</td> 
   <td><p>레이블: 마지막 관심 영역 소스</p><p>이름: Last_Interest_Moment_Source__c</p></td> 
   <td>잠재 고객을 위한 마지막 흥미로운 순간의 출처</td> 
  </tr> 
  <tr> 
   <td>우선순위</td> 
   <td><p>레이블: 참여</p><p>이름: 우선순위__c</p></td> 
   <td>리드의 우선 순위</td> 
  </tr> 
  <tr> 
   <td>relative긴급성</td> 
   <td><p>레이블: 상대적 긴급도 값</p><p>이름: Emergency_Value__c</p></td> 
   <td>리드의 상대적 긴급성</td> 
  </tr> 
  <tr> 
   <td>relativeScorecting</td> 
   <td><p>레이블: 상대 점수 값</p><p>이름: Relative_Score_Value__c</p></td> 
   <td>리드의 상대 점수</td> 
  </tr> 
 </tbody> 
</table>

리드 REST API에 대한 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET).

외부 필드를 올바르게 사용하는 것이 비네이티브 동기화를 성공적으로 수행하는 열쇠입니다. 일부 보기에서 데이터를 보지 못하면 특정 필드가 올바르게 동기화되지 않을 수 있습니다. 예를 들어 리드의 활동과 흥미로운 순간이 계정 아래의 MSI 위젯을 볼 때 표시되지 않는 경우 리드의 회사 또는 계정이 올바르게 동기화되지 않았을 수 있습니다. 외부 필드를 지정하는 동안 이 리드에 대한 GET 요청을 수행하면 리드가 올바르게 동기화되었는지 확인하는 데 도움이 됩니다. 또한 Marketo의 외부 영업자용 이메일은 Salesforce의 해당 사용자에 대한 이메일과 일치해야 합니다. 이메일이 일치하지 않는 경우 Salesforce의 Marketo 탭에 데이터가 표시되지 않을 수 있습니다.

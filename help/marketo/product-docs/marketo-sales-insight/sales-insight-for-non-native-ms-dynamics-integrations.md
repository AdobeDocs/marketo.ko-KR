---
description: 비기본 MS Dynamics 통합을 위한 Sales Insight - Marketo 문서 - 제품 설명서
title: 비네이티브 MS Dynamics 통합을 위한 Sales Insight
source-git-commit: fb663ddf4c0021f258317636fbc7794e8172ab7e
workflow-type: tm+mt
source-wordcount: '1426'
ht-degree: 0%

---

# 비네이티브 MS Dynamics 통합을 위한 Sales Insight {#sales-insight-for-non-native-ms-dynamics-integrations}

사용자 지정 또는 비기본 통합을 통해 Adobe Marketo Engage 계정이 MS Dynamics에 연결된 경우 이 문서를 사용하여 Sales Insight를 구성하십시오.

>[!PREREQUISITES]
>
>* MSI 설정을 시작하기 전에 Marketo 인스턴스에 대해 &quot;MSI Non-Native&quot; 기능이 활성화되었습니다(MSI가 아니고 기능을 이미 구입한 경우, 다음 주소로 문의하십시오 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target=&quot;_blank&quot;} - 이 기능을 아직 구입하지 않았다면 고객 성공 관리자에게 문의하십시오.)
>* MSI 설치([On-prem](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-365.md){target=&quot;_blank&quot;}, [Dynamics Online](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online.md){target=&quot;_blank&quot;}).
>* Marketo REST API [설정](https://developers.marketo.com/rest-api/){target=&quot;_blank&quot;}. 노출된 CRUD API는 비기본 동기화를 수행하는 기반이 됩니다.
>* 읽기 [이 블로그 게시물](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/)개체 및 관계를 이해하기 위해 {target=&quot;_blank&quot;}.


## MSI에 대해 네이티브 동기화가 실패하면 다음 항목이 필요합니다 {#successful-non-native-sync-for-msi-requires-the-following}

1. MS Dynamics Sales 사용자를 Marketo에 동기화합니다.

   MS Dynamics Sales User는 MS Dynamics에서 리드/연락처를 소유하는 외부 사용자입니다. MS Dynamics 영업 사용자를 위해 Marketo 영업 사원을 업데이트해야 합니다. Sales PersonId 필드는 Sales Person의 업사이드에 대해 지정됩니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 영업 담당자 필드</strong></td> 
      <td><strong>MS Dynamics 사용자 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics 사용자 대/소문자를 구분하지 않는 전역 고유 식별자입니다.</td> 
      <td><p>외부 MS Dynamics 사용자 개체에 대해 Marketo Sales Person 레코드를 식별합니다.</p><p>적절한 관계가 생성되도록 다른 객체를 동기화하기 전에 먼저 영업 담당자를 동기화해야 합니다.</p></td> 
     </tr> 
    </tbody> 
   </table>

   * 영업 사원에 대한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/sales-persons/](https://developers.marketo.com/rest-api/lead-database/sales-persons/){target=&quot;_blank&quot;}
   * 영업 담당자 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Sales_Persons/syncSalesPersonsUsingPOST){target=&quot;_blank&quot;}

1. MS Dynamics 계정을 Marketo에 동기화합니다.

   MS Dynamics 계정에 대해 Marketo 회사를 업데이트해야 합니다. 다음 _externalCompanyId_ 및 _externalSalesPersonId_ 이 회사의 업사이징에 대해 필드가 지정됩니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 회사 필드</strong></td> 
      <td><strong>MS Dynamics 계정 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
      <td>외부 MS Dynamics 계정 개체에 Marketo 회사 레코드를 식별합니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales 사용자 대/소문자를 구분하지 않는 전역 고유 식별자입니다.</td> 
      <td>계정 소유자인 외부 MS Dynamics Sales User 개체에 Marketo 회사 레코드를 식별합니다.<br><br>또한 Marketo 내에서 회사를 회사 레코드를 소유한 영업 사원과 연결하는 데 사용됩니다. 이 필드를 설정하기 전에 영업 담당자를 먼저 동기화해야 합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * 회사를 위한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/companies/](https://developers.marketo.com/rest-api/lead-database/companies/){target=&quot;_blank&quot;}
   * 회사 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Companies/syncCompaniesUsingPOST){target=&quot;_blank&quot;}

1. MS Dynamics 리드/연락처를 Marketo에 동기화합니다.

   MS Dynamics 리드/연락처에 Marketo 리드를 업데이트해야 합니다. 다음 _externalPersonId_, _externalSalesPersonId_, 및 _externalCompanyId_ 리드를 업데이트하려면 필드가 필수입니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 리드 필드</strong></td> 
      <td><strong>MS Dynamics 리드/연락처 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalPersonId</td> 
      <td>MS Dynamics Lead/Contact 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 MS Dynamics 리드/연락처 개체에 Marketo 리드 레코드를 식별합니다.<br><br>MSI Non-Native에 대해 도입된 새 필드입니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales 사용자 대/소문자를 구분하지 않는 전역 고유 식별자입니다.</td> 
      <td>이 리드/연락처를 소유한 외부 MS Dynamics Sales User 개체를 식별합니다.<br><br>Marketo의 영업 담당자와 가망 고객도 연관됩니다. 먼저 영업 담당자를 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
      <td>리드/연락처가 속한 외부 MS Dynamics 계정 개체를 식별합니다.<br><br>Marketo의 회사에 대한 리드 레코드도 관련이 있습니다. 먼저 MS Dynamics 계정을 올바르게 동기화해야 합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * 리드에 대한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/leads/](https://developers.marketo.com/rest-api/lead-database/leads/){target=&quot;_blank&quot;}
   * 리드 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/syncLeadUsingPOST){target=&quot;_blank&quot;}

1. MS Dynamics Opportunity를 Marketo에 동기화합니다.

   MS Dynamics Opportunity에 대한 Marketo Opportunity 를 업데이트해야 합니다. 다음 _externalOpportunityId_, _externalCompanyId_, 및 _externalSalesPersonId_ Opportunity 를 갱신하기 위해 필드가 지정됩니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 기회 객체 필드</strong></td> 
      <td><strong>MS Dynamics Opportunity Object 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Lead/Contact 대/소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 MS Dynamics Opportunity 개체에 대해 Marketo Opportunity 레코드를 식별합니다.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>MS Dynamics 계정 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
      <td>이 Opportunity가 속한 외부 MS Dynamics 계정 개체를 식별합니다. <br><br>먼저 MS Dynamics 계정을 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>MS Dynamics Sales 사용자 대/소문자를 구분하지 않는 전역 고유 식별자입니다.</td> 
      <td>이 Opportunity 를 소유한 외부 MS Dynamics Sales User 개체를 식별합니다. </td> 
     </tr> 
    </tbody> 
   </table>

   * Opportunity에 대한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/opportunities/](https://developers.marketo.com/rest-api/lead-database/opportunities/){target=&quot;_blank&quot;}
   * 기회 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunity/syncOpportunityUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunity/syncOpportunityUsingPOST){target=&quot;_blank&quot;}

1. MS Dynamics 연락처 역할을 Marketo에 동기화합니다.

   그런 다음 MS Dynamics Opportunity에 대한 MS Dynamics 연락처 역할을 Marketo Opportunity 역할을 통해 동기화할 수 있습니다. Opportunity Role 레코드는 _externalOpportunityId_, _역할_, 및 _leadId_ 필드.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 기회 역할 필드</strong></td> 
      <td><strong>MS Dynamics 연락처 역할 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>MS Dynamics Opportunity 대/소문자를 구분하지 않는 전역 고유 식별자</td> 
      <td>외부 MS Dynamics Opportunity 개체에 대해 Marketo Opportunity 역할을 식별합니다.<br><br>먼저 MS Dynamics Opportunity 를 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>leadId</td> 
      <td>N/A, Marketo 리드 ID입니다</td> 
      <td>동기화된 MS Dynamics 연락처의 Marketo 리드 ID입니다.<br><br>연락처가 Marketo에서 동기화되면 MS Dynamics 연락처 대/소문자를 구분하지 않는 전역 고유 식별자를 externalPersonId로 사용하고 Marketo REST API를 사용하여 Marketo 리드를 쿼리할 수 있습니다.</td> 
     </tr> 
     <tr> 
      <td>역할</td> 
      <td>MS Dynamics 연락처의 역할 필드</td> 
      <td>이 기회에 대한 연락처의 역할을 설명합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * Opportunity에 대한 API 설명서: [https://developers.marketo.com/rest-api/lead-database/opportunities/](https://developers.marketo.com/rest-api/lead-database/opportunities/){target=&quot;_blank&quot;}
   * 기회 동기화를 위한 API 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunity/syncOpportunityUsingPOST](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Opportunity/syncOpportunityUsingPOST){target=&quot;_blank&quot;}

1. 마지막 흥미로운 모멘트/MSI 점수 필드를 MS Dynamics에 동기화합니다.

   MS Dynamics 개체가 Marketo에 올바르게 동기화되면 MSI 기능을 활용할 수 있습니다. MSI Last Interest Moment/Scoring 필드는 Leads를 위한 REST API에 표시됩니다. 이러한 필드는 MSI에 의해 계산되며 읽기 전용입니다.

   Marketo 리드의 마지막 관심사 모멘트/점수 필드는 REST API 리드 종단점을 사용하여 MS Dynamics에 정기적으로 동기화해야 합니다. 를 사용하여 Marketo 리드에 대해 이 종단점을 쿼리합니다. _externalPersonId_ 를 filterType으로 설정하고 MS Dynamics 리드 GUID를 filterValue로 전달합니다.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=MS DynamicsLeadId1,MS DynamicsLeadId2 |
   |---|

   그런 다음 이러한 필드의 값을 사용하여 MS Dynamics 리드/연락처 개체에 동기화할 수 있습니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 리드 필드</strong></td> 
      <td><strong>MS Dynamics 리드/연락처 필드</strong></td> 
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

   * 리드 REST API에 대한 설명서: [https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Leads/getLeadByIdUsingGET){target=&quot;_blank&quot;}.
   외부 필드를 올바르게 사용하는 것이 비네이티브 동기화를 성공적으로 수행하는 열쇠입니다. 일부 보기에서 데이터를 보지 못하면 특정 필드가 올바르게 동기화되지 않을 수 있습니다. 예를 들어 리드의 활동과 흥미로운 순간이 계정 아래의 MSI 위젯을 볼 때 표시되지 않는 경우 리드의 회사 또는 계정이 올바르게 동기화되지 않았을 수 있습니다. 외부 필드를 지정하는 동안 이 리드에 대한 GET 요청을 수행하면 리드가 올바르게 동기화되었는지 확인하는 데 도움이 됩니다. 또한 Marketo의 외부 영업자용 이메일은 MS Dynamics에서 해당 사용자의 이메일과 일치해야 합니다. 이메일이 일치하지 않는 경우 MS Dynamics의 Marketo 탭에 데이터가 표시되지 않을 수 있습니다.

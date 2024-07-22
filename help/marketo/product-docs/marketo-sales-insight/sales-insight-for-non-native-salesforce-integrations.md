---
unique-page-id: 45417125
description: Sales Insight for Non-Native Salesforce 통합 - Marketo 문서 - 제품 설명서
title: Sales Insight for Non-Native Salesforce 통합
exl-id: a771ecdf-c610-44e4-9e93-7fdcc9d79f4b
feature: Marketo Sales Insights
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '1230'
ht-degree: 0%

---

# Sales Insight for Non-Native Salesforce 통합 {#sales-insight-for-non-native-salesforce-integrations}

Adobe Marketo Engage 계정이 맞춤화된 통합 또는 비원시 통합을 통해 Salesforce에 연결된 경우 이 문서를 사용하여 Sales Insight를 구성하십시오.

>[!PREREQUISITES]
>
>* MSI 설정을 시작하기 전에 Marketo 인스턴스에 대해 &quot;MSI 비기본&quot; 기능이 활성화되었습니다. 그렇지 않고 이미 기능을 구입한 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하십시오. 이 기능을 아직 구입하지 않은 경우 Adobe 계정 팀(계정 관리자)에 문의하십시오.
>* [MSI 패키지가 설정된 Salesforce 계정](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"}.
>* Marketo REST API [설정](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}이(가) 완료되었습니다. 노출된 CRUD API는 비원시 동기화를 수행하는 기초가 됩니다.
>* 개체 및 관계를 이해하려면 [이 블로그 게시물](https://developers.marketo.com/blog/create-and-associate-leads-companies-and-opportunities-with-the-marketo-rest-api/){target="_blank"}을 읽으십시오.
>* Salesforce 개체를 설정하여 15자의 대/소문자 구분 글로벌 고유 식별자가 아닌 18자의 대/소문자를 구분하지 않는 글로벌 고유 식별자를 표시합니다.

>[!NOTE]
>
>Marketo MSI 관리 패널의 REST API 구성은 비기본 동기화에 사용할 수 없습니다.

## MSI에 대한 비원시 동기화가 성공하려면 다음이 필요합니다. {#successful-non-native-sync-for-msi-requires-the-following}

1. Salesforce 영업 사용자를 Marketo에 동기화합니다.

   Salesforce Sales 사용자는 Salesforce의 리드/연락처를 소유하는 외부 사용자입니다. Marketo 영업 사원은 Salesforce 영업 사용자에 대해 업데이트해야 합니다. 영업 직원의 업데이트에 *externalSalesPersonId* 필드가 필요합니다.

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
      <td>Salesforce Sales 사용자 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td><p>외부 Salesforce Sales 사용자 개체에 대한 Marketo Sales Person 레코드를 식별합니다.</p><p>올바른 관계가 만들어지도록 다른 개체를 동기화하기 전에 영업 담당자를 먼저 동기화해야 합니다.</p></td> 
     </tr> 
    </tbody> 
   </table>

   * 영업 직원의 API 설명서: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/sales-persons](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/sales-persons){target="_blank"}
   * 영업 담당자 동기화를 위한 API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Sales-Persons/operation/syncSalesPersonsUsingPOST){target="_blank"}

1. Salesforce 계정을 Marketo에 동기화합니다.

   Salesforce 계정에 대해 Marketo 회사를 업데이트해야 합니다. _externalCompanyId_ 및 _externalSalesPersonId_ 필드는 회사 업데이트에 필수입니다.

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
      <td>Salesforce 계정 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 Salesforce 계정 개체에 대한 Marketo 회사 레코드를 식별합니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>Salesforce Sales 사용자 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>계정 소유자인 외부 Salesforce 영업 사용자 개체에 대한 Marketo 회사 레코드를 식별합니다.<br><br>회사를 회사 레코드를 담당하는 영업 사원과 연결하는 데 Marketo 내에서 사용되었습니다. 이 필드를 설정하기 전에 영업 담당자를 먼저 동기화해야 합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * 회사에 대한 API 설명서: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/companies){target="_blank"}
   * 회사 동기화에 대한 API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Companies/operation/syncCompaniesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Companies/operation/syncCompaniesUsingPOST){target="_blank"}

1. Salesforce 리드/연락처를 Marketo에 동기화합니다.

   Salesforce 리드/연락처에 대한 Marketo 리드를 업데이트해야 합니다. _externalPersonId_, _externalSalesPersonId_ 및 _externalCompanyId_ 필드는 잠재 고객 업데이트에 필수입니다.

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
      <td>Salesforce 리드/연락처 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 Salesforce 리드/연락처 개체에 대한 Marketo 리드 레코드를 식별합니다.<br><br>MSI가 Non-Native인 경우 도입된 새 필드입니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>Salesforce Sales 사용자 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>이 잠재 고객/연락처를 담당하는 외부 Salesforce 판매 사용자 개체를 식별합니다.<br><br>또한 Marketo의 영업 담당자와 잠재 고객을 연결합니다. 영업 담당자를 먼저 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>Salesforce 계정 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>리드/연락처가 속한 외부 Salesforce 계정 개체를 식별합니다.<br><br>잠재 고객 레코드와 Marketo 회사의 연결도 관련되어 있습니다. 먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * 리드에 대한 API 설명서: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads)
   * 잠재 고객 동기화를 위한 API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/syncLeadUsingPOST)

1. Salesforce 영업 기회를 Marketo에 동기화합니다.

   Salesforce 영업 기회에 대해 Marketo 영업 기회를 업데이트해야 합니다. _externalOpportunityId_, _externalCompanyId_ 및 _externalSalesPersonId_ 필드는 영업 기회 업데이트에 필요합니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 영업 기회 개체 필드</strong></td> 
      <td><strong>Salesforce 영업 기회 개체 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>Salesforce 리드/연락처 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 Salesforce Opportunity 개체에 대한 Marketo Opportunity 레코드를 식별합니다.</td> 
     </tr> 
     <tr> 
      <td>externalCompanyId</td> 
      <td>Salesforce 계정 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>해당 영업 기회가 속한 외부 Salesforce 계정 개체를 식별합니다. <br><br>먼저 Salesforce 계정을 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>externalSalesPersonId</td> 
      <td>Salesforce Sales 사용자 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>해당 영업 기회를 소유하고 있는 외부 Salesforce 영업 사용자 개체를 식별합니다. </td> 
     </tr> 
    </tbody> 
   </table>

   * 영업 기회에 대한 API 설명서: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * 기회 동기화를 위한 API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. Salesforce 연락처 역할을 Marketo에 동기화

   그런 다음 Salesforce 영업 기회에 대한 Salesforce 연락처 역할은 Marketo 영업 기회 역할을 통해 동기화할 수 있습니다. 영업 기회 역할 레코드에는 _externalOpportunityId_, _role_ 및 _leadId_ 필드가 필요합니다.

   <table> 
    <colgroup> 
     <col> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>Marketo 영업 기회 역할 필드</strong></td> 
      <td><strong>Salesforce 연락처 역할 필드</strong></td> 
      <td><strong>설명</strong></td> 
     </tr> 
     <tr> 
      <td>externalOpportunityId</td> 
      <td>Salesforce 영업 기회 대소문자를 구분하지 않는 글로벌 고유 식별자</td> 
      <td>외부 Salesforce Opportunity 개체에 대한 Marketo Opportunity 역할을 식별합니다.<br><br>먼저 Salesforce 영업 기회를 올바르게 동기화해야 합니다.</td> 
     </tr> 
     <tr> 
      <td>leadId</td> 
      <td>해당 사항 없음. Marketo 리드 ID입니다.</td> 
      <td>동기화된 Salesforce 연락처의 Marketo 잠재 고객 ID입니다.<br><br>연락처가 Marketo에서 동기화되면 Salesforce 연락처 대/소문자를 구분하지 않는 전역 고유 식별자를 externalPersonId로 사용하고 Marketo REST API를 사용하여 Marketo 잠재 고객을 쿼리할 수 있습니다.</td> 
     </tr> 
     <tr> 
      <td>역할</td> 
      <td>Salesforce 담당자의 역할 필드</td> 
      <td>해당 영업 기회에 대한 연락처의 역할을 설명합니다.</td> 
     </tr> 
    </tbody> 
   </table>

   * 영업 기회에 대한 API 설명서: [https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/opportunities){target="_blank"}
   * 기회 동기화를 위한 API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Opportunities/operation/syncOpportunitiesUsingPOST){target="_blank"}

1. 마지막 관심 순간/MSI 점수 필드를 SFDC에 동기화합니다.

   Salesforce 개체가 Marketo에 올바르게 동기화되면 MSI 기능을 활용할 수 있습니다. MSI 마지막 관심 순간/점수 필드가 리드를 위한 REST API에서 노출됩니다. 이러한 필드는 MSI에서 계산되며 읽기 전용입니다.

   Marketo 리드의 마지막 관심 순간/점수 필드는 REST API 리드 끝점을 사용하여 Salesforce에 정기적으로 동기화해야 합니다. _externalPersonId_&#x200B;을(를) filterType으로 사용하고 Salesforce 리드 GUID를 filterValue로 전달하여 Marketo 리드에 대해 이 끝점을 쿼리합니다.

   | GET /rest/v1/leads.json?filterType=externalPersonId&amp;filterValues=salesforceLeadId1,salesforceLeadId2 |
   |---|

   그런 다음 이러한 필드의 값을 사용하여 Salesforce 리드/연락처 오브젝트와 동기화할 수 있습니다.

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
      <td>msiLastInterestingMomentType</td> 
      <td>레이블: 마지막 관심 순간 유형<br>이름: Last_Interest_Moment_Type__c</td> 
      <td>잠재 고객에 대한 마지막 관심 순간 유형</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestMomentDate</td> 
      <td><p>레이블: 마지막 관심 순간 날짜</p><p>이름: Last_Interest_Moment_Date__c</p></td> 
      <td>잠재 고객의 마지막 관심 순간 날짜</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestMomentDesc</td> 
      <td><p>레이블: 마지막 관심 순간 설명</p><p>이름: Last_Interest_Moment_Desc__c</p></td> 
      <td>잠재 고객에 대한 마지막 관심 순간에 대한 설명</td> 
     </tr> 
     <tr> 
      <td>msiLastInterestMomentSource</td> 
      <td><p>라벨: 마지막 흥미로운 순간 Source</p><p>이름: Last_Interest_Moment_Source__c</p></td> 
      <td>마지막 흥미로운 리드 순간의 Source</td> 
     </tr> 
     <tr> 
      <td>우선 순위</td> 
      <td><p>레이블: 참여</p><p>이름: 우선 순위__c</p></td> 
      <td>잠재 고객의 우선 순위</td> 
     </tr> 
     <tr> 
      <td>relativeUrgency</td> 
      <td><p>레이블: 상대 긴급도 값</p><p>이름: Urgency_Value__c</p></td> 
      <td>잠재 고객의 상대적 긴급도</td> 
     </tr> 
     <tr> 
      <td>상대 점수</td> 
      <td><p>레이블: 상대 점수 값</p><p>이름: Relative_Score_Value__c</p></td> 
      <td>잠재 고객 상대 점수</td> 
     </tr> 
    </tbody> 
   </table>

   리드 REST API 설명서: [https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Leads/operation/getLeadByIdUsingGET){target="_blank"}.

   외부 필드를 적절하게 사용하면 성공적인 비원시 동기화가 가능합니다. 일부 보기에서 데이터를 보지 못하면 특정 필드가 올바르게 동기화되지 않았을 수 있습니다. 예를 들어 잠재 고객의 계정 아래에서 MSI 위젯을 볼 때 잠재 고객의 활동 및 흥미로운 순간이 표시되지 않으면 잠재 고객의 회사 또는 계정이 올바르게 동기화되지 않았을 수 있습니다. 외부 필드를 지정하는 동안 이 잠재 고객에 대한 GET 요청을 수행하면 잠재 고객이 올바르게 동기화되었는지 확인하는 데 도움이 됩니다. 또한 Marketo의 외부 영업 사원에 대한 이메일은 Salesforce의 해당 사용자에 대한 이메일과 일치해야 합니다. 이메일이 일치하지 않는 경우 Salesforce의 Marketo 탭에 데이터가 표시되지 않을 수 있습니다.

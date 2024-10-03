---
description: Salesforce 동기화 백로그 지표 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 백로그 지표
hide: true
hidefromtoc: true
feature: Reporting
source-git-commit: 1cc876285f8d7ac7a21a763dd65da34341341a0e
workflow-type: tm+mt
source-wordcount: '840'
ht-degree: 0%

---

# Salesforce 동기화 백로그 지표  {#salesforce-sync-backlog-metrics}

동기화 백로그는 Salesforce에서 Marketo Engage으로 동기화 보류 중인 레코드를 나타내며 그 반대의 경우도 마찬가지입니다. 백로그가 계속 제어되도록 하면 원활하고 시기 적절한 동기화가 이루어집니다.

>[!NOTE]
>
>백로그에는 동기화 후 업데이트가 보류 중인 숫자가 포함되며 [사용자를 SFDC에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} 또는 [사용자를 Microsoft에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} 흐름 단계와 같은 동기화 흐름 단계에서 수행되는 숫자가 아닙니다.

## 액세스 방법 {#how-to-access}

1. Marketo Engage에서 **관리자** 영역으로 이동합니다.

   스크린샷

1. **Salesforce**&#x200B;을(를) 선택합니다.

   스크린샷

## 동기화 백로그 트렌드 {#sync-backlog-trend}

백로그 트렌드는 지난 5일 동안 기록된 백로그의 변경 사항을 반영합니다. 백로그는 5일 동안 4시간 간격 분산으로 표시됩니다. 따라서 그래프는 하루에 6번, 5일을 30번 간격으로 보여줍니다.

백로그는 x축에서 특정 4시간 간격으로 관찰됩니다. 이 값은 동기화 중인 모든 개체에 사용됩니다. Salesforce의 총 백로그와 동기화 대기 중인 Marketo Engage 수입니다.

스크린샷

## 처리량 및 백로그 동기화 {#sync-throughput-and-backlog}

통계는 지난 24시간 동안 동기화 중인 모든 오브젝트 유형에 대한 처리량 및 백로그 상태를 반영합니다. 객체 유형에는 잠재 고객, 연락처, 계정, 기회, 캠페인, 사용자 및 사용자 정의 객체를 포함하여 동기화 중인 모든 객체가 포함됩니다. 처리량 통계는 15분마다 자동으로 새로 고쳐지지만 새로 고침 아이콘을 사용하여 수동으로 새로 고칠 수 있습니다. 백로그를 매 시간마다 가져옵니다.

>[!NOTE]
>
>통계는 역일이 아니라 순차적으로 업데이트됩니다.

스크린샷

<table><thead>
  <tr>
    <th>필드</th>
    <th>설명</th>
  </tr></thead>
<tbody>
  <tr>
    <td>동기화된 최대 레코드 수/시간</td>
    <td>객체 유형에 대해 지난 24시간 동안 관찰된 시간당 동기화된 최대 레코드 수(최대 처리량)입니다. 24시간 기간은 역일이 아니라 시간에 따라 순환됩니다.</td>
  </tr>
  <tr>
    <td>동기화된 최소 레코드 수/시간</td>
    <td>객체 유형에 대해 지난 24시간 동안 관찰된 시간당 동기화된 최소 레코드 수(최소 처리량)입니다. 24시간 기간은 역일이 아니라 시간에 따라 순환됩니다.</td>
  </tr>
  <tr>
    <td>동기화된 평균 레코드 수/시간</td>
    <td>객체 유형에 대해 지난 24시간 동안 관찰된 시간당 동기화된 평균 레코드 수(최소 처리량)입니다. 24시간 기간은 역일이 아니라 시간에 따라 순환됩니다. 지난 24시간 동안 동기화된 총 레코드 수로 계산됩니다.</td>
  </tr>
  <tr>
    <td>백로그 동기화</td>
    <td>오브젝트 유형에 대해 동기화 보류 중인 레코드의 백로그입니다. 두 방향(Salesforce에서 Marketo Engage으로, 그 반대로)에서 동기화 보류 중인 백로그의 합계입니다. Salesforce의 백로그는 Salesforce에 대한 API 호출을 사용하여 가져오며, Marketo Engage의 백로그는 변경 데이터 로그에서 가져온 통계를 사용하여 계산됩니다. 이것은 매시간마다 계산됩니다. 이 테이블의 다음 두 필드는 백로그가 마지막으로 계산된 시기와 다음 계산 일정을 각각 알려줍니다.</td>
  </tr>
  <tr>
    <td>예상 백로그(시간)</td>
    <td>오브젝트 유형별 백로그를 동기화하는 데 필요한 예상 시간입니다. '시간 당 동기화되는 동기화 백로그/평균 레코드'로 계산됩니다.</td>
  </tr>
  <tr>
    <td>백로그를 마지막으로 가져옴</td>
    <td>마지막 백로그 계산 시간입니다.</td>
  </tr>
  <tr>
    <td>백로그 다음 가져오기</td>
    <td>다음 백로그 계산 시간입니다.</td>
  </tr>
  <tr>
    <td>백로그 상태</td>
    <td>지난 6시간 동안 백로그가 증가했는지 여부를 보여 줍니다. 현재 백로그가 6시간 전에 기록된 백로그보다 큰 경우 '증가'로 유추됩니다. 그렇지 않으면 '보통'으로 표시됩니다. 이는 동기화 처리량이 백로그를 따라잡고 있는지 보여 주기 위한 것입니다.</td>
  </tr>
</tbody></table>

## 동기화 백로그의 원인 {#what-causes-sync-backlogs}

Marketo Engage 측이든 CRM 측이든, 업데이트가 이루어지면 CRM 동기화 주기에 대한 일반 Marketo Engage을 통해 다른 쪽 끝에 있는 정보를 업데이트하도록 레코드가 다시 동기화됩니다. Salesforce의 레코드를 업데이트할 때마다 &#39;SysModStamp&#39;라는 시스템 수정 타임스탬프가 생성됩니다. 이는 동기화 변경을 큐에 추가합니다.

필드 값 변경과 같이 대량의 업데이트가 이루어지면 많은 레코드가 변경되어 새 SysModStamp가 발생합니다. 그런 다음 Marketo Engage과 CRM 간에 많은 사용자 레코드 업데이트를 다시 동기화해야 하며 경우에 따라 일시적인 백로그가 생성됩니다.

## 동기화 백로그 관리 우수 사례 {#best-practices}

**동기화 중인 필드**: 동기화 중인 필드만 동기화해야 합니다. 필드를 변경하면 동기화 백로그가 증가하고 우선 순위가 낮은 필드가 중지되거나 동기화 중인 더 중요한 필드가 느려질 수 있습니다. 동기화 중인 필드를 제거하려면 [Marketo Engage 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하세요.

**중요 필드**: 일부 필드는 자주 업데이트됩니다(예: 통화 변경 대상인 통화 필드). 이러한 필드를 동기화해야 하는지 또는 필드를 다르게 디자인해야 하는지 검토합니다.

**사용자 지정 개체**: 동기화 중인 사용자 지정 개체를 정기적으로 검토하고 더 이상 동기화할 필요가 없는 개체를 제거합니다.

**활동**: 동기화에서 제거할 수 있는 동기화 중인 활동이 있는지 확인하십시오.

**중요하지 않은 시간에 일괄 업데이트를 예약합니다**: 데이터 동기화 패턴을 검토하여 중요하지 않은 기간을 식별하십시오. 이러한 중요하지 않은 기간 동안 대량 업데이트를 예약할 수 있는지 확인하십시오.

위의 모든 모범 사례를 따르고 있지만 여전히 많은 백로그가 발생하는 경우 [Marketo Engage 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하십시오.

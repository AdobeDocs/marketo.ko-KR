---
description: Salesforce와 작업 동기화 미리 알림 - Marketo 문서 - 제품 설명서
title: Salesforce와 작업 동기화 미리 알림
hide: true
hidefromtoc: true
exl-id: 4de933db-4626-4845-be70-8ad55d03a18e
source-git-commit: ee43ec3a8631ab6b9e5e345b5a273673a1dc6983
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---

# Salesforce와 작업 동기화 미리 알림 {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>작업 동기화 체크 아웃을 활성화하는 방법을 알아보려면 [Salesforce 작업에 Sales Connect 작업/미리 알림 동기화](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-connect-tasks-reminders-to-salesforce-tasks).

작업 동기화 설정이 활성화되면 사용자는 Salesforce와 양방향 동기화된 미리 알림 작업을 볼 수 있습니다. 즉, 사용자는 Salesforce 또는 Sales Connect에서 작업을 관리할 수 있으며 시스템이 계속 정렬될 것임을 확신하고 있습니다.

## 미리 알림 작업 필드 동기화 {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

다음은 Sales Connect의 미리 알림 작업 필드와 양방향 작업 동기화를 통해 지원되는 해당 Salesforce 필드 목록입니다.

<table>
 <tr>
  <th>영업 연결 작업 필드</th>
  <th>Salesforce 작업 필드</th>
  <th>Salesforce 작업</th>
 </tr>
 <tr>
  <td>작업 이름</td>
  <td>제목 필드</td>
  <td>작업의 제목을 표시하는 간단한 요약 필드입니다.</td>
 </tr>
 <tr>
  <td>상태</td>
  <td>작업 상태</td>
  <td><p>작업의 상태를 표시합니다. Sales Connect 작업에는 Salesforce 작업 상태 선택 목록의 값 중 두 개에 매핑되는 두 가지 상태가 있습니다.</p>
  <p>Sales Connect에서 열기 = Salesforce에서 시작되지 않음.</p>
  <p>Sales Connect에서 완료 = Salesforce에서 완료됨.</p>
  <p>Salesforce의 다른 상태 값은 Sales Connect에 동기화되지 않습니다.</p></td>
 </tr>
 <tr>
  <td>우선순위</td>
  <td>우선순위</td>
  <td><p>Sales Connect 우선 순위는 Salesforce의 Normal 및 High 우선 순위 값에 매핑되는 Normal 또는 High일 수 있습니다.</p>
  <p>Salesforce의 낮은 우선 순위 값은 Sales Connect에 동기화되지 않습니다.</p></td>
 </tr>
 <tr>
  <td>기한</td>
  <td>기한</td>
  <td>작업 기한 날짜입니다.</td>
 </tr>
 <tr>
  <td>세부 사항</td>
  <td>댓글</td>
  <td>미리 알림 작업과 함께 완료되는 작업에 대한 자세한 정보를 표시합니다.</td>
 </tr>
</table>

## Salesforce와 Sales Connect 작업 동기화 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

처음 Sales Connect와 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. 그렇게 하겠습니다 **not** Salesforce에 Sales Connect에서 현재 수행하는 모든 작업을 강제로 수행합니다. 불필요한 정보와 중복을 줄이기 위해 Sales Connect에서 Salesforce로 동기화되는 유일한 작업은 생성된 작업입니다 *after* sfdc와 Sales Connect를 동기화합니다.

다음은 Sales Connect 및 SFDC 작업을 동기화할 때 발생하는 작업입니다.

* 작업 동기화 시 저장을 클릭하면 동기화가 시작됩니다. 처음에는 시간이 좀 걸릴 겁니다

* 지난 24시간 동안 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Connect로 가져옵니다. 동기화는 만기 날짜를 기반으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만 Command Center에서는 오늘과 내일 작업만 표시됩니다.

* 이전에 동기화가 켜져 있고 SFDC에서 모든 작업을 삭제하면 지난 15일 동안 삭제된 작업은 명령 센터에서 삭제됩니다.

* 동기화가 활성화되면 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록에 동기화됩니다. Salesforce에서 생성, 편집, 완료 또는 삭제된 작업은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 동기화 상자를 [설정 페이지](https://toutapp.com/login) 참조하십시오.

>[!NOTE]
>
>Sales Connect에서 작업의 제목 필드를 업데이트할 수 있으며, `{{activity_subject}}` 동적 필드 [활동 세부 사항 사용자 지정](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) 설정. 반대로 Salesforce의 제목 필드에 대한 모든 업데이트는 _not_ Sales Connect 미리 알림 작업 제목 필드에 동기화합니다.

---
description: Salesforce - Marketo 문서 - 제품 설명서와 미리 알림 작업 동기화
title: Salesforce와의 미리 알림 작업 동기화
exl-id: 4de933db-4626-4845-be70-8ad55d03a18e
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '564'
ht-degree: 0%

---

# Salesforce와의 미리 알림 작업 동기화 {#reminder-task-sync-with-salesforce}

>[!NOTE]
>
>작업 동기화를 사용하는 방법에 대해 알아보려면 [Salesforce 작업에 Sales Connect 작업/미리 알림 동기화](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md#sync-sales-connect-tasks-reminders-to-salesforce-tasks)를 확인하십시오.

작업 동기화 설정이 활성화되면 사용자는 Salesforce와 양방향으로 동기화된 알림 작업을 보게 됩니다. 즉, 사용자는 Salesforce 또는 Sales Connect에서 작업을 관리할 수 있으며 시스템을 계속 조정할 수 있다고 확신할 수 있습니다.

## 미리 알림 작업 필드 동기화 {#reminder-task-field-sync}

![](assets/reminder-task-sync-with-salesforce-1.png)

다음은 Sales Connect의 미리 알림 작업 필드와 양방향 작업 동기화를 통해 지원되는 해당 Salesforce 필드 목록입니다.

<table>
 <tr>
  <th>Sales Connect 작업 필드</th>
  <th>Salesforce 작업 필드</th>
  <th>Salesforce 작업</th>
 </tr>
 <tr>
  <td>작업 이름</td>
  <td>제목 필드</td>
  <td>작업 제목을 표시하는 짧은 요약 필드입니다.</td>
 </tr>
 <tr>
  <td>상태</td>
  <td>작업 상태</td>
  <td><p>작업의 상태를 표시합니다. Sales Connect 작업에는 Salesforce 작업 상태 선택 목록의 값 중 두 개에 매핑되는 두 가지 상태가 있습니다.</p>
  <p>Sales Connect에서 열기 = Salesforce에서 시작되지 않음.</p>
  <p>Sales Connect에서 완료 = Salesforce에서 완료.</p>
  <p>Salesforce의 다른 상태 값이 Sales Connect에 동기화되지 않습니다.</p></td>
 </tr>
 <tr>
  <td>우선 순위</td>
  <td>우선 순위</td>
  <td><p>Sales Connect 우선순위는 Salesforce의 보통 및 높음 우선순위 값에 매핑되는 보통 또는 높음일 수 있습니다.</p>
  <p>Salesforce의 우선 순위가 낮은 값은 Sales Connect에 동기화되지 않습니다.</p></td>
 </tr>
 <tr>
  <td>기한</td>
  <td>기한</td>
  <td>작업 기한.</td>
 </tr>
 <tr>
  <td>세부 정보</td>
  <td>댓글</td>
  <td>미리 알림 작업으로 완료하기로 한 내용에 대한 자세한 정보를 표시합니다.</td>
 </tr>
</table>

## 처음으로 Salesforce와 Sales Connect 작업 동기화 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Sales Connect와 Salesforce 작업 간의 동기화를 처음 켜면 Salesforce 작업을 가져옵니다. Salesforce에 연결된 Sales Connect에서 현재 작업을 **밀어내지**&#x200B;합니다. 복잡함과 중복을 줄이기 위해 Sales Connect에서 Salesforce로 동기화되는 작업은 Sales Connect를 SFDC와 동기화하는 *후*&#x200B;에 만들어진 작업뿐입니다.

Sales Connect 및 SFDC 작업을 동기화할 때 발생하는 상황은 다음과 같습니다.

* 작업 동기화 시 저장 을 클릭하면 다시 동기화됩니다. 처음에는 시간이 좀 걸릴 것입니다.

* 지난 24시간 동안 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Connect로 가져옵니다. 동기화는 만기일을 기준으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만, 명령 센터에서는 오늘과 내일의 작업만 표시됩니다.

* 이전에 동기화가 켜져 있고 SFDC에서 작업을 삭제하면 최근 15일 동안 삭제된 모든 작업이 명령 센터에서 삭제됩니다.

* 동기화가 활성화되어 있는 한 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록과 동기화됩니다. 그리고 Salesforce에서 생성, 편집, 완료 또는 삭제된 모든 항목은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 응용 프로그램의 [설정 페이지](https://toutapp.com/login)에서 동기화 상자를 선택하면 됩니다.

>[!NOTE]
>
>[활동 세부 정보 사용자 지정](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/configure-salesforce-activity-detail-customization.md) 설정에서 `{{activity_subject}}` 동적 필드를 사용하는 경우 Sales Connect에서 작업의 제목 필드를 업데이트할 수 있으며 해당 업데이트는 동기화된 작업에 대한 Salesforce 제목 필드에서 동기화됩니다. 반대로 Salesforce의 제목 필드에 대한 모든 업데이트는 Sales Connect 미리 알림 작업 제목 필드와 동기화되지 _않습니다_.

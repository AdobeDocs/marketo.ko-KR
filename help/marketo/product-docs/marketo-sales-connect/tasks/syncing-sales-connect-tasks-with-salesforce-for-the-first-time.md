---
unique-page-id: 14352541
description: 처음 Salesforce와 Sales Connect 작업 동기화 - Marketing To Docs - 제품 설명서
title: 처음으로 Salesforce와 Sales Connect 작업 동기화
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# 처음으로 Salesforce와 Sales Connect 작업 동기화 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

처음 Sales Connect와 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. Adobe는 Sales Connect에서 Salesforce에 수행하는 현재 모든 작업을 **푸시하지 않습니다** . 번거로운 작업 및 중복을 줄이기 위해 Sales Connect에서 Salesforce로 동기화되는 유일한 작업은 Sales Connect와 SFDC를 동기화한 *후* 생성된 작업입니다.

Sales Connect 및 SFDC 작업을 동기화할 때 발생하는 작업은 다음과 같습니다.

- 동기화 작업 저장을 클릭하면 동기화가 시작됩니다. 처음에는 시간이 좀 걸릴 겁니다

- 업데이트 또는 작성된 미리 알림은 SFDC에서 Sales Connect로 `last 24 hours` 가져옵니다. 동기화는 기본적으로 `due date` 설정되며 이러한 모든 작업은 백엔드에서 동기화되지만 Command Center에서는 오늘과 내일 작업만 표시됩니다.

- 이전에 동기화가 켜져 있고 SFDC에서 모든 작업을 삭제하면 지난 15일 동안 삭제된 모든 작업이 명령 센터에서 삭제됩니다.

- 동기화가 활성화된 경우 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록과 동기화됩니다. 또한 Salesforce에서 생성, 편집, 완료 또는 삭제된 항목은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 애플리케이션의 [설정 페이지에서](http://toutapp.com/next#settings/crm/salesforce/configure) 동기화 상자를 선택하면 됩니다.


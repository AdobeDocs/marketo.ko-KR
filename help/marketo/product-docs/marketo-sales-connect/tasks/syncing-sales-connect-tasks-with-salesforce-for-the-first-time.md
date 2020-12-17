---
unique-page-id: 14352541
description: 처음 Salesforce와 Sales Connect 작업 동기화 - Marketing To Docs - 제품 설명서
title: 처음으로 Salesforce와 영업 연결 작업 동기화
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# 처음 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time} 동안 Salesforce와 Sales Connect 작업 동기화

처음 Sales Connect와 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. Adobe는 Salesforce에 Sales Connect에 있는 현재 모든 작업을 **푸시하지 않습니다.** 업무 혼돈과 복제를 줄이기 위해 Sales Connect에서 Salesforce에 동기화되는 유일한 작업은 Sales Connect와 SFDC를 동기화한 *후에 생성된 작업입니다.*

Sales Connect 및 SFDC 작업을 동기화할 때 수행되는 작업은 다음과 같습니다.

- 동기화 작업 저장을 클릭하자마자 동기화가 시작됩니다. 처음에는 시간이 좀 걸릴 겁니다

- `last 24 hours`에서 업데이트되었거나 만든 미리 알림은 SFDC에서 Sales Connect로 가져오게 됩니다. 동기화는 `due date`을 기반으로 하며 이러한 모든 작업은 백엔드에서 동기화되지만 Command Center에서는 오늘과 내일에만 작업을 볼 수 있습니다.

- 이전에 동기화가 켜져 있고 SFDC에서 모든 작업을 삭제하면 지난 15일 동안 삭제된 모든 작업이 명령 센터에서 삭제됩니다.

- 동기화가 활성화되어 있으면 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화할 수 있습니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록과 동기화됩니다. Salesforce에서 생성, 편집, 완료 또는 삭제된 작업은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 응용 프로그램의 [설정 페이지](http://toutapp.com/next#settings/crm/salesforce/configure)에서 동기화 상자를 선택합니다.


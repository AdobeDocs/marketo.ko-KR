---
unique-page-id: 14352541
description: Salesforce와 Sales Connect 작업 처음 동기화 - Marketo 문서 - 제품 설명서
title: Salesforce와 Sales Connect 작업 동기화
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# Salesforce와 Sales Connect 작업 동기화 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

처음 Sales Connect와 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. 그렇게 하겠습니다 **not** Salesforce에 Sales Connect에서 현재 수행하는 모든 작업을 강제로 수행합니다. 불필요한 정보와 중복을 줄이기 위해 Sales Connect에서 Salesforce로 동기화되는 유일한 작업은 생성된 작업입니다 *after* sfdc와 Sales Connect를 동기화합니다.

다음은 Sales Connect 및 SFDC 작업을 동기화할 때 발생하는 작업입니다.

- 작업 동기화 시 저장을 클릭하면 동기화가 시작됩니다. 처음에는 시간이 좀 걸릴 겁니다

- 지난 24시간 동안 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Connect로 가져옵니다. 동기화는 만기 날짜를 기반으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만 Command Center에서는 오늘과 내일 작업만 표시됩니다.

- 이전에 동기화가 켜져 있고 SFDC에서 모든 작업을 삭제하면 지난 15일 동안 삭제된 작업은 명령 센터에서 삭제됩니다.

- 동기화가 활성화되면 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록에 동기화됩니다. Salesforce에서 생성, 편집, 완료 또는 삭제된 작업은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 동기화 상자를 [설정 페이지](https://toutapp.com/login) 참조하십시오.

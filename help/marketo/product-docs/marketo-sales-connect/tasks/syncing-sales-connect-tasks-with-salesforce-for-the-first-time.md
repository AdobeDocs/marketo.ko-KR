---
unique-page-id: 14352541
description: 처음으로 Salesforce와 Sales Connect 작업 동기화 - Marketo 문서 - 제품 설명서
title: 처음으로 Salesforce와 Sales Connect 작업 동기화
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# 처음으로 Salesforce와 Sales Connect 작업 동기화 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

Sales Connect와 Salesforce 작업 간의 동기화를 처음 켜면 Salesforce 작업을 가져옵니다. Salesforce에 연결된 Sales Connect에서 현재 작업을 **밀어내지**&#x200B;합니다. 복잡함과 중복을 줄이기 위해 Sales Connect에서 Salesforce로 동기화되는 작업은 Sales Connect를 SFDC와 동기화하는 *후*&#x200B;에 만들어진 작업뿐입니다.

Sales Connect 및 SFDC 작업을 동기화할 때 발생하는 상황은 다음과 같습니다.

- 작업 동기화 시 저장 을 클릭하면 다시 동기화됩니다. 처음에는 시간이 좀 걸릴 것입니다.

- 지난 24시간 동안 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Connect로 가져옵니다. 동기화는 만기일을 기준으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만, 명령 센터에서는 오늘과 내일의 작업만 표시됩니다.

- 이전에 동기화가 켜져 있고 SFDC에서 작업을 삭제하면 최근 15일 동안 삭제된 모든 작업이 명령 센터에서 삭제됩니다.

- 동기화가 활성화되어 있는 한 Sales Connect와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Connect에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록과 동기화됩니다. 그리고 Salesforce에서 생성, 편집, 완료 또는 삭제된 모든 항목은 Sales Connect에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 응용 프로그램의 [설정 페이지](https://toutapp.com/login)에서 동기화 상자를 선택하면 됩니다.

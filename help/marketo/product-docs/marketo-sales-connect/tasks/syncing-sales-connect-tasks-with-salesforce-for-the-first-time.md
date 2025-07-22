---
unique-page-id: 14352541
description: Sales Connect 작업을 Salesforce과 처음 동기화 - Marketo 문서 - 제품 설명서
title: Sales Connect 작업을 Salesforce과 처음 동기화
exl-id: 42ac6b4f-76ac-40d7-9e10-7e0d3886a638
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# [!DNL Sales Connect]개 작업을 [!DNL Salesforce]과(와) 처음 동기화 중 {#syncing-sales-connect-tasks-with-salesforce-for-the-first-time}

[!DNL Sales Connect]과(와) [!DNL Salesforce] 작업 간의 동기화를 처음 켜면 [!DNL Salesforce] 작업을 가져옵니다. **에 있는 현재 작업을**(으)로 [!DNL Sales Connect]not[!DNL Salesforce] 푸시합니다. 혼란을 줄이고 중복을 줄이기 위해 [!DNL Sales Connect]에서 [!DNL Salesforce]&#x200B;(으)로 동기화되는 작업은 *을(를) SFDC과 동기화하는*&#x200B;이후[!DNL Sales Connect]에 만들어진 작업뿐입니다.

[!DNL Sales Connect] 및 SFDC 작업을 동기화할 때 발생하는 상황은 다음과 같습니다.

- 작업 동기화 시 저장 을 클릭하면 다시 동기화됩니다. 처음에는 시간이 좀 걸릴 것입니다.

- 지난 24시간 동안 업데이트되거나 만들어진 모든 미리 알림은 SFDC에서 [!DNL Sales Connect]&#x200B;(으)로 가져옵니다. 동기화는 만기일을 기준으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만, 명령 센터에서는 오늘과 내일의 작업만 표시됩니다.

- 이전에 동기화가 켜져 있고 SFDC에서 작업을 삭제하면 지난 15일 동안 삭제된 모든 항목이 명령 센터에서 삭제됩니다.

- 동기화가 활성화되어 있는 한 [!DNL Sales Connect]과(와) SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 [!DNL Sales Connect]에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 [!DNL Salesforce]의 작업 목록에 동기화됩니다. [!DNL Salesforce]에서 생성, 편집, 완료 또는 삭제된 모든 작업은 [!DNL Sales Connect]에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 응용 프로그램의 [설정 페이지](https://toutapp.com/login)에서 동기화 상자를 선택하면 됩니다.

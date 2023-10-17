---
unique-page-id: 1147031
description: SFDC에서 사용자 삭제 - Marketo 문서 - 제품 설명서
title: SFDC에서 사용자 삭제
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# SFDC에서 사용자 삭제 {#delete-person-from-sfdc}

Salesforce에서 특정 리드 세트를 제거해야 하지만 해당 리드를 Marketo Engage의 직원으로 남겨두어야 하는 경우 SFDC에서 직원 삭제 작업을 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **[!UICONTROL 개인 작업]** 및 선택 **[!DNL Salesforce]**.

   ![](assets/person-actions-salesforce.png)

1. 선택 **[!UICONTROL SFDC에서 사용자 삭제]**.

   ![](assets/delete-person-from-sfdc.png)

1. 다음을 확인합니다. **[!UICONTROL Marketo에서 삭제]** 설정: **[!UICONTROL false]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 지금 실행]**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   흐름 단계가 실행되면 사용자는 더 이상 Salesforce의 잠재 고객이 아니지만 Marketo에 남게 됩니다.

   >[!CAUTION]
   >
   >다음을 설정하는 경우 **[!UICONTROL Marketo에서 삭제]** 끝 **[!UICONTROL true]** Marketo의 직원과 Salesforce의 잠재 고객을 삭제하면 영구적으로 사라집니다. 이 작업은 취소할 수 없습니다.

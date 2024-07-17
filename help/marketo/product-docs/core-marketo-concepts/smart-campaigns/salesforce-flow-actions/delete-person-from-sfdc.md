---
unique-page-id: 1147031
description: SFDC에서 사용자 삭제 - Marketo 문서 - 제품 설명서
title: SFDC에서 사용자 삭제
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 934bb5f197f801e48cf8e7554335eb2d07289037
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# SFDC에서 사용자 삭제 {#delete-person-from-sfdc}

Salesforce에서 특정 리드 세트를 제거해야 하지만 해당 리드를 Marketo Engage의 직원으로 남겨두어야 하는 경우 SFDC에서 직원 삭제 작업을 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **[!UICONTROL 개인 작업]**&#x200B;을 클릭하고 **[!DNL Salesforce]**&#x200B;을(를) 선택합니다.

   ![](assets/delete-person-from-sfdc-1.png)

1. **[!UICONTROL SFDC에서 사용자 삭제]**&#x200B;를 선택하세요.

   ![](assets/delete-person-from-sfdc-2.png)

1. **[!UICONTROL Marketo에서 삭제]** 설정이 **[!UICONTROL false]**&#x200B;인지 확인한 다음 **[!UICONTROL 지금 실행]**&#x200B;을 클릭하세요.

   ![](assets/delete-person-from-sfdc-3.png)

   흐름 단계가 실행되면 사용자는 더 이상 Salesforce의 잠재 고객이 아니지만 Marketo에 남게 됩니다.

   >[!CAUTION]
   >
   >**[!UICONTROL Marketo에서 삭제]**&#x200B;를 **[!UICONTROL true]**(으)로 설정하고 Marketo의 직원과 Salesforce의 리드를 삭제하면 영구적으로 삭제됩니다. 이 작업은 취소할 수 없습니다.

---
unique-page-id: 1147154
description: 프로그램과 SFDC 캠페인 동기화 - Marketo 문서 - 제품 설명서
title: SFDC Campaign을 프로그램과 동기화
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
feature: Programs
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '163'
ht-degree: 1%

---

# SFDC Campaign을 프로그램과 동기화 {#sync-an-sfdc-campaign-with-a-program}

Marketo Engage을 사용하면 프로그램을 [!DNL Salesforce] 캠페인과 동기화하여 두 시스템의 상태를 포함하여 동일한 사용자 목록을 유지할 수 있습니다. 그럼 시작해 보겠습니다!

>[!PREREQUISITES]
>
>먼저 [캠페인 동기화를 활성화 [!DNL Salesforce] 활성화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"}해야 합니다.

>[!CAUTION]
>
>SFDC 캠페인을 Marketo Engage 프로그램과 동기화할 때 프로그램의 하위 캠페인에 대해 암시된 SFDC 작업(예: SFDC 캠페인에 추가, SFDC에 동기화)이 비활성화됩니다.

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/login-marketing-activities-1.png)

1. 프로그램을 선택합니다.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. **[!UICONTROL Program Actions]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Salesforce Campaign Sync]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. **[!UICONTROL Create New]**&#x200B;을(를) 선택하거나 기존 [!DNL Salesforce] 캠페인을 선택하십시오.

   >[!TIP]
   >
   >기존 [!DNL Salesforce] 캠페인을 선택하는 경우 [캠페인 및 Marketo 프로그램의 프로그램 상태 [!DNL Salesforce] 와(과) 일치해야 합니다](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md){target="_blank"}.

1. 새 캠페인의 이름을 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. 이제 프로그램 요약 페이지에서 캠페인 동기화 세부 사항을 확인할 수 있습니다.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   훌륭합니다! 이제 Marketo의 모든 프로그램 상태 변경 사항이 SFDC 캠페인에 동기화되거나 그 반대로 동기화됩니다.

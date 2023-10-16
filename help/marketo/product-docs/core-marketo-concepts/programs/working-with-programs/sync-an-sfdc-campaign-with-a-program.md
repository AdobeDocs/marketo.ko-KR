---
unique-page-id: 1147154
description: SFDC 캠페인을 프로그램과 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 캠페인을 프로그램과 동기화
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
feature: Programs
source-git-commit: 9e51ece12742152040dbbcb6a1584fba28e863ff
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 0%

---

# SFDC 캠페인을 프로그램과 동기화 {#sync-an-sfdc-campaign-with-a-program}

Marketo Engage을 사용하면 프로그램을 [!DNL Salesforce] 캠페인은 상태를 포함하여 두 시스템에서 동일한 사용자 목록을 유지 관리합니다. 시작해 보겠습니다!

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [활성화 [!DNL Salesforce] 캠페인 동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"} 첫 번째.

>[!CAUTION]
>
>SFDC 캠페인을 Marketo Engage 프로그램과 동기화할 때 프로그램의 하위 캠페인에 대해 암시된 SFDC 작업(예: SFDC 캠페인에 추가, SFDC에 동기화)이 비활성화됩니다.

1. 다음으로 이동 **[!UICONTROL 마케팅 활동]**.

   ![](assets/login-marketing-activities-1.png)

1. 프로그램을 선택합니다.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. 클릭 **[!UICONTROL 프로그램 동작]**&#x200B;을 선택한 다음 을 선택합니다. **[!UICONTROL Salesforce 캠페인 동기화]**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. 선택 **[!UICONTROL 새로 만들기]** 또는 기존 항목 선택 [!DNL Salesforce] 캠페인.

   >[!TIP]
   >
   >기존 을 선택하는 경우 [!DNL Salesforce] campaign, 다음을 확인하십시오. [의 프로그램 상태 일치 [!DNL Salesforce] campaign과 Marketo 프로그램](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md){target="_blank"}.

1. 새 캠페인의 이름을 입력하고 **[!UICONTROL 저장]**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. 이제 프로그램 요약 페이지에서 캠페인 동기화 세부 사항을 확인할 수 있습니다.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   훌륭합니다! 이제 Marketo의 모든 프로그램 상태 변경 사항이 SFDC 캠페인에 동기화되거나 그 반대로 동기화됩니다.

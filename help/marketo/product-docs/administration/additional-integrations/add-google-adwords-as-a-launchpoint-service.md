---
unique-page-id: 6095008
description: LaunchPoint를 통해  [!DNL Google AdWords] Marketo에 연결하여 AdWords에서 보고할 오프라인 전환 데이터를 업로드합니다.
title: ' [!DNL LaunchPoint] 서비스로  [!DNL Google AdWords] 추가'
exl-id: 993a057a-3f98-4a9f-a770-c9c80dedfd81
feature: Administration, Integrations
source-git-commit: 40f06a5391f2f7263bea0c5b8cefc1f3a607c68c
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 5%

---

# [!DNL Google AdWords]을(를) [!DNL LaunchPoint] 서비스로 추가 {#add-google-adwords-as-a-launchpoint-service}

[!DNL Google AdWords] 계정을 Marketo에 연결하여 Marketo에서 [!DNL Google AdWords]&#x200B;(으)로 오프라인 전환 데이터를 자동으로 업로드합니다. [!DNL AdWords]에서 [사용자 지정 열을 추가](https://support.google.com/adwords/answer/3073556){target="_blank"}한 후 [!DNL AdWords] UI에서 자격 있는 리드, 기회 및 신규 고객(또는 추적하려는 매출 단계)을 일으킨 클릭 수를 확인할 수 있습니다. 이 정보는 Marketo UI에 표시되지 않습니다.

[Google의 오프라인 전환 가져오기 기능](https://support.google.com/adwords/answer/2998031?hl=en){target="_blank"}에 대해 자세히 알아보세요.

>[!AVAILABILITY]
>
>모든 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>[[!DNL Google AdWords] as a [!DNL Launchpoint] 서비스를 관리자 계정](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md){target="_blank"}과 통합할 수도 있습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-1.png)

1. **[!UICONTROL LaunchPoint]**&#x200B;를 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-2.png)

1. **[!UICONTROL New]** 및 **[!UICONTROL New Service]**&#x200B;을(를) 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-3.png)

1. [!UICONTROL display name]을(를) 입력하고 **[!UICONTROL Google AdWords]**&#x200B;을(를) 선택하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-4.png)

1. **[!UICONTROL Authorize Marketo]**&#x200B;를 선택합니다.

   >[!NOTE]
   >
   >개인 [!DNL Gmail] 계정에서 로그아웃하고 팝업을 사용하도록 설정하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-5.png)

1. [!DNL Google AdWords]과(와) 연결된 계정을 선택하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-6.png)

1. **[!UICONTROL Accept]**&#x200B;를 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-7.png)

1. 상태가 **[!UICONTROL Success]**(으)로 표시됩니다. **[!UICONTROL Next]**&#x200B;를 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-8.png)

1. Marketo에서 [!DNL Google AdWords] **[!UICONTROL Weekly]** 또는 **[!UICONTROL Daily]**(으)로 오프라인 전환을 업로드합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-9.png)

1. **[!UICONTROL First Click]** 또는 **[!UICONTROL Last Click]**(으)로 특성을 전환했습니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-10.png)

   | 유형 | 정의 |
   |---|---|
   | [!UICONTROL First Click] | 오프라인 전환은 지난 90일 동안 한 사람이 클릭한 첫 번째 [!DNL AdWords] 광고로 인한 것입니다. |
   | [!UICONTROL Last Click] | 오프라인 전환은 사용자가 클릭한 마지막 [!DNL AdWords] 광고로 인한 것입니다. |

   >[!NOTE]
   >
   >Marketo 및 [!DNL AdWords]에서 일관된 속성 모델을 사용하면 가장 정확한 데이터를 제공합니다.

1. **[!UICONTROL Create]**&#x200B;를 클릭합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-11.png)

   >[!NOTE]
   >
   >이 기능을 사용하려면 [자동 태그 지정](https://support.google.com/adwords/answer/1752125?hl=en){target="_blank"}을 선택해야 합니다. 비활성화는 [!DNL AdWords] 내에서 수행해야 합니다.

See the Related Article below to learn how to map [!DNL AdWords] offline conversions in your revenue model.

>[!MORELIKETHIS]
>
>[Set [!DNL Google AdWords] Conversions in the Revenue Model](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model.md){target="_blank"}

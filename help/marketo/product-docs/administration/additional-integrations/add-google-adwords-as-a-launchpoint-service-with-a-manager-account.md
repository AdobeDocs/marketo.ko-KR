---
unique-page-id: 7504893
description: "관리자 계정으로  [!DNL Google AdWords] as a [!DNL Launchpoint] 서비스 추가 - Marketo 문서 - 제품 설명서"
title: "관리자 계정으로  [!DNL Google AdWords] as a [!DNL Launchpoint] Service 추가"
exl-id: aac106f4-6615-49d5-a561-0dd965c7b0ff
feature: Administration, Integrations
source-git-commit: 2671f81f62658447e4b2a3dc2e02a4e0927443e8
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---

# 관리자 계정을 사용하여 [!DNL Google AdWords]을(를) [!DNL Launchpoint] 서비스로 추가 {#add-google-adwords-as-a-launchpoint-service-with-a-manager-account}

[!DNL Google AdWords] 계정을 Marketo에 연결하여 Marketo에서 [!DNL Google AdWords](으)로 오프라인 전환 데이터를 자동으로 업로드합니다. [!DNL AdWords]에서 [사용자 지정 열을 추가](https://support.google.com/adwords/answer/3073556){target="_blank"}한 후 [!DNL AdWords] UI에서 자격 있는 리드, 기회 및 신규 고객(또는 추적하려는 매출 단계)을 일으킨 클릭 수를 쉽게 확인할 수 있습니다. 이 정보는 Marketo UI에 표시되지 않습니다.

[!DNL Google Adwords] 계정이 여러 개 있는 경우 [[!DNL Google AdWords Manager Account]](https://www.google.com/adwords/manager-accounts/){target="_blank"}(이전의 [!DNL My Client Center])을(를) 사용하여 Marketo과 통합할 수 있습니다.

[Google의 오프라인 전환 가져오기 기능에 대해 자세히 알아보세요](https://support.google.com/adwords/answer/2998031?hl=en){target="_blank"}.

>[!AVAILABILITY]
>
>일부 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>[독립형 [!DNL Google AdWords] 계정을  [!DNL Launchpoint] 서비스](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md){target="_blank"}(으)로 통합할 수도 있습니다.

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-1.png)

1. **[!UICONTROL LaunchPoint]**&#x200B;을 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-2.png)

1. **[!UICONTROL 새로 만들기]** 드롭다운을 클릭하고 **[!UICONTROL 새 서비스]**&#x200B;를 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-3.png)

1. **[!UICONTROL 표시 이름]**&#x200B;을 입력하고 **[!UICONTROL Google AdWords]**&#x200B;을(를) 선택하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-4.png)

1. **[!UICONTROL Marketo 승인]**&#x200B;을 선택합니다.

   >[!NOTE]
   >
   >개인 [!DNL Gmail] 계정에서 로그아웃하고 팝업을 사용하도록 설정하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-5.png)

1. **[!DNL Google AdWords]**&#x200B;과(와) 연결된 계정을 선택하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-6.png)

1. **[!UICONTROL 승인]**&#x200B;을 클릭합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-7.png)

1. 상태가 **[!UICONTROL 성공]**(으)로 표시됩니다. **[!UICONTROL 다음]**&#x200B;을 선택합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-8.png)

1. Marketo에서 [!DNL Google AdWords] **[!UICONTROL 주별]** 또는 **[!UICONTROL 일별]**(으)로 오프라인 전환을 업로드하십시오.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-9.png)

1. 특성을 **[!UICONTROL 첫 번째 클릭]** 또는 **[!UICONTROL 마지막 클릭]**(으)로 전환합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-10.png)

   | 유형 | 정의 |
   |---|---|
   | [!UICONTROL 첫 번째 클릭] | 오프라인 전환은 지난 90일 동안 한 사람이 클릭한 첫 번째 [!DNL AdWords] 광고로 인한 것입니다. |
   | [!UICONTROL 마지막 클릭] | 오프라인 전환은 사용자가 클릭한 마지막 [!DNL AdWords] 광고로 인한 것입니다. |

   >[!NOTE]
   >
   >이 기능을 사용하려면 [자동 태그 지정](https://support.google.com/adwords/answer/1752125?hl=en){target="_blank"}을 선택해야 합니다. [!DNL AdWords] 내에서 활성화되어야 합니다.

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-11.png)

1. 업데이트하지 않으려는 계정의 선택을 취소합니다. **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-12.png)

   이제 매출 모델에서 [!DNL AdWords] 오프라인 전환을 매핑하는 방법에 대해서는 아래 관련 문서를 참조하십시오.

   >[!MORELIKETHIS]
   >
   >관리자 계정을 사용하여 [수익 모델에서 전환 설정 [!DNL Google AdWords] 2}](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account.md){target="_blank"}

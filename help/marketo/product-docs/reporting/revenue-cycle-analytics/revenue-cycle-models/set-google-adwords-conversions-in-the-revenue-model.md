---
unique-page-id: 6095029
description: 매출 모델 - Marketo 문서 - 제품 설명서에서  [!DNL Google AdWords] 전환 설정
title: 수익 모델에서  [!DNL Google AdWords] 전환 설정
exl-id: dd1259fc-d3f2-44ec-8055-f75d55263b36
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '409'
ht-degree: 1%

---

# 수익 모델에서 [!DNL Google AdWords] 전환 설정 {#set-google-adwords-conversions-in-the-revenue-model}

[!DNL Google AdWords] 계정을 Marketo에 연결하여 Marketo에서 [!DNL Google AdWords]&#x200B;(으)로 오프라인 전환 데이터를 자동으로 업로드합니다. [!DNL AdWords]에서 [사용자 지정 열을 추가](https://support.google.com/adwords/answer/3073556)한 후 [!DNL AdWords] UI에서 자격 있는 리드, 기회 및 신규 고객(또는 추적하려는 매출 단계)을 일으킨 클릭 수를 쉽게 확인할 수 있습니다.

>[!NOTE]
>
>Marketo에서 [!DNL Google AdWords]&#x200B;(으)로의 푸시 통합입니다. 전환 데이터는 _포털에_&#x200B;만[!DNL Google AdWords]나타나며, _Marketo UI에는 표시되지 않습니다_.

[Google의 오프라인 전환 가져오기 기능](https://support.google.com/adwords/answer/2998031?hl=en)에 대해 자세히 알아보세요. [!DNL AdWords] 오프라인 전환을 수익 모델의 하나 이상의 단계에 매핑합니다. 매핑을 수행하는 방법에는 세 가지가 있습니다.

* [!DNL AdWords] 전환
* 스테이지 작업
* [!DNL AdWords] 매핑

단계 작업을 사용하는 경우 Marketo에서 새 [!DNL AdWords] 오프라인 전환을 만들 수 있습니다.

>[!PREREQUISITES]
>
>[LaunchPoint 서비스로 추가 [!DNL Google AdWords] 추가](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md)

## [!DNL AdWords] 변환 사용 {#use-adwords-conversion}

1. **[!UICONTROL Analytics]** 영역으로 이동합니다.

   ![](assets/image2015-2-23-18-3a9-3a34.png)

1. 모델을 선택합니다.

   ![](assets/image2015-2-23-18-3a3-3a12.png)

1. **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-3-10-15-3a3-3a20.png)

1. [!DNL AdWords] 전환에 매핑할 매출 단계를 선택하십시오.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Marketo 단계에 매핑할 **[!UICONTROL AdWords Conversion]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-2-26-16-3a46-3a15.png)

   좋네! [!DNL AdWords] 전환 데이터가 선택한 케이던스에서 [!DNL Google AdWords]에 업로드됩니다.

## 스테이지 작업 사용 {#use-stage-action}

[!UICONTROL AdWords Conversion]에서 **[!UICONTROL Stage Actions]**&#x200B;을(를) 매핑할 수도 있습니다.

1. [!DNL AdWords] 전환에 매핑할 단계를 선택하십시오.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. **[!UICONTROL Stage Actions]** 드롭다운 아래에서 **[!UICONTROL Set AdWords Conversion]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. **[!UICONTROL AdWords Conversion]** 선택.

   ![](assets/image2015-2-26-16-3a54-3a47.png)

   **팁**: [!DNL AdWords]개의 전환이 없는 경우 **[!UICONTROL +New Conversion]**&#x200B;을(를) 클릭하여 만드십시오.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-2-26-16-3a56-3a2.png)

1. 모든 [!DNL AdWords] 전환을 매출 단계로 매핑했으면 요약 페이지로 돌아갑니다. **[!UICONTROL Model Actions]**&#x200B;을(를) 선택하고 **[!UICONTROL Approve Stages]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro 팁: 새 변환 추가 {#pro-tip-add-a-new-conversion}

프로 팁! Marketo에서 새 [!DNL AdWords] 오프라인 전환을 만들 수 있습니다.

>[!CAUTION]
>
>Marketo에서 만든 새 전환에는 &quot;최적화&quot; 설정이 활성화되어 있습니다. 즉, [!DNL AdWords] 입찰 전략이 해당 전환에 대한 입찰을 최적화할 수 있습니다. [!DNL AdWords] 계정에서 이 설정을 변경할 수 있습니다.

1. **[!UICONTROL Stage Actions]** 드롭다운 아래에서 **[!UICONTROL Set AdWords Conversion]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. **[!UICONTROL New Conversion]**&#x200B;를 선택합니다.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. **[!UICONTROL Conversion Name]** 입력. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-2-26-21-3a24-3a7.png)

   훌륭합니다! 이 새 변환은 [!DNL AdWords] 계정에 표시됩니다.

## [!DNL AdWords] 매핑 사용 {#use-adwords-mapping}

[!UICONTROL AdWords Conversion] 매핑을 사용하여 모든 모델 단계를 [!DNL AdWords]과(와) 한 곳에서 연결할 수 있습니다.

1. **[!UICONTROL Edit AdWords Mappings]**&#x200B;를 선택합니다.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. 추적할 각 단계에 대해 원하는 **[!UICONTROL AdWords Conversion]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-26-17-3a6-3a15.png)

1. 단계를 매핑했으면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-2-26-17-3a7-3a48.png)

1. 모든 [!DNL AdWords] 전환을 매출 단계로 매핑했으면 요약 페이지로 돌아갑니다. **[!UICONTROL Model Actions]**&#x200B;을(를) 선택하고 **[!UICONTROL Approve Stages]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

오프라인 전환 데이터를 보려면 [!DNL AdWords] 계정에 로그인해야 합니다. 해당 [사용자 지정 열 기능](https://support.google.com/adwords/answer/3073556)을 사용하여 Marketo에서 가져오는 각 오프라인 변환에 대한 변환 수 열을 만드는 것이 좋습니다.

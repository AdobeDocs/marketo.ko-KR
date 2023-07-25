---
unique-page-id: 6095029
description: 수익 모델 - Google 문서 - 제품 설명서에서 Marketo AdWords 전환 설정
title: 수익 모델에서 Google AdWords 전환 설정
exl-id: dd1259fc-d3f2-44ec-8055-f75d55263b36
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '503'
ht-degree: 0%

---

# 수익 모델에서 Google AdWords 전환 설정 {#set-google-adwords-conversions-in-the-revenue-model}

Google AdWords 계정을 Marketo에 연결하여 Marketo에서 Google AdWords로 오프라인 전환 데이터를 자동으로 업로드합니다. 그런 다음 AdWords UI에서 자격 있는 리드, 기회 및 신규 고객(또는 추적하려는 매출 단계)을 초래한 클릭 수를 이후에 쉽게 확인할 수 있습니다 [사용자 정의 열 추가](https://support.google.com/adwords/answer/3073556) AdWords에서

>[!NOTE]
>
>Marketo에서 Google AdWords로의 푸시 통합입니다. 전환 데이터가 표시됩니다. _전용_ Google 애드워즈 포털에서 _Marketo UI에 없음_.

자세히 알아보기 [Google의 오프라인 전환 가져오기 기능](https://support.google.com/adwords/answer/2998031?hl=en). AdWords 오프라인 전환을 매출 모델의 하나 이상의 단계에 매핑합니다. 매핑을 수행하는 방법에는 세 가지가 있습니다.

* AdWords 변환
* 스테이지 작업
* AdWords 매핑

단계 작업을 사용하는 경우 Marketo에서 새 AdWords 오프라인 전환을 만들 수 있습니다.

>[!PREREQUISITES]
>
>[Google AdWords를 LaunchPoint Service로 추가](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md)

## AdWords 변환 사용 {#use-adwords-conversion}

1. 로 이동 **분석** 영역입니다.

   ![](assets/image2015-2-23-18-3a9-3a34.png)

1. 모델을 선택합니다.

   ![](assets/image2015-2-23-18-3a3-3a12.png)

1. 클릭 **초안 편집**.

   ![](assets/image2015-3-10-15-3a3-3a20.png)

1. AdWords 전환에 매핑할 매출 단계를 선택합니다.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. 다음 항목 선택 **AdWords 변환** Marketo 스테이지에 매핑합니다.

   ![](assets/image2015-2-26-16-3a46-3a15.png)

   좋네! AdWords 변환 데이터는 선택한 케이던스에서 Google AdWords에 업로드됩니다.

## 스테이지 작업 사용 {#use-stage-action}

단계 작업 아래에서 AdWords 변환을 매핑할 수도 있습니다.

1. AdWords 변환에 매핑할 단계를 선택합니다.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. 아래 **스테이지 작업** 드롭다운, 선택 **AdWords 변환 설정**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. 선택 **AdWords 변환**.

   ![](assets/image2015-2-26-16-3a54-3a47.png)

   **팁**: AdWords 전환이 없는 경우 다음을 클릭하여 만듭니다. **+새 전환**.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. 클릭 **저장**.

   ![](assets/image2015-2-26-16-3a56-3a2.png)

1. 모든 AdWords 전환을 매출 단계에 매핑한 후 요약 페이지로 돌아갑니다. 선택 **모델 작업** 및 선택 **단계 승인**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro 팁: 새 변환 추가 {#pro-tip-add-a-new-conversion}

프로 팁! Marketo에서 새 AdWords 오프라인 전환을 만들 수 있습니다.

>[!CAUTION]
>
>Marketo에서 만든 새 전환에는 &quot;최적화&quot; 설정이 활성화되어 있습니다. 즉, AdWords 입찰 전략이 그러한 전환에 대한 입찰을 최적화할 수 있습니다. AdWords 계정에서 이 설정을 변경할 수 있습니다.

1. 아래 **스테이지 작업** 드롭다운, 선택 **AdWords 변환 설정**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. 선택 **새 전환**.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. 입력 **전환 이름**. 클릭 **저장**.

   ![](assets/image2015-2-26-21-3a24-3a7.png)

   훌륭합니다! 이 새 변환은 AdWords 계정에 표시됩니다.

## 애드워즈 매핑 사용 {#use-adwords-mapping}

AdWords 매핑을 사용하여 모든 모델 단계를 AdWords 변환과 한 곳에서 연결할 수 있습니다.

1. 선택 **애드워즈 매핑 편집**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. 원하는 을 선택합니다 **AdWords 변환** 추적할 각 단계에 대해 설명합니다.

   ![](assets/image2015-2-26-17-3a6-3a15.png)

1. 단계를 매핑했으면 을 클릭합니다. **저장**.

   ![](assets/image2015-2-26-17-3a7-3a48.png)

1. 모든 AdWords 전환을 매출 단계에 매핑한 후 요약 페이지로 돌아갑니다. 선택 **모델 작업** 및 선택 **단계 승인**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

오프라인 전환 데이터를 보려면 AdWords 계정에 로그인해야 합니다. 다음 항목을 사용하는 것이 좋습니다. [사용자 정의 열 기능](https://support.google.com/adwords/answer/3073556) Marketo에서 가져오는 각 오프라인 변환에 대한 전환 카운트 열을 만들려면

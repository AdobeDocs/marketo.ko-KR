---
unique-page-id: 7504923
description: 관리자 계정 - 마케팅 문서 - 제품 설명서를 사용하여 매출 모델에서 Google AdWords 전환 설정
title: 관리자 계정으로 매출 모델에서 Google AdWords 전환 설정
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '448'
ht-degree: 0%

---


# 매출 모델에서 관리자 계정 {#set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account}으로 Google AdWords 전환 설정

Google AdWords 계정을 Marketing에 연결하여 Marketing에서 Google AdWords로 오프라인 전환 데이터를 자동으로 업로드합니다. 그런 다음 AdWords에 [사용자 지정 열](https://support.google.com/adwords/answer/3073556)을 추가한 후 AdWords UI에서 자격이 있는 리드, 기회 및 신규 고객(또는 추적하고자 하는 모든 매출 단계)이 발생한 클릭을 쉽게 확인할 수 있습니다.

Google Adwords 계정이 여러 개 있는 경우 [Google AdWords Manager 계정](https://www.google.com/adwords/manager-accounts/)(이전 내 클라이언트 센터)을 사용하여 Marketing과 통합할 수 있습니다.

매출 모델에서 하나 이상의 단계에 AdWords 오프라인 전환을 매핑할 수 있습니다. 두 가지 방법이 있습니다.

* 스테이지 동작
* AdWords 매핑

>[!PREREQUISITES]
>
>* [관리자 계정을 사용하여 Google AdWords를 Launchpoint 서비스로 추가](../../../../product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md)

>



## 스테이지 작업 사용 {#use-stage-action}

단계 작업 아래에 AdWords 전환을 매핑합니다.

1. AdWords 전환에 매핑할 단계를 선택합니다.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. **스테이지 액션** 드롭다운에서 **AdWords 전환 설정**&#x200B;을 선택합니다.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. **AdWords 전환**&#x200B;을 설정합니다.

   >[!NOTE]
   >
   >각 하위 계정에 대해 다른 AdWords 전환을 선택할 수 있습니다.

   ![](assets/image2015-3-27-17-3a16-3a37.png)

   팁:AdWords 전환이 없는 경우 **+New Conversion**&#x200B;을 클릭하여 AdWords 전환을 만듭니다.

   ![](assets/image2015-3-27-17-3a18-3a58.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-27-17-3a21-3a15.png)

1. 모든 AdWords 전환을 매출 단계에 매핑한 후 요약 페이지로 돌아갑니다. **모델 작업**&#x200B;을 선택하고 **단계 승인**&#x200B;을 선택합니다.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## 전문가 팁:새 전환 추가 {#pro-tip-add-a-new-conversion}

팁! Marketing To에서 새 AdWords 오프라인 전환을 만들 수 있습니다.

>[!CAUTION]
>
>Marketing에서 만든 새 전환에는 &quot;최적화&quot; 설정이 활성화되어 있습니다. 즉, AdWords 입찰 전략을 통해 이러한 전환에 대한 입찰을 최적화할 수 있습니다. AdWords 계정에서 이 설정을 변경할 수 있습니다.

1. **스테이지 액션** 드롭다운에서 **AdWords 전환 설정**&#x200B;을 선택합니다.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. **새 전환**&#x200B;을 선택합니다.

   ** ![](assets/image2015-3-27-17-3a23-3a13.png)

   **

1. **전환 이름**&#x200B;을 입력합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-27-17-3a24-3a49.png)

   훌륭해! 이 새 전환은 AdWords 계정에 표시됩니다.

## AdWords 매핑 사용 {#use-adwords-mapping}

AdWords 매핑을 사용하여 모든 모델 단계를 AdWords 전환과 연결할 수 있습니다.

1. **Edit AdWords 매핑**&#x200B;을 선택합니다.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. 추적할 각 스테이지에 대해 원하는 **AdWords 계정**&#x200B;과 원하는 **AdWords 전환**&#x200B;을 선택합니다.

   ![](assets/image2015-3-27-17-3a30-3a15.png)

1. 스테이지를 매핑했으면 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2015-3-27-17-3a30-3a48.png)

1. 모든 AdWords 전환을 매출 단계에 매핑한 후 요약 페이지로 돌아갑니다. **모델 작업**&#x200B;을 선택하고 **단계 승인**&#x200B;을 선택합니다.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

오프라인 전환 데이터를 보려면 AdWords 계정에 로그인해야 합니다. Marketing에서 가져오는 각 오프라인 변환에 대해 [사용자 지정 열 기능](https://support.google.com/adwords/answer/3073556)을 사용하여 전환 수 열을 만드는 것이 좋습니다.

---
unique-page-id: 10098812
description: 디지털 Advertising 캠페인 - Marketo 문서 - 제품 설명서에 대한 수익 속성 설정
title: 디지털 Advertising 캠페인에 대한 수익 속성 설정
exl-id: 7fb16c5f-7e76-429b-8b01-b5a1dd898158
feature: Social
source-git-commit: 97324d932b65020d041f728928d3792140bea71c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 0%

---

# 디지털 Advertising 캠페인에 대한 수익 속성 설정 {#set-up-revenue-attribution-for-digital-advertising-campaigns}

다음은 디지털 광고 채널 및 캠페인에 대한 매출 기여도 분석을 설정하는 방법입니다. 설정을 완료하면 다른 Marketo 프로그램과 동일한 방식으로 디지털 광고에 대한 첫 번째 터치 및 다중 터치 매출 기여도 분석을 수행할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

Marketo에서 첫 번째 광고 프로그램을 설정한 후 다른 채널에 대해 복제하고 업데이트할 수 있습니다. 예를 들어 LinkedIn 프로그램을 Facebook 프로그램으로 복제합니다.

그런 다음 별도의 프로그램을 사용하여 각 프로그램의 전환 수를 추적하고 프로그램 분석기, 영업 기회 영향 분석기 및 기타 Marketo Analytics 기능에서 프로그램을 볼 수 있습니다.

>[!PREREQUISITES]
>
>* 상태 값 및 프로그램 성공으로 채널 태그 설정(예: 디지털 Advertising 또는 소셜 유료 및 PPC)
>* 사용자를 통해 쿼리 문자열을 전달할 양식 만들기 또는 편집
>* 광고 채널 및 캠페인에 대해 보고할 수 있는 일부 수익 주기 분석 기능에 액세스할 수 있어야 합니다

## 기본 프로그램 만들기 {#create-a-default-program}

특정 기간 동안 주기적으로 실행될 수 있는 일부 프로그램(예: 이메일)과 달리 기본 프로그램은 항상 켜져 있습니다.

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/login-marketing-activities-5.png)

1. **새로 만들기**&#x200B;를 클릭하고 **새 프로그램**&#x200B;을 선택합니다.

   ![](assets/image2016-3-14-15-52-0.png)

1. 프로그램이 이미 있는 경우 [복제](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/clone-a-program.md)할 수 있습니다.

   >[!TIP]
   >
   >프로그램을 복제할 때마다 스마트 목록의 쿼리 문자열 필드에서 이름을 바꾸십시오.

1. 초기 프로그램이 설정된 후 특정 캠페인 폴더에 새 프로그램을 배치합니다.

   >[!NOTE]
   >
   >**예**
   >
   >URL을 통해 전달된 쿼리 문자열은 Marketo이 사용자가 Marketo에서 사람이 되었을 때 클릭한 광고 캠페인을 알 수 있도록 도와줍니다.
   >
   >측정하려는 모든 변수를 포함하는 쿼리 문자열 방법론을 만들 수 있습니다. Marketo은 이러한 변수를 사용하여 다른 프로그램에 사용자를 추가합니다.
   >
   >예를 들어 Channel type_Channel__Asset__Region을 사용할 수 있습니다. SP_FB_NewGuide_US와 같이 표시될 수 있습니다. **참고**: 약어는 공간을 절약합니다.
   >
   >또는 Channel_Adsource_AssetName_Region_UniqueIdNumber로 설정합니다. 다음과 같이 표시될 수 있습니다. Social-Paid_Facebook_NewGuide_NA_123.

## 새 이름에 대한 스마트 캠페인 만들기 {#create-a-smart-campaign-for-new-names}

1. 스마트 캠페인에서, 아래와 같이 두 개의 트리거와 두 개의 필터가 포함된 스마트 목록을 만듭니다.

   ![](assets/image2016-3-23-13-3a59-3a24.png)

   >[!NOTE]
   >
   >두 트리거와 **이름**&#x200B;을(를) 캡처한 프로그램 필터에 사용된 쿼리 문자열이 고유합니다. 여기에 표시된 쿼리 문자열은 예를 들면 다음과 같습니다. 필드를 복제한 경우 이러한 필드를 바꾸면 됩니다.

1. 흐름 단계를 만들어 특성을 **획득 프로그램**(으)로 변경하고 새 값을 유료 소셜 캠페인에 대해 정의한 값으로 설정합니다.

   ![](assets/image2016-3-14-14-3a58-3a6.png)

1. 캠페인을 예약하고 활성화합니다.

## 상태/프로그램 성공을 위한 스마트 캠페인 만들기 {#create-a-smart-campaign-for-status-program-success}

프로그램 성공을 달성하고 수익 속성 계산에 포함될 수 있도록 직원의 상태를 변경할 수 있는 두 번째 스마트 캠페인이 필요합니다.

1. **양식 채우기** 트리거에서 쿼리 문자열에 프로그램 이름을 입력합니다. 프로그램을 복제하는 경우 이전 쿼리 문자열 이름을 새 쿼리 문자열 이름으로 바꾸면 됩니다.

   ![](assets/image2016-3-23-14-3a7-3a20.png)

1. 흐름 단계를 만들어 프로그램 성공과 관련된 상태로 변경합니다.

   ![](assets/image2016-3-14-15-3a9-3a29.png)

   >[!NOTE]
   >
   >위의 예에서는 **전환됨**&#x200B;을 표시하지만 이는 상태/성공 값에 따라 다릅니다.

1. 캠페인을 예약하고 활성화합니다.

## 광고 만들기 {#create-your-ad}

프로그램 및 캠페인을 설정한 후 새 광고를 만듭니다.

1. 채널로 이동합니다(예: LinkedIn 또는 Facebook).
1. 새 광고를 만듭니다.
1. Marketo 랜딩 페이지를 캠페인에서 콜 투 액션의 대상으로 선택합니다.
1. URL에 쿼리 문자열을 추가합니다.

   >[!NOTE]
   >
   >**예**
   >
   >설정한 모든 정보를 실제 URL에 추가하는 방법은 다음과 같습니다. 항목은 앰퍼샌드(&amp;)로 구분됩니다.
   >
   >`www.marketo.com?**source**=Social-Paid&**comment**=Social-Paid_Facebook_NewGuide_NA&**camp**=abc&**kk=**xyz`
   >
   >* **source**&#x200B;은(는) 채널 식별자로 사용되는 개인 Source입니다.
   >* **comment**&#x200B;은(는) 각 프로그램에 대해 만들어진 고유 식별자입니다.
   >* **camp**&#x200B;은(는) Facebook, LinkedIn 또는 Google의 캠페인입니다
   >* **kk**&#x200B;은(는) 캡처할 키워드 또는 자산 이름입니다.
   >
   >**이 네 개의 용어는 모두 소문자여야 하며 URL에 이 정보를 캡처할 공백이 있을 수 없습니다.**

## 우수 사례 {#best-practices}

단일 채널 태그를 사용하여 모든 디지털 Advertising을 나타내거나, 다른 마케팅 채널(예: 소셜 유료, 검색 유료, 디스플레이, 재타겟팅)과 더 세분화된 비교를 원하는 경우 여러 채널 태그를 사용하십시오.

그런 다음 필요한 각 보고 보기에 대해 다른 프로그램을 설정합니다. 10개의 지역이 함께 &quot;Big Campaign&quot;을 시작하고 지역 간의 결과를 볼 수 있게 하려는 경우 쿼리 문자열에서 URL의 매개 변수로 일반 ID를 사용합니다(예: BC).

각 지역 및 Big Campaign의 전체 결과를 보고하려면 각 지역 및 Big Campaign에 대해 하나씩 총 11개의 프로그램을 만듭니다. 각 프로그램은 쿼리 문자열의 관련 문자만 참조합니다(BC 등).

Big Campaign과 지역 프로그램 간에 의도적으로 인원 수가 겹치므로, 일부 사람들이 Big Campaign과 지역 프로그램 중 하나에 모두 있으므로 11개 프로그램 전체의 총 인원 수를 보고하지 않으려 할 것입니다.

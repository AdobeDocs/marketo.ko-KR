---
unique-page-id: 10098812
description: 디지털 광고 캠페인에 대한 매출 속성 설정 - 마케팅 문서 - 제품 설명서
title: 디지털 광고 캠페인에 대한 매출 속성 설정
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '860'
ht-degree: 0%

---


# 디지털 광고 캠페인에 대한 매출 속성 설정 {#set-up-revenue-attribution-for-digital-advertising-campaigns}

디지털 광고 채널 및 캠페인에 대한 매출 기여도를 설정하는 방법은 다음과 같습니다. 설정을 완료하면 다른 Marketing To 프로그램과 동일한 방식으로 디지털 광고에 대해 첫 번째 접촉 및 다중 터치 매출 속성을 수행할 수 있습니다.

Marketing To에서 첫 번째 광고 프로그램을 설정한 후 다른 채널용으로 복제하여 업데이트할 수 있습니다. 예를 들어 LinkedIn 프로그램을 Facebook 프로그램으로 복제합니다.

별도의 프로그램을 사용하여 각 프로그램의 전환 수를 추적하고 프로그램 분석기, 기회 영향 분석기 및 기타 Marketing to Analytics 기능에서 프로그램을 확인할 수 있습니다.

>[!PREREQUISITES]
>
>* 상태 값 및 프로그램 성공(예: 디지털 광고 또는 소셜 유료 및 PPC)을 포함하는 채널 태그 설정
>* 양식을 만들거나 편집하여 사용자와 쿼리 문자열을 전달합니다.
>* 광고 채널 및 캠페인에 대해 보고하려면 일부 매출 주기 분석 기능에 액세스할 수 있어야 합니다

>



## 기본 프로그램 {#create-a-default-program} 만들기

특정 기간 동안 정기적으로 실행되는 일부 프로그램(예: 이메일)과 달리 기본 프로그램은 항상 켜져 있습니다.

1. **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/login-marketing-activities-5.png)

1. **새로 만들기**&#x200B;를 클릭하고 **새 프로그램**&#x200B;을 선택합니다.

   ![](assets/image2016-3-14-15-52-0.png)

1. 이미 적절한 프로그램이 있는 경우 [복제하여](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/clone-a-program.md)할 수 있습니다.

   >[!TIP]
   >
   >프로그램을 복제할 때마다 스마트 목록의 쿼리 문자열 필드에 있는 이름을 바꾸십시오.

1. 초기 프로그램이 설정된 후에 새 프로그램을 특정 캠페인 폴더에 배치합니다.

   >[!NOTE]
   >
   >**예**
   >
   >
   >URL을 통해 전달된 쿼리 문자열은 Marketing Cloud에서 개인이 되었을 때 클릭한 광고 캠페인을 알 수 있도록 도와줍니다.
   >
   >
   >측정할 모든 변수를 포함하는 쿼리 문자열 방법을 만들 수 있습니다. Marketing에서는 이러한 변수를 사용하여 다른 프로그램에 사용자를 추가합니다.
   >
   >
   >예를 들어 채널 유형_Channel__Asset__Region을 사용할 수 있습니다. 다음과 같이 표시됩니다.SP_FB_NewGuide_US. **참고**:약어는 공백을 저장합니다.
   >
   >
   >또는 Channel_Adsource_AssetName_Region_UniqueIdNumber로 설정합니다. 다음과 같이 표시됩니다.Social-Paid_Facebook_NewGuide_NA_123.

## 새 이름 {#create-a-smart-campaign-for-new-names}에 대한 스마트 캠페인 만들기

1. 스마트 캠페인에서 표시되는 대로 2개의 트리거와 2개의 필터가 포함된 스마트 목록을 만듭니다.

   ![](assets/image2016-3-23-13-3a59-3a24.png)

   >[!NOTE]
   >
   >두 개의 트리거에서 사용되는 쿼리 문자열 및 **캡처된 프로그램 이름** 필터는 사용자 고유의 값입니다. 여기에 표시된 쿼리 문자열은 예에만 있습니다. 필드를 복제한 경우 이 필드를 바꾸기만 하면 됩니다.

1. 속성을 **획득 프로그램**&#x200B;으로 변경하고 새 값을 유료 소셜 캠페인에 대해 정의한 값으로 설정합니다.

   ![](assets/image2016-3-14-14-3a58-3a6.png)

1. 캠페인을 예약하고 활성화합니다.

## 상태/프로그램 성공에 대한 스마트 캠페인 만들기 {#create-a-smart-campaign-for-status-program-success}

사람들의 상태를 변경하는 두 번째 스마트 캠페인이 필요합니다. 그래야 사람들이 프로그램 성공을 달성하고 매출 속성 계산에 포함될 수 있습니다.

1. **양식 채우기** 트리거에서 쿼리 문자열에 프로그램 이름을 입력합니다. 프로그램을 복제하는 경우 이전 쿼리 문자열 이름을 새 쿼리 문자열 이름으로 바꾸기만 하면 됩니다.

   ![](assets/image2016-3-23-14-3a7-3a20.png)

1. 프로그램 성공과 연관된 상태로 상태를 변경하는 플로우 단계를 만듭니다.

   ![](assets/image2016-3-14-15-3a9-3a29.png)

   >[!NOTE]
   >
   >위의 예는 **Converted를 **표시하지만 이것은 상태/성공 값에 따라 달라집니다.

1. 캠페인을 예약하고 활성화합니다.

## 광고 {#create-your-ad} 만들기

프로그램과 캠페인을 설정한 후 새 광고를 만듭니다.

1. 채널로 이동;예: LinkedIn 또는 Facebook.
1. 새 광고를 만듭니다.
1. 캠페인의 클릭유도문안 대상에 대한 마케팅 랜딩 페이지를 선택합니다.
1. 쿼리 문자열을 URL에 추가합니다.

   >[!NOTE]
   >
   >**예**
   >
   >
   >설정한 모든 정보를 실제 URL에 추가하는 방법은 다음과 같습니다. 항목은 앰퍼샌드(&amp;)로 구분됩니다.
   >
   >
   >[www.marketo.com?**source**=Social-Paid&amp;**comment**=Social-Paid_Facebook_NewGuide_NA&amp;**camp**=abc&amp;**kk=**xyz](http://www.marketo.com?source=Social-Paid&amp;comment=Social-Paid_Facebook_NewGUide_NA&amp;camp=abc&amp;kk+xyz)
   >
   >    
   >    
   >    * **출처: 채널 식별자로 사용되는 개인 출처** 
   >    * **각 프로그램에 대해 생성된 고유** 식별자
   >    * **캠페인** 은 Facebook, LinkedIn 또는 Google의 캠페인
   >    * **캡처할 키워드 또는 자산 이름을** 키스로 지정합니다.

   >    
   >    
   >**이 4개의 용어는 모두 소문자여야 하며 이 정보를 캡처하려면 URL에 공백이 없어야 합니다.**

## 우수 사례 {#best-practices}

단일 채널 태그를 사용하여 모든 디지털 광고를 나타내거나, 다른 마케팅 채널(예: Social-Paid, Search-Paid, Display, Retargeting)과 보다 세부적으로 비교하고자 하는 경우 다중 채널 태그를 사용합니다.

그런 다음 필요한 각 보고 보기에 대해 다른 프로그램을 설정합니다. &quot;큰 캠페인&quot;을 함께 시작하는 10개 지역이 있고 여러 지역에 걸쳐 결과를 보려는 경우 쿼리 문자열에서 URL(예: BC)의 매개 변수로 공통 ID를 사용합니다.

각 지역 및 빅캠페인의 집단 결과를 보고하려면 11개의 프로그램을 만듭니다(각 지역에 대해 1개, 큰 캠페인에 대해 1개). 각 프로그램은 쿼리 문자열(예: BC)의 관련 문자만 참조합니다.

빅캠페인과 지역 프로그램 간에 의도적인 오버랩이 있으므로, 일부 사람들이 빅캠페인과 지역 프로그램 중 하나에 있기 때문에 11개 프로그램 모두에서 총 인구 수를 보고하는 것을 원하지 않을 것입니다.

---
unique-page-id: 2949158
description: RTP를 Google Analytics - Marketo 문서 - 제품 설명서와 통합
title: RTP를 Google Analytics와 통합
exl-id: a2bc0c17-dc23-435e-9480-857e97e6fd50
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '559'
ht-degree: 2%

---

# RTP를 Google Analytics와 통합 {#integrate-rtp-with-google-analytics}

>[!NOTE]
>
>Universal Analytics는 현재 운영 표준이며 Google의 모든 속성이 Universal Analytics로 업그레이드되었습니다.
>
>이 문서에서는 이전 Google Standard Analytics를 사용하는 방법을 보여주지만 Universal Analytics로 전환하는 것이 좋습니다.
>
>아직 [analytics.js 추적 코드](https://developers.google.com/analytics/devguides/collection/analyticsjs/)를 사용하고 있지 않다면 Google에서는 사이트를 다시 태깅하여 사용할 것을 강력히 권장합니다. 다음 기능은 Google에서 더 이상 사용되지 않습니다.
>
>* ga.js
>* urchin.js
>* WAP/서버측 코드 조각
>* YT / 월
>* 사용자 지정 변수
>* 사용자 정의 변수
>
>[Web Personalization을 Universal Analytics와 통합하는 방법](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)을 참조하세요.

## 소개 {#introduction}

Marketo 실시간 Personalization(RTP)에서 Google Analytics(GA) 계정으로의 직접 데이터 흐름을 사용하여 새로운 각도에서 웹 분석을 분석합니다. 조직, 업계 및 RTP 캠페인에 따라 GA에서 웹 방문을 측정합니다. GA의 산업 또는 RTP 세그먼트 유형 및 다양한 트래픽 소스(소셜, 유료, 유기)에 따라 리드를 수행하고 생성하는 방법과 같은 지표를 보고, 캠페인의 클릭스루 비율을 분석하고, 개인화 캠페인이 웹 사이트에 미치는 영향을 측정합니다. 이 기능을 활용하여 RTP 계정의 최대 이점을 얻을 수 있습니다

**RTP Audience Analytics**

통합하면 GA 계정에 새 차원이 있습니다. RTP는 다음을 통해 대시보드를 자동으로 향상시킵니다.

1. 조직 및 업계
1. RTP에서 사용자 지정된 세그먼트
1. Account-Based Marketing 목록

주요 B2B 잠재 고객에 집중하십시오. 타겟팅된 업계 및 세그먼트별로 채널을 분석합니다.

## 채널 보고서 {#channel-report}

![](assets/image2014-11-28-16-3a39-3a28.png)

RTP B2B 대시보드는 세로 및 RTP 세그멘테이션에 따른 방문자 분류를 이해하는 데 도움이 됩니다. 금융 산업과 다양한 마케팅 캠페인(유료, 유기, 소셜)에 따라 방문자 성과를 볼 수 있습니다. 또한 대시보드는 RTP 세그먼트가 수행되는 방식에 대한 높은 수준의 개요를 제공하고 드릴다운하여 사이트를 방문하는 상위 조직을 표시합니다.

## 행동 흐름 {#behavioral-flow}

![](assets/image2014-11-28-16-3a40-3a43.png)

동작 흐름 보고서(이미지 참조)는 방문자가 한 페이지 또는 이벤트에서 다음 페이지로 이동하는 경로를 시각화합니다. 이 이미지 예제는 금융 부문의 모든 방문자 경로를 보여 줍니다. 이 보고서는 방문자가 사이트에 계속 참여할 수 있는 콘텐츠를 찾는 데 도움이 될 수 있습니다.

## RTP 성능 {#rtp-performance}

RTP 캠페인을 측정하고 이를 전체 사이트 평균과 상호 연관시킵니다. 이러한 캠페인이 웹 사이트 지표에 어떻게 영향을 미치는지 알아보고 이 데이터를 사용하여 적절한 타겟에 개인화 노력을 집중하십시오. 맞춤형 보고서를 생성하여 개인화 캠페인의 성과를 더 잘 이해합니다.

![](assets/image2014-11-28-16-3a47-3a0.png)

## Google Analytics으로 RTP 설정 {#setting-up-rtp-with-google-analytics}

1. GA 계정에 <rtp.ga2@gmail.com> 전자 메일을 읽기 및 분석 사용자로 추가합니다. 자세한 내용은 [여기](https://support.google.com/analytics/answer/2884495?hl=en)를 참조하세요.

1. RTP 계정에서 **[!UICONTROL Account Settings]**(으)로 이동합니다.

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. **[!UICONTROL Account Settings]**, **[!UICONTROL Domain]** 및 **[!UICONTROL Analytics]** 아래에 있습니다.

1. **Google Analytics**&#x200B;을(를) 클릭합니다.

1. 관련 **사용자 지정 변수** 및 **이벤트**&#x200B;를 켜서 RTP에서 이 데이터를 Google Analytics에 추가합니다.

1. 사용자 지정 변수 데이터를 전송하려면 **Slot** 번호를 입력하십시오(기본값은 1,2).

![](assets/image2014-11-28-17-3a0-3a17.png)

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

>[!NOTE]
>
>세그먼트 데이터를 GA로 보내려면 RTP 플랫폼의 [[!UICONTROL Edit Segment] 페이지](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) 아래에서 **[!UICONTROL Send Event to Google Analytics on Segment Match]** 확인란을 선택합니다.

## RTP 데이터를 사용하여 Google Analytics 보고서 설정 {#setting-up-google-analytics-reports-with-rtp-data}

Google Analytics에서 대시보드, GA 세그멘테이션 및 보고를 사용하여 RTP 데이터를 볼 수 있습니다.

* [대시보드](https://support.google.com/analytics/answer/1068216?hl=en)는 웹 사이트 성능에 대한 개요를 제공합니다.
* GA 세그먼트는 GA 인터페이스에서 방문자를 필터링하고 세그먼트당 트래픽을 보기 위한 것입니다. [여기](https://support.google.com/analytics/answer/3124493?hl=en)에서 세그먼트를 만드는 방법을 확인하세요.
* 예약된 전자 메일을 보거나 설정할 [사용자 지정된 보고서](https://support.google.com/analytics/answer/1033013?hl=en)를 만드는 중입니다. **[!UICONTROL Customization]** > **[!UICONTROL New Custom Report]**&#x200B;에서 참조하십시오.

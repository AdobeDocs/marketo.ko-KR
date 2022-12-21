---
unique-page-id: 2949158
description: RTP와 Google Analytics 통합 - Marketo 문서 - 제품 설명서
title: RTP와 Google Analytics 통합
exl-id: a2bc0c17-dc23-435e-9480-857e97e6fd50
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '608'
ht-degree: 0%

---

# RTP와 Google Analytics 통합 {#integrate-rtp-with-google-analytics}

>[!NOTE]
>
>Universal Analytics는 이제 운영 표준이며 Google의 모든 속성이 Universal Analytics로 업그레이드되었습니다.
>
>이 문서에서는 이전 Google Standard Analytics를 사용하는 방법을 보여주지만 Universal Analytics로 전환하는 것이 좋습니다.
>
>아직 [analytics.js 추적 코드](https://developers.google.com/analytics/devguides/collection/analyticsjs/)Google에서는 사이트를 다시 태깅하여 사용할 것을 강력히 권장합니다. Google은 다음 작업을 더 이상 사용하지 않습니다.
>
>* ga.js
>* urchin.js
>* WAP/서버측 코드 조각
>* YT / MO
>* 사용자 지정 변수
>* 사용자 정의 변수
>
>통합 방법 참조 [Universal Analytics를 사용한 웹 개인화](/help/marketo/product-docs/web-personalization/reporting-for-web-personalization/web-analytics-integrations/integrate-rtp-with-google-universal-analytics.md)

## 소개 {#introduction}

Marketo RTP(실시간 개인화)에서 Google Analytics(GA) 계정으로의 직접 데이터 흐름을 사용하여 웹 분석을 새로운 각도에서 분석합니다. 조직, 업계 및 RTP 캠페인에 따라 GA에서 웹 방문을 측정합니다. GA의 산업 유형 또는 RTP 세그먼트 유형과 다양한 트래픽 소스(소셜, 유료, 유기)에 따라 리드를 수행 및 생성하는 방법과 같은 지표를 보고, 캠페인의 클릭스루 비율을 분석하고, 웹 사이트에서 개인화 캠페인의 영향을 측정합니다. 이 기능을 활용하여 RTP 계정의 최대 이점을 얻을 수 있습니다

**RTP Audience Analytics**

통합을 통해 GA 계정에 새 차원이 있습니다. RTP는 다음을 통해 대시보드를 자동으로 향상시킵니다.

1. 조직 및 업계
1. RTP에서 사용자 지정된 세그먼트
1. Account-Based Marketing 목록

주요 B2B 잠재 고객 타깃팅된 업계 및 세그먼트별로 채널을 분석합니다.

## 채널 보고서 {#channel-report}

![](assets/image2014-11-28-16-3a39-3a28.png)

RTP B2B 대시보드는 수직과 RTP 세그멘테이션에 따라 방문자의 분류를 이해하는 데 도움이 됩니다. 금융 업계 및 다양한 마케팅 캠페인(유료, 유기, 소셜)에 따라 방문자 성과를 볼 수 있습니다. 또한 대시보드는 RTP 세그먼트가 수행되는 방식에 대한 개요 및 드릴다운 기능을 제공하여 사이트를 방문하는 상위 조직을 표시합니다.

## 행동 흐름 {#behavioral-flow}

![](assets/image2014-11-28-16-3a40-3a43.png)

동작 흐름 보고서(이미지 참조)는 방문자가 한 페이지 또는 이벤트에서 다음 페이지로 이동하는 경로를 시각화합니다. 이미지 예는 금융 부문의 모든 방문자의 경로를 보여줍니다. 이 보고서를 통해 방문자가 사이트에 계속 참여하는 콘텐츠를 확인할 수 있습니다.

## RTP 성능 {#rtp-performance}

RTP 캠페인을 측정하고 전체 사이트 평균과의 상관 관계를 만듭니다. 이러한 캠페인이 웹 사이트 지표에 어떻게 영향을 미치는지 알아보고 이 데이터를 사용하여 올바른 타겟에 개인화 노력을 집중할 수 있습니다. 사용자 지정된 보고서를 생성하여 개인화 캠페인의 성과를 더 잘 이해할 수 있습니다.

![](assets/image2014-11-28-16-3a47-3a0.png)

## Google Analytics을 사용하여 RTP 설정 {#setting-up-rtp-with-google-analytics}

1. GA 계정에 읽기 및 분석 사용자로 이메일 rtp.ga2@gmail.com 을 추가합니다. 자세한 내용은 [여기](https://support.google.com/analytics/answer/2884495?hl=en).

1. RTP 계정에서 다음을 수행합니다. 이동 **계정 설정**.

   ![](assets/image2014-11-28-16-3a54-3a40.png)

1. 아래 **계정 설정**, **도메인** 및 **Analytics**.

1. 클릭 **Google Analytics**.

1. 관련 사항 설정 **사용자 지정 변수** 및 **이벤트** RTP에서 Google Analytics에 이 데이터를 추가합니다.

1. 을(를) 입력합니다. **슬롯** 사용자 지정 변수 데이터를 전송하는 번호(기본값은 1,2)입니다.

![](assets/image2014-11-28-17-3a0-3a17.png)

1. 클릭 **저장**.

>[!NOTE]
>
>세그먼트 데이터를 GA에 보내려면 [세그먼트 편집 페이지](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md) RTP 플랫폼에서 확인란을 선택합니다 **세그먼트 일치 시 Google Analytics에게 이벤트 보내기**.

## RTP 데이터를 사용하여 Google Analytics 보고서 설정 {#setting-up-google-analytics-reports-with-rtp-data}

Google Analytics에서 대시보드, GA 세그멘테이션 및 보고를 사용하여 RTP 데이터를 볼 수 있습니다.

* [대시보드](https://support.google.com/analytics/answer/1068216?hl=en) 웹 사이트 성능에 대한 개요를 제공합니다.
* GA 세그먼트는 GA 인터페이스에서 방문자를 필터링하고 세그먼트당 트래픽을 보기 위한 것입니다. 세그먼트 빌드 방법 참조 [여기](https://support.google.com/analytics/answer/3124493?hl=en).
* 만들기 [사용자 지정 보고서](https://support.google.com/analytics/answer/1033013?hl=en) 예약된 이메일을 보거나 설정하려면 다음을 수행하십시오. 사용자 지정 > 새 사용자 지정 보고서에서 을 참조하십시오.

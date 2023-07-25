---
unique-page-id: 4720125
description: RTP를 Google Universal Analytics - Marketo 문서 - 제품 설명서와 통합
title: RTP를 Google Universal Analytics와 통합
exl-id: e8fc8730-c91d-44ad-8843-aa5b38f1ebd1
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '456'
ht-degree: 0%

---

# RTP를 Google Universal Analytics와 통합 {#integrate-rtp-with-google-universal-analytics}

## 소개 {#intro}

Google Real-Time Personalization (RTP) 그래픽 및 개인화 데이터와 함께 GUA(Marketo Universal Analytics)를 활용하여 온라인 마케팅 활동을 더 잘 측정하고 분석할 수 있습니다.

이 게시물에서는 Marketo 실시간 개인화 (RTP) 플랫폼을 Google Universal Analytics (GUA) 계정과 통합하는 방법을 설명합니다. RTP 데이터를 GUA 계정에 추가하여 웹 사이트를 방문하는 조직, 업계, 펌웨어 및 RTP 세그먼트의 성능을 보고 확인할 수 있습니다.

**Google 유니버설 애널리틱스**

RTP의 데이터가 포함된 Google Universal Analytics를 사용하면 B2B 사용자가 온라인 컨텐츠와 상호 작용하는 방법을 더 잘 이해하고 개인화 캠페인을 측정하여 더 나은 결과를 얻을 수 있습니다. [Google Universal Analytics에 대해 자세히 알아보기](https://support.google.com/analytics/answer/2790010/?hl=en&amp;authuser=1).

>[!NOTE]
>
>**Google Tag Manager 사용자 전용**
>
>코딩이나 특수 구성을 수행할 필요가 없습니다. 다음 체크리스트를 완료하십시오.
>
>* RTP 차원은 Google Universal Analytics에서 만들어집니다
>* [RTP 태그가 Google Tag Manager에 올바르게 설치됨](https://docs.marketo.com/display/public/DOCS/Implementing+RTP+using+Google+Tag+Manager)
>* Google Universal Analytics 통합이 RTP의 계정 설정에서 활성화됩니다
>* [Google Universal Analytics 태그가 Google 태그 관리자에 올바르게 구성되어 있음](https://support.google.com/tagmanager/answer/6107124?hl=en)
>* [웹 사이트에 Google Tag Manager 태그가 올바르게 설치됨](https://developers.google.com/tag-manager/quickstart)

## GUA에서 사용자 정의 Dimension 설정 {#set-up-custom-dimensions-in-gua}

1. Google Analytics,

   1. 다음으로 이동 **관리자**
   1. 다음 항목 선택 **계정.**
   1. 다음 항목 선택 **속성.**
   1. 선택 **사용자 정의** 및 **사용자 지정 Dimension**.
      ![](assets/image2014-11-29-11-3a2-3a32.png)

1. 새 사용자 지정 차원을 추가합니다. 클릭 **+새 사용자 지정 Dimension**

   ![](assets/image2014-11-29-11-3a8-3a16.png)

1. 다음 추가 **사용자 지정 Dimension:**

<table> 
 <tbody> 
  <tr> 
   <td><p><strong>사용자 정의 Dimension 이름</strong></p></td> 
   <td><p><strong>범위</strong></p></td> 
   <td><p><strong>활성</strong></p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-조직</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓ 덧신</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-업계</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP 범주</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP 그룹</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>**사용자 정의 Dimension 이름** 위의 표에 정의된 대로 정확히 정의해야 합니다(그렇지 않으면 GUA의 사용자 정의 RTP 대시보드 및 보고서가 올바르게 표시되지 않음).

1. 추가 **이름**. 다음으로 범위 선택 **세션**. Click **Create**.

   ![](assets/image2014-11-29-11-3a12-3a51.png)

사용자 지정 Dimension 목록은 다음과 같아야 합니다.

![](assets/image2014-11-29-11-36-50-version-2.png)

GUA에서 사용자 정의 Dimension을 활성화했으면 RTP 플랫폼으로 이동하여 RTP 내에서 이러한 차원을 활성화합니다.

## RTP 계정에서 GUA 통합 활성화 {#activate-the-gua-integration-in-your-rtp-account}

1. RTP 플랫폼에서 로 이동합니다. **계정 설정.**

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. 아래 **계정 설정**, 클릭 **도메인**.
1. 아래 **분석**, 클릭 **Google 유니버설 애널리틱스**.
1. 회전 **날짜** 관련 사용자 지정 Dimension 및 이벤트 를 사용하여 RTP에서 Google Universal Analytics로 이 데이터를 추가합니다.
1. 다음을 입력합니다. **색인 번호** GUA의 색인 번호와 정렬된 치수의 경우입니다.
1. 클릭 **저장**.

![](assets/image2014-11-29-11-31-23-version-2.png)

>[!NOTE]
>
>사용자 지정 Dimension의 색인 번호는 사용자 지정 Dimension 아래의 GUA에 있습니다.
>
>예: RTP-Industry Index Number 는 1, RTP-Organization Index Number 는 2 입니다.

## Google Analytics에서 이전 대시보드 제거 {#remove-old-dashboards-in-google-analytics}

1. Google Analytics. 다음으로 이동 **보고.**
1. 클릭 **대시보드.**
1. 선택 **대시보드** (RTP B2B 또는 RTP 성능)
1. 클릭 **대시보드 삭제**.

![](assets/image2014-11-29-11-3a42-3a55.png)

---
unique-page-id: 4720125
description: RTP를 Google Universal Analytics - Marketing Docs - 제품 문서와 통합
title: Google Universal Analytics와 RTP 통합
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '432'
ht-degree: 0%

---


# Google Universal Analytics와 RTP 통합 {#integrate-rtp-with-google-universal-analytics}

## 인트로 {#intro}

Marketing to Real-Time Personalization&#39;s (RTP) 1차 및 개인화 데이터와 함께 Google Universal Analytics(GUA)를 활용하여 온라인 마케팅 활동을 보다 효과적으로 측정 및 분석할 수 있습니다.

이 게시물은 Marketing to Real-Time Personalization(RTP) 플랫폼을 Google Universal Analytics(GUA) 계정과 통합하는 방법을 설명합니다. RTP 데이터는 GUA 계정에 추가되므로 웹 사이트를 방문하는 조직, 산업, 초기 그래픽 및 RTP 세그먼트의 성과를 보고 확인할 수 있습니다.

**Google Universal Analytics**

RTP의 데이터가 포함된 Google Universal Analytics를 사용하면 B2B 사용자가 온라인 컨텐츠와 상호 작용하는 방법을 보다 잘 이해할 수 있고 개인화 캠페인을 통해 더 나은 결과를 얻을 수 있습니다. [Google Universal Analytics에 대한 자세한 내용을 참조하십시오](https://support.google.com/analytics/answer/2790010/?hl=en&amp;authuser=1).

>[!NOTE]
>
>**`For Google Tag Manager Users Only`**
>
>코딩 또는 특수 구성은 필요 없습니다. 다음 체크리스트를 완료해야 합니다.
>
>* `RTP dimensions are created in Google Universal Analytics`
>* [RTP 태그가 Google 태그 관리자에 올바르게 설치됨](https://docs.marketo.com/display/public/DOCS/Implementing+RTP+using+Google+Tag+Manager)
>* `Google Universal Analytics Integration is enabled in the RTP's Account Settings`
>* [Google Universal Analytics 태그가 Google Tag Manager에서 올바르게 구성되어 있습니다.](https://support.google.com/tagmanager/answer/6107124?hl=en)
>* [Google Tag Manager 태그가 웹 사이트에 올바르게 설치되어 있습니다.](https://developers.google.com/tag-manager/quickstart)

>



## GUA에서 사용자 정의 Dimension 설정 {#set-up-custom-dimensions-in-gua}

1. Google Analytics에서

   1. 관리자로 **이동**
   1. 계정을 **선택합니다.**
   1. 속성을 **선택합니다.**
   1. **사용자 정의 정의 **와 사용자 정의 Dimension을 **선택합니다.**

      ![](assets/image2014-11-29-11-3a2-3a32.png)

1. 새 사용자 지정 차원을 추가합니다. 클릭 **+새 사용자 지정 Dimension**

   ![](assets/image2014-11-29-11-3a8-3a16.png)

1. 다음 사용자 지정 **Dimension을 추가합니다.**

<table> 
 <tbody> 
  <tr> 
   <td><p><strong>사용자 지정 Dimension 이름</strong></p></td> 
   <td><p><strong>범위</strong></p></td> 
   <td><p><strong>활성</strong></p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-조직</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Industry</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Category</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
  <tr> 
   <td><p><strong>RTP-Group</strong></p></td> 
   <td><p>세션</p></td> 
   <td><p align="center">✓</p></td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>**사용자 지정 Dimension 이름은** 위 표에 정의된 것과 정확히 같아야 합니다(그렇지 않으면 GUA에 있는 사용자 지정 RTP 대시보드 및 보고서가 올바로 표시되지 않음).

1. **이름을 추가합니다. **범위를 세션으로 **선택합니다.** 만들기를 **클릭합니다.**

   ![](assets/image2014-11-29-11-3a12-3a51.png)

사용자 지정 Dimension 목록은 다음과 같아야 합니다.

![](assets/image2014-11-29-11-36-50-version-2.png)

GOA에서 사용자 지정 Dimension을 활성화한 후 RTP 플랫폼으로 이동하여 RTP 내에서 이러한 차원을 활성화합니다.

## RTP 계정에서 GUA 통합 활성화 {#activate-the-gua-integration-in-your-rtp-account}

1. RTP 플랫폼에서 계정 **설정으로 이동합니다.**

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. 계정 **설정에서**&#x200B;도메인을 **클릭합니다.**
1. **Analytics 아래에서 ** **Google Universal Analytics를 클릭합니다**.
1. 관련 **사용자** 지정 Dimension 및 이벤트를 설정하여 이 데이터를 RTP에서 Google Universal Analytics에 추가합니다.
1. GUA에서 **색인 번호와** 정렬된 차원의 인덱스 번호를 입력합니다.
1. 저장을 **클릭합니다**.

![](assets/image2014-11-29-11-31-23-version-2.png)

>[!NOTE]
>
>사용자 정의 Dimension의 색인 번호는 사용자 정의 Dimension 아래에 있는 GUA에서 찾을 수 있습니다.
>
>예:RTP-산업 인덱스 번호는 1이고, RTP-조직 인덱스 번호는 2입니다.

## Google Analytics에서 이전 대시보드 제거 {#remove-old-dashboards-in-google-analytics}

1. Google Analytics에서 보고로 **이동합니다.**
1. 대시보드를 **클릭합니다.**
1. **대시보드 **(RTP B2B 또는 RTP 성능)를 선택합니다.
1. 대시보드 **삭제를 클릭합니다**.

![](assets/image2014-11-29-11-3a42-3a55.png)


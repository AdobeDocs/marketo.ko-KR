---
unique-page-id: 4720796
description: 웹 개인화 데이터를 사용한 재타겟팅 - Marketo 문서 - 제품 설명서
title: 웹 개인화 데이터를 사용하여 재타겟팅
exl-id: b5af1f84-2061-4d0d-9d1f-2fff9191f028
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# 웹 개인화 데이터를 사용하여 재타겟팅 {#retargeting-with-web-personalization-data}

>[!AVAILABILITY]
>
>이제 웹 사이트 재타깃팅이 웹 개인화 타일에 포함됩니다. 리타겟팅만 구입한 경우 이 타일이 표시되고 **전용** 재타겟팅 기능이 활성화되었습니다. 계정 설정, 재타겟팅 페이지, 세그먼트 및 추가 추적 페이지에 액세스할 수 있습니다.

리마케팅 타겟팅은 사용자의 신원과 행동을 기반으로 디스플레이 광고를 통해 과거에 사이트를 방문한 잠재 고객을 대상으로 합니다. 개인화된 재타겟팅은 업계, 명명 계정 및 알려진 개인 데이터를 기반으로 관련 광고를 사용하여 특정 대상을 타겟팅합니다.

웹 개인화는 현재 다음 리마케팅 플랫폼에 데이터를 추가합니다.

* [Google](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)
* [Facebook](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)

웹 개인화는 다음 데이터를 리마케팅 플랫폼으로 전송하여 대상을 만들고 리마케팅 광고 캠페인을 실행합니다.

<table> 
 <tbody> 
  <tr> 
   <th colspan="1">웹 개인화 데이터</th> 
  </tr> 
  <tr> 
   <th><p>산업</p></th> 
  </tr> 
  <tr> 
   <th><p>그룹(엔터프라이즈, SMB)</p></th> 
  </tr> 
  <tr> 
   <th><p>카테고리(Fortune 500/1000, 글로벌 2000년)</p></th> 
  </tr> 
  <tr> 
   <th><p>ABM 목록(명명된 계정 목록)</p></th> 
  </tr> 
  <tr> 
   <th><p>세그먼트화된 대상(세그먼트 기반)</p></th> 
  </tr> 
  <tr> 
   <th><p>클릭한 웹 캠페인</p></th> 
  </tr> 
 </tbody> 
</table>

## 리마케팅 구성 {#remarketing-configuration}

1. 이동 **재타겟팅**.

   ![](assets/one.png)

   >[!NOTE]
   >
   >재타겟팅 구성은 도메인 또는 하위 도메인별로 이루어집니다. 해당 도메인에서 재타겟팅 플랫폼으로 데이터를 전송하려면 다른 도메인을 활성화합니다.

1. 도메인별 Google Analytics 또는 Google Universal Analytics에 대한 설정 을 활성화합니다.

   >[!NOTE]
   >
   >웹 사이트에 Google 리타겟팅 태그를 구현해야 합니다.
   >
   >웹 개인화 및 Google Analytics과 통합을 이미 설정한 경우 계정 설정에서 동일한 구성이므로 이 부분을 편집할 필요가 없습니다.

   ![](assets/two.png)

1. facebook에 대한 구성을 활성화합니다. facebook 아코디언을 클릭하고 확장합니다. **설정** 각 이벤트 및 데이터를 Facebook Audience Manager으로 전송합니다. 클릭 **저장**.

   >[!NOTE]
   >
   >다음을 수행해야 합니다. [Facebook 사용자 지정 대상 픽셀](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel)이 기능이 작동하도록 웹 사이트를 설치했습니다.

   ![](assets/three.png)

## 세그먼트화된 대상 만들기 {#creating-segmented-audience}

세그먼트화된 대상을 사용하면 기존 세그먼트를 리타겟팅하는 캠페인에 사용할 대상으로 선택할 수 있습니다. 예를 들어 알려진 개인 세그먼트 선택

>[!TIP]
>
>도메인 구성에서 이미 전송한 업계 또는 기타 데이터에 대해 세그먼트화된 대상을 만들 필요가 없습니다. 알려진 개인 데이터를 기반으로 세그먼트화된 대상을 세그먼트에 사용하는 것이 가장 좋습니다.

1. 클릭 **세그먼트화된 대상 만들기**.

   ![](assets/image2015-1-15-16-3a36-3a38.png)

1. 대상 이름을 입력하고 채널을 선택한 다음, 기존 세그먼트 목록에서 세그먼트 를 선택합니다.

   ![](assets/image2015-1-15-16-3a40-3a17.png)

1. 클릭 **저장**.

   이제 웹 개인화에서 재타겟팅 설정을 완료하고, 재타겟팅 플랫폼에 로그인하여 이 데이터를 기반으로 대상을 만들고, 재타겟팅 광고 캠페인을 설정했습니다.

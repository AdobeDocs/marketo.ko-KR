---
unique-page-id: 4720917
description: facebook의 개인화된 리마케팅 - Marketo 문서 - 제품 설명서
title: facebook의 개인화된 리마케팅
exl-id: 47636afa-49df-40ba-8948-4f2850467c2f
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 1%

---

# facebook의 개인화된 리마케팅 {#personalized-remarketing-in-facebook}

개인화된 리마케팅을 사용하면 RTP 데이터 및 Facebook 리마케팅의 기능을 사용하여 사용자와 다시 연결할 수 있습니다.

>[!PREREQUISITES]
>
>* 다음을 완료합니다. [웹 개인화 데이터를 사용하여 재타겟팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) 설정
>* 리뷰 [](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [사용자 지정 대상에 대한 facebook 설명서](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) 및 리마케팅

## facebook에서 대상 만들기 {#creating-an-audience-in-facebook}

1. facebook에서 [대상 탭](https://www.facebook.com/ads/audience_manager) 광고 관리자에서.

1. 클릭 **도구** 및 선택 **대상**.

   ![](assets/one-1.png)

1. 클릭 **사용자 지정 대상 만들기**.

   ![](assets/two-1.png)

1. 선택 **웹 사이트 트래픽**.

   ![](assets/image2015-1-19-16-3a32-3a2.png)

1. 웹 사이트 트래픽 목록에서 **사용자 정의 조합**.

   ![](assets/image2015-1-19-16-3a33-3a21.png)

1. 포함 목록에서 **이벤트**.

   ![](assets/image2015-1-19-16-3a34-3a9.png)

1. 이벤트 목록에서 다음을 선택합니다. **RTP 리마케팅** 매개 변수를 선택합니다.

   ![](assets/image2015-1-19-16-3a52-3a29.png)

1. 이 예에서는 포함할 산업을 선택합니다 **교육**. 입력 **교육**, 및 편집 **마지막** 180일이 될 거야 대상 이름 입력: **교육 산업**. 클릭 **대상자 만들기**.

   ![](assets/image2015-1-19-16-3a56-3a15.png)

1. 이제 Facebook에서 RTP 데이터를 사용하여 새 사용자 지정 대상을 만들었습니다.

   ![](assets/image2015-1-19-16-3a59-3a2.png)

## facebook의 RTP 데이터 포인트 {#rtp-data-points-in-facebook}

<table> 
 <tbody> 
  <tr> 
   <th>이벤트 이름</th> 
   <th> </th> 
  </tr> 
  <tr> 
   <td>RTP 리마케팅</td> 
   <td> 
    <div> 
     <table> 
      <tbody> 
       <tr> 
        <th>매개 변수</th> 
        <th>값</th> 
       </tr> 
       <tr> 
        <td>ABM 목록</td> 
        <td>(계정 기반 목록 이름)</td> 
       </tr> 
       <tr> 
        <td colspan="1">범주</td> 
        <td colspan="1"><p>Fortune</p><p>Fortune</p><p>글로벌 2000</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">그룹</td> 
        <td colspan="1"><p>엔터프라이즈</p><p>중소기업</p></td> 
       </tr> 
       <tr> 
        <td>산업</td> 
        <td><p>방어</p><p>교육</p><p>금융 서비스</p><p>정부</p><p>의료, 제약, 생명 공학</p><p>소프트웨어 및 인터넷</p><p>등(RTP 업계 옵션에 따라)</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">세분화된 대상자</td> 
        <td colspan="1">(RTP에서 생성된 세그먼트화된 대상자의 이름)</td> 
       </tr> 
      </tbody> 
     </table> 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## 광고로 대상자 Target {#target-your-audience-with-an-ad}

자세한 내용은 [Facebook 설명서](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience).

1. 광고 관리자로 이동하여 **광고 만들기**.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. 선택 **웹 사이트로 사람 보내기** 를 캠페인의 목표로 설정합니다.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. 웹 사이트 URL을 입력합니다.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. 광고 세트를 만듭니다. 만든 대상 목록에서 사용자 정의 대상을 선택합니다(예: Education Industry).

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. 다른 광고 세트 옵션을 모두 선택하고 예산을 설정하고 광고 크리에이티브를 정의합니다.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. 이제 Facebook에서 개인화된 리마케팅 캠페인을 모두 설정했습니다.

>[!MORELIKETHIS]
>
>* [웹 개인화 데이터를 사용하여 재타겟팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Google의 개인화된 리마케팅](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)

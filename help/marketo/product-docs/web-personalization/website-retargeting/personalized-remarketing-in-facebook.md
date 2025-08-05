---
unique-page-id: 4720917
description: Facebook의 개인화된 리마케팅 - Marketo 문서 - 제품 설명서
title: Facebook의 개인화된 리마케팅
exl-id: 47636afa-49df-40ba-8948-4f2850467c2f
feature: Web Personalization
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 6%

---

# [!DNL Facebook]의 개인화된 리마케팅 {#personalized-remarketing-in-facebook}

개인화된 리마케팅을 사용하면 RTP 데이터와 Facebook 리마케팅의 기능을 사용하여 사용자와 다시 연결할 수 있습니다.

>[!PREREQUISITES]
>
>* [웹 Personalization 데이터를 사용하여 다시 타깃팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) 설정을 완료합니다.
>* 사용자 지정 대상[ 및 리마케팅에 대한 ](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [&#128279;](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel)Facebook 설명서를 검토하십시오.

## [!DNL Facebook]에서 대상을 만드는 중 {#creating-an-audience-in-facebook}

1. [!DNL Facebook]에서 Ads Manager의 [대상자 탭](https://www.facebook.com/ads/audience_manager)&#x200B;(으)로 이동합니다.

1. **[!UICONTROL Tools]**&#x200B;을(를) 클릭하고 **[!UICONTROL Audiences]**&#x200B;을(를) 선택합니다.

![](assets/one-1.png)

1. **[!UICONTROL Create a Custom Audience]**&#x200B;을(를) 클릭합니다.

![](assets/two-1.png)

1. **[!UICONTROL Website Traffic]**&#x200B;를 선택합니다.

![](assets/image2015-1-19-16-3a32-3a2.png)

1. [!UICONTROL Website traffic] 목록에서 **[!UICONTROL Custom Combination]**&#x200B;을(를) 선택합니다.

![](assets/image2015-1-19-16-3a33-3a21.png)

1. 포함 목록에서 **[!UICONTROL Event]**&#x200B;을(를) 선택합니다.

![](assets/image2015-1-19-16-3a34-3a9.png)

1. [!UICONTROL Event] 목록에서 **[!UICONTROL RTP Remarketing]**&#x200B;을(를) 선택하고 매개 변수를 선택합니다.

![](assets/image2015-1-19-16-3a52-3a29.png)

1. 이 예제에서는 [!UICONTROL Industry]을(를) 포함할 **[!UICONTROL Education]**&#x200B;을(를) 선택합니다. **[!UICONTROL Education]**&#x200B;을(를) 입력하고 **[!UICONTROL In the Last]**&#x200B;을(를) 180일로 편집합니다. 대상 이름 입력: **교육 산업**. **[!UICONTROL Create Audience]**&#x200B;을(를) 클릭합니다.

![](assets/image2015-1-19-16-3a56-3a15.png)

1. 이제 [!DNL Facebook]에서 RTP 데이터를 사용하여 새 사용자 지정 대상을 만들었습니다.

![](assets/image2015-1-19-16-3a59-3a2.png)

## [!DNL Facebook]의 RTP 데이터 포인트 {#rtp-data-points-in-facebook}

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
        <th>매개변수</th>
        <th>값</th>
       </tr>
       <tr>
        <td>ABM 목록</td>
        <td>(계정 기반 목록 이름)</td>
       </tr>
       <tr>
        <td colspan="1">카테고리</td>
        <td colspan="1"><p>Fortune 500</p><p>Fortune 1000</p><p>글로벌 2000</p></td>
       </tr>
       <tr>
        <td colspan="1">그룹</td>
        <td colspan="1"><p>엔터프라이즈</p><p>중소기업</p></td>
       </tr>
       <tr>
        <td>업종</td>
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

## 광고로 대상자 타겟팅 {#target-your-audience-with-an-ad}

자세한 내용은 [Facebook 설명서](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience)를 참조하세요.

1. 광고 관리자로 이동하여 **[!UICONTROL Create Ad]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. **[!UICONTROL Send people to your website]**&#x200B;을(를) 캠페인 목표로 선택합니다.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. 웹 사이트 URL을 입력합니다.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. 광고 세트를 만듭니다. 만든 대상 목록에서 사용자 정의 대상을 선택합니다(예: Education Industry).

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. 다른 광고 세트 옵션을 모두 선택하고 예산을 설정하고 광고 크리에이티브를 정의합니다.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. 이제 모두 [!DNL Facebook]에서 개인화된 리마케팅 캠페인을 설정했습니다.

>[!MORELIKETHIS]
>
>* [웹 Personalization 데이터를 사용하여 재타겟팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Google에서 개인화된 리마케팅](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.md)

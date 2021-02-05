---
unique-page-id: 4720917
description: Facebook에서 개인화된 리마케팅 - 마케팅 문서 - 제품 설명서
title: Facebook에서 개인화된 리마케팅
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '309'
ht-degree: 0%

---


# Facebook에서 개인화된 리마케팅 {#personalized-remarketing-in-facebook}

개인화된 리마케팅을 사용하면 RTP 데이터와 Facebook 리마케팅의 강력한 기능을 사용하여 사용자와 다시 교류할 수 있습니다.

>[!PREREQUISITES]
>
>* 웹 개인화 데이터](retargeting-with-web-personalization-data.md) 설정을 사용하여 [리타깃팅 완료
>* 사용자 지정 대상](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel)과 리마케팅에 대한 [](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#install-the-pixel) [Facebook 설명서를 검토하십시오.

>



## Facebook {#creating-an-audience-in-facebook}에서 대상자 만들기

1. Facebook에서 광고 관리자의 [대상 탭](https://www.facebook.com/ads/audience_manager)으로 이동합니다.
1. **도구**&#x200B;를 클릭하고 **대상**&#x200B;을 선택합니다.

   ![](assets/one-1.png)

1. **사용자 지정 대상 만들기**&#x200B;를 클릭합니다.

   ![](assets/two-1.png)

1. **웹 사이트 트래픽**&#x200B;을 선택합니다.

   ![](assets/image2015-1-19-16-3a32-3a2.png)

1. 웹 사이트 트래픽 목록에서 사용자 지정 조합** 선택합니다**.

   ![](assets/image2015-1-19-16-3a33-3a21.png)

1. 포함 목록에서 **이벤트**&#x200B;를 선택합니다.

   ![](assets/image2015-1-19-16-3a34-3a9.png)

1. 이벤트 목록에서 **RTP 리마케팅 **을 선택하고 매개 변수를 선택합니다.

   ![](assets/image2015-1-19-16-3a52-3a29.png)

1. 이 예제의 경우 **교육**&#x200B;을 포함하려면 산업을 선택합니다. **교육**&#x200B;을 입력하고 마지막&#x200B;**에서 180일이 되도록**&#x200B;을 편집합니다. 대상자 이름 입력:**교육 업계**. **대상자 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-1-19-16-3a56-3a15.png)

1. 이제 Facebook에서 RTP 데이터를 사용하여 새 사용자 지정 대상을 만들었습니다.

   ![](assets/image2015-1-19-16-3a59-3a2.png)

## Facebook의 RTP 데이터 포인트 {#rtp-data-points-in-facebook}

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
        <td colspan="1">카테고리</td> 
        <td colspan="1"><p>Fortune 500</p><p>Fortune 1000</p><p>2000 글로벌</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">그룹</td> 
        <td colspan="1"><p>엔터프라이즈</p><p>SMB</p></td> 
       </tr> 
       <tr> 
        <td>업계</td> 
        <td><p>방위</p><p>교육 기관</p><p>금융 서비스</p><p>정부</p><p>의료, Pharma, 생명 공학</p><p>소프트웨어 및 인터넷</p><p>등.(RTP 산업 옵션에 따라)</p></td> 
       </tr> 
       <tr> 
        <td colspan="1">고객 세분화</td> 
        <td colspan="1">(RTP에서 생성된 세그먼트화된 대상의 이름)</td> 
       </tr> 
      </tbody> 
     </table> 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## 광고 {#target-your-audience-with-an-ad}으로 대상 Target

자세한 내용은 [Facebook 설명서](https://developers.facebook.com/docs/ads-for-websites/website-custom-audiences/getting-started#target-your-audience)를 참조하십시오.

1. 광고 관리자로 이동하고 **광고 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-1-19-17-3a10-3a19.png)

1. 캠페인의 목표로 **웹 사이트**&#x200B;로 인물 보내기를 선택합니다.

   ![](assets/image2015-1-19-17-3a11-3a20.png)

1. 웹 사이트 URL을 입력합니다.

   ![](assets/image2015-1-19-17-3a12-3a39.png)

1. 광고 세트를 만듭니다. 만든 대상 목록(예: 교육 산업)에서 사용자 지정 대상자를 선택합니다.

   ![](assets/image2015-1-19-17-3a18-3a13.png)

1. 다른 모든 광고 세트 옵션을 선택하고 예산을 설정하고 광고 크리에이티브를 정의합니다.

   ![](assets/image2015-1-19-17-3a19-3a25.png)

1. 이제 Facebook에서 개인화된 리마케팅 캠페인이 준비됩니다.

>[!MORELIKETHIS]
>
>* [웹 개인화 데이터를 사용한 리타겟팅](retargeting-with-web-personalization-data.md)
>* [Google에서 개인화된 리마케팅](personalized-remarketing-in-google.md)

>




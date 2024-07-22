---
unique-page-id: 4720810
description: Google의 개인화된 리마케팅 - Marketo 문서 - 제품 설명서
title: Google의 개인화된 리마케팅
exl-id: cc733f43-161d-41e4-afdf-8b5217700810
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '293'
ht-degree: 0%

---

# Google의 개인화된 리마케팅 {#personalized-remarketing-in-google}

개인화된 리마케팅을 사용하면 Google Display Network를 통해 RTP 데이터와 Google Analytics 기능을 사용하여 사용자와 다시 연결할 수 있습니다.

>[!PREREQUISITES]
>
>* [웹 Personalization 데이터를 사용하여 다시 타깃팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md) 구성을 완료합니다.
>* [Google Analytics 도움말로 리마케팅](https://support.google.com/analytics/topic/2611283?hl=en&amp;ref_topic=3413645) 설명서를 검토하십시오.

## Google에서 리마케팅 대상 만들기 {#creating-a-remarketing-audience-in-google}

1. Google Analytics에 로그인합니다. **관리자**, **계정**, **속성**&#x200B;을 클릭합니다. **대상 정의** 및 **대상**&#x200B;을 클릭합니다.

   ![](assets/remarketing-ga-screenshots.jpg)

1. **+새 대상**&#x200B;을 클릭합니다.

   ![](assets/image2015-1-15-17-3a26-3a40.png)

1. **링크 구성**: Google Adwords 계정에 연결합니다. **대상 정의**: **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-1-15-17-3a32-3a4.png)

1. 대상 빌더에서 **시퀀스**&#x200B;를 클릭하고 사용자 지정 Dimension, 사용자 지정 변수, 이벤트에서 **RTP 데이터 찾기**&#x200B;를 클릭합니다.

>[!TIP]
>
>Analytics에서 RTP 데이터를 찾아 대상을 작성하는 방법
>
>Google Analytics:
>
>* 사용자 지정 변수: 조직, 업계
>* 이벤트 카테고리: Segment, Insightera-CTA, RTP-Remarketing
>* 이벤트 레이블: 세그먼트 이름, 캠페인 이름, 세그먼트화된 대상자 이름
>
>Google Universal Analytics에서
>
>* 사용자 정의 Dimension: 조직, 업계, 범주(Fortune 500,1000, Global 2000), 그룹(엔터프라이즈, SMB), ABM 목록(지정 계정 목록)
>* 이벤트 범주: RTP-Segment, RTP-Campaign RTP-Remarketing
>* 이벤트 레이블: 세그먼트 이름, 캠페인 이름, 세그먼트화된 대상자 이름

**RTP로 세그먼트화된 대상 데이터에서 리마케팅 대상의 예**

1. **시퀀스**&#x200B;를 클릭합니다.
1. **이벤트 레이블 선택**
1. RTP에 표시되는 대로 **세그먼트화된 대상자의 이름**&#x200B;을 입력하십시오.
1. **적용**&#x200B;을 클릭합니다.

![](assets/image2015-2-10-14-3a51-3a43.png)

**RTP 업계 데이터의 대상 예제**

![](assets/image2015-1-15-17-3a36-3a5.png)

1. **시퀀스**&#x200B;를 클릭합니다.
1. **RTP-Industry**&#x200B;을 선택합니다.
1. **업계 이름**&#x200B;을(를) 입력하십시오(예: 금융 서비스, 교육...)
1. **적용**&#x200B;을 클릭합니다.
1. **대상 이름**&#x200B;을 입력하십시오. **저장**&#x200B;을 클릭합니다.

![](assets/image2015-1-15-18-3a29-3a16.png)

## Google Adwords에서 리마케팅 광고 캠페인 만들기 {#create-a-remarketing-ad-campaign-in-google-adwords}

1. **Google Adwords**&#x200B;에 로그인합니다. **캠페인**&#x200B;을 클릭하고 **네트워크만 표시**&#x200B;를 선택합니다.

   ![](assets/image2015-1-15-18-3a31-3a58.png)

1. **캠페인 이름**&#x200B;을 입력하고 **리마케팅 유형**&#x200B;을 선택하세요.

   ![](assets/image2015-1-15-18-3a35-3a7.png)

1. **광고 그룹 이름**&#x200B;을(를) 입력하고 **향상된 CPC**&#x200B;을(를) 입력하고 **리마케팅 목록**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-1-15-18-3a51-3a57.png)

1. 저장 을 클릭하고 계속합니다.
1. 이미지 또는 텍스트 광고를 추가하고 리마케팅 캠페인을 시작합니다.

   ![](assets/image2015-1-15-18-3a47-3a21.png)

>[!MORELIKETHIS]
>
>* [웹 Personalization 데이터를 사용하여 재타겟팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [Facebook에서 개인화된 리마케팅](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)

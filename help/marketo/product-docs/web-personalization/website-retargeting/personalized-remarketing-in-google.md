---
unique-page-id: 4720810
description: Google의 개인화된 리마케팅 - Marketo 문서 - 제품 설명서
title: Google의 개인화된 리마케팅
exl-id: cc733f43-161d-41e4-afdf-8b5217700810
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 6%

---

# Google의 개인화된 리마케팅 {#personalized-remarketing-in-google}

개인화된 리마케팅을 사용하면 Google Display Network를 통해 Google Analytics의 강력한 기능과 RTP 데이터를 사용하여 사용자와 다시 연결할 수 있습니다.

>[!PREREQUISITES]
>
>* [데이터 [!DNL Web Personalization]  구성을 사용하여 &#x200B;](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)재타겟팅 완료
>* [Google Analytics 도움말로 리마케팅](https://support.google.com/analytics/topic/2611283?hl=en&ref_topic=3413645) 설명서를 검토하십시오.

## Google에서 리마케팅 대상 만들기 {#creating-a-remarketing-audience-in-google}

1. Google Analytics에 로그인. **[!UICONTROL Admin]**, **[!UICONTROL Account]**, **[!UICONTROL Property]**&#x200B;을(를) 클릭합니다. **[!UICONTROL Audience Definitions]** 및 **[!UICONTROL Audiences]**&#x200B;을(를) 클릭합니다.

   ![](assets/remarketing-ga-screenshots.jpg)

1. **[!UICONTROL +New Audience]**&#x200B;를 클릭합니다.

   ![](assets/image2015-1-15-17-3a26-3a40.png)

1. **[!UICONTROL Link Configuration]**: [!DNL Google Adwords] 계정에 연결합니다. **[!UICONTROL Define Audience]**: **[!UICONTROL Create New]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-1-15-17-3a32-3a4.png)

1. 대상 빌더에서 **[!UICONTROL Sequences]**, **[!UICONTROL Find the RTP Data]**, [!UICONTROL Custom Dimensions] 아래의 [!UICONTROL UICONTROL [ !] Custom Variables] 및 [!UICONTROL Events]을(를) 클릭합니다.

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
>* 사용자 정의 차원: 조직, 업계, 범주(Fortune 500,1000, Global 2000), 그룹(엔터프라이즈, SMB), ABM 목록(지정 계정 목록)
>* 이벤트 범주: RTP-Segment, RTP-Campaign RTP-Remarketing
>* 이벤트 레이블: 세그먼트 이름, 캠페인 이름, 세그먼트화된 대상자 이름

**RTP로 세그먼트화된 대상 데이터에서 리마케팅 대상의 예**

1. **[!UICONTROL Sequences].** 클릭
1. **[!UICONTROL Event Label].** 선택
1. RTP에 나타나는 대로 **[!UICONTROL Name of Segmented Audience]**&#x200B;을(를) 입력합니다.
1. **[!UICONTROL Apply]**&#x200B;를 클릭합니다.

![](assets/image2015-2-10-14-3a51-3a43.png)

**RTP 업계 데이터의 대상 예제**

![](assets/image2015-1-15-17-3a36-3a5.png)

1. **[!UICONTROL Sequences]**&#x200B;를 클릭합니다.
1. **[!UICONTROL RTP-Industry]**&#x200B;를 선택합니다.
1. **업계 이름**(예: [!UICONTROL Financial Services], [!UICONTROL Education]...)을 입력하십시오.
1. **[!UICONTROL Apply]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Audience Name]** 입력. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

![](assets/image2015-1-15-18-3a29-3a16.png)

## [!DNL Google Adwords]에서 리마케팅 광고 캠페인 만들기 {#create-a-remarketing-ad-campaign-in-google-adwords}

1. **[!DNL Google Adwords]**&#x200B;에 로그인합니다. **[!UICONTROL Campaigns]**&#x200B;을(를) 클릭하고 **[!UICONTROL Display Network only]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-1-15-18-3a31-3a58.png)

1. **[!UICONTROL Campaign Name]**&#x200B;을(를) 입력하고 **[!UICONTROL Type Remarketing]을(를) 선택합니다.**

   ![](assets/image2015-1-15-18-3a35-3a7.png)

1. **[!UICONTROL Ad Group Name],** 입력 **[!UICONTROL Enhanced CPC]**, **[!UICONTROL Remarketing List]** 선택.

   ![](assets/image2015-1-15-18-3a51-3a57.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭하고 계속합니다.
1. 이미지 또는 텍스트 광고를 추가하고 리마케팅 캠페인을 시작합니다.

   ![](assets/image2015-1-15-18-3a47-3a21.png)

>[!MORELIKETHIS]
>
>* [데이터를 사용하여  [!DNL Web Personalization] 다시 타깃팅](/help/marketo/product-docs/web-personalization/website-retargeting/retargeting-with-web-personalization-data.md)
>* [의  [!DNL Facebook]](/help/marketo/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-facebook.md)개인화된 리마케팅

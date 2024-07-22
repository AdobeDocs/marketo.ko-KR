---
unique-page-id: 10092925
description: 웹 캠페인 미리보기 및 테스트 - Marketo 문서 - 제품 설명서
title: 웹 캠페인 미리보기 및 테스트
exl-id: 6cc4ebd8-0d39-4a7d-bc3d-e8cd18157470
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '396'
ht-degree: 0%

---

# 웹 캠페인 미리보기 및 테스트 {#preview-and-test-a-web-campaign}

이 문서에서는 웹 캠페인을 미리 보는 다양한 방법과, 웹 사이트에서 실시간으로 샌드박스 세그먼트를 사용하여 테스트하는 방법을 보여줍니다.

>[!NOTE]
>
>미리보기에는 선택한 사이트에서 캠페인이 표시되는 방식만 표시됩니다. 링크 및 위젯은 분석에서 잘못된 클릭/보기를 방지하기 위해 작동하지 않습니다.

## 만들기 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-creation-page}

1. **웹 캠페인**(으)로 이동합니다.

   ![](assets/image2016-8-18-15-3a59-3a35.png)

1. 기존 캠페인을 편집하려면 **새 웹 캠페인 만들기** 또는 아이콘을 클릭하십시오.

   ![](assets/create-new-or-edit-web-campaign.png)

1. 사이트에서 미리 보기에서 페이지 URL을 추가하고 **미리 보기**&#x200B;를 클릭합니다. 캠페인 미리보기를 표시하는 새 창/탭이 열립니다.

   ![](assets/three-1.png)

   >[!TIP]
   >
   >캠페인 미리 보기의 URL이 고정된 이메일을 열려면 **공유**&#x200B;를 클릭하세요.

   >[!NOTE]
   >
   >캠페인을 미리 보는 최상의 경험을 위해 브라우저 플러그인([Chrome](https://chrome.google.com/webstore/detail/marketo-web-personalizati/ldiddonjplchallbngbccbfdfeldohkj) 또는 [Firefox](https://rtp-static.marketo.com/rtp/libs/mwp-0.0.0.8.xpi))을 설치할 수도 있습니다. 아래 섹션을 참조하십시오.

## 브라우저 플러그인을 사용하여 생성 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-creation-page-using-the-browser-plug-in}

1. 위의 섹션에서 1 및 2단계를 수행합니다.

1. 브라우저 플러그인에 대한 링크를 클릭합니다(이 경우 Chrome을 사용 중).

   ![](assets/4-1.png)

1. 새 창/탭이 열립니다. **Chrome에 추가**&#x200B;를 클릭합니다.

   ![](assets/five.png)

1. **확장 추가**&#x200B;를 클릭합니다.

   ![](assets/six.png)

1. Marketo으로 돌아갑니다. 페이지 URL을 추가하고 **미리 보기**&#x200B;를 클릭합니다.

   ![](assets/seven.png)

1. 데스크탑, 휴대폰 또는 태블릿에서 캠페인의 모양을 미리 볼 수 있는 새 창/탭이 열립니다.

   ![](assets/campaign-preview.png)

## 웹 캠페인 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-web-campaigns-page}

1. 웹 캠페인 목록을 보면서 캠페인을 선택하고 **미리 보기** 아이콘을 클릭하면 됩니다.

   ![](assets/web-campaigns-1-preview-hand.png)

   진정해!

## 웹 사이트에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-your-website}

샌드박스 세그먼트 및 캠페인을 만듭니다.

1. **세그먼트**(으)로 이동합니다.

   ![](assets/new-dropdown-segments-hand.jpg)

1. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2015-9-10-10-3a42-3a39.png)

1. 세그먼트 이름을 지정합니다.

1. 동작 아래에서 포함 페이지를 캔버스로 드래그합니다. &#42;샌드박스=1&#42; 값을 추가합니다. **캠페인 저장 및 정의**&#x200B;를 클릭합니다.

   ![](assets/segment.png)

1. 웹 캠페인 설정 페이지의 목록에서 타겟 세그먼트를 선택하여 샌드박스 세그먼트로 변경합니다.

   ![](assets/set-web-campaign-target-segment.jpg)

1. 캠페인 크리에이티브를 완료하고 **시작**&#x200B;을 클릭하세요.

   ![](assets/click-launch.jpg)

1. 웹 사이트로 이동하여 URL 끝에 URL 매개 변수 &quot;?sandbox=1&quot;을(를) 추가합니다. 예: `www.marketo.com?sandbox=1`

1. 웹 사이트에서 Campaign React 를 참조하십시오.

>[!NOTE]
>
>캠페인은 방문자 세션 중에 한 번만 반응합니다. 캠페인을 다시 보려면 브라우저 쿠키를 지우십시오.

>[!NOTE]
>
>리디렉션 캠페인은 미리 볼 수 없습니다. 샌드박스 세그먼트(&#42;샌드박스=리디렉션&#42;)를 사용하여 테스트할 수 있습니다.

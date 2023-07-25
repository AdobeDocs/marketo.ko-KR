---
unique-page-id: 10092925
description: 웹 캠페인 미리보기 및 테스트 - Marketo 문서 - 제품 설명서
title: 웹 캠페인 미리보기 및 테스트
exl-id: 6cc4ebd8-0d39-4a7d-bc3d-e8cd18157470
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '402'
ht-degree: 0%

---

# 웹 캠페인 미리보기 및 테스트 {#preview-and-test-a-web-campaign}

이 문서에서는 웹 캠페인을 미리 보는 다양한 방법과, 웹 사이트에서 실시간으로 샌드박스 세그먼트를 사용하여 테스트하는 방법을 보여줍니다.

>[!NOTE]
>
>미리보기에는 선택한 사이트에서 캠페인이 표시되는 방식만 표시됩니다. 링크 및 위젯은 분석에서 잘못된 클릭/보기를 방지하기 위해 작동하지 않습니다.

## 만들기 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-creation-page}

1. 다음으로 이동 **웹 캠페인**.

   ![](assets/image2016-8-18-15-3a59-3a35.png)

1. 클릭 **새 웹 캠페인 만들기** 또는 아이콘을 클릭하여 기존 캠페인을 편집합니다.

   ![](assets/create-new-or-edit-web-campaign.png)

1. 사이트에서 미리 보기에서 페이지 URL을 추가하고 을 클릭합니다. **미리 보기**. 캠페인 미리보기를 표시하는 새 창/탭이 열립니다.

   ![](assets/three-1.png)

   >[!TIP]
   >
   >클릭 **공유** 캠페인 미리 보기의 URL이 고정된 이메일을 여는 방법.

   >[!NOTE]
   >
   >브라우저 플러그인을 설치할 수도 있습니다. [크롬](https://chrome.google.com/webstore/detail/marketo-web-personalizati/ldiddonjplchallbngbccbfdfeldohkj) 또는 [Firefox](https://rtp-static.marketo.com/rtp/libs/mwp-0.0.0.8.xpi))을 클릭하여 캠페인을 미리 볼 수 있습니다. 아래 섹션을 참조하십시오.

## 브라우저 플러그인을 사용하여 생성 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-creation-page-using-the-browser-plug-in}

1. 위의 섹션에서 1 및 2단계를 수행합니다.

1. 브라우저 플러그인(이 경우 Chrome 사용)에 대한 링크를 클릭합니다.

   ![](assets/4-1.png)

1. 새 창/탭이 열립니다. 클릭 **Chrome에 추가**.

   ![](assets/five.png)

1. 클릭 **확장 추가**.

   ![](assets/six.png)

1. Marketo으로 돌아갑니다. 페이지 URL을 추가하고 **미리 보기**.

   ![](assets/seven.png)

1. 데스크탑, 휴대폰 또는 태블릿에서 캠페인의 모양을 미리 볼 수 있는 새 창/탭이 열립니다.

   ![](assets/campaign-preview.png)

## 웹 캠페인 페이지에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-the-web-campaigns-page}

1. 웹 캠페인 목록을 보면서 캠페인을 선택하고 **미리 보기** 아이콘.

   ![](assets/web-campaigns-1-preview-hand.png)

   진정해!

## 웹 사이트에서 웹 캠페인 미리 보기 {#preview-a-web-campaign-on-your-website}

샌드박스 세그먼트 및 캠페인을 만듭니다.

1. 다음으로 이동 **세그먼트**.

   ![](assets/new-dropdown-segments-hand.jpg)

1. 클릭 **새로 만들기**.

   ![](assets/image2015-9-10-10-3a42-3a39.png)

1. 세그먼트 이름을 지정합니다.

1. 동작 아래에서 포함 페이지를 캔버스로 드래그합니다. 값 추가 &#42;sandbox=1&#42;. 클릭 **Campaign 저장 및 정의**.

   ![](assets/segment.png)

1. 웹 Target 설정 페이지의 목록에서 세그먼트 를 선택하여 샌드박스 세그먼트로 변경합니다.

   ![](assets/set-web-campaign-target-segment.jpg)

1. 캠페인 크리에이티브를 완료하고 클릭 **시작**.

   ![](assets/click-launch.jpg)

1. 웹 사이트로 이동하여 URL 끝에 URL 매개 변수 &quot;?sandbox=1&quot;을(를) 추가합니다. 예: `www.marketo.com?sandbox=1`.

1. 웹 사이트에서 Campaign React 를 참조하십시오.

>[!NOTE]
>
>캠페인은 방문자 세션 중에 한 번만 반응합니다. 캠페인을 다시 보려면 브라우저 쿠키를 지우십시오.

>[!NOTE]
>
>리디렉션 캠페인은 미리 볼 수 없습니다. 이를 테스트하는 유일한 방법은 샌드박스 세그먼트(특정 페이지별로 타깃팅)를 사용하는 것입니다. &#42;sandbox=redirect&#42;)

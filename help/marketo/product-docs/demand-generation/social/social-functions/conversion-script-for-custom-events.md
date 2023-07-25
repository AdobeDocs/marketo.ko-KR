---
unique-page-id: 2950561
description: 사용자 지정 이벤트에 대한 변환 스크립트 - Marketo 문서 - 제품 설명서
title: 사용자 지정 이벤트에 대한 변환 스크립트
exl-id: 202b7e66-af83-42fd-8067-a5808eba7c32
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# 사용자 지정 이벤트에 대한 변환 스크립트 {#conversion-script-for-custom-events}

추천 오퍼를 생성할 때 이행 목표를 정의합니다. 목표에 대해 카운트되는 작업이 자체 웹 페이지의 특정 이벤트인 경우 전환 스크립트를 사용하여 JavaScript API를 호출할 수 있습니다.

## 변환 스크립트 검색 {#retrieve-the-conversion-script}

1. 추천 오퍼 편집기 내에서 **오퍼 세부 정보** 다음을 선택합니다. **고객 JavaScript 이벤트** 이행 목표 드롭다운에서

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. 회색 상자에 있는 상단 스크립트를 복사하고 `<body>` 태그 사이에 코드를 삽입하지 마십시오. 맨 아래 스크립트는 `<header>` 태그 사이에 코드를 삽입하지 마십시오.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >Marketo 이외의 웹 사이트에서 진행되는 경우 두 스크립트를 모두 복사하여 붙여넣는 것을 잊지 마십시오.

## 로더 스크립트 검색 {#retrieve-the-loader-script}

1. 트리에서 참조 오퍼를 선택한 다음 를 클릭합니다. **추천 오퍼 작업** 및 **포함 코드**.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. 마우스 오른쪽 단추 클릭 **헤더 코드** 웹 페이지 헤더에 삽입합니다. 그런 다음 동일한 작업을 수행합니다 **본문 코드**.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## 웹 페이지에 스크립트 붙여넣기 {#pasting-the-scripts-onto-your-webpage}

변환 스크립트를 본문 및 헤더의 HTML에 붙여넣습니다. 그런 다음 로더 스크립트를 본문 및 헤더의 HTML에 넣습니다.

![](assets/image2015-4-20-21-3a0-3a16.png)

## 변환 스크립트 연결 {#connecting-the-conversion-script}

여기에서는 목표 완료를 트리거할 페이지 요소의 특정 HTML ID를 사용하는 JavaScript 함수를 작성합니다. For example:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

이 예에는 웹 페이지에 ID가 &quot;#myButtonId&quot;인 버튼이 있습니다. 해당 버튼을 클릭하면 개인이 목표를 완료한 것으로 등록됩니다.

멋지다! 이제 웹 사이트에서 Marketo의 사용자 지정 소셜 프로모션 목표를 캡처하고 있습니다.

>[!MORELIKETHIS]
>
>* [추천 오퍼에 대한 목표 지정](/help/marketo/product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [참조 오퍼 만들기](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [웹 사이트에 Social 배포](/help/marketo/product-docs/demand-generation/social/social-functions/deploy-social-on-your-website.md)

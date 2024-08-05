---
unique-page-id: 2950561
description: 사용자 지정 이벤트에 대한 변환 스크립트 - Marketo 문서 - 제품 설명서
title: 사용자 지정 이벤트에 대한 변환 스크립트
exl-id: 202b7e66-af83-42fd-8067-a5808eba7c32
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 1%

---

# 사용자 지정 이벤트에 대한 변환 스크립트 {#conversion-script-for-custom-events}

추천 오퍼를 생성할 때 이행 목표를 정의합니다. 목표에 대해 카운트되는 작업이 자체 웹 페이지의 특정 이벤트인 경우 전환 스크립트를 사용하여 JavaScript API를 호출할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

## 변환 스크립트 검색 {#retrieve-the-conversion-script}

1. 추천 오퍼 편집기에서 **오퍼 세부 정보**&#x200B;를 클릭한 다음, 이행 목표 드롭다운에서 **고객 JavaScript 이벤트**&#x200B;를 선택합니다.

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. 회색 상자에 있는 위쪽 스크립트를 복사하여 `<body>` 태그 내에 있는 웹 페이지에 배치합니다. 아래 스크립트는 `<header>` 태그 내에 배치됩니다.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >Marketo 이외의 웹 사이트에서 진행되는 경우 두 스크립트를 모두 복사하여 붙여넣는 것을 잊지 마십시오.

## 로더 스크립트 검색 {#retrieve-the-loader-script}

1. 트리에서 참조 오퍼를 선택한 다음 **참조 오퍼 작업** 및 **포함 코드**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. **머리글 코드**&#x200B;를 마우스 오른쪽 단추로 클릭하고 웹 페이지 머리글에 삽입합니다. 그런 다음 **본문 코드**&#x200B;에 대해서도 동일한 작업을 수행합니다.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## 웹 페이지에 스크립트 붙여넣기 {#pasting-the-scripts-onto-your-webpage}

변환 스크립트를 본문 및 헤더의 HTML에 붙여넣습니다. 그런 다음 로더 스크립트를 본문 및 헤더의 HTML에 넣습니다.

![](assets/image2015-4-20-21-3a0-3a16.png)

## 변환 스크립트 연결 {#connecting-the-conversion-script}

여기에서는 목표 완료를 트리거할 페이지 요소의 특정 HTML ID를 사용하는 JavaScript 함수를 작성할 수 있습니다. For example:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

이 예에는 웹 페이지에 ID가 &quot;#myButtonId&quot;인 버튼이 있습니다. 해당 버튼을 클릭하면 개인이 목표를 완료한 것으로 등록됩니다.

멋지다! 이제 웹 사이트에서 Marketo의 사용자 지정 소셜 프로모션 목표를 캡처하고 있습니다.

>[!MORELIKETHIS]
>
>* [참조 오퍼에 대한 목표 지정](/help/marketo/product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [조회 오퍼 만들기](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [웹 사이트에 Social 배포](/help/marketo/product-docs/demand-generation/social/social-functions/deploy-social-on-your-website.md)

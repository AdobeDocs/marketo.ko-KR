---
unique-page-id: 2950524
description: 웹 사이트에 Social 배포 - Marketo 문서 - 제품 설명서
title: 웹 사이트에 Social 배포
exl-id: bccfa461-29c1-4cf1-8e6a-2186c36bdf7e
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '264'
ht-degree: 0%

---

# 웹 사이트에 Social 배포 {#deploy-social-on-your-website}

Marketo이 아닌 페이지에 소셜 앱을 포함합니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

>[!AVAILABILITY]
>
>일부 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

자체 웹 사이트에 소셜 앱을 배포하여 대상자를 참여시키고 모든 사람을 소셜 네트워크에서 대화에 참여시킬 수 있습니다. 사람들이 소셜 네트워크에서 친구들과 프로모션 및 콘텐츠를 공유하면 사이트에 더 많은 트래픽이 생성됩니다.

1. YouTube 비디오 또는 소셜 버튼과 같이 승인된 소셜 앱을 선택합니다.

   ![](assets/image2015-5-12-11-3a43-3a24.png)

1. 소셜 앱 작업에서 **포함 코드**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-5-12-12-3a59-3a46.png)

1. 사이트의 페이지 머리글(`<head>`) 및 본문(`<body>`)에 대한 코드를 복사합니다.

   ![](assets/image2015-5-12-13-3a3-3a34.png)

1. 웹 사이트의 페이지 헤더에 첫 번째 코드 조각을 붙여넣습니다.

   ![](assets/socialonsite-embedhead.png)

1. 소셜 앱을 페이지에 표시할 각 페이지에 두 번째 코드 조각을 붙여 넣습니다.

   ![](assets/socialonsite-embedwidget.png)

1. 소셜 앱의 크기를 페이지의 특정 차원으로 설정해야 하는 경우 **outerHeight** 및 **outerWidth** 옵션을 두 번째 코드 조각에 추가하십시오. 예를 들어 다음과 같이 `options='{"outerHeight":400, "outerWidth":600}'`을(를) 추가할 수 있습니다.

   ![](assets/socialonsite-resizewidget2.png)

   이제 Marketo 소셜 앱에서 웹 사이트에 콘텐츠와 상호 작용을 추가하여 팬, 방문자 및 기존 고객을 초대하여 사용자에 대한 소문을 퍼뜨립니다. 동시에 데이터베이스에 프로필 데이터를 추가하고 소셜 영향 지표를 추적합니다.

   >[!MORELIKETHIS]
   >
   >* [소셜 앱 사용자 지정 단추](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)
   >* [소셜 공유 요구 사항 설정](/help/marketo/product-docs/demand-generation/social/social-functions/set-social-share-requirement.md)
   >* facebook으로 [Publish 랜딩 페이지](/help/marketo/product-docs/demand-generation/facebook/publish-landing-pages-to-facebook.md)

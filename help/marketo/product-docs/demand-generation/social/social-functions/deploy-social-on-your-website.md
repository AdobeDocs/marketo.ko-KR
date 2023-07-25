---
unique-page-id: 2950524
description: 웹 사이트에 Social 배포 - Marketo 문서 - 제품 설명서
title: 웹 사이트에 Social 배포
exl-id: bccfa461-29c1-4cf1-8e6a-2186c36bdf7e
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 0%

---

# 웹 사이트에 Social 배포 {#deploy-social-on-your-website}

Marketo이 아닌 페이지에 소셜 앱을 포함합니다.

>[!AVAILABILITY]
>
>자세한 내용은 영업 담당자에게 문의하십시오.

자체 웹 사이트에 소셜 앱을 배포하여 대상자를 참여시키고 모든 사람을 소셜 네트워크에서 대화에 참여시킬 수 있습니다. 사람들이 소셜 네트워크에서 친구들과 프로모션 및 콘텐츠를 공유하면 사이트에 더 많은 트래픽이 생성됩니다.

1. YouTube 비디오 또는 소셜 버튼과 같이 승인된 소셜 앱을 선택합니다.

   ![](assets/image2015-5-12-11-3a43-3a24.png)

1. 선택 **포함 코드** 소셜 앱 작업에서 을 참조하십시오.

   ![](assets/image2015-5-12-12-3a59-3a46.png)

1. 사이트의 페이지 헤더에 대한 코드 복사(`<head>`) 및 본문(`<body>`).

   ![](assets/image2015-5-12-13-3a3-3a34.png)

1. 웹 사이트의 페이지 헤더에 첫 번째 코드 조각을 붙여넣습니다.

   ![](assets/socialonsite-embedhead.png)

1. 소셜 앱을 페이지에 표시할 각 페이지에 두 번째 코드 조각을 붙여 넣습니다.

   ![](assets/socialonsite-embedwidget.png)

1. 소셜 앱의 크기를 페이지의 특정 차원으로 설정해야 하는 경우 **바깥쪽 높이** 및 **외부 너비** 두 번째 코드 조각에 대한 옵션입니다. 예를 들어 다음을 추가할 수 있습니다 `options='{"outerHeight":400, "outerWidth":600}'`과 같은 형식으로 프로필 스크립트에서 참조할 수 있습니다.

   ![](assets/socialonsite-resizewidget2.png)

   이제 Marketo 소셜 앱에서 웹 사이트에 콘텐츠와 상호 작용을 추가하여 팬, 방문자 및 기존 고객을 초대하여 사용자에 대한 소문을 퍼뜨립니다. 동시에 데이터베이스에 프로필 데이터를 추가하고 소셜 영향 지표를 추적합니다.

   >[!MORELIKETHIS]
   >
   >* [소셜 앱 사용자 지정 단추](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-social-app-button.md)
   >* [소셜 공유 요구 사항 설정](/help/marketo/product-docs/demand-generation/social/social-functions/set-social-share-requirement.md)
   >* [facebook에 랜딩 페이지 게시](/help/marketo/product-docs/demand-generation/facebook/publish-landing-pages-to-facebook.md)

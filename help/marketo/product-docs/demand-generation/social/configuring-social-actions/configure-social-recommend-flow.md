---
unique-page-id: 2950549
description: 소셜 추천 플로우 구성 - Marketo 문서 - 제품 설명서
title: 소셜 추천 플로우 구성
exl-id: 01b54215-4a0c-4639-80d2-ec30603b3695
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '513'
ht-degree: 0%

---

# 소셜 추천 플로우 구성 {#configure-social-recommend-flow}

소셜 앱을 만들 때, 사용자가 등록할 때 표시되는 소셜 네트워크 선택 사항 및 프롬프트를 구성할 수 있습니다.

## 공유할 네트워크 선택 {#select-networks-for-sharing}

>[!NOTE]
>
>이는 [소셜 등록/공유 흐름을 구성하는](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/configure-social-sign-up-share-flow.md)과(와) 매우 유사하지만, 소셜 앱의 공유 링크 _아래_&#x200B;에 사용됩니다.

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/login-marketing-activities-1.png)

1. 앱을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-22-11-3a51-3a6.png)

1. 소셜 앱 편집기에서 **추천 흐름** > **소셜 네트워크**(으)로 이동합니다.

   ![](assets/recommendedflow.png)

1. 사용자가 공유할 수 있는 네트워크를 선택합니다.

   ![](assets/socialnetworkschoose.png)

## facebook 메시지 구성 {#configure-the-facebook-message}

1. facebook 게시물에 표시될 메시지를 구성합니다.

   ![](assets/image2014-9-22-11-3a53-3a21.png)

   >[!NOTE]
   >
   >비디오 공유에서 썸네일은 자동으로 생성됩니다.

   **다이내믹 콘텐츠 추가**&#x200B;를 선택하면 페이지의 OpenGraph 태그(og:title, og:caption 및 og:description) 및 썸네일 값이 자동으로 Facebook 게시물에 추가됩니다. 다음 단계를 참조하십시오.

   **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목, 캡션 및 설명을 입력하고 이미지를 업로드하십시오. 다음 두 단계를 참조하십시오.

1. 보기 및 편집 창에서 **편집 표시**&#x200B;를 클릭하여 Facebook 게시물에 표시될 공유 메시지 및 메시지를 사용자 지정합니다.

   >[!TIP]
   >
   >자세한 내용은 [Facebook 리치 게시물 설정 편집](/help/marketo/product-docs/demand-generation/facebook/edit-facebook-rich-post-settings.md)을 참조하십시오.

   ![](assets/image2014-9-22-11-3a54-3a36.png)

   >[!NOTE]
   >
   >[공유 URL](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md)이(가) 모든 공유 메시지에 자동으로 추가됩니다.

1. 위에서 **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목, 캡션 및 설명을 편집하고 Marketo 이미지 및 파일에서 사용자 지정 이미지를 업로드하십시오.

   ![](assets/image2014-9-22-11-3a55-3a14.png)

   [Marketo에 이미지 및 파일 추가](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md)를 참조하십시오.

   >[!NOTE]
   >
   >이미지를 업로드하면 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

1. **다음**&#x200B;을 클릭합니다.

을 선택하는 경우 페이지의 OpenGraph 태그(og:title, og:caption 및 og:description) 값과 썸네일이 자동으로 Facebook 게시물에 추가됩니다. 다음 단계를 참조하십시오.

## twitter 메시지 구성 {#configure-the-twitter-message}

1. twitter 트윗에 표시할 공유 프롬프트 및 메시지를 편집하려면 클릭하십시오.

   ![](assets/image2014-9-22-12-3a2-3a40.png)

   >[!TIP]
   >
   >트윗 텍스트에 {html_title}을(를) 사용하면 페이지 제목을 자동으로 표시할 수 있습니다.

1. **다음**&#x200B;을 클릭합니다.

## linkedIn 메시지 구성 {#configure-the-linkedin-message}

1. linkedIn 게시물에 표시될 메시지를 구성합니다.

   ![](assets/image2014-9-22-12-3a3-3a21.png)

   **다이내믹 추가** 콘텐츠를 선택하면 페이지 태그(제목 및 설명) 및 썸네일 값이 자동으로 LinkedIn 게시물에 추가됩니다. 다음 단계를 참조하십시오.

   **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목, 캡션 및 설명을 입력하고 이미지를 업로드하십시오. 다음 두 단계를 참조하십시오.

1. **보기 및 편집** 창에서 **편집 표시**&#x200B;를 클릭하고 LinkedIn 게시물에 표시될 공유 메시지 및 메시지를 편집합니다.

   ![](assets/image2014-9-22-12-3a3-3a38.png)

   >[!TIP]
   >
   >게시물 텍스트에서 {html_title}을(를) 사용하여 페이지 제목을 자동으로 표시합니다.

1. 위에서 **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목과 설명을 편집하고 Marketo 이미지 및 파일에서 사용자 지정 이미지를 업로드하십시오.

   ![](assets/image2014-9-22-12-3a4-3a43.png)

   [Marketo에 이미지 및 파일 추가](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md)를 참조하십시오.

   >[!NOTE]
   >
   >이미지를 업로드하면 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

1. **다음**&#x200B;을 클릭합니다.

## 확인 메시지 구성 {#configure-the-confirmation-message}

1. 공유 확인 텍스트를 편집합니다.

   ![](assets/image2014-9-22-12-3a5-3a30.png)

1. **완료** > **승인** 및 **닫기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-22-12-3a5-3a45.png)

>[!MORELIKETHIS]
>
>다음 단계는 랜딩 페이지, Facebook 또는 웹 사이트에 [비디오 공유를 추가](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-video-share-flow.md) 또는 [투표](/help/marketo/product-docs/demand-generation/social/creating-a-poll/create-a-poll.md)하는 것입니다.

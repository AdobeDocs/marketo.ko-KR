---
unique-page-id: 2950549
description: 소셜 추천 흐름 구성 - Marketo 문서 - 제품 설명서
title: 소셜 추천 흐름 구성
exl-id: 01b54215-4a0c-4639-80d2-ec30603b3695
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '515'
ht-degree: 0%

---

# 소셜 추천 흐름 구성 {#configure-social-recommend-flow}

소셜 앱을 만들 때 소셜 네트워크 선택 사항을 구성하고 등록할 때 사용자가 방문하는지 여부를 묻습니다.

## 공유할 네트워크 선택 {#select-networks-for-sharing}

>[!NOTE]
>
>이것은 매우 유사합니다 [소셜 등록/공유 흐름 구성](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/configure-social-sign-up-share-flow.md), 하지만 공유 링크를 위한 것입니다 _아래에_ 소셜 앱입니다.

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-1.png)

1. 앱을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/image2014-9-22-11-3a51-3a6.png)

1. 소셜 앱 편집기에서 로 이동합니다. **추천 흐름** > **소셜 네트워크**.

   ![](assets/recommendedflow.png)

1. 사용자가 공유할 수 있는 네트워크를 선택합니다.

   ![](assets/socialnetworkschoose.png)

## facebook 메시지 구성 {#configure-the-facebook-message}

1. facebook 게시물에 나타날 메시지를 구성합니다.

   ![](assets/image2014-9-22-11-3a53-3a21.png)

   >[!NOTE]
   >
   >비디오 공유에서 축소판이 자동으로 생성됩니다.

   만약 **동적 콘텐츠 추가**, 페이지의 OpenGraph 태그(og:title, og:caption 및 og:description)의 값과 축소판이 Facebook 게시물에 자동으로 추가됩니다. 다음 단계를 참조하십시오.

   만약 **정적 콘텐츠 추가**&#x200B;제목, 캡션 및 설명을 입력하고 이미지를 업로드합니다. 다음 두 단계를 참조하십시오.

1. 보기 및 편집 창에서 **편집 내용 표시** facebook 게시물에 표시되는 공유 프롬프트 및 메시지를 사용자 지정하려면 를 사용하십시오.

   >[!TIP]
   >
   >자세한 내용은 [facebook 리치 게시물 설정 편집](/help/marketo/product-docs/demand-generation/facebook/edit-facebook-rich-post-settings.md).

   ![](assets/image2014-9-22-11-3a54-3a36.png)

   >[!NOTE]
   >
   >다음 [공유 URL](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md) 모든 공유 메시지에 자동으로 추가됩니다.

1. 선택한 경우 **정적 콘텐츠 추가** 위에서 제목, 캡션 및 설명을 편집하고 사용자 지정 이미지(Marketo 이미지 및 파일)를 업로드합니다.

   ![](assets/image2014-9-22-11-3a55-3a14.png)

   자세한 내용은 [Marketo에 이미지 및 파일 추가](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md).

   >[!NOTE]
   >
   >이미지를 업로드하는 경우 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

1. 클릭 **다음**.

를 선택하면 페이지의 OpenGraph 태그(og:title, og:caption 및 og:description)의 값과 축소판이 Facebook 게시물에 자동으로 추가됩니다. 다음 단계를 참조하십시오.

## twitter 메시지 구성 {#configure-the-twitter-message}

1. twitter 트윗에 표시될 공유 메시지와 메시지를 편집하려면 을(를) 클릭합니다.

   ![](assets/image2014-9-22-12-3a2-3a40.png)

   >[!TIP]
   >
   >트윗 텍스트에 {html_title}을(를) 사용하여 페이지의 제목을 자동으로 표시합니다.

1. 클릭 **다음**.

## LinkedIn 메시지 구성 {#configure-the-linkedin-message}

1. LinkedIn 게시물에 나타날 메시지를 구성합니다.

   ![](assets/image2014-9-22-12-3a3-3a21.png)

   만약 **동적 추가** 컨텐츠, 페이지 태그 값(제목 및 설명) 및 축소판이 LinkedIn 게시물에 자동으로 추가됩니다. 다음 단계를 참조하십시오.

   만약 **정적 추가** 컨텐츠에서 제목, 캡션 및 설명을 입력하고 이미지를 업로드합니다. 다음 두 단계를 참조하십시오.

1. 에서 **보기 및 편집** 창 **편집 내용 표시** LinkedIn 게시물에 표시될 공유 메시지와 메시지를 편집합니다.

   ![](assets/image2014-9-22-12-3a3-3a38.png)

   >[!TIP]
   >
   >게시물 텍스트에서 {html_title}을(를) 사용하여 페이지의 제목을 자동으로 표시합니다.

1. 선택한 경우 **정적 추가** 위의 컨텐츠를 편집하고, 제목 및 설명을 편집하고, 사용자 지정 이미지(Marketo 이미지 및 파일)를 업로드합니다.

   ![](assets/image2014-9-22-12-3a4-3a43.png)

   자세한 내용은 [Marketo에 이미지 및 파일 추가](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md).

   >[!NOTE]
   >
   >이미지를 업로드하는 경우 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

1. 클릭 **다음**.

## 확인 메시지 구성 {#configure-the-confirmation-message}

1. 공유 확인 텍스트를 편집합니다.

   ![](assets/image2014-9-22-12-3a5-3a30.png)

1. 클릭 **완료** > **승인** 및 **닫기**.

   ![](assets/image2014-9-22-12-3a5-3a45.png)

>[!MORELIKETHIS]
>
>다음 단계는 [비디오 공유 추가](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/customize-video-share-flow.md) 또는 [투표](/help/marketo/product-docs/demand-generation/social/creating-a-poll/create-a-poll.md) 랜딩 페이지, Facebook 또는 자체 웹 사이트에 연결할 수 있습니다.

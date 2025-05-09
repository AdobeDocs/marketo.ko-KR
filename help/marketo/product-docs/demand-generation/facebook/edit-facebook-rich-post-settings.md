---
unique-page-id: 2950555
description: Facebook 리치 게시물 설정 편집 - Marketo 문서 - 제품 설명서
title: Facebook 리치 게시물 설정 편집
exl-id: f72bfb03-9bc7-46c4-bfb8-b377b2d23fc9
hide: true
hidefromtoc: true
feature: Integrations
source-git-commit: 7a8f5146126d6e8a4902be9337eef4d51e108cf0
workflow-type: tm+mt
source-wordcount: '316'
ht-degree: 0%

---

# Facebook 리치 게시물 설정 편집 {#edit-facebook-rich-post-settings}

사람들이 Facebook에서 귀하를 공유할 때 게시물을 사용자 지정합니다.

>[!AVAILABILITY]
>
>모든 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

Marketo _소셜 앱_&#x200B;을 사용하면 리드가 Facebook, Twitter 등의 소셜 네트워크에 연결된 랜딩 페이지를 공유할 수 있습니다. Facebook OpenGraph 태그(OG 태그)를 사용하면 랜딩 페이지의 정보가 Facebook 게시물에 포함되도록 지정할 수 있습니다.

## 리치 게시물 옵션 선택 {#select-rich-post-options}

랜딩 페이지의 공유로 생성된 Facebook 리치 게시물에서 사용할 페이지 정보 유형을 지정할 수 있습니다.

1. 편집기에서 **YouTube** 비디오 또는 소셜 단추에 대한 **Facebook 메시지**&#x200B;를 선택합니다.

   ![](assets/image2014-9-22-16-3a47-3a21.png)

1. Facebook 메시지에 대해 다음 옵션 중에서 선택합니다.

   * 정적 컨텐츠 추가: 제목, 캡션 및 설명을 수동으로 입력하려면 이 옵션을 선택하십시오.

   ![](assets/image2014-9-22-16-3a48-3a0.png)

   * 다이내믹 콘텐츠 추가: 소셜 앱에서 랜딩 페이지의 `<TITLE>`, `<CAPTION>` 및 `<DESCRIPTION>` 태그를 사용하여 리치 게시물을 채울 수 있습니다.

   ![](assets/image2014-9-22-16-3a48-3a9.png)

   >[!NOTE]
   >
   >이러한 태그가 이미 페이지 소스에 존재해야 하지만, 더 많은 제어를 위해 특정 Facebook OG 태그를 랜딩 페이지에 추가할 수 있습니다.

   * 리치 콘텐츠를 추가하지 않음: 랜딩 페이지의 Facebook 게시물을 기본 메시지 및 링크로 제한합니다.

   ![](assets/image2014-9-22-16-3a48-3a18.png)

## 랜딩 페이지에 Facebook OG 태그 추가 {#add-facebook-og-tags-to-a-landing-page}

랜딩 페이지에서 Facebook 공유에 포함될 페이지 요소를 제어하려면 랜딩 페이지에 제목, 캡션 및 설명에 대한 Facebook OG(Open Graph) 태그를 추가할 수 있습니다.

1. **YouTube 비디오** 또는 소셜 단추가 포함된 랜딩 페이지를 엽니다.

   ![](assets/image2014-9-22-16-3a51-3a28.png)

   **랜딩 페이지 Designer**&#x200B;이 새 창에서 열립니다.

1. **랜딩 페이지 작업** > **페이지 메타 태그 편집**&#x200B;을 선택합니다.

   ![](assets/image2014-9-22-16-3a51-3a36.png)

1. og:title, og:caption 및 og:description을 정의하는 HTML을 추가합니다. 다음 줄을 복사하여 붙여넣고 자리 표시자 텍스트를 바꿉니다.

   `<meta property="og:title" content="My Post Title"/>`

   `<meta property="og:caption" content="My Post Caption"/>`

   `<meta property="og:description" content="This text appears in the post description"/>`

   ![](assets/image2014-9-22-16-3a52-3a8.png)

>[!NOTE]
>
>OG 태그를 추가할 때는 적절한 HTML 구문을 사용해야 합니다.

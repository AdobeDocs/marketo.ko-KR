---
unique-page-id: 2950530
description: 소셜 등록/공유 흐름 구성 - Marketo 문서 - 제품 설명서
title: 소셜 등록/공유 흐름 구성
exl-id: 521187d1-2228-42e7-a87b-3b20a45adb03
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 0%

---

# 소셜 등록/공유 흐름 구성 {#configure-social-sign-up-share-flow}

소셜 앱을 만들 때, 사용자가 등록할 때 표시되는 소셜 네트워크 선택 사항 및 프롬프트를 구성할 수 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

## 공유할 네트워크 선택 {#select-networks-for-sharing}

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/ma-1.png)

1. 앱을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-22-13-3a57-3a43.png)

1. 소셜 앱 편집기에서 **등록 흐름** > **소셜 네트워크**&#x200B;를 클릭합니다.

   ![](assets/three.png)

1. 개인이 공유할 수 있는 네트워크를 선택(또는 선택 취소)합니다.

   ![](assets/four.png)

## facebook 메시지 구성 {#configure-the-facebook-message}

1. **등록 흐름** > **메시지 공유**(으)로 이동합니다.

   ![](assets/five.png)

1. facebook 게시물에 표시될 메시지를 구성합니다.

   ![](assets/image2014-9-22-13-3a58-3a54.png)

   >[!NOTE]
   >
   >비디오 공유에서 썸네일은 자동으로 생성됩니다.

   **다이내믹 콘텐츠 추가**&#x200B;를 선택하면 페이지의 **OpenGraph** 태그(og:title, og:caption 및 og:description) 값 및 축소판이 자동으로 Facebook 게시물에 추가됩니다. 다음 단계를 참조하십시오.

   **정적 콘텐츠 추가**&#x200B;를 선택하는 경우 제목, 캡션, 설명을 입력하고 이미지를 업로드하십시오. 다음 두 단계를 참조하십시오.

1. 보기 및 편집 창에서 **편집 표시**&#x200B;를 클릭하고 공유 프롬프트 및 Facebook 게시물에 표시될 메시지를 편집합니다.

   >[!TIP]
   >
   >자세한 내용은 [Facebook 리치 게시물 설정 편집](/help/marketo/product-docs/demand-generation/facebook/edit-facebook-rich-post-settings.md)을 참조하십시오.

   ![](assets/image2014-9-22-13-3a59-3a57.png)

   >[!NOTE]
   >
   >[공유 URL](/help/marketo/product-docs/demand-generation/social/social-functions/choose-the-share-url-for-a-social-app.md)이(가) 모든 공유 메시지에 자동으로 추가됩니다.

1. 위에서 **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목, 캡션 및 설명을 편집하고 사용자 지정 이미지([**Marketo 이미지 및 파일**](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md)&#x200B;에서)를 업로드하십시오.

   ![](assets/image2014-9-22-14-3a1-3a11.png)

   [Marketo에 이미지 및 파일 추가](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md)를 참조하십시오.

   >[!NOTE]
   >
   >이미지를 업로드하면 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

1. **다음**&#x200B;을 클릭합니다.

페이지의 태그(og:title, og:caption 및 og:description) 값을 선택하면 썸네일이 자동으로 Facebook 게시물에 추가됩니다. 다음 단계를 참조하십시오.

## twitter 메시지 구성 {#configure-the-twitter-message}

1. twitter 트윗에 표시할 공유 프롬프트 및 메시지를 편집합니다.

   ![](assets/image2014-9-22-14-3a2-3a31.png)

   >[!TIP]
   >
   >트윗 텍스트에 {html_title}을(를) 사용하면 페이지 제목을 자동으로 표시할 수 있습니다.

1. **다음**&#x200B;을 클릭합니다.

## linkedIn 메시지 구성 {#configure-the-linkedin-message}

1. linkedIn 게시물에 표시될 메시지를 구성합니다.

   ![](assets/image2014-9-22-14-3a3-3a8.png)

   **다이내믹 콘텐츠 추가**&#x200B;를 선택하면 페이지 태그(제목 및 설명) 및 썸네일 값이 자동으로 LinkedIn 게시물에 추가됩니다. 다음 단계를 참조하십시오.

   **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목, 캡션 및 설명을 입력하고 이미지를 업로드하십시오. 다음 두 단계를 참조하십시오.

1. **보기 및 편집** 창에서 **편집 표시**&#x200B;를 클릭하고 LinkedIn 게시물에 표시될 공유 메시지 및 메시지를 편집합니다.

   ![](assets/image2014-9-22-14-3a4-3a6.png)

   >[!TIP]
   >
   >게시물 텍스트에서 {html_title}을(를) 사용하여 페이지 제목을 자동으로 표시합니다.

1. 위에서 **정적 콘텐츠 추가**&#x200B;를 선택한 경우 제목과 설명을 편집하고 사용자 지정 이미지([**Marketo 이미지 및 파일**](/help/marketo/product-docs/demand-generation/images-and-files/add-images-and-files-to-marketo.md)&#x200B;에서)를 업로드하십시오.

   ![](assets/image2014-9-22-13-3a55-3a17.png)

>[!NOTE]
>
>이미지를 업로드하면 소셜 앱 편집기를 닫았다가 다시 열 때까지 여기에 표시되지 않습니다.

>[!MORELIKETHIS]
>
>다음으로 **완료** > **승인 및 닫기**&#x200B;를 클릭하고 소셜 앱을 랜딩 페이지에 넣을 수 있습니다. [개인 캡처](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/configure-person-capture-for-a-social-app.md) 또는 [다시 공유 프롬프트](/help/marketo/product-docs/demand-generation/social/configuring-social-actions/configure-re-share-email-and-prompt-for-a-social-app.md)를 구성할 수도 있습니다.

---
unique-page-id: 4720145
description: Google Tag Manager를 사용하여 RTP 구현 - Marketo 문서 - 제품 설명서
title: Google Tag Manager를 사용하여 RTP 구현
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# [!DNL Google Tag Manager]을(를) 사용하여 RTP 구현 {#implementing-rtp-using-google-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. [!DNL Google Tag Manager] 계정에 로그인합니다.

1. 새 **[!UICONTROL Tag]** > **[!UICONTROL Tag Configurations]** > **[!UICONTROL Custom HTML Tag]을(를) 추가합니다.** **RTP**&#x200B;로 호출합니다.

1. **RTP 계정**&#x200B;에 로그인합니다.

1. **[!UICONTROL Account Settings]**(으)로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 6단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. [!UICONTROL Domain]에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. RTP JavaScript 태그를 복사하여 새로 만든 **사용자 지정 HTML 태그**&#x200B;에 붙여넣습니다(1단계).

1. **[!UICONTROL Add Rule to Fire Tag]**&#x200B;을(를) 클릭합니다. **[!UICONTROL All Pages]**&#x200B;를 선택합니다.

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭하고 [새 버전을 게시](https://support.google.com/tagmanager/answer/2699097?hl=en)합니다.

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **[!UICONTROL Inspect Element]**(으)로 이동하여 **RTP**&#x200B;를 검색하여 태그를 찾습니다.

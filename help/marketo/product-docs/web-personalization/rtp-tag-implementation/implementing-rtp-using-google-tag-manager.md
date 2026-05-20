---
unique-page-id: 4720145
description: dnl google을 사용하여 rtp를 구현하는 방법을 포함하여 Marketo Engage에서 google tag manager를 사용하여 rtp에 대해 알아봅니다. 이 안내서를 사용하여 다음 단계를 완료하십시오.
title: Google Tag Manager를 사용하여 RTP 구현
exl-id: f7f06779-8abe-4c8c-9197-9d0c6bcfed49
feature: Web Personalization
TQID: https://experienceleague.adobe.com/XesXGBf2aDsnsbS2Ro1RLdd1EVrj-mBdCiv8C0dj8NU
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 152
ht-degree: 6%

---

# [!DNL Google Tag Manager]을(를) 사용하여 RTP 구현 {#implementing-rtp-using-google-tag-manager}

RTP 태그를 구현하려면 아래의 설치 지침을 따르십시오.

1. [!DNL Google Tag Manager] 계정에 로그인합니다.

1. 새 **[!UICONTROL Tag]** > **[!UICONTROL Tag Configurations]** > **[!UICONTROL Custom HTML Tag].** 추가 **RTP**&#x200B;로 호출합니다.

1. **RTP 계정**&#x200B;에 로그인합니다.

1. **[!UICONTROL Account Settings]** 으로 이동합니다.

   a. 지원에서 이미 JavaScript 태그를 받은 경우 6단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21.png)

1. [!UICONTROL Domain]에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17.png)

1. RTP JavaScript 태그를 복사하여 새로 만든 **사용자 지정 HTML 태그**&#x200B;에 붙여넣습니다(1단계).

1. **[!UICONTROL Add Rule to Fire Tag]**&#x200B;를 클릭합니다. **[!UICONTROL All Pages]**&#x200B;를 선택합니다.

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭하고 [새 버전을 게시](https://support.google.com/tagmanager/answer/2699097?hl=en)합니다.

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **[!UICONTROL Inspect Element]**(으)로 이동하여 **RTP**&#x200B;를 검색하여 태그를 찾습니다.

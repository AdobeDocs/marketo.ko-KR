---
unique-page-id: 4720149
description: dnl wordpress에서 rtp를 구현하는 방법을 포함하여 Marketo Engage의 wordpress에서 rtp를 구현하는 방법에 대해 알아봅니다. 이 안내서를 사용하여 다음 단계를 완료하십시오.
title: Wordpress에 RTP 구현
exl-id: f010942b-02bb-447b-a272-c4237782b2d7
feature: Web Personalization
TQID: https://experienceleague.adobe.com/5V3CEgasEJi4zrYoezh8Tt340VGHNNHaliF2wdbBLwY
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 189
ht-degree: 3%

---

# [!DNL Wordpress]에서 RTP 구현 {#implementing-rtp-on-wordpress}

[!UICONTROL RTP tag]을(를) 구현하려면 아래 설치 지침을 따르십시오.

1. **[!DNL WordPress]테마의** header.php **파일을 엽니다**.

   FTP 클라이언트를 사용하여 서버에 액세스하거나 [!DNL WordPress] 대시보드에서 직접 테마 파일을 편집할 수 있습니다. 파일 편집기는 사이드바 메뉴의 **[!UICONTROL Appearance]** 탭에 있습니다.

   ![](assets/image2014-11-30-15-3a35-3a30.png)

1. 텍스트 편집기 오른쪽의 템플릿 파일 목록에서 **header.php**&#x200B;을(를) 찾아 엽니다.

1. **[!UICONTROL Account Settings]** 으로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 5단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-1.png)

1. [!UICONTROL Domain]에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-11-30-15-3a20-3a17-1.png)

1. RTP JavaScript 태그를 복사하여 웹 사이트 템플릿에 붙여넣습니다.

   a. 페이지 헤더(**`<head> </head>`** 태그 사이)의 첫 번째 스크립트인지 확인하십시오.

   ![](assets/image2014-11-30-15-3a36-3a31.png)

1. header.php 파일의 **[!UICONTROL Update File]**&#x200B;을(를) 클릭합니다.

1. 랜딩 페이지 및 하위 도메인을 포함한 모든 페이지에 표시되는지 확인합니다.

   a. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **[!UICONTROL View Page Source].**(으)로 이동 태그를 찾으려면 **RTP**&#x200B;을 검색하십시오.

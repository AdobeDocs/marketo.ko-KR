---
unique-page-id: 4720151
description: marketo에서의 rtp 구현을 포함하여 Marketo Engage의 marketo 랜딩 페이지에서 rtp를 구현하는 방법에 대해 알아봅니다. 이 안내서를 사용하여 다음 단계를 완료하십시오.
title: Marketo 랜딩 페이지에 RTP 구현
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
TQID: https://experienceleague.adobe.com/scyZfbFBloPu8JRfJiMjm62AFCHM7WCxaats3qssq2A
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: d65b4a73-87a3-4d56-b638-74e74d9939ceid: e2290edd-b061-4880-9d79-dee306cf5aa9id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bccid: f82558ea-6af5-44eb-a424-5b3389abb0a3
topic_v2: id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 187
ht-degree: 6%

---

# Marketo 랜딩 페이지에 RTP 구현 {#implementing-rtp-on-marketo-landing-pages}

[!UICONTROL RTP tag]을(를) 구현하려면 아래 설치 지침을 따르십시오.

1. **[!UICONTROL Design Studio].**(으)로 이동 편집할 항목을 엽니다. **[!UICONTROL Template Actions]**&#x200B;을(를) 선택하고 **[!UICONTROL Edit Draft]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-4-26-18-3a27-3a4.png)

1. **HTML Source** 탭에서 템플릿을 변경합니다.

   ![](assets/image2015-4-26-18-3a28-3a17.png)

1. RTP 계정에서 **[!UICONTROL Account Settings]**(으)로 이동합니다.

   a. 지원에서 JavaScript 태그를 이미 받은 경우 5단계로 이동합니다.

   ![](assets/image2014-11-30-15-3a19-3a21-2.png)

1. [!UICONTROL Domain]에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-26-18-3a27-3a35.png)

   ![](assets/image2014-11-30-15-3a20-3a17-2.png)

1. RTP JavaScript 태그를 복사하여 **`<head> </head>`** 태그 사이의 모든 랜딩 페이지 템플릿에 붙여넣습니다.

1. **[!UICONTROL Save]** 및 **[!UICONTROL Close]** 창을 클릭합니다.

1. **[!UICONTROL Design Studio]**(으)로 돌아가서 **[!UICONTROL Template Actions]**&#x200B;에서 랜딩 페이지를 승인하고 **[!UICONTROL Approve]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-26-18-3a28-3a30.png)

1. 마지막으로, 템플릿 변경 사항을 적용하려면 해당 템플릿을 사용하는 모든 랜딩 페이지를 **다시 승인**&#x200B;해야 합니다. 기본 [!UICONTROL Landing Pages] 섹션에서 한 번에 모두 다시 승인할 수 있습니다.

   ![](assets/image2015-4-26-18-3a28-3a49.png)

1. 랜딩 페이지 및 하위 도메인을 포함한 모든 페이지에 표시되는지 확인합니다.

   웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **[!UICONTROL View Page Source].**(으)로 이동 태그를 찾으려면 **[!UICONTROL RTP]**&#x200B;을(를) 검색하세요.

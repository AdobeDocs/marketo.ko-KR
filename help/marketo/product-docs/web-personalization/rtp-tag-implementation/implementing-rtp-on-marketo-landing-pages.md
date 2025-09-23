---
unique-page-id: 4720151
description: Marketo 랜딩 페이지에서 RTP 구현 - Marketo 문서 - 제품 설명서
title: Marketo 랜딩 페이지에 RTP 구현
exl-id: fd19c3ad-d3f6-44a3-9f7a-d518e2d3f02a
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '169'
ht-degree: 7%

---

# Marketo 랜딩 페이지에 RTP 구현 {#implementing-rtp-on-marketo-landing-pages}

[!UICONTROL RTP tag]을(를) 구현하려면 아래 설치 지침을 따르십시오.

1. **[!UICONTROL Design Studio](으)로 이동합니다.** 편집할 항목을 엽니다. **[!UICONTROL Template Actions]**&#x200B;을(를) 선택하고 **[!UICONTROL Edit Draft]**&#x200B;을(를) 선택합니다.

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

   웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 이 작업을 수행할 수 있습니다. **[!UICONTROL View Page Source](으)로 이동합니다.** **[!UICONTROL RTP]**&#x200B;을(를) 검색하여 태그를 찾습니다.

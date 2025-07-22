---
unique-page-id: 11385053
description: Content-AI용 JavaScript 배포 - Marketo 문서 - 제품 설명서
title: Content-AI용 JavaScript 배포
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
feature: Predictive Content
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# Content-AI용 JavaScript 배포 {#deploy-the-javascript-for-content-ai}

예측 콘텐츠를 사용하려면 RTP(웹 Personalization) 태그를 생성하고 설정해야 합니다.

## 태그 생성 {#generate-tag}

1. Predictive Content 계정에 로그인합니다. **[!UICONTROL Account Settings]**(으)로 이동합니다.

   ![](assets/settings-dropdown-account-hands.png)

1. **[!UICONTROL Domain Configuration]**&#x200B;에서 관련 도메인을 찾아 **[!UICONTROL Generate Tag]**&#x200B;을(를) 클릭합니다.

   ![](assets/generate-tag.png)

1. 웹 Personalization 태그를 복사하여 웹 사이트의 HTML에 붙여넣습니다.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >웹 Personalization JavaScript 태그를 복사하여 페이지의 헤더에 `<head> </head>` 태그 사이에 있는 첫 번째 스크립트로 붙여넣습니다. 자세한 [구현 지침은 여기를 참조하십시오](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 태그가 표시되는지 확인합니다. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 확인합니다. 웹 브라우저에서 **[!UICONTROL View Page Source]**(으)로 이동합니다. 검색: &#39;RTP&#39;.

1. 태그 토글이 **[!UICONTROL ON]**(으)로 설정되어 있는지 확인하십시오.

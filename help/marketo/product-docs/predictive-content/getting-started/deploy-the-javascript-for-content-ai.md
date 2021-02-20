---
unique-page-id: 11385053
description: Content-AI용 JavaScript - Marketing To Docs - 제품 설명서 배포
title: Content-AI용 JavaScript 배포
translation-type: tm+mt
source-git-commit: 06e0f5489e6375a97e2fe77834bf45fa41f23ea6
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---


# Content-AI {#deploy-the-javascript-for-content-ai}용 JavaScript 배포

예측 컨텐츠를 사용하려면 RTP(웹 개인화) 태그를 생성하고 설정해야 합니다.

## 태그 {#generate-tag} 생성

1. 예측 컨텐츠 계정에 로그인합니다. **계정 설정**&#x200B;으로 이동합니다.

   ![](assets/settings-dropdown-account-hands.png)

1. **도메인 구성**&#x200B;에서 관련 도메인을 찾아 **태그 생성**&#x200B;을 클릭합니다.

   ![](assets/generate-tag.png)

1. 웹 개인화 태그를 복사하여 웹 사이트의 HTML에 붙여 넣습니다.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >웹 개인화 JavaScript 태그를 복사하고 페이지 헤더의 첫 번째 스크립트로 `<head> </head>` 태그 사이에 붙여 넣습니다. 자세한 [구현 지침은](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md)에서 확인하십시오.

1. 태그가 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 나타나는지 확인합니다. 웹 사이트 페이지를 마우스 오른쪽 단추로 클릭하여 확인합니다. 웹 브라우저에서 **페이지 소스 보기**&#x200B;로 이동합니다. 검색:&#39;RTP&#39;.

1. 태그 토글이 **ON**&#x200B;으로 설정되어 있는지 확인합니다.

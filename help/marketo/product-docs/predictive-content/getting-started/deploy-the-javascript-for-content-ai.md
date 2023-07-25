---
unique-page-id: 11385053
description: Content-AI용 JavaScript 배포 - Marketo 문서 - 제품 설명서
title: Content-AI용 JavaScript 배포
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
feature: Predictive Content
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# Content-AI용 JavaScript 배포 {#deploy-the-javascript-for-content-ai}

예측 콘텐츠를 사용하려면 RTP(Web Personalization) 태그를 생성하고 설정해야 합니다.

## 태그 생성 {#generate-tag}

1. Predictive Content 계정에 로그인합니다. 다음으로 이동 **계정 설정**.

   ![](assets/settings-dropdown-account-hands.png)

1. 위치 **도메인 구성**&#x200B;을 클릭하고 관련 도메인을 찾은 다음 을 클릭합니다. **태그 생성**.

   ![](assets/generate-tag.png)

1. 웹 개인화 태그를 복사하여 웹 사이트의 HTML에 붙여넣습니다.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >웹 개인화 JavaScript 태그를 복사하여 페이지 머리글의 사이에 있는 첫 번째 스크립트로 붙여넣습니다. `<head> </head>` 태그 사이에 코드를 삽입하지 마십시오. 자세히 보기 [구현 지침 여기](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 태그가 표시되는지 확인합니다. 웹 사이트의 페이지를 마우스 오른쪽 버튼으로 클릭하여 확인합니다. 다음으로 이동 **페이지 소스 보기** 웹 브라우저에서. 검색: &#39;RTP&#39;.

1. 태그 토글이 다음으로 설정되었는지 확인 **날짜**.

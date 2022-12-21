---
unique-page-id: 11385053
description: Content-AI용 JavaScript 배포 - Marketo 문서 - 제품 설명서
title: Content-AI용 JavaScript 배포
exl-id: d48bfd1b-73e8-4013-88d6-8750e4ef532b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# Content-AI용 JavaScript 배포 {#deploy-the-javascript-for-content-ai}

Predictive Content를 사용하려면 RTP(웹 개인화) 태그를 생성하고 설정해야 합니다.

## 태그 생성 {#generate-tag}

1. 예측 컨텐츠 계정에 로그인합니다. 이동 **계정 설정**.

   ![](assets/settings-dropdown-account-hands.png)

1. in **도메인 구성**&#x200B;를 클릭하고 관련 도메인을 찾은 다음 를 클릭합니다. **태그 생성**.

   ![](assets/generate-tag.png)

1. 웹 개인화 태그를 복사하여 웹 사이트의 HTML에 붙여넣습니다.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >웹 개인화 JavaScript 태그를 복사하여 페이지 헤더의 첫 번째 스크립트로 페이지 사이에 붙여넣습니다. `<head> </head>` 태그 사이에 Analytics JavaScript 코드를 배치했습니다. 자세한 내용 [구현 지침](/help/marketo/product-docs/web-personalization/rtp-tag-implementation/deploy-the-rtp-javascript.md).

1. 태그가 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 표시되는지 확인합니다. 웹 사이트의 페이지를 마우스 오른쪽 단추로 클릭하여 확인합니다. 이동 **페이지 소스 보기** 참조하십시오. 검색: &#39;RTP&#39;.

1. 태그 토글이 로 설정되어 있는지 확인합니다. **설정**.

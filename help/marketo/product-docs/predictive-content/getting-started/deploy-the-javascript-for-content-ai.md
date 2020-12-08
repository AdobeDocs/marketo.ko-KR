---
unique-page-id: 11385053
description: Content-AI용 JavaScript 배포 - Marketing Docs - 제품 설명서
title: Content-AI용 JavaScript 배포
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---


# Content-AI용 JavaScript 배포 {#deploy-the-javascript-for-content-ai}

>[!NOTE]
>
>구매 날짜에 따라 마케팅 구독에 마케팅 토 예측 컨텐츠 또는 컨텐츠가 포함될 수 있습니다`<sup>AI</sup>`. 예측 컨텐츠를 사용하는 사용자의 경우 Marketing에서는 2018년 4월 30일까지 컨텐츠`<sup>AI</sup>` 분석 기능을 활성화합니다. 이러한 기능을 해당 날짜 이상으로 유지하려면 마케팅 고객 성공 관리자에게 문의하여 Marketing Cloud 콘텐츠로 업그레이드하십시오`<sup>AI</sup>`.

예측 컨텐츠를 사용하려면 RTP(웹 개인화)를 생성하고 설정해야 합니다 `tag.`

## 태그 생성 {#generate-tag}

1. 예측 컨텐츠 계정에 로그인합니다. 계정 **설정으로 이동합니다**.

   ![](assets/settings-dropdown-account-hands.png)

1. 도메인 **구성에서**&#x200B;관련 도메인을 찾아 태그 **생성을 클릭합니다.**

   ![](assets/generate-tag.png)

1. 웹 개인화 태그를 복사하여 웹 사이트의 HTML에 붙여넣습니다.

   ![](assets/web-personalization-tag.png)

   >[!NOTE]
   >
   >웹 개인화 JavaScript 태그를 복사하여 페이지 헤더의 첫 번째 스크립트로, 태그 사이에 붙여 `<head> </head>` 넣습니다. 자세한 [구현 지침을 보려면 여기를](http://docs.marketo.com/display/docs/rtp+tag+implementation) 참조하십시오 [.](http://pages2.marketo.com/rtp-implementation.html)

1. 태그가 랜딩 페이지 및 하위 도메인을 포함하여 모든 페이지에 나타나는지 확인합니다. 페이지를 마우스 오른쪽 단추로 클릭하여 `website’s` 확인합니다. 웹 브라우저에서 **페이지 소스** 보기로 이동합니다. 검색:&#39;RTP&#39;.
1. 태그 전환 설정이 **켜짐으로 설정되어 있는지 확인합니다**.


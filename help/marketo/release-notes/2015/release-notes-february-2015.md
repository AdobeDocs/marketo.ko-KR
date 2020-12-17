---
unique-page-id: 6094890
description: 릴리스 노트 - 2015년 2월 - Marketing Docs - 제품 설명서
title: 릴리스 노트 - 2015년 2월
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '336'
ht-degree: 0%

---


# 릴리스 노트:2015년 2월 {#release-notes-february}

다음 기능은 2015년 2월 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 확인하려면 Marketing To Edition을 확인하십시오. 릴리스 후에는 각 기능에 대한 자세한 아티클에 대한 링크를 다시 찾아보십시오. 드럼 롤...

## 마케팅 자동화 개선 사항 {#marketing-automation-enhancements}

** [스마트 캠페인 이동](../../product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/move-a-smart-campaign.md)**

기뻐하세요! 이제 트리에서 드래그하여 놓기 또는 이동 기능을 사용하여 프로그램 내/외부로 스마트 캠페인을 이동할 수 있습니다.

** [Dynamics 2015(온라인)](http://docs.marketo.com/display/docs/microsoft+dynamics+2013+on-premises) **- 지원됨!

**HTTPS 인증서 변경 사항**

고객 데이터와 SaaS 서비스의 기밀성과 무결성을 보호하기 위해 Marketing Cloud는 SaaS 업계 모범 사례를 따릅니다.

현재 사용되는 보안 프로토콜(SHA-1 및 SSL)을 다음 도메인에 대한 보안 버전(SHA-2(SHA-256) 및 TLS)으로 바꿉니다.

`·` [marketing.net](http://marketo.net) (암호화된 Munchkin 트래픽)

`·` [marketing.com](http://marketo.com) (기본 SaaS 애플리케이션)

이 문제는 이 릴리스 직후 발생합니다. SHA-1 프로토콜은 이전 시스템 및 응용 프로그램의 소유자가 SHA-2 호환성으로 시스템을 업데이트할 수 있도록 2015년 12월까지 [mktoapi.com](http://mktoapi.com) 도메인에서 일시적으로 지원됩니다.

**Secure Munchkin**

SSL3에 대한 지원을 제거하고 있습니다. 이전 웹 브라우저에 대한 지원을 유지하기 위해 지금까지 SSL3을 유지했지만, 2015년에는 이러한 브라우저에서 중요한 웹 트래픽이 더 이상 표시되지 않습니다. 이는 보안 페이지에서 사용될 경우 Munchkin에만 영향을 주고 2월 릴리스 이후 느리게 롤아웃됩니다.

## 실시간 개인화 개선 사항 {#real-time-personalization-enhancements}

** [캠페인 Target URL](../../product-docs/web-personalization/working-with-web-campaigns/adding-a-target-url-to-a-web-campaign.md)**

&#39;Target URL 추가&#39;를 사용하여 실시간 캠페인을 표시할 페이지를 선택합니다. 이 기능은 모든 캠페인 유형(대화 상자, 영역, 위젯)에서 작동하지만, 선택된 대상 URL에 대해서만 [영역 ID]에서 캠페인이 렌더링되는 [인 영역] 캠페인에서 특히 유용합니다. 여러 웹 페이지를 타깃팅하는 여러 URL 추가를 지원합니다.

![](assets/image2015-2-19-11-3a0-3a30.png)

** [계정 기반 타깃팅에 추가된 국가 및 상태](https://docs.marketo.com/display/DOCS/View+a+Named+Account+List)**

이제 국가 및 주를 지정된 계정 목록에 추가할 수 있습니다. 특정 위치의 Target 주요 계정 잠재 고객.

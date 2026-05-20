---
unique-page-id: 6094890
description: 릴리스 노트 - 2015년 2월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2015년 2월
exl-id: a7ce88dc-a4d2-4ccb-9fe5-61130334d24d
feature: Release Information
TQID: https://experienceleague.adobe.com/IC-YEO8DuW1Y8bNWyUGo9EBp98dsmhZBOVOXmRBPFds
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
  - id: c954475c-8548-4e33-a0b8-6b550d956115
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 338
ht-degree: 1%

---

# 릴리스 정보: 2015년 2월 {#release-notes-february}

다음 기능은 2015년 2월 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오. 릴리스 후에 다시 돌아와 각 기능에 대한 세부 문서에 대한 링크를 찾으십시오. 드럼 롤...

## 향상된 마케팅 자동화 {#marketing-automation-enhancements}

**[스마트 캠페인 이동](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/move-a-smart-campaign.md)**

기뻐하라! 이제 트리의 드래그 앤 드롭 또는 이동 기능을 사용하여 스마트 캠페인을 프로그램 안과 밖으로 이동할 수 있습니다.

**[[!DNL Dynamics] 2015(온라인)](https://docs.marketo.com/display/docs/microsoft+dynamics+2013+on-premises)** - 지원됨!

**HTTPS 인증서 변경**

고객 데이터와 SaaS 서비스의 기밀성과 무결성을 보호하기 위해 Marketo은 SaaS 업계 모범 사례를 따릅니다

및 은 현재 사용되는 보안 프로토콜(SHA-1 및 SSL)을 다음 도메인에 대한 더 안전한 버전(SHA-2(SHA-256)과 TLS)로 대체합니다.

* marketo.net (암호화된 [!DNL Munchkin] 트래픽)

* [marketo.com](https://marketo.com)&#x200B;(기본 SaaS 애플리케이션)

이 문제는 이 릴리스 직후 발생합니다. SHA-1 프로토콜은 레거시 시스템 및 응용 프로그램의 소유자가 SHA-2 호환성으로 시스템을 업데이트할 수 있도록 2015년 12월까지 [mktoapi.com](https://mktoapi.com) 도메인에서 임시로 지원됩니다.

**보안[!DNL Munchkin]**

SSL3에 대한 지원이 제거되었습니다. 이전 웹 브라우저에 대한 지원을 유지하기 위해 지금까지 SSL3을 유지했지만 2015년에는 더 이상 해당 브라우저에서 상당한 웹 트래픽이 발생하지 않습니다. 이는 보안 페이지에서 사용할 경우 [!DNL Munchkin]에만 영향을 주며 2월 릴리스 이후 느리게 롤아웃됩니다.

## 실시간 Personalization 개선 사항 {#real-time-personalization-enhancements}

**[캠페인용 Target URL](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/adding-a-target-url-to-a-web-campaign.md)**

&#39;Target URL 추가&#39;를 사용하여 실시간 캠페인에 표시할 페이지를 선택합니다. 이 기능은 모든 캠페인 유형(대화 상자, 영역, 위젯)에 작동하지만, 특히 선택한 대상 URL에 대해서만 영역 ID로 캠페인이 렌더링되는 영역 내 캠페인에 유용합니다. 여러 URL을 추가하여 다른 웹 페이지를 타깃팅할 수 있습니다.

![](assets/image2015-2-19-11-3a0-3a30.png)

**계정 기반 타깃팅에 추가된 국가 및 상태**

이제 국가와 주를 명명 계정 목록에 추가할 수 있습니다. 특정 지역의 주요 잠재 고객을 대상으로 합니다.

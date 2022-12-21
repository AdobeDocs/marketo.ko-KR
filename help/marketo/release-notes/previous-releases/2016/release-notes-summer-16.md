---
unique-page-id: 11380218
description: 릴리스 노트 - 여름 '16 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2016년 여름
exl-id: 3843668e-c729-42aa-b05c-55c33ee0d783
source-git-commit: 74effe9f8078f8d71e6de01d6e737ddc86978abb
workflow-type: tm+mt
source-wordcount: '783'
ht-degree: 0%

---

# 릴리스 노트: 16년 여름 {#release-notes-summer}

다음 기능은 2016년 여름 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오. 각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오.

## [계정 기반 마케팅](https://docs.marketo.com/display/docs/account+based+marketing) {#account-based-marketing}

Marketo 계정 기반 마케팅은 하나의 통합 플랫폼에서 모든 핵심 사항을 제공합니다.

* **Target** - 계정 검색, 계정 간 일치 및 명명 계정 목록
* **참여** - 계정 기반 개인화, 크로스 채널 참여 및 계정별 워크플로우
* **측정** - 계정 및 목록 수준 인사이트, 계정 참여 점수, 파이프라인 및 매출 영향

![](assets/abm-5-acme.png)

>[!NOTE]
>
>ABM은 Marketo 구독의 추가 기능으로 사용할 수 있으므로 영업 담당자에게 문의하여 구현하십시오.

## [감사 추적](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md) {#audit-trail}

감사 추적은 Marketo 구독 내에서 수행된 변경 사항에 대한 포괄적인 내역을 제공합니다. 사용자 및 관리자 간에 책임을 생성하고, 예기치 않은 행동의 원인을 식별하는 데 도움이 되며, 누가 무엇을 하고 있는지 알 수 있는 보안을 제공합니다. 이 정보는 언제든지 이용할 수 있으며 다음과 같은 질문에 답변하는 데 사용할 수 있습니다.

* 이 자산 또는 설정은 어떻게 되었으며 마지막으로 업데이트한 사람은 누구입니까?
* 사용자 X는 어떤 작업을 수행하고 있습니까?
* 누가 우리 계정에 로그인합니까?

![](assets/audit-trail.png)

## [Marketo-Video SMS LaunchPoint 통합](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-a-vibes-sms-message.md) {#marketo-vibes-sms-launchpoint-integration}

Marketo 내에서 바로 SMS 메시지를 손쉽게 만들 수 있습니다. 풍부한 Marketo 데이터를 사용하여 메시지를 개인화하고 타겟팅하고 SMS 메시지 대시보드를 사용하여 성과를 쉽게 모니터링할 수 있습니다.

>[!NOTE]
>
>이 기능을 사용하려면 기존 Video SMS 계정이 있어야 합니다.

![](assets/vibes-sms2.png)

## [이메일 2.0 개선 사항](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.md) {#email-enhancements}

**모듈 수준 변수**

이전에는 이메일 2.0 템플릿에 지정된 모든 변수가 범위의 &quot;전역&quot;이었습니다. 모듈 내에서 변수를 사용할 때는 모듈의 여러 인스턴스를 사용하려는 경우 이러한 작업이 항상 권장되지 않습니다. 이 릴리스에서는 변수를 이제 &quot;모듈 수준&quot;으로 지정할 수 있습니다. 이 경우 사용자가 사용되는 각 모듈에 대해 고유한 값을 설정할 수 있음을 나타낼 수 있습니다.

![](assets/module-level-variables.png)

**구문 업데이트**

* 이제 이메일 2.0 템플릿에 지정된 모듈에서 &quot;mktoAddByDefault&quot;를 사용하여 기본적으로 새 전자 메일에 표시할 모듈을 표시할 수 있습니다. 모듈이 많은 이메일 템플릿을 만드는 경우 훨씬 편리합니다.
* 이제 이미지 요소에서 `<img>` HTML 요소의 &quot;height&quot; 및 &quot;width&quot; 속성은 잠긴 상태이거나 최종 사용자가 편집할 수 있어야 합니다. mktoLockImgSize=&quot;true&quot;로 설정되면 높이/너비가 잠깁니다(이미지가 변경되더라도). 마찬가지로 mktoLockImgStyle=&quot;true&quot;로 인해 &quot;style&quot; 속성이 잠깁니다.

**코드 검색**

새로운 검색 기능을 사용하여 이메일 코드 내에서 컨텐츠를 효율적으로 찾고 바꿀 수 있습니다. 이 기능은 이메일 템플릿 편집기에서도 사용할 수 있습니다.

![](assets/2nd-screenshot.png)

**이미지 요소의 토큰 지원**

이제 삽입 이미지 환경의 &quot;외부 URL&quot; 영역에서 토큰을 사용할 수 있습니다. 이미지를 `{{my.tokens}}`이제 이메일 편집기 2.0 내에서 이러한 토큰을 참조할 수 있습니다. 이미지가 이메일 편집기 2.0 캔버스에서 계속 끊어져 있습니다. 그러나 이메일을 보내기 전에 미리 보기 및 샘플 보내기 내에서 렌더링된 경우가 표시됩니다.

## 여러 브랜딩 도메인 {#multiple-branding-domains}

이메일 추적 링크를 단일 브랜딩 도메인으로만 브랜딩할 수 있었던 시대는 지나갔습니다. 이제 여러 브랜딩 도메인을 추가하여 소비자 신뢰도를 높이고, 브랜드에 집중할 수 있도록 보다 능률적인 디자인을 만들어 전자 메일 게재 능력을 향상시키며, 각 전자 메일의 추적 링크에 사용할 브랜딩 도메인을 전자 메일로 선택할 수 있습니다.

![](assets/multiple-branding-domains.png)

## [프로그램 토큰](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) {#program-tokens}

프로그램에 대한 새로운 토큰 유형을 만들었습니다. 이제 자산 및 스마트 캠페인 흐름 단계에서 프로그램 이름, 설명 및 ID를 렌더링할 수 있습니다.

![](assets/program-tokens.png)

## [Enterprise 키](/help/marketo/product-docs/marketo-sales-insight/msi-outlook-plugin/authorize-the-marketo-outlook-plugin.md) {#enterprise-key}

영업 팀의 각 직원이 Outlook용 Sales Insight 플러그인을 설치하도록 하는 것은 지루할 수 있습니다. 엔터프라이즈 키를 사용하여 원격으로 Outlook용 플러그인을 설치하는 새로운 방법이 도입되었습니다. 관리자의 Marketo Sales Insight 섹션에 있는 고유 키를 IT 팀에 보내 나머지 작업을 수행하도록 합니다.

![](assets/enterprise-key.png)

## [웹 개인화 캠페인](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md) {#web-personalization-campaigns}

웹 캠페인이 웹 사이트에서 반응할 시간 지연을 지정합니다.

![](assets/dialog-campaign-delay.png)

## [컨텐츠 분석 및 Recommendations 내보내기](/help/marketo/product-docs/web-personalization/understanding-web-personalization/understanding-content-analytics.md) {#content-analytics-and-recommendations-export}

콘텐츠 분석 및 권장 사항 데이터를 오프라인으로 봅니다.

## [이메일 편집기 2.0에 대한 API 지원](https://developers.marketo.com/documentation/asset-api/) {#api-support-for-email-editor}

이제 v1.0 이메일 및 템플릿과 호환되던 기존 자산 API가 v2.0 이메일 자산에 대해 활성화됩니다.

## [Marketo 개발자 사이트](https://developers.marketo.com/) {#marketo-developers-site}

새롭고 개선되었습니다!

## [개인 정보 설정](/help/marketo/product-docs/administration/settings/understanding-privacy-settings.md) {#privacy-settings}

마케터는 개인 정보 설정을 사용하여 Munchkin 및 웹 개인화 기능을 사용하여 방문자를 추적할지 여부를 결정할 수 있습니다. 추적 수준은 브라우저의 추적 안 함 설정, 옵트아웃 쿠키 또는 특정 IP를 사용하여 제어됩니다. 이러한 메서드는 Marketo의 특정 영역의 값 및 기능에 영향을 줄 수 있지만 마케터가 변경하지 않으면 Marketo 기능이 동일하게 유지됩니다.

이 기능은 6주 동안 점진적으로 고객에게 출시될 예정입니다. 즉시 필요한 경우 Marketo 지원 센터에 문의하십시오.

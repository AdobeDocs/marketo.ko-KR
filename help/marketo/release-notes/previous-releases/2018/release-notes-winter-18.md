---
unique-page-id: 13795395
description: 릴리스 노트 - 겨울 '18 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2018년 겨울
exl-id: f08bdc91-86d3-4ea2-a74a-1398ed525bbb
source-git-commit: 6ad418c8f4056b9a2fb31b0ac995692f0c618795
workflow-type: tm+mt
source-wordcount: '599'
ht-degree: 0%

---

# 릴리스 노트: 18년 겨울 {#release-notes-winter}

다음 기능은 2018년 겨울 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오. **참고**: 이 릴리스에 포함된 기능 중 일부에는 관련 문서가 없습니다. 항목에 여러 하위 제목이 있으면 링크가 해당 항목에 배치됩니다.

## 캠페인 성능 및 처리량 개선 사항 {#campaign-performance-and-throughput-enhancements}

Marketo은 우리의 빅 데이터 아키텍처를 활용하여 트리거 캠페인 처리량을 늘리고 웹 활동 처리를 개선하므로 대상의 작업에 보다 신속하게 대응할 수 있습니다.

## Marketo의 Salesforce CRM 통합 개선 사항 {#enhancements-to-marketo-s-salesforce-crm-integration}

Salesforce CRM 통합에 대한 두 가지 개선 사항이 있습니다.

* [Marketo 관리 알림](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications/notification-types.md) 특정 CRM 동기화 실패(자격 증명이 만료됨, API 제한에 도달함 등)의 경우

* [이메일 알림 끄기 기능](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/turn-off-email-notifications-to-lead-owner.md) 리드 지정 시 리드 소유자로 이동

이러한 개선 사항은 2018년에 출시될 예정입니다.

## [Marketo 성능 통찰력](/help/marketo/product-docs/reporting/performance-insights/performance-insights-overview.md) {#marketo-performance-insights}

>[!AVAILABILITY]
>
>Performance Insights 는 추가 기능 제품입니다. 견적서는 Marketo 고객 성공 관리자 또는 계정 담당자에게 문의하십시오.

기여도 분석, 대화형 시각화 및 자세한 데이터 표를 사용하여 캠페인 및 채널이 비즈니스 결과에 미치는 영향을 알아봅니다.

![](assets/image2018-2-5-7-3a55-3a46.png)

## 계정 기반 마케팅 개선 사항 {#account-based-marketing-enhancements}

**[ABM 계층](/help/marketo/product-docs/target-account-management/target/named-accounts/tam-hierarchies.md)**

Salesforce 또는 Microsoft Dynamics를 사용하는 ABM 고객의 경우 ABM이 이제 CRM에 설정된 상위-하위 관계를 자동으로 상속(및 표시)합니다. 롤업 보고 및 캠페인 실행 모두에서 이러한 관계를 사용할 수 있습니다.

## 이메일 마케팅 {#email-marketing}

**[다이내믹 이메일 스크립트](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md)**

이제 다이내믹 콘텐츠를 사용하는 이메일에서 속도 스크립팅이 지원됩니다. 속도와 세그멘테이션 기반의 다이내믹 콘텐츠를 결합하여 개인화된 이메일을 만듭니다.

**받는 사람 시간대**

* **[월간 Cedence Cidence](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)**: 우리는 한 달에 한 번 꼴로 육성프로그램을 예약할 수 있는 능력을 추가했다.

* **[게재 중지](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)**: 이제 나머지 전송을 중간에 중지할 수 있습니다.

## 광고 네트워크 통합 {#ad-network-integrations}

**[Google Customer Match 통합](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-google-customer-match-as-a-launchpoint-service.md)**

이 통합을 사용하면 Google AdWords를 사용하여 타깃팅할 Google에 Marketo 대상자를 보내고 YouTube, 검색 및 Gmail에서 대상을 다시 타깃팅할 수 있습니다.

**[linkedIn Matched Audiences API 개선 사항](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md)**

새로운 LinkedIn API를 사용하면 이제 여러 LinkedIn Campaign Manager 계정에서 Marketo 데이터베이스의 사용자를 다시 타겟팅할 수 있습니다.

## 웹 개인화 {#web-personalization}

**웹 Personalization용 일본어 데이터 소스**

Marketo은 일본에서 오는 방문자를 위한 웹 방문자 식별(역 IP 조회)과 개인화를 개선하기 위해 웹 Personalization에 대한 추가 일본어 데이터 소스를 추가하고 있습니다. 조직 이름이 일본어로 표시됩니다.

**[정적 목록을 사용하여 웹 세그먼트 만들기](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-segment-using-a-static-list.md)**

이제 웹 Personalization에서는 MLM(마케팅 활동)에 정의된 정적 목록에 속하는 알려진 웹 방문자에게 컨텐츠를 개인화할 수 있습니다. 이러한 개선 사항을 통해 이제 여러 채널에서 정적 목록을 마케팅하고 웹 사이트에서 개인화된 콘텐츠를 통해 이러한 목록에 있는 사람들을 타깃팅할 수 있습니다.

## ContentAI {#contentai}

**예측 알고리즘 개선 사항**

Marketo의 최적화된 ContentAI 알고리즘을 통해 권장되는 콘텐츠는 무작위 컨텐츠보다 최대 2회 클릭을 생성합니다.

## 통합 {#integration}

**[Campaign API 활성화/비활성화](https://developers.marketo.com/rest-api/assets/smart-campaigns/)**

이 새로운 API를 사용하면 트리거 캠페인을 원격으로 활성화 및 비활성화할 수 있으므로 이제 완전히 자동화된 프로그램 템플릿을 만들 수 있습니다. 프로그램 템플릿을 한 번 만든 다음 복제, 마케팅 자료 업데이트, 이제 스마트 캠페인의 활성화/예약을 자동화합니다.

## ToutApp {#toutapp}

**업데이트 구독 취소**

2018년 3월 1일부터 보낸 모든 이메일 [ToutApp.com](https://ToutApp.com) (및 Salesforce에서 &quot;Email with Tout&quot; 버튼을 사용하면 아래에 가입 해지 링크가 추가됩니다.

**라이브 피드 업데이트**

Adobe는 영업 구성원이 라이브 피드에서 직접 고객의 활동에 보다 쉽고 빠르게 응답할 수 있도록 참여 및 작업 탭의 모양과 느낌을 업데이트했습니다.

**사람 세부 사항 보기 업데이트**

향상된 사용자 세부 사항 보기(PDV)는 Tout 및 Salesforce CRM 연락처 세부 사항을 함께 가져와서 연락처에 대한 포괄적인 보기를 제공합니다.

---
unique-page-id: 13795395
description: 릴리스 노트 - 1818년 겨울 - Marketo 문서 - 제품 설명서
title: 릴리스 정보 - 2018년 겨울
exl-id: f08bdc91-86d3-4ea2-a74a-1398ed525bbb
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '580'
ht-degree: 0%

---

# 릴리스 정보: 2018년 겨울 {#release-notes-winter}

다음 기능은 18년 겨울 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오. **참고**: 이 릴리스에 포함된 일부 기능에 연결된 문서가 없습니다. 한 주제에 여러 하위 머리글이 있는 경우 링크가 배치됩니다.

## Campaign 성능 및 처리량 개선 {#campaign-performance-and-throughput-enhancements}

Marketo은 빅 데이터 아키텍처를 활용하여 트리거 캠페인 처리량을 증가시키고 웹 활동 처리를 향상시킴으로써 대상의 행동에 보다 신속하게 대응할 수 있습니다.

## Marketo [!DNL Salesforce] CRM 통합 개선 사항 {#enhancements-to-marketo-s-salesforce-crm-integration}

[!DNL Salesforce] CRM 통합에 대한 두 가지 개선 사항이 있습니다.

* 특정 CRM 동기화 실패(자격 증명이 만료됨, API 제한에 도달함 등)에 대한 [Marketo 관리 알림](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications/notification-types.md)

* 잠재 고객 할당 시 잠재 고객 소유자에 대한 [이메일 알림을 끄는 기능](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/turn-off-email-notifications-to-lead-owner.md)

이러한 개선 사항은 2018년에 걸쳐 제공될 예정입니다.

## [Marketo 성능 인사이트](/help/marketo/product-docs/reporting/performance-insights/performance-insights-overview.md) {#marketo-performance-insights}

>[!AVAILABILITY]
>
>[!UICONTROL Performance Insights]은(는) 추가 기능 제품입니다. 견적은 Marketo 고객 성공 관리자 또는 계정 담당자에게 문의하십시오.

기여도 분석, 대화형 시각화 및 세부 데이터 테이블을 통해 캠페인과 채널이 비즈니스 결과에 미치는 영향을 살펴봅니다.

![](assets/image2018-2-5-7-3a55-3a46.png)

## 계정 기반 마케팅 개선 사항 {#account-based-marketing-enhancements}

**[ABM 계층](/help/marketo/product-docs/target-account-management/target/named-accounts/tam-hierarchies.md)**

[!DNL Salesforce] 또는 [!DNL Microsoft Dynamics]을(를) 사용하는 ABM 고객의 경우 ABM은 이제 CRM에 설정된 부모-자식 관계를 자동으로 상속(및 표시)합니다. 롤업 보고와 캠페인 실행 모두에서 이러한 관계를 사용할 수 있습니다.

## 이메일 마케팅 {#email-marketing}

**[동적 전자 메일 스크립트](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md)**

이제 다이내믹 콘텐츠를 사용하는 이메일에서 속도 스크립팅이 지원됩니다. 속도 및 세그먼테이션 기반의 다이내믹 콘텐츠를 결합하여 고도로 개인화된 이메일을 만듭니다.

**받는 사람 시간대**

* **[월별 케이던스](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)**: 월별 케이던스로 육성 프로그램을 예약하는 기능이 추가되었습니다.

* **[게재 중지](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)**: 이제 나머지 전송 중간을 중지할 수 있습니다.

## 광고 네트워크 통합 {#ad-network-integrations}

**[Google Customer Match 통합](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-google-customer-match-as-a-launchpoint-service.md)**

이 통합을 통해 [!DNL Google AdWords]을(를) 사용하여 타깃팅할 Marketo 대상자를 Google으로 보내고 [!DNL YouTube], 검색 및 [!DNL Gmail]에서 대상자를 다시 타깃팅할 수 있습니다.

**[[!DNL LinkedIn] 일치하는 대상 API 개선 사항](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md)**

이제 새로운 [!DNL LinkedIn] API를 사용하여 여러 [!DNL LinkedIn] Campaign Manager 계정에서 Marketo 데이터베이스의 사용자를 다시 타깃팅할 수 있습니다.

## 웹 Personalization {#web-personalization}

**Web Personalization용 일본어 데이터 Source**

Marketo은 일본에서 들어오는 방문자에 대한 웹 방문자 식별(역방향 IP 조회) 및 개인화를 개선하기 위해 Web Personalization에 대한 일본어 데이터 소스를 추가할 예정입니다. 조직 이름은 일본어로 표시됩니다.

**[정적 목록을 사용하여 웹 세그먼트 만들기](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-segment-using-a-static-list.md)**

이제 웹 Personalization은 마케팅 활동(MLM)에 정의된 정적 목록의 일부인 알려진 웹 방문자에게 콘텐츠를 개인화할 수 있습니다. 이제 이 향상된 기능을 통해 채널 전반의 정적 목록을 마케팅하고 웹 사이트에 개인화된 콘텐츠를 사용하여 이러한 목록의 사용자를 타깃팅할 수 있습니다.

## ContentAI {#contentai}

**예측 알고리즘 개선**

Marketo의 최적화된 ContentAI 알고리즘을 통해 권장되는 콘텐츠는 무작위 콘텐츠보다 최대 2배 많은 클릭 수를 생성합니다.

## 통합 {#integration}

**[Campaign API 활성화/비활성화](https://developers.marketo.com/rest-api/assets/smart-campaigns/)**

이 새 API를 사용하면 트리거 캠페인을 원격으로 활성화 및 비활성화할 수 있으므로 이제 완전히 자동화된 프로그램 템플릿을 만들 수 있습니다. 프로그램 템플릿을 한 번 만든 다음 복제, 마케팅 자료 업데이트 및 이제 스마트 캠페인의 활성화/일정을 자동화합니다.

## [!DNL ToutApp] {#toutapp}

**업데이트 구독 취소**

2018년 3월 1일부터 [ToutApp.com](https://ToutApp.com)에서 보낸 모든 전자 메일([!DNL Salesforce]에서 &quot;[!DNL Tout]이 포함된 전자 메일&quot; 단추 사용)에 구독 취소 링크가 맨 아래에 추가됩니다.

**라이브 피드 업데이트**

영업 멤버가 라이브 피드에서 직접 고객의 활동에 보다 쉽고 빠르게 응답할 수 있도록 참여 및 작업 탭의 모양과 느낌을 업데이트했습니다.

**사람 세부 정보 보기 업데이트**

개선된 PDV(사용자 세부 정보 보기)에서는 [!DNL Tout] 및 [!DNL Salesforce] CRM 연락처 세부 정보를 통합하여 연락처를 종합적으로 볼 수 있습니다.

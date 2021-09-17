---
unique-page-id: 12983280
description: 릴리스 노트 - 17년 가을 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2017년 가을
exl-id: 329022e6-f388-4ff9-9724-62aeed76c0b9
source-git-commit: cbfa6110e85c185a5b65342052f168d9715f2f6a
workflow-type: tm+mt
source-wordcount: '597'
ht-degree: 0%

---

# 릴리스 노트: 17년 가을 {#release-notes-fall}

다음 기능은 17년 가을 릴리스에 포함되어 있습니다. 기능을 사용할 수 있는지 Marketo 버전을 확인하십시오.

각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오. 참고: 이 릴리스에 포함된 기능 중 일부에는 관련 문서가 없습니다. 항목에 여러 하위 제목이 있으면 링크가 해당 항목에 배치됩니다.

## 시스템 안정성 {#system-reliability}

Adobe는 더 나은 시퀀싱, 더 적은 불일치와 Munchkin 안정성을 향상하는 등 핵심 Marketo 인프라를 추가로 개선했습니다.

## SFDC 동기화 성능 {#sfdc-sync-performance}

Marketo 및 Salesforce 전체에서 풍부하고 빠른 동기화를 활용할 수 있습니다. 계정 또는 리드에서 벌크 업데이트를 필요로 하는 데이터 변경 사항은 백로그를 방지하기 위해 병렬 큐로 분할할 수 있습니다. 이제 이벤트와 작업을 최대 50% 더 빠르게 동기화합니다.

## Analytics 성능 개선 {#analytics-performance-improvements}

최근의 인프라 개선 사항은 Marketo 보고 및 분석 도구 내에서 향상된 가동 시간 및 안정성을 제공하므로 Ad Hoc 보고서를 보다 신속하게 작성할 수 있습니다.

## [받는 사람 시간대](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md) {#recipient-time-zone}

이 새로운 기능을 사용하면 이제 로컬 시간대에 따라 이메일을 길게 보류하고 전달할 수 있습니다. 전자 메일 및 참여 프로그램은 수신자의 시간대에 전달되도록 구성할 수 있으므로 여러 프로그램을 만들 필요가 없습니다. 한 번 전송하면 Marketo에서 올바른 로컬 시간까지 전자 메일을 자동으로 보관합니다. 이메일 지표를 높이고, 로컬 사례를 관찰하며, 단일 프로그램을 전체적으로 사용하여 시간을 절약할 수 있습니다.

![](assets/image2017-11-29-8-3a45-3a47.png)

>[!NOTE]
>
>전자 메일 및 참여 프로그램에서 받는 사람 시간대를 아직 사용할 수 없다면 당황하지 마십시오! Dell은 모든 고객에게 이 기능을 점진적으로 제공하고 있습니다.

## [세그먼트별 샘플 이메일 검토](/help/marketo/product-docs/email-marketing/general/creating-an-email/send-a-sample-email.md) {#review-sample-emails-by-segment}

Marketo에는 검토를 위해 샘플 이메일을 보낼 때 세그먼트를 선택하는 새 옵션이 있습니다. 리드가 속한 세그먼트를 더 이상 수동으로 확인할 필요가 없으므로 다이내믹 콘텐츠가 포함된 이메일을 다른 세그먼트로 쉽게 보낼 수 있습니다.

## [linkedIn 리드 세대 맞춤형 질문](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md) {#linkedin-lead-gen-custom-questions}

LinkedIn 리드 세대 양식을 사용자 지정하여 사용자 지정 리드 속성을 수집합니다. 이제 양식당 최대 3개의 사용자 지정 질문을 하고, 단일 행 텍스트 입력 또는 다중 선택 질문 중에서 선택하고, Marketo 리드 필드에 다시 매핑할 수 있습니다.

## Slack 통합 {#slack-integration}

새로운 Slack 통합의 일부로 다음과 같은 두 가지 기능을 릴리스했습니다.

* 시스템 알림: 현재 캠페인 상태 및 즉각적인 주의가 필요한 문제에 대한 경고와 같이 Marketo 인스턴스의 중요한 이벤트에 대한 Slack 알림을 받을 수 있습니다.
* 흥미로운 순간: 알려진 개인이 판매 계정을 통해 Marketo Insight를 트리거하면 Slack을 통해 리드 소유자에게 알릴 수 있습니다. 알림에는 판매 계정에 대한 세부 정보와 리드 정보가 포함됩니다.

## ABM 개선 사항 {#abm-enhancements}

**[연락처가 없는 계정 표시](https://docs.marketo.com/x/fKCt)**

이제 Marketo ABM이 동기화되고 연락처 없는 CRM 계정을 표시합니다. 이전 판매 또는 마케팅 기록 없이 새 계정을 포함하고 후속 리드를 계정에 일치시켜 진행 상황을 추적합니다.

## ContentAI Analytics {#contentai-analytics}

**[새 ABM 계정 목록 필터](https://docs.marketo.com/x/1BPG)**

ABM 계정 목록에서 컨텐츠 성능을 보고 비교하여 기존 컨텐츠를 최적화합니다. ContentAI가 다음을 표시합니다.

* 조회된 상위 컨텐츠
* 전환된 콘텐츠
* 마케팅 활동을 위한 AI 기반의 추천 콘텐츠

## 웹 개인화 개선 사항 {#web-personalization-enhancements}

**[웹 캠페인에 대한 토큰](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

이제 웹 캠페인 내에서 토큰을 사용할 수 있습니다. 토큰을 활용하여 개인화된 메시지와 콘텐츠를 전달하여 웹 캠페인의 참여를 높일 수 있습니다.

![](assets/image2017-11-16-11-3a25-3a7.png)

**[웹 캠페인 편집기의 Design Studio 이미지](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

Marketo 내의 여러 채널에서 크리에이티브 자산과 이미지를 다시 사용하여 시간을 절약할 수 있습니다.

![](assets/image2017-11-16-11-3a26-3a10.png)

## 통합  {#integration}

**[이메일 미리 보기 API](https://developers.marketo.com/rest-api/assets/emails/)**

이제 Marketo 외부에서 전자 메일을 원격으로 미리 볼 수 있으므로 전자 메일 콘텐츠 로컬라이제이션 프로세스를 간소화하고 오류를 줄일 수 있습니다.

**[HTML API 바꾸기](https://developers.marketo.com/rest-api/assets/emails/)**

개발자는 이메일 자산의 HTML 콘텐츠를 원격으로 업데이트하여 자산을 유지 관리하기 위해 단일 시스템 내에서 작업할 수 있습니다.

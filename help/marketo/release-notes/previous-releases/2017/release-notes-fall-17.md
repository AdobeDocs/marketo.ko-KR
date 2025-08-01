---
unique-page-id: 12983280
description: 릴리스 노트 - 17년 가을 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2017년 가을
exl-id: 329022e6-f388-4ff9-9724-62aeed76c0b9
feature: Release Information
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 0%

---

# 릴리스 정보: 2017년 가을 {#release-notes-fall}

다음 기능은 17년 가을 릴리스에 포함되어 있습니다. Marketo 버전에서 사용 가능한 기능이 있는지 확인하십시오.

각 기능에 대한 자세한 문서를 보려면 제목 링크를 클릭하십시오. 참고: 이 릴리스에 포함된 일부 기능에는 관련 문서가 없습니다. 한 주제에 여러 하위 머리글이 있는 경우 링크가 배치됩니다.

## 시스템 안정성 {#system-reliability}

시퀀싱 개선, 불일치 감소, [!DNL Munchkin] 안정성 개선 등 핵심 Marketo 인프라에 대한 추가 개선 사항이 있습니다.

## SFDC 동기화 성능 {#sfdc-sync-performance}

Marketo 및 [!DNL Salesforce]에서 풍부하고 빠른 동기화를 활용하십시오. 계정이나 잠재 고객에 대한 대량 업데이트가 필요한 데이터 변경 사항은 병렬 대기열로 분할하여 백로그를 방지할 수 있습니다. 이제 이벤트와 작업도 최대 50% 더 빠르게 동기화됩니다.

## Analytics 성능 개선 {#analytics-performance-improvements}

최근의 인프라 개선 사항은 Marketo 보고 및 분석 도구 내에서 가동 시간과 안정성을 높여 애드혹 보고서를 보다 신속하게 작성할 수 있도록 해 줍니다.

## [받는 사람 시간대](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md) {#recipient-time-zone}

이제 이 새로운 기능을 사용하여 현지 시간대에 따라 이메일을 보류하고 게재할 수 있습니다. 수신자의 시간대에 이메일 및 참여 프로그램을 전달하도록 구성할 수 있으므로 여러 프로그램을 만들 필요가 없습니다. 한 번만 보내면 Marketo에서 올바른 현지 시간까지 이메일을 자동으로 유지합니다. 이메일 지표를 상승시키고, 로컬 사례를 관찰하며, 전 세계에 하나의 프로그램을 사용하여 시간을 절약할 수 있습니다.

![](assets/image2017-11-29-8-3a45-3a47.png)

>[!NOTE]
>
>아직 이메일 및 참여 프로그램에서 수신자 시간대를 활성화할 수 없다면 당황하지 마십시오! 모든 고객에게 이 기능을 점차 활성화하고 있습니다.

## [세그먼트별로 샘플 전자 메일 검토](/help/marketo/product-docs/email-marketing/general/creating-an-email/send-a-sample-email.md) {#review-sample-emails-by-segment}

Marketo에는 검토를 위해 샘플 이메일을 보낼 때 세그먼트를 선택하는 새로운 옵션이 있습니다. 더 이상 잠재 고객이 속한 세그먼트를 수동으로 확인할 필요가 없어 다이내믹 콘텐츠가 포함된 이메일을 다른 세그먼트로 더 쉽게 보낼 수 있습니다.

## [LinkedIn 리드 세대 사용자 지정 질문](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md) {#linkedin-lead-gen-custom-questions}

[!UICONTROL LinkedIn Lead Gen] 양식을 사용자 지정하여 사용자 지정 리드 특성을 수집하십시오. 이제 양식당 최대 3개의 사용자 정의 질문을 하고, 한 줄 텍스트 입력 또는 다중 선택 질문 중에서 선택하고, Marketo 리드 필드에 다시 매핑할 수 있습니다.

## Slack 통합 {#slack-integration}

새로운 Slack 통합의 일부로 다음 두 가지 기능이 릴리스되었습니다.

* 시스템 알림: 현재 캠페인 상태 및 즉각적인 주의가 필요한 문제에 대한 경고와 같은 Marketo 인스턴스의 중요한 이벤트에 대한 Slack 알림을 받습니다.
* 흥미로운 순간: Marketo Insight이 판매 계정의 알려진 개인에 의해 트리거되면 Slack을 통해 잠재 고객 소유자에게 알릴 수 있습니다. 알림에는 잠재 고객 정보와 판매 계정에 대한 세부 정보가 포함됩니다.

## ABM 개선 사항 {#abm-enhancements}

**[연락처가 없는 계정 표시](https://docs.marketo.com/x/fKCt)**

이제 Marketo ABM이 동기화되어 연락처 없이 CRM 계정을 표시합니다. 이전 판매 또는 마케팅 기록이 없는 새 계정을 포함하고 후속 리드를 계정에 대응시켜 진행 상황을 추적합니다.

## ContentAI 분석 {#contentai-analytics}

**[새 ABM 계정 목록 필터](https://docs.marketo.com/x/1BPG)**

ABM 계정 목록에서 컨텐츠 성능을 보고 비교하여 기존 컨텐츠를 최적화합니다. ContentAI는 다음을 보여줍니다.

* 조회한 상위 콘텐츠
* 상위 변환 콘텐츠
* 마케팅 활동을 위한 AI 기반 제안 콘텐츠

## 웹 Personalization 개선 사항 {#web-personalization-enhancements}

웹 캠페인용 토큰 **[개](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

이제 웹 캠페인 내에서 토큰을 사용할 수 있습니다. 토큰을 활용하여 개인화된 메시지와 콘텐츠를 전달하여 웹 캠페인에 대한 참여도를 높일 수 있습니다.

![](assets/image2017-11-16-11-3a25-3a7.png)

**[웹 캠페인 편집기의 Studio 이미지 디자인](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/using-the-web-personalization-rich-text-editor.md)**

Marketo 내의 여러 채널에서 크리에이티브 에셋 및 이미지를 재사용하여 시간을 절약할 수 있습니다.

![](assets/image2017-11-16-11-3a26-3a10.png)

## 통합  {#integration}

**[전자 메일 미리 보기 API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/email-scripting)**

이제 Marketo 외부에서 이메일을 원격으로 미리 볼 수 있으므로 이메일 콘텐츠 현지화 프로세스를 단순화하고 오류를 줄일 수 있습니다.

**[HTML API 바꾸기](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/email-scripting)**

개발자는 이메일 에셋의 HTML 콘텐츠를 원격으로 업데이트할 수 있으므로 에셋을 유지 관리하기 위해 단일 시스템 내에서 작업할 수 있습니다.

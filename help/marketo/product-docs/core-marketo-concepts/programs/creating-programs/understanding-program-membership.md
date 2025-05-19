---
unique-page-id: 1147091
description: 프로그램 멤버십 이해 - Marketo 문서 - 제품 설명서
title: 프로그램 멤버십 이해
exl-id: 02480a93-b499-4e0f-8a1c-a22f7d3b7178
feature: Programs
source-git-commit: 93d6e498ee69a1a9fdee7956ac351764cf18a87a
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 0%

---

# 프로그램 멤버십 이해 {#understanding-program-membership}

>[!NOTE]
>
>**정의:** 구성원은 프로그램에 있는 상태입니다.

## 사람들이 프로그램의 구성원이 되는 방법 {#how-people-become-members-of-a-program}

1. 사용자가 프로그램의 랜딩 페이지[&#128279;](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}에 양식을 작성합니다.

   * 개인은 자동으로 진행 중 첫 번째 상태를 갖게 됩니다.

1. CSV 파일에서 [구성원을 프로그램으로 가져오기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-members-from-a-spreadsheet-into-a-program.md){target="_blank"}합니다.

   * 개인은 자동으로 진행 중 첫 번째 상태를 갖게 됩니다.

1. [프로그램 상태 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md){target="_blank"} 흐름 단계를 사용합니다.
1. 사용자가 이벤트 프로그램과 동기화된 [웨비나](/help/marketo/product-docs/demand-generation/events/understanding-events/event-partners.md){target="_blank"}에 등록하거나 참여합니다.
1. 사용자가 [Marketo iPad 체크 인 응용 프로그램을 사용하여 만들어졌습니다](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/check-people-into-your-event-from-your-tablet.md){target="_blank"}.
1. 사용자가 SFDC 캠페인에 추가되었으며, 이 캠페인은 [프로그램에 동기화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}입니다.

>[!NOTE]
>
>이메일 프로그램의 경우 이메일을 전송할 때만 멤버십에 개인이 추가됩니다.

## 프로그램 상태 {#program-statuses}

프로그램 상태는 프로그램에서 사람들이 거치는 단계입니다(예: 초대됨, 참석, 표시 안 함). 이러한 단계는 [채널](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}에 의해 정의됩니다.

![](assets/image2015-2-5-15-3a14-3a48.png)

>[!NOTE]
>
>이전 프로그램 상태로 되돌릴 수 없습니다. 상태 진행은 한 가지 방법일 뿐입니다.

## 성공 상태 {#success-statuses}

프로그램의 목적은 개인 또는 잠재 고객과의 의미 있는 상호 작용을 창출하는 것이다. 성공 은 개인이 해당 목표를 달성하는 상태에 도달하면 표시됩니다.

>[!NOTE]
>
>웨비나의 경우, 실제로 웨비나를 시청하지 않는다면 등록은 의미 있는 상호 작용이 아닙니다. 이 경우 참석은 성공입니다.

## 고객 확보 프로그램 {#acquisition-program}

새 이름이 시스템에 프로그램 구성원으로 들어오면 Marketo은 해당 프로그램을 자동으로 &quot;획득&quot;으로 설정합니다. [첫 번째 터치 속성](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md){target="_blank"}에 대한 크레딧을 설정합니다.

>[!MORELIKETHIS]
>
>* [프로그램에서 태그 사용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/use-tags-in-a-program.md){target="_blank"}
>* [프로그램 성과 보고서 만들기](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report.md){target="_blank"}

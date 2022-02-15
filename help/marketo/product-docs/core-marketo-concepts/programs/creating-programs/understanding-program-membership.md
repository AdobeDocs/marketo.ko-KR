---
unique-page-id: 1147091
description: 프로그램 멤버십 이해 - Marketo 문서 - 제품 설명서
title: 프로그램 멤버십 이해
exl-id: 02480a93-b499-4e0f-8a1c-a22f7d3b7178
source-git-commit: 441482ea4d367d6d751c4dd5b8bcd67f7fb7935a
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 0%

---

# 프로그램 멤버십 이해 {#understanding-program-membership}

>[!NOTE]
>
>Marketo은 이제 모든 구독에서 언어를 표준화하고 있으므로 docs.marketo.com에서 구독에 리드/리드가 표시되고 사람/사람이 표시될 수 있습니다. 이 용어는 같은 것을 의미합니다. 문서 지침에는 영향을 주지 않습니다. 다른 변화들도 있습니다. [추가 정보](/help/marketo/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.md).

>[!NOTE]
>
>**정의:** 구성원은 프로그램에서 상태가 있는 사람입니다.

## 사람들이 프로그램의 회원이 되는 방법 {#how-people-become-members-of-a-program}

1. 한 사람이 [랜딩 페이지의 양식](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) 프로그램에서 다음을 수행합니다.

   1. 사람은 자동으로 첫 번째 승급 상태를 갖습니다.

1. 사용자 [프로그램에 구성원 가져오기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-members-from-a-spreadsheet-into-a-program.md) CSV 파일로 내보낼 때 시간별 세부기간이 작동하지 않는 문제를 해결했습니다.

   1. 사람은 자동으로 첫 번째 승급 상태를 갖습니다.

1. 를 사용합니다 [프로그램 상태 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md) 흐름 단계.
1. 등록하거나 참석합니다. [이벤트 프로그램과 동기화된 웨비나](/help/marketo/product-docs/demand-generation/events/events/launchpoint-event-partners.md).
1. 사람은 [Marketo iPad 체크인 애플리케이션을 사용하여 생성됨](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/check-people-into-your-event-from-your-tablet.md).
1. 한 사람이 SFDC 캠페인에 추가되며, [프로그램에 동기화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md).

>[!NOTE]
>
>이메일 프로그램의 경우 이메일을 보낼 때만 구성원이 멤버십에 추가됩니다.

## 프로그램 상태 {#program-statuses}

프로그램 상태는 사람들이 프로그램(예: 초대됨, 회답함, 참석함, 표시 안 함)에서 수행하는 단계입니다. 이러한 단계는 [channel](/help/marketo/product-docs/administration/tags/create-a-program-channel.md).

![](assets/image2015-2-5-15-3a14-3a48.png)

>[!NOTE]
>
>이전 프로그램 상태로 이동할 수 없습니다. 상태 진행은 한 가지 방식으로만 제공됩니다.

## 성공 상태 {#success-statuses}

프로그램의 목적은 개인 또는 잠재 고객과 의미 있는 상호 작용을 만드는 것이다. 사용자가 해당 목표를 달성하는 상태에 도달하면 성공이 표시됩니다.

>[!NOTE]
>
>웨비나의 경우, 웨비나를 실제로 보지 않는 경우 등록은 의미 있는 상호 작용이 아닙니다. 이 경우에는 참석이 성공적이다.

## 획득 프로그램  {#acquisition-program}

새 이름이 시스템에 프로그램 멤버로 진입하면 Marketo에서 자동으로 해당 프로그램을 &quot;획득&quot;으로 설정합니다. 이것은 다음에 대한 크레딧을 설정합니다 [첫 번째 터치 속성](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md).

>[!MORELIKETHIS]
>
>* [프로그램에서 태그 사용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags/use-tags-in-a-program.md)
>* [프로그램 성과 보고서 만들기](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report.md)


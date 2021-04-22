---
unique-page-id: 2953473
description: SFDC 동기화 - 활동 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 활동 동기화
exl-id: 780e9cb7-b8b2-4a79-a0b8-d9d34a655330
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---

# SFDC 동기화:활동 동기화 {#sfdc-sync-activity-sync}

또한 Marketo은 Salesforce 활동 데이터를 동기화합니다. 몇 가지 질문과 답변이 있습니다.

## Marketo은 어떤 유형의 활동 데이터를 동기화합니까?{#what-types-of-activity-data-does-marketo-sync-over}

Marketo은 리드 또는 담당자와 연관된 이벤트와 작업 모두에 동기화합니다.

## 두 시스템 간에 활동 세부 정보가 어떻게 동기화됩니까?{#how-are-activity-details-kept-in-sync-between-the-two-systems}

동기화는 Salesforce에서 Marketo에 이르는 모든 과정에서 가능합니다. 그러나 Salesforce에 [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 흐름 단계 또는 [활동 동기화 사용자 지정](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md)을 사용하여 작업을 만들 수 있습니다.

## Marketo을 사용하여 작업을 만들 수 있습니까?{#can-i-create-a-task-using-marketo}

예. [작업 흐름 만들기 작업](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md)을 사용할 수 있습니다.

## 활동과 관련된 트리거/필터는 무엇입니까?{#what-are-the-triggers-filters-related-to-activity}

트리거

* 활동이 기록됨
* 활동이 업데이트됨

필터

* 활동이 기록됨/로그인되지 않음 활동이 기록됨
* 활동이 업데이트됨/업데이트되지 않음

>[!TIP]
>
>&quot;활동 없음&quot; 문구에 대해 확실하지 않습니까? &quot;not&quot;은 비활성 필터를 나타냅니다. 자세한 내용은[스마트 목록에 비활성 필터 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)

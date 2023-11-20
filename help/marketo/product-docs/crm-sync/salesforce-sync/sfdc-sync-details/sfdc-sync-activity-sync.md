---
unique-page-id: 2953473
description: SFDC 동기화 - Activity Sync - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 활동 동기화
exl-id: 780e9cb7-b8b2-4a79-a0b8-d9d34a655330
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# SFDC 동기화: 활동 동기화 {#sfdc-sync-activity-sync}

Marketo Engage은 Salesforce 활동 데이터를 통해서도 동기화됩니다. 여기 몇 가지 질문과 대답이 있습니다.

## Marketo은 어떤 유형의 활동 데이터를 동기화합니까? {#what-types-of-activity-data-does-marketo-sync-over}

Marketo은 리드 또는 연락처와 연결된 이벤트 및 작업을 모두 동기화합니다.

## 활동 세부 사항이 두 시스템 간에 어떻게 동기화됩니까? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

동기화는 Salesforce에서 Marketo에 이르는 한 가지 방법입니다. 하지만 다음을 사용하여 Salesforce에서 작업을 만들 수 있습니다. [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} flow step or [Customize Activities Sync](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md){target="_blank"} Salesforce로.

## Marketo을 사용하여 작업을 만들 수 있습니까? {#can-i-create-a-task-using-marketo}

예, 다음을 사용할 수 있습니다. [작업 흐름 작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"}.

## 활동과 관련된 트리거/필터는 무엇입니까? {#what-are-the-triggers-filters-related-to-activity}

트리거

* 활동이 기록됨
* 활동이 업데이트됨

필터

* 활동이 기록됨/활동이 기록되지 않음
* 활동이 업데이트됨/활동이 업데이트되지 않음

>[!TIP]
>
>&quot;활동 없음&quot;이라는 단어를 모르시나요? &quot;아님&quot;은 비활성 필터를 나타냅니다. 여기에서 자세히 알아보십시오. [스마트 목록에서 비활성 필터 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md){target="_blank"}

---
unique-page-id: 2953473
description: SFDC 동기화 - 활동 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 활동 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---


# SFDC 동기화:활동 동기화 {#sfdc-sync-activity-sync}

Marketing은 Salesforce 활동 데이터도 동기화합니다. 몇 가지 질문과 답변이 있습니다.

## Marketing에서 동기화할 활동 데이터 유형은 무엇입니까? {#what-types-of-activity-data-does-marketo-sync-over}

Marketing to는 리드 또는 담당자와 연관된 이벤트와 작업 모두에 동기화됩니다.

## 두 시스템 간에 활동 세부 정보가 어떻게 동기화됩니까? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

Salesforce에서 Marketing Cloud에 이르는 모든 과정에서 하지만 Salesforce에서 작업 흐름 [만들기 단계나 Salesforce에 활동 동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 사용자 [지정](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md) 단계를 사용하여 작업을만들 수 있습니다.

## Marketing To를 사용하여 작업을 만들 수 있습니까? {#can-i-create-a-task-using-marketo}

예. TaskFlow [생성 작업을 사용할 수 있습니다](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md).

## 활동과 관련된 트리거/필터란? {#what-are-the-triggers-filters-related-to-activity}

트리거

* 활동이 기록됨
* 활동이 업데이트됨

필터

* 활동이 기록됨/기록되지 않음
* 활동이 업데이트됨/업데이트되지 않았습니다.

>[!TIP]
>
>&quot;활동이 아님&quot; 문장에 대해서는 확실하지 않습니까? &quot;not&quot;은 비활동 필터를 나타냅니다. 자세한 내용은 [스마트 목록에서 비활동 필터 사용](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)


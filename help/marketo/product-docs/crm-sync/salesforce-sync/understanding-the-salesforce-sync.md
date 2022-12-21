---
unique-page-id: 4719283
description: Salesforce 동기화 이해 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 이해
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 1%

---

# Salesforce 동기화 이해 {#understanding-the-salesforce-sync}

Marketo과 Salesforce는 완두콩과 당근 같이 모입니다. Adobe는 귀사의 영업 및 마케팅 자료를 계속 동기화합니다.

## 동기화 작동 방식 {#how-sync-works}

Marketo은 매일 Salesforce와 동기화됩니다. 각 동기화는 시간이 좀 걸리고 5분 동안 일시 중지된 다음 다시 시작합니다.

>[!NOTE]
>
>Marketo이 Salesforce에서 전체 데이터베이스를 복사하므로 구독의 첫 번째 동기화는 몇 시간 또는 며칠이 걸릴 수 있습니다. 이후 각 동기화는 일반적으로 초 또는 분이 걸리며 변경된 데이터만 동기화합니다.

![](assets/sync-illustration.png)

Salesforce와 Marketo 간의 동기화는 리드, 연락처 및 Salesforce 캠페인에 대해서만 양방향 동기화입니다. 이러한 경우 Salesforce 또는 Marketo에서 변경할 때마다 업데이트가 두 시스템 모두에 반영됩니다. 다른 모든 동기화는 Salesforce에서 Marketo로만 제공됩니다. 각 링크에 대한 자세한 내용을 보려면 아래 링크를 클릭하십시오.

## Marketo과 Salesforce 간에 동기화되는 기능 {#what-is-synced-between-marketo-and-salesforce}

* [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md)
* [연락처](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md)
* [계정](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md)
* [사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [기회](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [Salesforce 캠페인](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [사용자 정의 개체](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [활동](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>다음 [Salesforce용 Marketo에 입력하는 자격 증명](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 데이터를 동기화하는 데 사용됩니다. 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

Marketo과 Salesforce의 동기화는 세계에서 가장 강력한 기능입니다. 마치 마법처럼 느껴지죠 변경이 이루어졌고 다른 시스템이 곧 최신입니다.

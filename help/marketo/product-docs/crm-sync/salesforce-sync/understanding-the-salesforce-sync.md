---
unique-page-id: 4719283
description: Salesforce 동기화 이해 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 이해
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# Salesforce 동기화 이해 {#understanding-the-salesforce-sync}

Marketo과 Salesforce는 완두콩 및 당근처럼 통합됩니다. Adobe는 귀사의 세일즈 및 마케팅 데이터를 일관되게 유지합니다.

## 동기화 작동 방식 {#how-sync-works}

Marketo은 Salesforce와 매일 동기화됩니다. 각 동기화에는 약간의 시간이 걸리고 5분 동안 일시 정지한 다음 다시 시작됩니다.

>[!NOTE]
>
>Marketo에서 Salesforce의 전체 데이터베이스를 복사하고 있으므로 사용료 지불 옵션의 최초 동기화 작업은 몇 시간 또는 며칠이 걸릴 수 있습니다. 이후 각 동기화는 일반적으로 몇 초 또는 몇 분이 걸리고 변경된 데이터만 동기화합니다.

![](assets/sync-illustration.png)

Salesforce와 Marketo 간의 동기화는 리드, 연락처 및 Salesforce 캠페인에만 양방향 지원이 가능합니다. 이러한 경우 Salesforce 또는 Marketo에서 변경할 때마다 업데이트가 두 시스템에 모두 반영됩니다. 다른 모든 동기들은 Salesforce에서 Marketo으로 제공됩니다. 각 링크에 대한 자세한 내용을 보려면 아래 링크를 클릭하십시오.

## Marketo과 Salesforce 간에 동기화되는 항목{#what-is-synced-between-marketo-and-salesforce}

* [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md)
* [연락처](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md)
* [계정](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md)
* [사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [기회](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [Salesforce 캠페인](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [사용자 정의 객체](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [활동](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>Salesforce용 Marketo](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)에 입력한 [자격 증명은 데이터를 동기화하는 데 사용됩니다. 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

Marketo은 Salesforce와 동기화되어 있으며 세계에서 가장 강력한 기능을 제공합니다. 마법처럼 느껴져요변경 사항이 적용되었으며 다른 시스템은 곧 최신 상태입니다.

---
unique-page-id: 4719283
description: Salesforce 동기화 이해 - Marketo 설명서 - 제품 설명서
title: Salesforce 동기화 이해
exl-id: 658c81ff-5fb3-4ad8-8759-da55bbf4e263
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: ht
source-wordcount: '212'
ht-degree: 100%

---

# [!DNL Salesforce] 동기화 이해 {#understanding-the-salesforce-sync}

Marketo Engage와 Salesforce는 완두콩과 당근처럼 서로 잘 어울립니다. 우리는 고객 판매 및 마케팅 데이터를 동기화합니다.

## 동기화의 작동 방식 {#how-sync-works}

Marketo는 매일 온종일 [!DNL Salesforce]와 동기화됩니다. 각 동기화는 약간의 시간이 소요된 다음 5분 동안 일시 중지되었다가 다시 시작됩니다.

>[!NOTE]
>
>Marketo는 [!DNL Salesforce]에서 전체 데이터베이스를 복사하고 있으므로 구독의 첫 번째 동기화는 몇 시간 또는 며칠이 걸릴 수 있습니다. 그 후에는 각 동기화에 일반적으로 몇 초 또는 몇 분이 소요되며 변경된 데이터만 동기화합니다.

![](assets/sync-illustration.png)

[!DNL Salesforce]와 Marketo 간의 동기화는 리드, 연락처 및 [!DNL Salesforce] 캠페인에 대해서만 양방향으로 이루어집니다. 이 경우에는 사용자가 [!DNL Salesforce] 또는 Marketo에서 변경할 때마다 두 시스템 모두에 업데이트가 반영됩니다. 다른 동기화는 모두 [!DNL Salesforce]에서 Marketo로만 동기화됩니다. 각각에 대한 자세한 내용을 보려면 아래 링크를 클릭하십시오.

## Marketo와 [!DNL Salesforce] 간에 동기화되는 것은 무엇입니까? {#what-is-synced-between-marketo-and-salesforce}

* [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-sync.md){target="_blank"}
* [연락처](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}
* [계정](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"}
* [사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md){target="_blank"}
* [기회](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-opportunity-sync.md){target="_blank"}
* [Salesforce 캠페인](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}
* [사용자 정의 오브젝트](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.md){target="_blank"}
* [활동](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-activity-sync.md){target="_blank"}

>[!NOTE]
>
>Salesforce용 Marketo에 입력한 [자격 증명](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}은 데이터를 동기화하는 데 사용됩니다. 해당 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

Marketo와 [!DNL Salesforce]의 동기화는 전 세계에서 가장 강력한 동기화입니다. 그것은 마술처럼 느껴집니다. 변경가 이루어지고 다른 시스템은 곧 최신 상태가 됩니다.

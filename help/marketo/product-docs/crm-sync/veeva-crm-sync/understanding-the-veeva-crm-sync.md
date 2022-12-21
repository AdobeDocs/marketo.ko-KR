---
description: Veva CRM 동기화 이해 - Marketo 문서 - 제품 설명서
title: Veva CRM 동기화 이해
exl-id: 99ade106-7f32-40e8-8b9a-2b1d0e769b9c
source-git-commit: 884c9a27f3876ec3036f2f7187db30565cdd49a7
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# Veva CRM 동기화 이해 {#understanding-the-veeva-crm-sync}

몇 가지 간단한 단계로 Adobe Marketo Engage과 Veva CRM 간의 동기화를 쉽게 실행할 수 있습니다.

## 동기화 작동 방식 {#how-the-sync-works}

Marketo Engage은 매일 Veva CRM과 동기화됩니다. 각 동기화는 시간이 좀 걸리고, 5분 동안 일시 중지된 다음 다시 시작합니다.

>[!NOTE]
>
>Marketo Engage이 Veveva에서 전체 데이터베이스를 복사하고 있으므로 첫 번째 동기화는 몇 시간 또는 며칠이 걸릴 수 있습니다. 이후 각 동기화는 일반적으로 분(때로 초)이 걸리고 변경된 데이터만 동기화합니다.

![](assets/understanding-the-veeva-sync-1.png)

Veeva와 Marketo Engage 간의 동기화는 개인 계정 개체의 연락처 필드에 대해서만 양방향 동기화입니다. 이러한 경우 Vevar 또는 Marketo Engage에서 변경할 때마다 업데이트가 두 시스템에 모두 반영됩니다. 다른 모든 동기화는 Veveva에서 Marketo Engage만 동기화합니다. 각 링크에 대한 자세한 내용을 보려면 아래 링크를 클릭하십시오.

## Marketo Engage과 Veva 간에 동기화되는 사항 {#what-is-synced-between-marketo-engage-and-veeva}

* [개인 계정](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/person-account-sync-faq.md){target=&quot;_blank&quot;}
* 사용자
* [키 개체 호출 및 호출](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target=&quot;_blank&quot;}
* [사용자 정의 개체](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target=&quot;_blank&quot;}

## 알아야 할 사항 {#things-to-know}

* 다음 [veveva용 Marketo Engage에 입력하는 자격 증명](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target=&quot;_blank&quot;}은 데이터를 동기화하는 데 사용됩니다. 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

* Vevar CRM은 force.com을 기반으로 하며 플랫폼과 함께 있는 풍부한 경험 Marketo Engage이 이 동기화에 상속됩니다.

* Vevar CRM에 다음이 표시됩니다. Lead, Contact, Account(Business Account, Opportunity, Campaign 및 Activity) 그러나 Marketo Engage 동기화 상태에서는 지원되지 않습니다.

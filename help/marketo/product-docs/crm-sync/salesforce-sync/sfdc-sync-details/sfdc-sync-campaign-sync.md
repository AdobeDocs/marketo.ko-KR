---
unique-page-id: 2953469
description: SFDC 동기화 - 캠페인 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 캠페인 동기화
exl-id: 62435e00-9c59-4dee-a9b7-ccf1d1f41b78
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# SFDC 동기화:캠페인 동기화 {#sfdc-sync-campaign-sync}

Marketo 프로그램은 Salesforce 캠페인과 동기화할 수 있습니다. 다음은 이 기능이 작동하는 방식에 대한 개요입니다.

## Marketo 프로그램을 Salesforce 캠페인과 동기화해야 하는 이유는 무엇입니까?{#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* Marketo 프로그램의 강력한 기능 사용
* Marketo 프로그램과 Salesforce 캠페인 간에 멤버와 상태를 동기화할 수 있습니다.
* Marketo 및 Salesforce의 보고 기능을 활용할 수 있습니다.

## Marketo 프로그램과 Salesforce 캠페인은 어떻게 동기화됩니까?{#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

Marketo에서는 프로그램과 Salesforce 캠페인 간에 일대일 매핑을 만들 수 있습니다.

![](assets/image2015-7-8-9-3a43-3a8.png)

Salesforce에 동기화되는 Marketo의 **[채널](/help/marketo/product-docs/administration/tags/create-a-program-channel.md)** 및 **[기간 비용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md)**&#x200B;은 **캠페인 유형** 및 **실제 비용**&#x200B;입니다. 이 동기화는 Marketo에서 Salesforce로 **단방향**&#x200B;입니다.

Marketo **프로그램 멤버** 및 해당 **[진행 상태](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)**&#x200B;는 **Salesforce 캠페인 구성원** 및 **캠페인 구성원 동석**&#x200B;과(와) 동기화됩니다. 이것은 **양방향 동기화**&#x200B;이므로 Marketo 또는 Salesforce에서 변경한 내용이 두 시스템에 모두 반영됩니다.

>[!NOTE]
>
>Salesforce에 없는 Marketo 프로그램에 멤버가 있는 경우 Marketo은 이러한 사람을 Salesforce에서 리드로 만듭니다.

## 캠페인과 관련된 트리거/필터는 무엇입니까?{#what-are-the-triggers-filters-related-to-campaigns}

트리거:

* SFDC 캠페인에 추가됨
* SFDC 캠페인에서 제거됨
* SFDC 캠페인에서 상태가 변경됨

필터:

* SFDC 캠페인 구성원

## SFDC 캠페인에 Marketo 사람을 추가할 수 있습니까?{#can-i-add-marketo-people-to-my-sfdc-campaign}

예, [SFDC 캠페인 흐름 작업에 추가 작업](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md)을 사용합니다. 이 사용자가 Salesforce에 없는 경우 Marketo은 Salesforce에서 만든 다음 캠페인에 추가합니다.

## Marketo을 사용하여 SFDC 캠페인에서 구성원을 제거할 수 있습니까?{#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

예, [SFDC 캠페인 흐름 액션에서 제거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md)를 사용합니다.

## Marketo을 사용하여 캠페인 구성원 상태를 변경할 수 있습니까?{#can-i-change-campaign-member-status-using-marketo}

예, SFDC 캠페인 흐름 동작의 [상태 변경을 사용하십시오](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md).

## Salesforce 캠페인을 볼 수 없는 이유는 무엇입니까?{#why-cant-i-see-any-of-my-salesforce-campaigns}

다음은 확인할 수 있는 사항입니다.

1. [캠페인 동기화가 활성화되어 있는지 확인합니다](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
1. [Marketo 동기화 사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)가 Salesforce의 [마케팅 사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)인지 확인합니다.

>[!NOTE]
>
>Salesforce 캠페인과 매핑된 Marketo 프로그램에 호환되지 않는 프로그램 상태가 있는 경우 오류 메시지가 표시될 수 있습니다. [동기화](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md) 전에 프로그램 상태와 일치시키는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [프로그램과 SFDC 캠페인 동기화](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md)
>* [프로그램 회원 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)
>* [캠페인 동기화 활성화/비활성화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md)
>* [Marketo 동기화 사용자를 마케팅 사용자로 만들기](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)


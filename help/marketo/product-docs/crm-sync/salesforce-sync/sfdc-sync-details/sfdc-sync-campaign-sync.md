---
unique-page-id: 2953469
description: SFDC 동기화 - 캠페인 동기화 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 캠페인 동기화
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---


# SFDC 동기화:캠페인 동기화 {#sfdc-sync-campaign-sync}

Marketing To 프로그램은 Salesforce 캠페인과 동기화할 수 있습니다. 다음은 이 기능이 작동하는 방식에 대한 개요입니다.

## Salesforce 캠페인과 Marketing 프로그램을 동기화해야 하는 이유는 무엇입니까?{#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* Marketing To 프로그램의 강력한 기능을 사용합니다.
* Marketing To 프로그램과 Salesforce 캠페인 간에 멤버와 상태를 동기화할 수 있습니다.
* Marketing 및 Salesforce의 보고 기능을 활용할 수 있습니다.

## Marketing To 프로그램과 Salesforce 캠페인은 어떻게 동기화됩니까?{#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

Marketing To에서는 프로그램과 Salesforce 캠페인 간에 1대1 매핑을 만들 수 있습니다.

![](assets/image2015-7-8-9-3a43-3a8.png)

Marketing의 ** [channel](../../../../product-docs/administration/tags/create-a-program-channel.md) **및 ** [기간 비용](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md)**&#x200B;은 **캠페인 유형** 및 **실제 비용**&#x200B;으로 Salesforce에 동기화됩니다. 이 동기화는 Marketing에서 Salesforce에 이르기까지 **단일 방식의**&#x200B;입니다.

**프로그램 구성원** 및 그 ** [진행 상태](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)**는 **Salesforce 캠페인 구성원** 및 **캠페인 구성원 동석**&#x200B;과(와) 동기화됩니다. 이것은 **양방향** **동기화**&#x200B;이므로 Marketing 또는 Salesforce에서 변경한 내용이 두 시스템 모두에 반영됩니다.

>[!NOTE]
>
>Salesforce에 없는 Marketing To 프로그램에 멤버가 있는 경우 Marketing은 해당 사람을 Salesforce에서 리드로 만듭니다.

## 캠페인과 관련된 트리거/필터는 무엇입니까?{#what-are-the-triggers-filters-related-to-campaigns}

트리거:

* SFDC 캠페인에 추가됨
* SFDC 캠페인에서 제거됨
* SFDC 캠페인에서 상태가 변경됨

필터:

* SFDC 캠페인 구성원

## SFDC 캠페인에 마케팅 담당자를 추가할 수 있습니까?{#can-i-add-marketo-people-to-my-sfdc-campaign}

예, [SFDC 캠페인 흐름 작업에 추가 작업](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md)을 사용합니다. 이 사람이 Salesforce에 없는 경우 Marketing에서 Salesforce에 만든 다음 캠페인에 추가합니다.

## Marketing To를 사용하여 SFDC 캠페인에서 구성원을 제거할 수 있습니까?{#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

예, [SFDC 캠페인 흐름 액션에서 제거](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md)를 사용합니다.

## Marketing To를 사용하여 캠페인 구성원 상태를 변경할 수 있습니까?{#can-i-change-campaign-member-status-using-marketo}

예, SFDC 캠페인 흐름 동작의 [상태 변경을 사용하십시오](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md).

## Salesforce 캠페인을 볼 수 없는 이유는 무엇입니까?{#why-cant-i-see-any-of-my-salesforce-campaigns}

다음은 확인할 수 있는 사항입니다.

1. [캠페인 동기화가 활성화되어 있는지 확인합니다](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
1. [Marketing To Sync 사용자](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)가 Salesforce의 [마케팅 사용자](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)인지 확인합니다.

>[!NOTE]
>
>Salesforce 캠페인과 매핑된 Marketing To 프로그램이 호환되지 않는 프로그램 상태가 있는 경우 오류 메시지가 표시될 수 있습니다. [동기화](sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md) 전에 프로그램 상태와 일치시키는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [프로그램과 SFDC 캠페인 동기화](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md)
>* [프로그램 회원 이해](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)
>* [캠페인 동기화 활성화/비활성화](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md)
>* [Marketing To 동기화 사용자를 마케팅 사용자로 만들기](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)

>




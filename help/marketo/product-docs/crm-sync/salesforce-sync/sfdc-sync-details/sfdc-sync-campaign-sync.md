---
unique-page-id: 2953469
description: SFDC 동기화 - 캠페인 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 캠페인 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '379'
ht-degree: 0%

---


# SFDC 동기화:캠페인 동기화 {#sfdc-sync-campaign-sync}

마케팅 프로그램은 Salesforce 캠페인과 동기화할 수 있습니다. 다음은 이 기능의 사용 방법에 대한 개요입니다.

## Marketing To 프로그램을 Salesforce 캠페인과 동기화해야 하는 이유는 무엇입니까? {#why-should-i-sync-marketo-programs-with-salesforce-campaigns}

* 마케팅 프로그램의 강력한 기능 사용
* Marketing 프로그램과 Salesforce 캠페인 간에 멤버와 상태를 동기화할 수 있습니다.
* Marketing and Salesforce의 보고 기능을 활용할 수 있습니다.

## 마케팅 프로그램과 Salesforce 캠페인은 어떻게 동기화됩니까? {#how-is-a-marketo-program-and-a-salesforce-campaign-synced}

Marketing에서는 프로그램과 Salesforce 캠페인 간에 1대1 매핑을 만들 수 있습니다.

![](assets/image2015-7-8-9-3a43-3a8.png)

** 채널 [](../../../../product-docs/administration/tags/create-a-program-channel.md)**[및 **](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md)** 기간 비용 **은 Marketing에서 Salesforce와 동기화하여 실제** 비용 **으로**&#x200B;사용됩니다. Marketing Cloud에서 Salesforce **에 이르기까지**&#x200B;이러한 동기화

Marketing **프로그램 멤버** 및 ** [진행 상태](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)**는 **Salesforce 캠페인 구성원** 및 **캠페인 구성원 동그라미**&#x200B;와 동기화됩니다. 양방향 **동기화이므로** Marketing ****&#x200B;또는 Salesforce에서 변경한 내용이 두 시스템에 모두 반영됩니다.

>[!NOTE]
>
>Salesforce에 존재하지 않는 Marketing To 프로그램에 멤버가 있는 경우 Marketing은 해당 사용자를 Salesforce에서 리드로 만듭니다.

## 캠페인과 관련된 트리거/필터는 무엇입니까? {#what-are-the-triggers-filters-related-to-campaigns}

트리거:

* SFDC 캠페인에 추가됨
* SFDC 캠페인에서 제거됨
* SFDC 캠페인에서 상태가 변경됨

필터:

* SFDC 캠페인 구성원

## SFDC 캠페인에 Marketing To People을 추가할 수 있습니까? {#can-i-add-marketo-people-to-my-sfdc-campaign}

예, SFDC에 [추가 캠페인 흐름 작업을 사용하십시오](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/add-to-sfdc-campaign.md). 이 사용자가 Salesforce에 없는 경우 Marketing에서 Salesforce에 만든 다음 캠페인에 추가합니다.

## Marketing To를 사용하여 SFDC 캠페인에서 구성원을 제거할 수 있습니까? {#can-i-remove-members-from-my-sfdc-campaign-using-marketo}

예, SFDC [캠페인 흐름](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/remove-from-sfdc-campaign.md)작업에서 제거 작업을 사용하십시오.

## Marketing to를 사용하여 캠페인 구성원 상태를 변경할 수 있습니까? {#can-i-change-campaign-member-status-using-marketo}

예, SFDC 캠페인 [흐름 동작에서 상태 변경 작업을 사용하십시오](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md).

## Salesforce 캠페인을 볼 수 없는 이유는 무엇입니까? {#why-cant-i-see-any-of-my-salesforce-campaigns}

다음은 확인할 수 있는 사항입니다.

1. 캠페인 [동기화가 활성화되어 있는지 확인합니다](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
1. Marketing [to Sync 사용자](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 가 Salesforce의 [마케팅 사용자인지](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) 확인합니다.

>[!NOTE]
>
>Salesforce 캠페인 및 매핑된 Marketing To 프로그램이 호환되지 않는 프로그램 상태에 있는 경우 오류 메시지가 표시될 수 있습니다. 프로그램 상태 [를 동기화하기 전에 일치시키는 것이 좋습니다](sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md).

>[!NOTE]
>
>**관련 문서**
>
>* [프로그램과 SFDC 캠페인 동기화](../../../../product-docs/core-marketo-concepts/programs/working-with-programs/sync-an-sfdc-campaign-with-a-program.md)
>* [프로그램 회원 이해](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)
>* [캠페인 동기화 활성화/비활성화](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md)
>* [Marketing To 동기화 사용자를 마케팅 사용자로 만들기](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md)

>




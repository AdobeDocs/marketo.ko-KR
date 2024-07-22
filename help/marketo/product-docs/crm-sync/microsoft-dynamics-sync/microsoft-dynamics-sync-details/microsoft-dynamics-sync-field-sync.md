---
unique-page-id: 3571838
description: Microsoft Dynamics 동기화 - 필드 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 필드 동기화
exl-id: 78eef0eb-4086-45c5-bce3-a3399016f228
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 0%

---

# Microsoft Dynamics 동기화: 필드 동기화 {#microsoft-dynamics-sync-field-sync}

Dynamics 동기화로의 Marketo Engage 기능은 매우 강력합니다. 세부사항은 다음과 같습니다.

## 필드 세부 사항이 두 시스템 간에 어떻게 동기화됩니까? {#how-are-field-details-kept-in-sync-between-the-two-systems}

동기화는 리드 및 연락처 엔티티에 대해 양방향입니다. Dynamics의 잠재 고객이나 연락처 또는 Marketo의 사용자를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

계정, 사용자, 영업 기회, 팀 및 사용자 지정 엔터티의 경우 동기화는 단방향(Marketo에 Dynamics)입니다. Dynamics에서 이러한 엔티티를 변경하면 업데이트가 Marketo에 반영됩니다.

## 두 시스템의 동일한 필드에 동시에 변경 사항이 적용되면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이긴 하지만 Marketo은 사람(잠재 고객)이, Dynamics는 연락처가 각각 승리합니다. 이는 마케팅 부서가 사람을 위한 권위적인 것으로 간주되는 반면, 연락처에 대한 공식 기록 시스템은 영업(CRM) 부서에 있기 때문입니다. 단방향 동기화 엔터티의 경우 Dynamics가 항상 성공합니다.

## Marketo을 사용하여 Dynamics에서 필드를 만들 수 있습니까? {#can-i-create-a-field-in-dynamics-using-marketo}

아니요. 현재 지원되지 않습니다.

## Dynamics에서 필드를 만들었습니다. Marketo에 동기화할 수 있습니까? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

예, 동기화 사용자가 Dynamics에서 해당 필드에 액세스할 수 있는 한 [필드를 동기화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"}할 수 있습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#what-fields-will-sync-to-marketo}

설치하는 동안 [동기화할 필드를 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"}할 수 있습니다.

## Marketo 및 Dynamics가 동기화된 후 사용자 지정 필드를 추가해야 하는 경우 어떻게 합니까? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

언제든지 필드를 추가할 수 있으며 데이터가 Dynamics에서 Marketo으로 새로 고쳐질 것으로 예상됩니다. 자세한 내용은 [새 사용자 지정 필드에 대해 Microsoft Dynamics와 빠른 동기화 사용](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md){target="_blank"}을 참조하십시오.

## 동기화에 필드를 추가한 후 Dynamics에서 필드를 삭제하려면 어떻게 해야 합니까? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo은 동기화할 필드에 대한 참조를 저장합니다. Dynamics에서 필드를 삭제하는 경우 [동기화가 비활성화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}을(를) 사용하여 삭제하는 것이 좋습니다. 그런 다음 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}을 편집하고 저장하여 Marketo의 스키마를 새로 고치십시오.

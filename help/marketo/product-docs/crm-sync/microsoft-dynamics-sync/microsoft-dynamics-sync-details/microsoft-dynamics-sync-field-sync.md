---
unique-page-id: 3571838
description: Microsoft Dynamics 동기화 - 필드 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 필드 동기화
exl-id: 78eef0eb-4086-45c5-bce3-a3399016f228
source-git-commit: 7fcbaeda589682fdb5a75b89a0abd8661181566e
workflow-type: tm+mt
source-wordcount: '337'
ht-degree: 0%

---

# Microsoft Dynamics 동기화: 필드 동기화 {#microsoft-dynamics-sync-field-sync}

Marketo에서 Dynamics로의 동기화 기능은 매우 강력합니다. 자세한 내용은 다음과 같습니다.

## 필드 세부 사항이 두 시스템 간에 어떻게 동기화됩니까? {#how-are-field-details-kept-in-sync-between-the-two-systems}

동기화는 리드 및 연락처 엔터티에 대한 양방향 동기화입니다. Dynamics 또는 Marketo에서 잠재 고객 또는 연락처를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

계정, 사용자, 기회, 팀 및 사용자 지정 엔터티의 경우 동기화는 단방향: Dynamics에서 Marketo으로 이동합니다. Dynamics에서 이러한 엔티티를 변경하면 업데이트가 Marketo에 반영됩니다.

## 두 시스템의 동일한 필드를 동시에 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이지만 Marketo이 사람(리드)에게 승리하고 Dynamics가 연락처 면에서 승리합니다. 이것은 우리가 마케팅 부서가 사람들에게 권한을 부여한다고 생각하는데 반해, 공식적인 연락처 기록 시스템은 판매(CRM) 부서에 있기 때문입니다. 단방향 동기화 엔티티의 경우 Dynamics가 항상 승리합니다.

## Marketo을 사용하여 Dynamics에서 필드를 만들 수 있습니까? {#can-i-create-a-field-in-dynamics-using-marketo}

아니요. 현재 지원되지 않습니다.

## Dynamics에서 필드를 만들었습니다. Marketo에 동기화할 수 있습니까? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

네, 가능합니다 [필드 동기화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) 동기화 사용자가 Dynamics에서 해당 항목에 액세스할 수 있는 한.

## Marketo에 동기화할 필드는 무엇입니까? {#what-fields-will-sync-to-marketo}

다음을 수행할 수 있습니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) 설정하는 동안.

## Marketo 및 Dynamics가 동기화된 후 사용자 지정 필드를 추가해야 하는 경우 어떻게 합니까? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

언제든지 필드를 추가할 수 있으며 Dynamics에서 Marketo으로 데이터를 새로 고칠 수 있습니다. 자세한 내용은 [새 사용자 지정 필드에 Microsoft Dynamics와 빠른 동기화 사용](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) 자세한 내용

## 동기화하도록 필드를 추가한 후 Dynamics에서 필드를 삭제하려면 어떻게 해야 합니까? {#what-if-i-want-to-delete-a-field-in-dynamics-after-the-field-has-been-added-to-sync}

Marketo은 동기화할 필드에 대한 참조를 저장합니다. Dynamics에서 필드를 삭제하는 경우 [동기화 사용 안 함](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). 그런 다음 를 편집하고 저장하여 Marketo에서 스키마를 새로 고칩니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).

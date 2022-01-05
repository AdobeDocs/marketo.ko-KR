---
unique-page-id: 3571848
description: Microsoft Dynamics 동기화 - 리드 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 리드 동기화
exl-id: ea04a039-32f7-41f9-85fb-18df8e236390
source-git-commit: 17cacaa56a437a568bd0d2cc23020f3f880eaf52
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---

# Microsoft Dynamics 동기화: 리드 동기화 {#microsoft-dynamics-sync-lead-sync}

Marketo에서 Dynamics로의 동기화 기능은 매우 강력합니다. 세부 사항은 다음과 같습니다.

## 두 시스템 간에 세부 정보가 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

동기화는 양방향 동기화입니다. Dynamics에서 리드를 변경하거나 Marketo에서 사용자를 변경하면 두 시스템 모두에 업데이트가 반영됩니다.

>[!NOTE]
>
>삭제는 두 방향 모두에서 자동으로 동기화되는 것은 아닙니다. 자세한 내용은 [리드 또는 연락처 삭제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md).

## 두 시스템의 동일한 필드를 동시에 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이지만 Marketo이 사람(리드)에게 승리하고 Dynamics가 연락처 면에서 승리합니다. 이것은 우리가 마케팅 부서가 사람들에게 권한을 부여한다고 생각하는데 반해, 공식적인 연락처 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketo을 사용하여 Dynamics에서 리드를 만들 수 있습니까? {#can-i-create-a-lead-in-dynamics-using-marketo}

예, [Microsoft에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 작업. 리드가 없는 경우 Dynamics에서 리드가 생성됩니다. 리드가 존재하는 경우 흐름 단계는 어떤 작업도 수행하지 않습니다.

>[!NOTE]
>
>&quot;Microsoft에 개인 동기화&quot; 흐름 작업을 사용할 때(트리거 캠페인에서만) 리드/연락처가 Dynamics에서 실시간으로 생성됩니다.

## Marketo에서 리드로 개인 동기화를 Dynamics에서 수동으로 강제 적용할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

아니요. 자동화된 백그라운드 동기화는 Marketo과 Dynamics 간에 업데이트를 동기화하는 유일한 방법입니다. 다음 [Microsoft에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 동작은 리드의 동기화를 강제하지 않습니다.

## Marketo에 동기화할 필드는 무엇입니까? {#what-fields-will-sync-to-marketo}

다음을 수행할 수 있습니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-4-of-4-connect.md#select-fields-to-sync) 설정하는 동안.

## Marketo이 Dynamics 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

예. 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이런 경우 Marketo은 결과를 개인 활동 로그에 기록합니다.

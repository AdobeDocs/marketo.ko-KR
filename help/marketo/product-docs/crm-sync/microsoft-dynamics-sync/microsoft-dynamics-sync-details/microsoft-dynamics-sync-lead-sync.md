---
unique-page-id: 3571848
description: Microsoft Dynamics Sync - 잠재 고객 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 동기화 리드
exl-id: ea04a039-32f7-41f9-85fb-18df8e236390
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 0%

---

# Microsoft Dynamics Sync: 잠재 고객 동기화 {#microsoft-dynamics-sync-lead-sync}

Dynamics 동기화로의 Marketo Engage 기능은 매우 강력합니다. 세부사항은 다음과 같습니다.

## 두 시스템 간에 세부 사항이 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

동기화는 양방향입니다. Dynamics의 잠재 고객이나 Marketo의 사용자를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

>[!NOTE]
>
>삭제는 항상 두 방향에서 자동으로 동기화되지 않습니다. 다음을 참조하십시오 [리드 또는 연락처 삭제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md){target="_blank"}.

## 두 시스템의 동일한 필드에 동시에 변경 사항이 적용되면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이긴 하지만 Marketo은 사람(잠재 고객)이, Dynamics는 연락처가 각각 승리합니다. 이는 마케팅 부서가 사람을 위한 권위적인 것으로 간주되는 반면, 연락처에 대한 공식 기록 시스템은 영업(CRM) 부서에 있기 때문입니다.

## Marketo을 사용하여 Dynamics에서 잠재 고객을 만들 수 있습니까? {#can-i-create-a-lead-in-dynamics-using-marketo}

예, 다음을 사용합니다. [Microsoft에 사용자 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} 흐름 작업. 잠재 고객이 없는 경우 Dynamics에서 잠재 고객이 생성됩니다. 잠재 고객이 존재하는 경우 흐름 단계에서 아무 작업도 수행되지 않습니다.

>[!NOTE]
>
>트리거 캠페인에서만 &quot;사용자와 Microsoft 동기화&quot; 흐름 작업을 사용하는 경우, 리드/연락처는 Dynamics에서 실시간으로 생성됩니다.

## Marketo의 사용자를 Dynamics의 리드로 수동으로 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

아니요. 자동화된 백그라운드 동기화는 Marketo과 Dynamics 간에 업데이트를 동기화하는 유일한 방법입니다. 다음 [Microsoft에 사용자 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md){target="_blank"} 흐름 액션은 리드의 동기화를 강제하지 않습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#what-fields-will-sync-to-marketo}

다음을 수행할 수 있습니다. [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"} 설정하는 동안.

## Marketo이 Dynamics 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

네. 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이 경우 Marketo은 개인의 활동 로그에 결과를 기록합니다.

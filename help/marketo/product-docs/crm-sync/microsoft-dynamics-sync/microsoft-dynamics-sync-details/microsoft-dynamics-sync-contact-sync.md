---
unique-page-id: 3571833
description: Microsoft Dynamics 동기화 - 연락처 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 연락처 동기화
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
source-git-commit: 7fcbaeda589682fdb5a75b89a0abd8661181566e
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# Microsoft Dynamics 동기화: 동기화 문의 {#microsoft-dynamics-sync-contact-sync}

Marketo이 전체 데이터베이스를 Dynamics와 동기화하는 것을 알고 있습니까? 동기화되고 5분을 기다린 다음 하루 종일 다시 동기화됩니다. 다음은 Marketo에서 Dynamics 연락처를 처리하는 방법에 대한 자세한 정보입니다.

## 두 시스템 간에 세부 정보가 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

연락처 동기화는 양방향 동기화입니다. Dynamics 또는 Marketo에서 연락처를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템의 동일한 필드를 동시에 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드물긴 하지만 Marketo이 인맥에서 승리하고 Dynamics가 연락처 면에서 승리를 거두게 됩니다. 이것은 우리가 마케팅 부서가 사람들에게 권한을 부여한다고 생각하는데 반해, 공식적인 연락처 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketo을 사용하여 연락처를 만들 수 있습니까? {#can-i-create-a-contact-using-marketo}

예. [방법은 다음과 같습니다](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md).

>[!NOTE]
>
>&quot;Microsoft에 개인 동기화&quot; 흐름 작업을 사용할 때(트리거 캠페인에서만) 리드/연락처가 Dynamics에서 실시간으로 생성됩니다.

## 개인 또는 연락처를 수동으로 강제 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

아니요. 자동화된 백그라운드 동기화는 Marketo과 Dynamics 간에 업데이트를 동기화하는 유일한 방법입니다. 다음 [Microsoft에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 리드를 강제로 동기화하지 않습니다.

## Marketo에 동기화할 필드는 무엇입니까? {#what-fields-will-sync-to-marketo}

다음을 수행할 수 있습니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) 설정하는 동안. 그러나 Marketo은 Dynamics 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 Dynamics 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

예. 충돌이 발생하면 리드 활동 로그에 결과를 기록합니다.

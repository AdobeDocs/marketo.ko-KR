---
unique-page-id: 3571833
description: Microsoft Dynamics 동기화 - 연락처 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 연락처 동기화
exl-id: d4583ea0-2b52-415e-b28c-a8eafebeff64
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화: 연락처 동기화 {#microsoft-dynamics-sync-contact-sync}

Marketo이 전체 데이터베이스를 [!DNL Dynamics]과(와) 동기화한다는 것을 알고 계십니까? 동기화한 후 5분을 기다린 후 다시 매일 하루 종일 동기화합니다. 다음은 Marketo에서 [!DNL Dynamics] 연락처를 구체적으로 처리하는 방법에 대한 세부 정보입니다.

## 두 시스템 간에 세부 사항이 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

연락처 동기화는 양방향입니다. [!DNL Dynamics]의 연락처 또는 Marketo의 사용자를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

## 두 시스템의 동일한 필드에 동시에 변경 사항이 적용되면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이긴 하지만 Marketo은 사람을 위해 우승하고 [!DNL Dynamics]은(는) 연락처를 위해 우승합니다. 이는 마케팅 부서가 사람을 위한 권위적인 것으로 간주되는 반면, 연락처에 대한 공식 기록 시스템은 영업(CRM) 부서에 있기 때문입니다.

## Marketo을 사용하여 연락처를 만들 수 있습니까? {#can-i-create-a-contact-using-marketo}

예. [방법은 다음과 같습니다](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md){target="_blank"}.

>[!NOTE]
>
>&quot;사용자와 Microsoft 동기화&quot; 흐름 작업(트리거 캠페인에서만)을 사용하는 경우 리드/연락처가 [!DNL Dynamics]에 실시간으로 만들어집니다.

## 개인 또는 연락처의 동기화를 수동으로 강제할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

아니요. 자동 백그라운드 동기화는 Marketo과 [!DNL Dynamics] 간에 업데이트를 동기화하는 유일한 방법입니다. [사용자를 Microsoft에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md)하면 잠재 고객의 동기화가 강제 수행되지 않습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#what-fields-will-sync-to-marketo}

설치하는 동안 [동기화할 필드를 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync)할 수 있습니다. 하지만 Marketo은 [!DNL Dynamics] 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 [!DNL Dynamics] 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

예. 충돌이 발생하면 리드 활동 로그에 결과가 기록됩니다.

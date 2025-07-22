---
unique-page-id: 3571848
description: Microsoft Dynamics 동기화 - 리드 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 리드 동기화
exl-id: ea04a039-32f7-41f9-85fb-18df8e236390
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화: 리드 동기화 {#microsoft-dynamics-sync-lead-sync}

[!DNL Dynamics] 동기화로의 Marketo은 매우 강력합니다. 자세한 내용은 다음과 같습니다.

## 두 시스템 간에 세부 사항이 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

동기화는 양방향입니다. [!DNL Dynamics]의 잠재 고객이나 Marketo의 사용자를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

>[!NOTE]
>
>삭제는 항상 두 방향에서 자동으로 동기화되지 않습니다. [잠재 고객 또는 연락처 삭제](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md){target="_blank"}를 참조하십시오.

## 두 시스템의 동일한 필드에 동시에 변경 사항이 적용되면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이긴 하지만 Marketo이 사람(잠재 고객)을 위해 우승하고 [!DNL Dynamics]이(가) 연락처를 위해 우승합니다. 이는 마케팅 부서가 사람을 위한 권위적인 것으로 간주되는 반면, 연락처에 대한 공식 기록 시스템은 영업(CRM) 부서에 있기 때문입니다.

## Marketo을 사용하여 [!DNL Dynamics]에서 잠재 고객을 만들 수 있습니까? {#can-i-create-a-lead-in-dynamics-using-marketo}

예, [[!UICONTROL Sync Person to Microsoft]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 동작을 사용합니다. 잠재 고객이 없는 경우 [!DNL Dynamics]에 잠재 고객이 만들어집니다. 잠재 고객이 존재하는 경우 흐름 단계에서 아무 작업도 수행되지 않습니다.

>[!NOTE]
>
>&quot;[!UICONTROL Sync Person to Microsoft]&quot; 흐름 작업을 사용할 때(트리거 캠페인에서만) 리드/연락처가 [!DNL Dynamics]에 실시간으로 만들어집니다.

## Marketo의 사용자를 [!DNL Dynamics]의 리드에 수동으로 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

아니요. 자동 백그라운드 동기화는 Marketo과 [!DNL Dynamics] 간에 업데이트를 동기화하는 유일한 방법입니다. [[!UICONTROL Sync Person to Microsoft]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 작업은 잠재 고객의 동기화를 강제하지 않습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#what-fields-will-sync-to-marketo}

설치하는 동안 [동기화할 필드를 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"}할 수 있습니다.

## Marketo이 [!DNL Dynamics] 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

예. 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이 경우 Marketo은 개인의 활동 로그에 결과를 기록합니다.

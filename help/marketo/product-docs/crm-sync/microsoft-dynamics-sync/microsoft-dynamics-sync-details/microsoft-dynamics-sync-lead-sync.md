---
unique-page-id: 3571848
description: Microsoft Dynamics 동기화 - 리드 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 리드 동기화
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:리드 동기화 {#microsoft-dynamics-sync-lead-sync}

Marketing to Dynamics 동기화가 매우 강력합니다. 자세한 내용은 다음과 같습니다.

## 두 시스템 간에 세부 사항은 어떻게 동기화됩니까?{#how-are-details-kept-in-sync-between-the-two-systems}

동기화가 양방향 상태입니다. Dynamics의 리드 또는 Marketing의 사람을 변경하면 두 시스템 모두에 업데이트가 반영됩니다.

>[!NOTE]
>
>삭제는 두 방향 모두에서 자동으로 동기화되는 것은 아닙니다. [리드 또는 연락처](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/deleting-a-lead-or-contact.md)를 참조하십시오.

## 두 시스템에서 동시에 동일한 필드를 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드문 경우이지만 Marketing은 사람(리드)을 확보하고 Dynamics는 고객 접점에서 승리하게 됩니다. 이는 Adobe가 마케팅 부서가 사람들에게 권한을 부여한다고 생각하는 반면 담당자를 위한 공식 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketing To를 사용하여 Dynamics에서 리드를 만들 수 있습니까?{#can-i-create-a-lead-in-dynamics-using-marketo}

예, [Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 작업을 사용하십시오. 리드가 없는 경우 Dynamics에서 리드가 만들어집니다. 리드가 존재하는 경우 흐름 단계는 어떤 작업도 수행하지 않습니다.

>[!NOTE]
>
>&quot;Microsoft에 사람 동기화&quot; 흐름 작업을 사용하는 경우(트리거 캠페인에서만) 리드/연락처가 Dynamics에서 실시간으로 만들어집니다.

## Marketing에서 Dynamics의 리드로 사람의 동기화를 수동으로 강제 적용할 수 있습니까?{#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

아니요. 백그라운드 동기화 자동화는 Marketing To와 Dynamics 간에 업데이트를 동기화할 수 있는 유일한 방법입니다. [Microsoft](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 동작에서는 리드를 강제로 동기화하지 않습니다.

## Marketing To와 동기화할 필드는 무엇입니까?{#what-fields-will-sync-to-marketo}

설정 중에 [필드를 선택하여](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-3-of-3-connect.md#select-fields-to-sync)을 동기화할 수 있습니다.

## Marketing에서 Dynamics 유효성 검사 규칙을 준수합니까?{#will-marketo-respect-the-dynamics-validation-rules}

네. 데이터 형식이 잘못되었거나 필수 필드 정보가 없는 경우 동기화가 실패합니다. 이렇게 되면 Marketing Cloud는 개인의 활동 로그에 결과를 기록합니다.

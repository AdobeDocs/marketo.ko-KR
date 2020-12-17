---
unique-page-id: 3571833
description: Microsoft Dynamics 동기화 - 연락처 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 연락처 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:동기화 연락처 {#microsoft-dynamics-sync-contact-sync}

Marketing에서 전체 데이터베이스를 Dynamics와 동기화한다는 사실을 알고 계십니까? 5분을 기다린 다음 다시 동기화합니다. 하루 종일, 매일. 다음은 Marketing To가 Dynamics 연락처를 구체적으로 취급하는 방법에 대한 자세한 정보입니다.

## 두 시스템 간에 세부 사항은 어떻게 동기화됩니까?{#how-are-details-kept-in-sync-between-the-two-systems}

연락처 동기화는 양방향 동기화입니다. Dynamics 또는 Marketing To의 담당자를 변경하면 두 시스템 모두에 업데이트가 반영됩니다.

## 두 시스템에서 동시에 동일한 필드를 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

이러한 경우가 드물지만 Marketing To는 사람들을 위해 승리하고 Dynamics는 고객 접점에서 승리하게 됩니다. 이는 Adobe가 마케팅 부서가 사람들에게 권한을 부여한다고 생각하는 반면 담당자를 위한 공식 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketing To를 사용하여 연락처를 만들 수 있습니까?{#can-i-create-a-contact-using-marketo}

네. [방법](microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md) 보기

>[!NOTE]
>
>&quot;Microsoft에 사람 동기화&quot; 흐름 작업을 사용하는 경우(트리거 캠페인에서만) 리드/연락처가 Dynamics에서 실시간으로 만들어집니다.

## 수동으로 사람 또는 연락처를 강제 동기화할 수 있습니까?{#can-i-manually-force-a-sync-of-a-person-or-a-contact}

아니요. 백그라운드 동기화 자동화는 Marketing To와 Dynamics 간에 업데이트를 동기화할 수 있는 유일한 방법입니다. [Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md)에 사람 동기화를 수행하면 리드의 동기화가 강제되지 않습니다.

## Marketing To와 동기화할 필드는 무엇입니까?{#what-fields-will-sync-to-marketo}

설정 중에 [필드를 선택하여](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync)을 동기화할 수 있습니다. 그러나 Marketing Cloud는 Dynamics 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketing에서 Dynamics 유효성 검사 규칙을 준수합니까?{#will-marketo-respect-the-dynamics-validation-rules}

예. 충돌이 있는 경우 리드 활동 로그에 결과를 기록합니다.

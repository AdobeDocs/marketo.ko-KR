---
unique-page-id: 3571833
description: Microsoft Dynamics 동기화 -연락처 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 연락처 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:연락처 동기화 {#microsoft-dynamics-sync-contact-sync}

Marketing에서 전체 데이터베이스를 Dynamics와 동기화한다는 사실을 알고 계십니까? 동기화 후 5분을 기다린 다음 하루 종일 다시 동기화합니다. 다음은 Marketing To가 Dynamics 연락처를 구체적으로 처리하는 방법에 대한 자세한 정보입니다.

## 두 시스템 간의 세부 사항은 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

연락처 동기화는 양방향 동기화입니다. Dynamics 또는 Marketing To의 담당자를 변경하면 업데이트 내용이 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 동일한 필드를 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

드물지만 Marketing에서 인맥을 확보하고 Dynamics에서 인맥을 잇게 된다. 이는 Adobe가 마케팅 부서가 사람들에게 권위적이라고 간주하는 반면 연락처의 공식 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketing To를 사용하여 연락처를 만들 수 있습니까? {#can-i-create-a-contact-using-marketo}

네 [방법은 다음과 같습니다](microsoft-dynamics-sync-lead-sync/create-a-contact-in-microsoft-dynamics.md).

>[!NOTE]
>
>&quot;사람과 Microsoft 동기화&quot; 플로우 동작(트리거 캠페인에만 해당)을 사용하는 경우 리드/연락처가 Dynamics에서 실시간으로 생성됩니다.

## 수동으로 사람 또는 연락처를 강제 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-or-a-contact}

아니요. 자동화된 배경 동기화는 Marketing To와 Dynamics 간에 업데이트를 동기화할 수 있는 유일한 방법입니다. Microsoft [에](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 사람 동기화 기능은 리드를 강제로 동기화하지 않습니다.

## 어떤 필드가 Marketing To와 동기화됩니까? {#what-fields-will-sync-to-marketo}

설정하는 동안 동기화할 [필드를](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) 선택할 수 있습니다. 그러나 Marketing Cloud에서는 Dynamics 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketing이 Dynamics 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

예, 충돌이 있는 경우 리드 활동 로그에 결과를 기록합니다.

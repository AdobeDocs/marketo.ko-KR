---
unique-page-id: 3571848
description: Microsoft Dynamics 동기화 - 리드 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 리드 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:리드 동기화 {#microsoft-dynamics-sync-lead-sync}

Marketing to Dynamics 동기화가 매우 강력합니다. 자세한 내용은 다음과 같습니다.

## 두 시스템 간의 세부 사항은 어떻게 동기화됩니까? {#how-are-details-kept-in-sync-between-the-two-systems}

동기화는 양방향으로 이루어집니다. Dynamics의 리드 또는 Marketing To의 담당자를 변경하면 두 시스템 모두에 업데이트가 반영됩니다.

>[!NOTE]
>
>삭제도 양방향으로 자동으로 동기화되는 것은 아닙니다. 리드 [또는 연락처 삭제를 참조하십시오](http://docs.marketo.com/x/agO1Ag).

## 두 시스템에서 동시에 동일한 필드를 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

이러한 경우가 드물지만 Marketing은 사람(리드)에게 유리하며 Dynamics는 고객 접점에 유리합니다. 이는 Adobe가 마케팅 부서가 사람들에게 권위적이라고 간주하는 반면 연락처의 공식 기록 시스템은 판매(CRM) 부서에 있기 때문입니다.

## Marketing To를 사용하여 Dynamics에서 리드를 만들 수 있습니까? {#can-i-create-a-lead-in-dynamics-using-marketo}

예. 사람과 [Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 동기화 작업을 사용하십시오. 리드가 없는 경우 Dynamics에서 리드가 만들어집니다. 리드가 존재하는 경우 흐름 단계는 어떤 작업도 수행하지 않습니다.

>[!NOTE]
>
>&quot;사람과 Microsoft 동기화&quot; 플로우 동작(트리거 캠페인에만 해당)을 사용하는 경우 리드/연락처가 Dynamics에서 실시간으로 생성됩니다.

## Marketing에서 Dynamics의 리드로 사람의 동기화를 수동으로 강제 적용할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-from-marketo-to-a-lead-in-dynamics}

아니요. 자동화된 배경 동기화는 Marketing To와 Dynamics 간에 업데이트를 동기화할 수 있는 유일한 방법입니다. 사람과 [Microsoft](../../../../product-docs/core-marketo-concepts/smart-campaigns/microsoft-dynamics-flow-actions/sync-person-to-microsoft.md) 흐름 동기화 작업은 리드를 강제로 동기화하지 않습니다.

## 어떤 필드가 Marketing To와 동기화됩니까? {#what-fields-will-sync-to-marketo}

설정하는 동안 동기화할 [필드를](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) 선택할 수 있습니다.

## Marketing이 Dynamics 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-dynamics-validation-rules}

네 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이렇게 되면 Marketing은 개인의 활동 로그에 결과를 기록합니다.


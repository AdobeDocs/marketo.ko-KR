---
unique-page-id: 2953457
description: SFDC 동기화 - 연락처 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 연락처 동기화
exl-id: 537bbc95-9233-4454-892e-81f962cf729d
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---

# SFDC 동기화:동기화 연락처 {#sfdc-sync-contact-sync}

Marketo이 전체 데이터베이스를 Salesforce와 동기화한다는 사실을 알고 계십니까? 5분을 기다린 다음 다시 동기화합니다. 하루 종일, 매일. 다음은 Marketo에서 Salesforce 연락처를 취급하는 방법에 대한 자세한 정보입니다.

## 동기화 방향 {#sync-direction}

연락처 동기화는 양방향 동기화입니다. Salesforce 또는 Marketo에서 연락처를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경이 이루어지는 경우 어떻게 합니까?{#what-if-changes-are-made-in-both-systems-at-the-same-time}

Salesforce가 승리하게 하는 것이 좋습니다. 이런 종류의 데이터 충돌이 일어나는 것은 드문 일이다.

## Marketo에서 사람을 연락처로 전환할 수 있습니까?{#can-i-convert-a-person-into-a-contact-in-marketo}

예, **[사람 변환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)** 흐름 작업을 사용하십시오.

>[!CAUTION]
>
>Marketo에서 사람을 전환하면 Salesforce에 새로운 계정과 기회가 생깁니다. 중복 계정을 원치 않는 경우 Salesforce를 사용하여 변환합니다.

## 수동으로 연락처 동기화를 강제 적용할 수 있습니까?{#can-i-manually-force-a-sync-of-a-contact}

예. **[SFDC에 사람 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 흐름 작업을 사용하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketo과 동기화됩니까?{#does-every-single-standard-field-sync-to-marketo}

아니요, 일부 표준 필드가 유용하지는 않습니다. 모든 사용자 정의 필드는 동기화에 포함될 수 있습니다.

>[!NOTE]
>
>Marketo은 Marketo Sync 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo은 Salesforce 유효성 검사 규칙을 준수합니까?{#will-marketo-respect-the-salesforce-validation-rules}

예. 충돌이 있는 경우 리드 활동 로그에 결과를 기록합니다.

---
unique-page-id: 2953457
description: SFDC 동기화 - 연락처 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - Contact Sync
exl-id: 537bbc95-9233-4454-892e-81f962cf729d
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---

# SFDC 동기화: 동기화 문의 {#sfdc-sync-contact-sync}

Marketo이 전체 데이터베이스를 Salesforce와 동기화한다는 사실을 알고 계십니까? 동기화되고 5분을 기다린 다음 하루 종일 다시 동기화됩니다. 다음은 Marketo에서 Salesforce 연락처를 구체적으로 처리하는 방법에 대한 몇 가지 세부 정보입니다.

## 동기화 방향 {#sync-direction}

연락처 동기화는 양방향 동기화입니다. Salesforce 또는 Marketo에서 연락처를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경되는 경우 어떻게 합니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

우리는 훌륭하고 Salesforce가 이기도록 놔두었습니다. 이런 종류의 데이터 충돌이 일어나는 것은 드문 일이다.

## Marketo에서 사람을 연락처로 변환할 수 있습니까? {#can-i-convert-a-person-into-a-contact-in-marketo}

예, **[개인 변환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)** 흐름 작업.

>[!CAUTION]
>
>Marketo에서 사람을 전환하면 Salesforce에서 새 계정과 기회가 생깁니다. 중복 계정을 원하지 않는 경우 Salesforce를 사용하여 변환합니다.

## 수동으로 연락처 동기화를 수행할 수 있습니까? {#can-i-manually-force-a-sync-of-a-contact}

예, **[SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 흐름 작업을 수행하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketo과 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요, 모든 표준 필드가 유용하지는 않습니다. 모든 사용자 지정 필드는 동기화의 일부일 수 있습니다.

>[!NOTE]
>
>Marketo은 Marketo 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 Salesforce 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

예. 충돌이 발생하면 리드 활동 로그에 결과를 기록합니다.

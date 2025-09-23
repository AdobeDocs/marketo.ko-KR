---
unique-page-id: 2953457
description: SFDC 동기화 - 연락처 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 연락처 동기화
exl-id: 537bbc95-9233-4454-892e-81f962cf729d
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '229'
ht-degree: 1%

---

# SFDC 동기화: 연락처 동기화 {#sfdc-sync-contact-sync}

Marketo이 전체 데이터베이스를 [!DNL Salesforce]과(와) 동기화한다는 것을 알고 계십니까? 동기화한 후 5분을 기다린 후 다시 매일 하루 종일 동기화합니다. 다음은 Marketo에서 [!DNL Salesforce] 연락처를 구체적으로 처리하는 방법에 대한 세부 정보입니다.

## 동기화 방향 {#sync-direction}

연락처 동기화는 양방향입니다. [!DNL Salesforce] 또는 Marketo에서 연락처를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

## 두 시스템에서 동시에 변경되는 경우 어떻게 됩니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

[!DNL Salesforce]이(가) 이기도록 하겠습니다. 이런 종류의 데이터 충돌이 발생하는 경우는 거의 없습니다.

## Marketo에서 개인을 연락처로 전환할 수 있습니까? {#can-i-convert-a-person-into-a-contact-in-marketo}

예, **[사용자 전환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"}** 흐름 동작을 사용하세요.

>[!CAUTION]
>
>Marketo의 사용자를 전환하면 [!DNL Salesforce]에 새 계정과 기회가 생깁니다. 중복 계정을 사용하지 않으려면 [!DNL Salesforce]을(를) 사용하여 전환하십시오.

## 연락처를 수동으로 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-contact}

예, **[사용자와 SFDC 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}** 흐름 동작을 사용하면 실시간으로 동기화됩니다.

## 모든 단일 표준 필드가 Marketo에 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요. 모든 표준 필드가 유용한 것은 아닙니다. 모든 사용자 지정 필드는 동기화의 일부가 될 수 있습니다.

>[!NOTE]
>
>Marketo은 Marketo 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 [!DNL Salesforce] 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

예. 충돌이 발생하면 리드 활동 로그에 결과가 기록됩니다.

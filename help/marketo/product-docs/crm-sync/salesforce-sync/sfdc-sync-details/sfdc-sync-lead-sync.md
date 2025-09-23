---
unique-page-id: 2953455
description: SFDC 동기화 - 리드 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드 동기화
exl-id: cf38e091-7344-4b95-b9e1-77eda751c4a9
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '230'
ht-degree: 2%

---

# SFDC 동기화: 리드 동기화 {#sfdc-sync-lead-sync}

[!DNL Salesforce] 데이터베이스에서 Marketo 동기화를 알고 있습니까? 동기화한 후 5분 동안 기다렸다가 다시 동기화합니다. 하루 종일, 매일 다음은 Marketo에서 [!DNL Salesforce] 리드를 구체적으로 처리하는 방법에 대한 세부 정보입니다.

## 동기화 방향 {#sync-direction}

리드(개인) 및 연락처 동기화는 양방향입니다. [!DNL Salesforce] 또는 Marketo에서 레코드를 변경하면 업데이트가 두 시스템에 모두 반영됩니다.

## 두 시스템에서 동시에 변경되는 경우 어떻게 됩니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo이 우승했습니다. 이런 종류의 데이터 충돌이 발생하는 경우는 거의 없습니다.

## Marketo을 사용하여 [!DNL Salesforce]에서 잠재 고객을 만들 수 있습니까? {#can-i-create-a-lead-in-salesforce-using-marketo}

예, [사용자와 SFDC 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 액션을 사용하십시오. 잠재 고객이 없는 경우 [!DNL Salesforce]에 잠재 고객이 만들어집니다.

## Marketo의 사용자를 [!DNL Salesforce]의 리드에 수동으로 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

예, [사용자와 SFDC 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} 흐름 동작을 사용하면 실시간으로 동기화됩니다.

## 모든 단일 표준 필드가 Marketo에 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요. 모든 표준 필드가 유용한 것은 아닙니다. 모든 사용자 지정 필드는 동기화의 일부가 될 수 있습니다.

>[!NOTE]
>
>Marketo은 [!DNL Salesforce] 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 [!DNL Salesforce] 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

예. 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이런 경우 Marketo은 리드 활동 로그에 결과를 기록합니다.

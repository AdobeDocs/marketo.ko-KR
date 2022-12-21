---
unique-page-id: 2953455
description: SFDC 동기화 - 리드 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드 동기화
exl-id: cf38e091-7344-4b95-b9e1-77eda751c4a9
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# SFDC 동기화: 리드 동기화 {#sfdc-sync-lead-sync}

Salesforce 데이터베이스에서 Marketo 동기화 사실을 알고 계십니까? 동기화되고 5분을 기다린 다음 다시 동기화합니다. 하루 종일 매일 다음은 Marketo에서 Salesforce 리드를 구체적으로 처리하는 방법에 대한 몇 가지 세부 사항입니다.

## 동기화 방향 {#sync-direction}

리드(개인) 및 연락처 동기화는 양방향 동기화입니다. Salesforce 또는 Marketo에서 레코드를 변경하면 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경되는 경우 어떻게 합니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketo이 승리합니다. 이런 종류의 데이터 충돌이 일어나는 것은 드문 일이다.

## Marketo을 사용하여 Salesforce에서 리드를 만들 수 있습니까? {#can-i-create-a-lead-in-salesforce-using-marketo}

예, [SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업. 리드가 없는 경우 Salesforce에서 리드가 생성됩니다.

## Salesforce에서 Marketo에 있는 사람의 동기화를 리드에 수동으로 적용할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

예, [SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 수행하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketo과 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요, 모든 표준 필드가 유용하지는 않습니다. 모든 사용자 지정 필드는 동기화의 일부일 수 있습니다.

>[!NOTE]
>
>Marketo은 Salesforce 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketo이 Salesforce 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

예. 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이런 경우 Marketo은 리드 활동 로그에 결과를 기록합니다.

---
unique-page-id: 2953455
description: SFDC 동기화 - 리드 동기화 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 리드 동기화
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---


# SFDC 동기화:리드 동기화 {#sfdc-sync-lead-sync}

Salesforce 데이터베이스에서 Marketing To 동기화 사실을 알고 계십니까? 동기화 후 5분을 기다린 다음 다시 동기화합니다. 하루 종일 매일 다음은 Marketing To가 Salesforce 리드를 구체적으로 처리하는 방법에 대한 자세한 정보입니다.

## 동기화 방향 {#sync-direction}

리드(개인) 및 연락처 동기화는 양방향 동기화입니다. Salesforce 또는 Marketing에서 레코드를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경이 이루어지는 경우 어떻게 합니까?{#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketing Cloud의 이수 이런 종류의 데이터 충돌이 일어나는 것은 드문 일이다.

## Marketing To를 사용하여 Salesforce에서 리드를 만들 수 있습니까?{#can-i-create-a-lead-in-salesforce-using-marketo}

예, [SFDC에 사람 동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 사용하십시오. 리드가 없는 경우 Salesforce에서 리드가 생성됩니다.

## Marketing에서 수동으로 사람의 동기화를 Salesforce의 리드로 강제 적용할 수 있습니까?{#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

예. [SFDC에 사람 동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 사용하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketing To와 동기화됩니까?{#does-every-single-standard-field-sync-to-marketo}

아니요, 일부 표준 필드가 유용하지는 않습니다. 모든 사용자 정의 필드는 동기화에 포함될 수 있습니다.

>[!NOTE]
>
>Marketing은 Salesforce 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Marketing에서 Salesforce 유효성 검사 규칙을 준수합니까?{#will-marketo-respect-the-salesforce-validation-rules}

네. 데이터 형식이 잘못되었거나 필수 필드 정보가 없는 경우 동기화가 실패합니다. 이렇게 되면 리드 활동 로그에 결과를 기록합니다.

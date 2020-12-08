---
unique-page-id: 2953455
description: SFDC 동기화 - 리드 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 리드 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# SFDC 동기화:리드 동기화 {#sfdc-sync-lead-sync}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Salesforce 데이터베이스에서 Marketing To 동기화 알고 계십니까? 동기화 후 5분을 기다린 다음 다시 동기화합니다. 하루 종일 매일 다음은 Marketing to가 Salesforce의 리드를 구체적으로 처리하는 방법에 대한 자세한 정보입니다.

## 동기화 방향 {#sync-direction}

리드(개인) 및 연락처 동기화는 양방향 것입니다. Salesforce 또는 Marketing에서 기록을 변경하면 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경 사항이 발생하는 경우 어떻게 됩니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Marketing의 성공 사례 이런 종류의 데이터 충돌이 일어나는 것은 드물다.

## Marketing To를 사용하여 Salesforce에서 리드를 만들 수 있습니까? {#can-i-create-a-lead-in-salesforce-using-marketo}

예. SFDC에 사람 [동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름을 사용하십시오. 리드가 없는 경우 Salesforce에서 리드를 만듭니다.

## Marketing의 한 사람을 Salesforce의 리드로 수동으로 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-person-in-marketo-to-a-lead-in-salesforce}

예. SFDC에 [사람 동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름을 사용하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketing To와 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요, 모든 표준 필드가 유용하지는 않습니다. 모든 사용자 정의 필드는 동기화의 일부가 될 수 있습니다.

>[!NOTE]
>
>Marketing will only sync the fields that your Salesforce sync user has access to.

## Marketing이 Salesforce 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

네 데이터 형식이 잘못되었거나 필수 필드 정보가 누락된 경우 동기화가 실패합니다. 이렇게 되면 리드 활동 로그에 결과가 기록됩니다.

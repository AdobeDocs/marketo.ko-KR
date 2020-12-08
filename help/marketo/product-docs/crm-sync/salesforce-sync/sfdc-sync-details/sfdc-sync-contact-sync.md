---
unique-page-id: 2953457
description: SFDC 동기화 - 연락처 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 연락처 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '286'
ht-degree: 0%

---


# SFDC 동기화:연락처 동기화 {#sfdc-sync-contact-sync}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Marketing에서 전체 데이터베이스를 Salesforce와 동기화한다는 사실을 알고 계십니까? 동기화 후 5분을 기다린 다음 하루 종일 다시 동기화합니다. 다음은 Marketing to가 Salesforce 연락처를 취급하는 방법에 대한 자세한 정보입니다.

## 동기화 방향 {#sync-direction}

연락처 동기화는 양방향 동기화입니다. Salesforce 또는 Marketing Cloud에서 연락처를 변경하는 경우 업데이트가 두 시스템 모두에 반영됩니다.

## 두 시스템에서 동시에 변경 사항이 발생하는 경우 어떻게 됩니까? {#what-if-changes-are-made-in-both-systems-at-the-same-time}

Salesforce가 성공적으로 이런 종류의 데이터 충돌이 일어나는 것은 드물다.

## Marketing To에서 사람을 연락처로 전환할 수 있습니까? {#can-i-convert-a-person-into-a-contact-in-marketo}

예. ** 사람 [변환](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)** 흐름 동작을 사용하십시오.

>[!CAUTION]
>
>Marketing에서 사람을 전환하면 Salesforce에서 새로운 계정과 기회가 생깁니다. 중복 계정을 원치 않는 경우 Salesforce를 사용하여 전환하십시오.

## 수동으로 연락처를 강제 동기화할 수 있습니까? {#can-i-manually-force-a-sync-of-a-contact}

예. ** [Sync Person과 SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) **플로우 액션을 사용하면 실시간으로 동기화됩니다.

## 모든 표준 필드가 Marketing To와 동기화됩니까? {#does-every-single-standard-field-sync-to-marketo}

아니요, 모든 표준 필드가 유용하지는 않습니다. 모든 사용자 정의 필드는 동기화의 일부가 될 수 있습니다.

>[!NOTE]
>
>Marketing to Sync 사용자가 액세스할 수 있는 필드만 동기화됩니다.

## Marketing이 Salesforce 유효성 검사 규칙을 준수합니까? {#will-marketo-respect-the-salesforce-validation-rules}

예, 충돌이 있는 경우 리드 활동 로그에 결과를 기록합니다.

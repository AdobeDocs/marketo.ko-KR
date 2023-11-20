---
unique-page-id: 2953459
description: SFDC 동기화 - 계정 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 계정 동기화
exl-id: 94f7a9e5-86ea-4bb4-9d78-96a09c61321d
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '226'
ht-degree: 0%

---

# SFDC 동기화: 계정 동기화 {#sfdc-sync-account-sync}

Marketo Engage은 계정 정보를 Salesforce와 동기화합니다. 다음은 알아야 할 몇 가지 구체적인 사항입니다!

## 정보는 어느 방향으로 동기화됩니까? {#which-way-does-the-information-sync}

SFDC에서 Marketo으로의 유일한 방법입니다.

## 업데이트는 어떻게 작동합니까? {#how-do-the-updates-work}

Marketo의 연락처에 대한 계정 필드를 업데이트하면 Marketo의 해당 계정에 속하는 모든 연락처의 값이 변경됩니다. SFDC와 동기화되지 않습니다. 그러나 다음에 해당 계정이 SFDC에서 업데이트되면 변경 사항이 Marketo의 모든 계정 정보보다 우선 적용됩니다.

## 연락처가 여러 계정에 속할 수 있습니까?  {#can-a-contact-belong-to-multiple-accounts}

아니요. 계정에는 여러 연락처가 있을 수 있으며 연락처에는 하나의 계정만 있을 수 있습니다.

## Marketo에서 계정을 만들 수 있습니까? {#can-i-create-accounts-from-marketo}

대부분, 아니야 그러나 를 사용하는 경우 [사용자 전환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md){target="_blank"} 개인에 대한 플로우 단계를 수행하면 새 연락처, 새 계정 및 새 기회가 만들어집니다.

>[!CAUTION]
>
>이 플로우 단계는 사용 사례가 매우 제한적입니다. 확실하지 않다면 사용하지 말아야 할 것 같습니다.

## Salesforce에서 계정 필드를 변경하면 각 연락처에 대한 데이터 값 변경 활동 로그가 발생합니까?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

대부분, 네. 그러나 계정에 5,000명 이상의 연락처가 있고 해당 계정의 필드가 SFDC에서 변경되는 경우 변경 사항을 동기화하지만 5,000명 이상의 연락처에 대한 활동은 기록하지 않습니다.

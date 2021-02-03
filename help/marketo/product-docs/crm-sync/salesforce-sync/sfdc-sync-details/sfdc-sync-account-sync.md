---
unique-page-id: 2953459
description: SFDC 동기화 - 계정 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 계정 동기화
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---


# SFDC 동기화:계정 동기화 {#sfdc-sync-account-sync}

또한 Marketing Cloud는 계정 정보를 Salesforce와 동기화합니다. 여러분이 알아야 할 몇 가지 구체적인 것이 있습니다!

## 정보는 어떤 방식으로 동기화됩니까?{#which-way-does-the-information-sync}

한 가지 방법:SFDC에서 Marketing에 이르는 전 과정을

## 업데이트는 어떻게 작동합니까?{#how-do-the-updates-work}

Marketing에서 연락처에 대한 계정 필드를 업데이트하면 Marketing To에서 해당 계정에 속하는 모든 연락처의 값이 변경됩니다. SFDC와 동기화되지 않습니다. 하지만 다음에 SFDC에서 계정이 업데이트되면 변경 내용이 Marketing의 모든 계정 정보를 덮어씁니다.

## 담당자가 여러 계정에 속할 수 있습니까? {#can-a-contact-belong-to-multiple-accounts}

아니. 계정에는 여러 명의 연락처가 있을 수 있으며 연락처에는 하나의 계정만 있을 수 있습니다.

## Marketing To에서 계정을 만들 수 있습니까?{#can-i-create-accounts-from-marketo}

대부분 아닙니다. 그러나 한 사람에게 [사람 전환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) 흐름 단계를 사용하는 경우 새 연락처, 새 계정 및 새 기회가 만들어집니다.

>[!CAUTION]
>
>이 흐름 단계는 매우 제한된 사용 사례가 있습니다. 확실하지 않다면, 아마 사용하지 말아야 할 것이다.

## Salesforce의 계정 필드가 변경되면 각 연락처에 대한 데이터 값 변경 작업 로그가 생성됩니까? {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

대부분, 네. 하지만 계정에 5,000명이 넘는 연락처가 있고 SFDC에서 해당 계정에 대한 필드가 변경되면, 변경 사항은 동기화하지만 5,000명 이상의 연락처에 대한 작업은 기록하지 않습니다.

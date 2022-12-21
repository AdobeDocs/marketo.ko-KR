---
unique-page-id: 2953459
description: SFDC 동기화 - 계정 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 계정 동기화
exl-id: 94f7a9e5-86ea-4bb4-9d78-96a09c61321d
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 0%

---

# SFDC 동기화: 계정 동기화 {#sfdc-sync-account-sync}

또한 Marketo은 계정 정보를 Salesforce와 동기화합니다. 몇 가지 구체적인 사항을 알려드리겠습니다!

## 정보는 어떤 방식으로 동기화됩니까? {#which-way-does-the-information-sync}

한 가지 방법만: SFDC에서 Marketo으로

## 업데이트는 어떻게 작동합니까? {#how-do-the-updates-work}

Marketo에서 연락처에 대한 계정 필드를 업데이트하면 Marketo에서 해당 계정에 속하는 모든 연락처의 값이 변경됩니다. SFDC와 동기화되지 않습니다. 그러나 다음에 해당 계정이 SFDC에서 업데이트되면 변경 사항이 Marketo의 모든 계정 정보를 덮어씁니다.

## 연락처가 여러 계정에 속할 수 있습니까?  {#can-a-contact-belong-to-multiple-accounts}

아니요. Account에는 연락처가 여러 개 있을 수 있으며 연락처에는 하나의 계정만 있을 수 있습니다.

## Marketo에서 계정을 만들 수 있습니까? {#can-i-create-accounts-from-marketo}

대부분 아닙니다 그러나 [개인 변환](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) 한 개인에게 흐름 단계를 수행하면 새 연락처, 새 계정 및 새 Opportunity 가 생성됩니다.

>[!CAUTION]
>
>이 흐름 단계에는 매우 제한된 사용 사례가 있습니다. 잘 모르겠으면 사용하지 말아야 할 거예요

## Salesforce의 계정 필드를 변경하면 각 연락처에 대한 데이터 값 변경 활동 로그가 발생합니까?  {#does-a-change-in-an-account-field-in-salesforce-result-in-a-change-data-value-activity-log-for-each-contact}

대부분 그래 그러나 계정에 5,000명 이상의 연락처가 있고 SFDC에서 해당 계정의 필드가 변경되면 변경 사항을 동기화하지만 5,000명 이상의 연락처에 대한 활동은 기록하지 않습니다.

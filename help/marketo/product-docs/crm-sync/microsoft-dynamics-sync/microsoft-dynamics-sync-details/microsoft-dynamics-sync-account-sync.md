---
unique-page-id: 3571836
description: Microsoft Dynamics 동기화 - 계정 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 계정 동기화
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
source-git-commit: 17cacaa56a437a568bd0d2cc23020f3f880eaf52
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 0%

---

# Microsoft Dynamics 동기화: 계정 동기화 {#microsoft-dynamics-sync-account-sync}

Marketo이 전체 데이터베이스를 Dynamics와 동기화하는 것을 알고 있습니까? 동기화되고 5분을 기다린 다음 하루 종일 다시 동기화됩니다. 다음은 Marketo에서 Dynamics 계정을 특히 처리하는 방법에 대한 자세한 정보입니다.

## 정보는 어떤 방식으로 동기화됩니까? {#which-way-does-the-information-sync}

한 가지 방법만: Dynamics에서 Marketo으로 이동합니다.

## 업데이트는 어떻게 작동합니까? {#how-do-the-updates-work}

Marketo에서 연락처에 대한 계정 필드를 업데이트하면 Marketo에서 해당 계정에 속하는 모든 연락처의 값이 변경됩니다. Dynamics와 동기화되지 않습니다. 그러나 다음에 해당 계정이 Dynamics에서 업데이트되면 변경 사항이 Marketo의 모든 계정 정보를 덮어씁니다.

## Marketo을 사용하여 계정을 만들 수 있습니까? {#can-i-create-an-account-using-marketo}

아니요. Marketo은 Dynamics에서 계정을 만들 수 없습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#which-fields-will-sync-to-marketo}

다음을 수행할 수 있습니다 [동기화할 필드 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync) 설정하는 동안. 그러나 Marketo은 Dynamics 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Dynamics의 계정 필드를 변경하면 각 연락처에 대한 변경 데이터 값 활동 로그가 발생합니까?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

대부분 그래 하지만 계정에 5,000명 이상의 연락처가 있고 Dynamics에서 해당 계정에 대한 필드가 변경되면 변경 사항을 동기화하지만 5,000명 이상의 연락처에 대한 활동은 기록하지 않습니다.

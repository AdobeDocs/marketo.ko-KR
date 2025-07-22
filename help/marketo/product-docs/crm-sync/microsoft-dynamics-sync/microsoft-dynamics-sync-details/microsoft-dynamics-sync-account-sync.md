---
unique-page-id: 3571836
description: Microsoft Dynamics 동기화 - 계정 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 계정 동기화
exl-id: 86249d33-60dd-47e1-a7c8-3996c9444084
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '209'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화: 계정 동기화 {#microsoft-dynamics-sync-account-sync}

Marketo이 전체 데이터베이스를 [!DNL Dynamics]과(와) 동기화한다는 것을 알고 계십니까? 동기화한 후 5분을 기다린 후 다시 매일 하루 종일 동기화합니다. 다음은 Marketo에서 [!DNL Dynamics] 계정을 구체적으로 처리하는 방법에 대한 세부 정보입니다.

## 정보는 어느 방향으로 동기화됩니까? {#which-way-does-the-information-sync}

한 가지 방법: [!DNL Dynamics]에서 Marketo.

## 업데이트는 어떻게 작동합니까? {#how-do-the-updates-work}

Marketo의 연락처에 대한 계정 필드를 업데이트하면 Marketo의 해당 계정에 속하는 모든 연락처의 값이 변경됩니다. [!DNL Dynamics]과(와) 동기화되지 않습니다. 그러나 다음에 [!DNL Dynamics]에서 해당 계정이 업데이트되면 변경 사항이 Marketo의 모든 계정 정보를 재정의합니다.

## Marketo을 사용하여 계정을 만들 수 있습니까? {#can-i-create-an-account-using-marketo}

아니요. Marketo에서 [!DNL Dynamics]에 계정을 만들 수 없습니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#which-fields-will-sync-to-marketo}

설치하는 동안 [동기화할 필드를 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync)할 수 있습니다. 하지만 Marketo은 [!DNL Dynamics] 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## [!DNL Dynamics]의 계정 필드를 변경하면 각 연락처에 대한 변경 데이터 값 활동 로그가 생성됩니까?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

대부분, 네. 그러나 계정에 연락처가 5,000개가 넘고 해당 계정의 필드가 [!DNL Dynamics]에서 변경되는 경우 변경 내용을 동기화하지만 5,000개 이상의 연락처에 대한 활동은 기록하지 않습니다.

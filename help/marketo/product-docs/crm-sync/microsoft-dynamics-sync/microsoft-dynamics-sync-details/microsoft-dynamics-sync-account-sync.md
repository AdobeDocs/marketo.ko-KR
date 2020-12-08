---
unique-page-id: 3571836
description: Microsoft Dynamics 동기화 -계정 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 계정 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:계정 동기화 {#microsoft-dynamics-sync-account-sync}

Marketing에서 전체 데이터베이스를 Dynamics와 동기화한다는 사실을 알고 계십니까? 동기화 후 5분을 기다린 다음 하루 종일 다시 동기화합니다. 다음은 Marketing To가 Dynamics 계정을 어떻게 취급하는지에 대한 자세한 정보입니다.

## 정보는 어떤 방식으로 동기화됩니까? {#which-way-does-the-information-sync}

한 가지 방법:Dynamics에서 Marketing에 이르기까지 다양한 프로젝트를 진행할 수 있습니다.

## 업데이트는 어떻게 이루어집니까? {#how-do-the-updates-work}

Marketing에서 연락처에 대한 계정 필드를 업데이트하면 Marketing To에서 해당 계정에 속한 모든 연락처의 값이 변경됩니다. Dynamics와 동기화되지 않습니다. 그러나 다음 번에 Dynamics에서 해당 계정이 업데이트되면 변경 내용이 Marketing Cloud의 모든 계정 정보에 우선합니다.

## Marketing To를 사용하여 계정을 만들 수 있습니까? {#can-i-create-an-account-using-marketo}

아뇨 Dynamics에서 계정을 만들 수 없습니다.

## 어떤 필드가 Marketing To와 동기화됩니까? {#which-fields-will-sync-to-marketo}

설정하는 동안 동기화할 [필드를](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) 선택할 수 있습니다. 그러나 Marketing Cloud에서는 Dynamics 동기화 사용자가 액세스할 수 있는 필드만 동기화합니다.

## Dynamics의 계정 필드가 변경되면 각 연락처에 대한 데이터 값 작업 로그 변경 결과가 발생합니까?  {#does-a-change-in-an-account-field-in-dynamics-results-in-a-change-data-value-activity-log-for-each-contact}

대부분 그래 하지만 계정에 5,000개 이상의 연락처가 있고 Dynamics에서 해당 계정에 필드가 변경되면 변경 사항을 동기화하지만 5,000개 이상의 연락처에 대한 활동은 기록하지 않습니다.

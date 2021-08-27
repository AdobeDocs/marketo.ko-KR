---
unique-page-id: 2360370
description: 동기화 전에 프로그램 상태 및 Salesforce 캠페인 상태를 일치시키는 방법 - Marketo 문서 - 제품 설명서
title: 동기화 전에 프로그램 상태 및 Salesforce 캠페인 상태를 일치시키는 방법
exl-id: 623676ff-ce63-484f-8467-71127fa40fe0
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# 동기화 전에 프로그램 상태 및 Salesforce 캠페인 상태를 일치시키는 방법 {#how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync}

이 문서에서는 Marketo 프로그램 및 Salesforce 캠페인 동기화 전에 호환되지 않는 상태 오류를 수정하고 상태를 매핑하는 방법을 설명합니다.

## 오류 메시지를 받으면 어떻게 합니까? {#what-do-you-do-if-you-received-an-error-message}

리드가 포함된 기존 Salesforce 캠페인에 동기화하려고 하며 캠페인에 하나 이상의 호환되지 않는 상태가 포함되어 있으면 오류 메시지가 표시됩니다. Marketo 프로그램 및 Salesforce 캠페인 *은(는) 상태가 정확히 일치하지 않는 경우* 동기화를 수행하지 않습니다.

![](assets/image2015-7-22-9-3a23-3a29.png)

이 오류 메시지에서 다음을 선택할 수 있습니다.

1. 드롭다운 메뉴에서 동기화할 다른 캠페인을 선택하거나
1. 오류를 취소하고, 상태 오류를 수정하고, 오류가 복구되면 동기화를 시도할 수 있습니다. 상태 오류를 수정하려면 다음 중 하나를 수행합니다.

   * Salesforce에 로그인하고 호환되지 않는 캠페인 구성원 상태를 제거하거나 이름을 바꾸면 Marketo 프로그램과 연결된 채널 유형에 사용되는 Marketo 프로그램 상태에 매핑됩니다.
   * Marketo의 프로그램 상태 를 수정하여 보유한 Salesforce 캠페인 구성원 상태에 매핑합니다. Marketo 관리 기능입니다. 자세한 내용은 [프로그램 채널 만들기](/help/marketo/product-docs/administration/tags/create-a-program-channel.md)를 참조하십시오.

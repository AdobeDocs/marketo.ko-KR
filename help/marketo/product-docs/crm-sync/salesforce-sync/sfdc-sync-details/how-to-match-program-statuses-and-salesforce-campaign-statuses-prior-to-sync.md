---
unique-page-id: 2360370
description: 동기화 전 프로그램 상태와 Salesforce 캠페인 상태를 일치시키는 방법 - Marketo 문서 - 제품 설명서
title: 동기화하기 전에 프로그램 상태와 Salesforce 캠페인 상태를 일치시키는 방법
exl-id: 623676ff-ce63-484f-8467-71127fa40fe0
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---

# 동기화 전에 프로그램 상태와 [!DNL Salesforce] 캠페인 상태를 일치시키는 방법 {#how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync}

이 문서에서는 Marketo 프로그램 및 [!DNL Salesforce] Campaign 동기화 전에 호환되지 않는 상태 오류를 수정하고 상태를 매핑하는 방법에 대해 설명합니다.

## 오류 메시지가 표시되면 어떻게 합니까 {#what-do-you-do-if-you-received-an-error-message}

잠재 고객이 포함된 기존 [!DNL Salesforce] 캠페인에 동기화하려고 하는데 캠페인에 호환되지 않는 상태가 하나 이상 포함된 경우 오류 메시지가 표시됩니다. 상태가 정확히 일치하지 않으면 Marketo 프로그램과 [!DNL Salesforce] 캠페인 *이(가) 동기화되지* 않습니다.

![](assets/image2015-7-22-9-3a23-3a29.png)

이 오류 메시지에서 다음을 선택할 수 있습니다.

1. 드롭다운 메뉴에서 동기화할 다른 캠페인을 선택하거나
1. 취소하거나, 상태 오류를 수정하고, 오류가 복구되면 동기화를 시도할 수 있습니다. 상태 오류를 수정하려면 다음 중 하나를 수행합니다.

   * Salesforce에 로그인하고 호환되지 않는 캠페인 멤버 상태를 제거하거나 이름을 변경하여 Marketo 프로그램과 연결된 채널 유형에 사용되는 Marketo 프로그램 상태에 매핑합니다.
   * Marketo에서 프로그램 상태를 수정하여 현재 진행 중인 Salesforce 캠페인 멤버 상태에 매핑합니다. Marketo 관리 기능입니다. 자세한 내용은 [프로그램 채널 만들기](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}를 참조하세요.

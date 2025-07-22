---
unique-page-id: 4719316
description: 개인 계정 사용 - Marketo 문서 - 제품 설명서
title: 개인 계정 사용
exl-id: 3cc67ff2-f689-4dfb-8b67-2b5b8d389aaf
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# 개인 계정 사용 {#using-person-accounts}

조직의 필요에 맞게 Salesforce에서 개인 계정을 설정할 수 있습니다. Marketo Engage에서 개인 계정을 처리하는 방법은 다음과 같습니다.

>[!NOTE]
>
>기본 [!DNL Salesforce] 계정은 비즈니스 계정입니다. [!DNL Salesforce] 관리자는 개인 계정을 별도로 설정해야 합니다.

## 개인 계정이란 무엇입니까? {#what-is-a-person-account}

사용자 계정이 [!DNL Salesforce]의 계정 개체와 매우 유사합니다. 단, 개인 계정은 계정 필드와 연락처 필드 모두에 액세스할 수 있습니다.

## 개인 계정이 Marketo에 동기화되면 어떻게 됩니까? {#what-happens-when-a-person-account-is-synced-to-marketo}

개인 계정은 회사 및 개인으로 Marketo에 동기화됩니다.

>[!NOTE]
>
>개인 계정에 대한 사용자 정의 필드는 Marketo의 회사와 사용자 모두에게 복사됩니다.

## 비즈니스 계정과 개인 계정을 어떻게 구분합니까? {#how-do-i-differentiate-business-accounts-and-person-accounts}

스마트 목록의 &quot;개인 계정&quot; 필터를 사용하여 개인 계정을 표준 비즈니스 계정과 구분합니다.

## Marketo Sales Insight에 표시되는 내 개인 계정 정보는 어디에 있습니까? {#where-is-my-person-accounts-information-displayed-in-marketo-sales-insight}

개인 계정과 관련된 활동이 **[!UICONTROL Account]** 패널에 표시됩니다.

>[!NOTE]
>
>Marketo Sales Insight의 **[!UICONTROL Add to Marketo Campaign]** 및 **[!UICONTROL Send Email]** 옵션은 현재 개인 계정에 사용할 수 없습니다.

## 기회를 개인 계정에 연결하려면 어떻게 해야 합니까? {#how-do-i-associate-opportunities-to-a-person-account}

Marketo은 영업 기회를 연결할 사람을 결정하는 영업 기회 연락처 역할에 따라 다릅니다. Marketo의 적절한 사용자에게 기회를 연결하려면 각 사용자 계정에 대해 영업 기회 연락처 역할을 추가해야 합니다. 영업 기회 연락처 역할을 자동으로 추가하는 워크플로우를 설정하는 것이 좋습니다.

## 개인 계정에 대해 어떤 이메일 필드를 사용해야 합니까? {#which-email-field-should-i-use-for-person-accounts}

개인 계정에는 두 개의 이메일 필드가 있습니다. 양식의 **[!UICONTROL Email Address]** 필드(**[!UICONTROL Person Email Address]**&#x200B;이 아님)를 사용하여 Marketo의 중복 제거 및 기타 전자 메일 처리가 제대로 작동하는지 확인하십시오.

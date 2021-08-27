---
unique-page-id: 4719316
description: 개인 계정 사용 - Marketo 문서 - 제품 설명서
title: 개인 계정 사용
exl-id: 3cc67ff2-f689-4dfb-8b67-2b5b8d389aaf
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---

# 개인 계정 사용 {#using-person-accounts}

조직의 요구 사항에 맞게 Salesforce에서 개인 계정을 설정할 수 있습니다. Marketo이 개인 계정을 처리하는 방법은 다음과 같습니다.

>[!NOTE]
>
>기본 Salesforce 계정은 비즈니스 계정입니다. Salesforce 관리자는 개인 계정을 별도로 설정해야 합니다.

## 개인 계정이란 무엇입니까? {#what-is-a-person-account}

개인 계정은 Salesforce의 계정 개체와 매우 유사합니다. 그러나 개인 계정은 계정 필드와 연락처 필드 모두에 액세스할 수 있습니다.

## 개인 계정이 Marketo에 동기화되면 어떻게 됩니까? {#what-happens-when-a-person-account-is-synced-to-marketo}

개인 계정은 회사 및 개인으로서 Marketo에 동기화됩니다.

>[!NOTE]
>
>개인 계정에 대한 사용자 지정 필드는 Marketo의 회사와 개인 모두에 복사됩니다.

## 비즈니스 계정과 개인 계정을 어떻게 구분합니까? {#how-do-i-differentiate-business-accounts-and-person-accounts}

스마트 목록의 **개인 계정임** 필터를 사용하여 개인 계정을 표준 비즈니스 계정과 구분하십시오.

## Marketo Sales Insight에 표시되는 개인 계정 정보는 어디에 있습니까? {#where-is-my-person-accounts-information-displayed-in-marketo-sales-insight}

개인 계정과 관련된 활동은 **계정** 패널에 표시됩니다.

>[!NOTE]
>
>Marketo Sales Insight의 **Marketo Campaign에 추가** 및 **이메일 보내기** 옵션은 현재 개인 계정에 사용할 수 없습니다.

## 개인 계정에 기회를 연결하려면 어떻게 해야 합니까? {#how-do-i-associate-opportunities-to-a-person-account}

Marketo은 영업 기회를 연결할 사람을 결정하기 위해 영업 기회 담당자 역할에 따라 달라집니다. Marketo의 해당 사람에게 기회를 연결하려면 각 개인 계정에 대해 기회 담당자 역할을 추가해야 합니다. 영업 기회 연락처 역할을 자동으로 추가할 워크플로우를 설정하는 것이 좋습니다.

## 개인 계정에 사용할 이메일 필드는 무엇입니까? {#which-email-field-should-i-use-for-person-accounts}

개인 계정에 대한 두 개의 이메일 필드가 있습니다. 양식의 **이메일 주소** 필드(**개인 이메일 주소** 아님)를 사용하여 Marketo의 중복 제거 및 기타 이메일 처리가 제대로 작동하는지 확인하십시오.

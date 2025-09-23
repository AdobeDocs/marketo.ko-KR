---
unique-page-id: 2953467
description: SFDC 동기화 - 영업 기회 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 영업 기회 동기화
exl-id: f8acc528-c631-43f0-8899-2f3c6fdabe9e
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 1%

---

# SFDC 동기화: 기회 동기화 {#sfdc-sync-opportunity-sync}

## 두 시스템 간에 영업 기회 세부 정보가 어떻게 동기화됩니까? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

동기화는 [!DNL Salesforce]에서 Marketo으로 가는 한 가지 방법입니다. [!DNL Salesforce]의 영업 기회에 대한 업데이트가 Marketo에 동기화됩니다.

>[!NOTE]
>
>[에 대해 Marketo에 입력한  [!DNL Salesforce]](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)자격 증명은 데이터를 동기화하는 데 사용됩니다. 해당 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

## Opportunity Sync 를 시작할 수 있습니까? {#can-i-initiate-an-opportunity-sync}

안돼, 안돼. [!DNL Salesforce]의 모든 영업 기회에 대한 변경 사항은 자동으로 Marketo에 동기화됩니다.

## Marketo은 Opportunity Amount에서 두 개 이상의 통화를 지원합니까? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

아니요. Marketo은 하나의 통화만 지원합니다. 영업 기회 금액은 [!DNL Salesforce]에서 동기화되지만 통화는 Marketo 구독에서 [기본 통화](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription)가 됩니다.

## Marketo은 기회와 연락처를 어떻게 연결합니까? {#how-does-marketo-associate-opportunities-and-contacts}

Marketo은 [영업 기회 연락처 역할](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm){target="_blank"}을 사용하여 영업 기회와 연락처를 연결합니다. 할당된 연락처 역할이 없는 기회는 Marketo에 동기화되지만 누구에게도 속하지 않습니다. 예를 들어 영업 기회 보유 필터에 대한 자격이 부여되지 않습니다.

## 한 사람의 모든 기회를 어떻게 볼 수 있습니까? {#how-can-i-see-all-the-opportunities-of-a-person}

**[!UICONTROL Opportunity Info]**&#x200B;개인 세부 정보[ 페이지의 ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) 탭에서 기회 목록을 볼 수 있습니다.

## 영업 기회와 관련된 트리거/필터는 무엇입니까? {#what-are-the-triggers-filters-related-to-opportunity}

트리거:

* 영업 기회에 추가됨
* 영업 기회에서 제거됨
* 영업 기회가 업데이트되었습니다.

필터:

* 영업 기회 있음
* 영업 기회가 업데이트됨/영업 기회가 업데이트되지 않음
* 영업 기회에 추가됨/영업 기회에 추가되지 않음
* 영업 기회에서 제거됨/영업 기회에서 제거되지 않음
* 총 Opty 금액
* 옵션 수
* 총 Opty 예상 수익

>[!TIP]
>
>필터 및 트리거에 대한 제약 조건을 확인하십시오. 멋진 디테일이 많이 들어 있어요.
>
>[!DNL Salesforce]의 영업 기회 개체에 새 필드를 만들면 자동으로 제약 조건이 됩니다.

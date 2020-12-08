---
unique-page-id: 2953467
description: SFDC 동기화 - 기회 동기화 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 기회 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '312'
ht-degree: 0%

---


# SFDC 동기화:기회 동기화 {#sfdc-sync-opportunity-sync}

## 두 시스템 간에 기회 세부 정보가 어떻게 동기화됩니까? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

동기화 방법:Salesforce에서 Marketing Cloud에 통합 Salesforce의 기회 업데이트가 Marketing To에 동기화됩니다.

>[!NOTE]
>
>Salesforce용 [Marketing](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 에서 입력한 자격 증명은 데이터를 동기화하는 데 사용됩니다. 액세스 권한이 있는 데이터만 포함됩니다.

## 기회 동기화를 시작할 수 있습니까? {#can-i-initiate-an-opportunity-sync}

안돼, 안돼Salesforce의 모든 영업 기회에 대한 변경 사항은 Marketing To에 자동으로 동기화됩니다.

## Marketing To가 기회 금액 내에서 두 개 이상의 통화를 지원합니까? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

아니요. Marketing은 하나의 통화만 지원합니다. 기회 금액은 Salesforce에서 동기화되지만 Marketing To 구독의 [기본 통화가](https://docs.marketo.com/display/DOCS/Set+Default+Location+Settings+for+a+Subscription#SetDefaultLocationSettingsforaSubscription-SettheDefaultCurrencySettingsforaSubscription) 됩니다.

## Marketing To는 기회와 연락처를 어떻게 연관시키는가? {#how-does-marketo-associate-opportunities-and-contacts}

Marketing To는 기회 연락처 역할을 사용하여 [기회 및 담당자를 연결합니다](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm). 담당자 역할이 할당되지 않은 기회는 Marketing To와 동기화되지만 다른 사람에게 속하지 않습니다. 예를 들어, 이 사람은 [기회 있음] 필터의 자격을 갖추지 못합니다.

## 내가 어떻게 사람들의 모든 기회를 볼 수 있을까? {#how-can-i-see-all-the-opportunities-of-a-person}

[개인 세부 정보] 페이지의 [ **기회 정보** ] 탭에서 기회 목록을 [볼 수](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) 있습니다.

## 기회와 관련된 트리거/필터는 무엇입니까? {#what-are-the-triggers-filters-related-to-opportunity}

트리거:

* 기회에 추가
* 기회에서 제거됨
* 기회 업데이트

필터:

* 기회 있음
* 기회가 업데이트됨/업데이트되지 않음
* Opportunity에 추가됨/Not이 Opportunity에 추가됨
* Opportunity에서 제거됨/Not이 Opportunity에서 제거됨
* 총 수량
* 옵션 수
* 총 예상 매출

>[!TIP]
>
>필터 및 트리거에 대한 제한 사항을 확인합니다. 멋진 디테일이 많네요
>
>Salesforce의 기회 개체에 새로운 필드를 만들면 자동으로 제약이 됩니다.

세계 최고의 Salesforce 동기화!
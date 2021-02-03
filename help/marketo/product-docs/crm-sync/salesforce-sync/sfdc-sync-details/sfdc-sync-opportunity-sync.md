---
unique-page-id: 2953467
description: SFDC 동기화 - 기회 동기화 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 기회 동기화
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---


# SFDC 동기화:기회 동기화 {#sfdc-sync-opportunity-sync}

## 두 시스템 간에 기회 세부 정보가 어떻게 동기화됩니까?{#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

동기화 방법:Salesforce에서 Marketing에 통합 Salesforce의 기회에 대한 업데이트는 Marketing To와 동기화됩니다.

>[!NOTE]
>
>Salesforce용 Marketing에 입력한 [자격 증명은 데이터를 동기화하는 데 사용됩니다. ](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 자격 증명이 액세스할 수 있는 데이터만 포함됩니다.

## 기회 동기화를 시작할 수 있습니까?{#can-i-initiate-an-opportunity-sync}

안돼, 안돼.Salesforce의 모든 영업 기회에 대한 변경 사항은 Marketing To에 자동으로 동기화됩니다.

## Marketing To는 기회 금액에서 두 개 이상의 통화를 지원합니까?{#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

아니요. Marketing은 하나의 통화만 지원합니다. 기회 금액은 Salesforce에서 동기화되지만 Marketing To 구독의 통화가 [기본 통화](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription)입니다.

## Marketing To는 기회와 담당자를 어떻게 연관시키는가?{#how-does-marketo-associate-opportunities-and-contacts}

Marketing To는 [기회 연락처 역할](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm)을(를) 사용하여 기회 및 연락처를 연결합니다. 담당자 역할이 할당되지 않은 기회는 Marketing To와 동기화되지만 다른 사람에게 속하지 않습니다. 예를 들어 이 사람은 [기회 있음] 필터의 자격을 갖추지 못합니다.

## 사람의 모든 기회를 어떻게 볼 수 있습니까?{#how-can-i-see-all-the-opportunities-of-a-person}

[개인 세부 정보](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) 페이지의 **기회 정보** 탭에서 기회 목록을 볼 수 있습니다.

## 기회와 관련된 트리거/필터는 무엇입니까?{#what-are-the-triggers-filters-related-to-opportunity}

트리거:

* 기회에 추가
* 기회에서 제거됨
* 기회가 업데이트됨

필터:

* 기회 있음
* 기회가 업데이트됨/업데이트되지 않음
* Opportunity에 추가됨/Not이 Opportunity에 추가되었습니다.
* Opportunity에서 제거됨/Not이 Opportunity에서 제거되었습니다.
* 총 불투명도 금액
* 옵션 수
* 총 예상 매출액

>[!TIP]
>
>필터 및 트리거에 대한 제한 사항을 확인합니다. 그 안에 많은 멋진 세부 사항들이 있습니다.
>
>Salesforce의 기회 개체에 새 필드를 만들면 자동으로 제약조건이 됩니다!

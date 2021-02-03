---
unique-page-id: 2953463
description: SFDC 동기화 - 리드/계정 소유자 동기화 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 리드/계정 소유자 동기화
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# SFDC 동기화:리드/계정 소유자 동기화 {#sfdc-sync-lead-account-owner-sync}

기술적으로 Salesforce의 &quot;사용자&quot; 테이블을 동기화하지만 리드/계정 소유자 필드라고 합니다.

## 어떤 필드가 Marketing To와 동기화됩니까?{#which-fields-will-sync-to-marketo}

Marketing To에 동기화된 각 사용자에 대해 다음 소유자 필드도 동기화합니다.

* 영업 담당자 이름
* 영업 소유자 성
* 영업 소유자 제목
* 판매 소유자 전화 번호
* 판매 소유자 이메일 주소

각 연락처에 대해 위의 5개의 리드 소유자 필드와 다음 계정 소유자 필드를 동기화합니다.

* 계정 소유자 이름
* 계정 소유자 성
* 계정 소유자 이메일 주소

## Marketing To에서 리드 소유자를 변경할 수 있습니까?{#can-i-change-the-lead-owner-in-marketo}

물론이죠. [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md) 흐름 작업을 사용하십시오.

>[!NOTE]
>
>[개인 세부 정보 페이지 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)을 사용하여 소유자 정보를 변경할 수 없습니다.

## 이 데이터로 수행할 수 있는 작업은 무엇입니까?{#what-can-i-do-with-this-data}

이러한 데이터를 사용해야 하는 이유는 다음과 같습니다.

* 판매 소유자로부터 서명이 있는 개인화된 이메일 전송
* 마케팅 또는 효과를 분석할 때 특정 영업 담당자에게 필터링
* Marketing To의 할당(및 재할당) 규칙
* [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md), [사람을 SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 및 [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 흐름 작업에 사용합니다.

Marketing Cloud는 최적의 Salesforce 동기화를 보장합니다. 다른 누구도 그렇게 잘하지 못하잖아!

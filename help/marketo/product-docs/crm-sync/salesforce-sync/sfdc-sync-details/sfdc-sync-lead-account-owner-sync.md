---
unique-page-id: 2953463
description: SFDC 동기화 - 리드/계정 소유자 동기화 - Marketing Docs - 제품 설명서
title: SFDC 동기화 - 리드/계정 소유자 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---


# SFDC 동기화:리드/계정 소유자 동기화 {#sfdc-sync-lead-account-owner-sync}

기술적으로 Salesforce의 &quot;사용자&quot; 테이블을 동기화하지만 리드/계정 소유자 필드라고 합니다.

## 어떤 필드가 Marketing To와 동기화됩니까? {#which-fields-will-sync-to-marketo}

Marketing to에 동기화된 각각의 사용자에 대해서도 다음 소유자 필드도 동기화합니다.

* 영업 담당자 이름
* 영업 담당자 성
* 영업 소유자 제목
* 영업 담당자 전화 번호
* 영업 담당자 이메일 주소

각 연락처에 대해 위의 5개의 리드 소유자 필드와 다음 계정 소유자 필드를 동기화합니다.

* 계정 소유자 이름
* 계정 소유자 성
* 계정 소유자 이메일 주소

## Marketing To에서 리드 소유자를 변경할 수 있습니까? {#can-i-change-the-lead-owner-in-marketo}

물론이죠. 소유자 [변경](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md) 흐름 동작을 사용하십시오.

>[!NOTE]
>
>개인 세부 정보 페이지 [사용을 사용하여 소유자 정보를 변경할 수 없습니다](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

## 이 데이터를 사용하여 무엇을 할 수 있습니까? {#what-can-i-do-with-this-data}

이 데이터를 사용해야 하는 이유는 다음과 같습니다.

* 세일즈 담당자의 서명이 포함된 개인화된 이메일 전송
* 마케팅 또는 효과 분석을 위해 특정 영업 담당자를 필터링합니다.
* Marketing to의 할당(및 재할당) 규칙
* 소유자 [변경](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md), 사람을 SFDC로 [동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)및 작업 흐름 [만들기 작업](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 에서사용합니다

Marketing Cloud는 탁월한 Salesforce 동기화를 제공합니다. 아무도 그렇게 잘하지 않아!

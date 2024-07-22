---
unique-page-id: 2953463
description: SFDC 동기화 - 잠재 고객/계정 소유자 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 잠재 고객/계정 소유자 동기화
exl-id: b9effcc2-f426-4390-aef1-42f4e525b182
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---

# SFDC 동기화: 잠재 고객/계정 소유자 동기화 {#sfdc-sync-lead-account-owner-sync}

이는 Salesforce에서 &quot;사용자&quot; 테이블을 기술적으로 동기화하고 있지만 이를 리드/계정 소유자 필드라고 부릅니다.

## 어떤 필드가 Marketo Engage에 동기화됩니까? {#which-fields-will-sync-to-marketo-engage}

Marketo에 동기화된 각 사용자에 대해 다음 소유자 필드도 동기화합니다.

* 영업 담당자 이름
* 영업 담당자 성
* 판매 소유자 제목
* 영업 담당자 전화 번호
* 영업 담당자 이메일 주소

각 연락처에 대해 위의 5개 리드 소유자 필드와 이러한 계정 소유자 필드를 동기화합니다.

* 계정 소유자의 이름
* 계정 소유자 성
* 계정 소유자 이메일 주소

## Marketo에서 리드 소유자를 변경할 수 있습니까? {#can-i-change-the-lead-owner-in-marketo}

[소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"} 흐름 동작을 사용하세요.

>[!NOTE]
>
>[개인 세부 정보 페이지 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"}을 사용하여 소유자 정보를 변경할 수 없습니다.

## 이 데이터로 무엇을 할 수 있습니까? {#what-can-i-do-with-this-data}

이 데이터를 사용해야 하는 이유는 다음과 같습니다.

* 판매 소유자의 서명이 포함된 개인화된 이메일 보내기
* 마케팅 또는 효과 분석을 위해 특정 영업 담당자를 필터링합니다.
* Marketo의 할당(및 재할당) 규칙
* [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"}, [사용자를 SFDC에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} 및 [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} 흐름 작업에서 사용합니다.

Marketo에는 멋진 Salesforce 동기화가 있습니다. 아무도 그렇게 잘하지 않아!

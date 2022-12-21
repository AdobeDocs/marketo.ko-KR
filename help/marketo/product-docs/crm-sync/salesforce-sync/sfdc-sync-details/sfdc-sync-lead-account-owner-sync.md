---
unique-page-id: 2953463
description: SFDC 동기화 - 리드/계정 소유자 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드/계정 소유자 동기화
exl-id: b9effcc2-f426-4390-aef1-42f4e525b182
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# SFDC 동기화: 리드/계정 소유자 동기화 {#sfdc-sync-lead-account-owner-sync}

이들은 Salesforce에서 &quot;사용자&quot; 테이블을 기술적으로 동기화하지만 리드/계정 소유자 필드라고 합니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#which-fields-will-sync-to-marketo}

Marketo에 동기화된 각 사용자에 대해 다음 소유자 필드도 동기화합니다.

* 영업 담당자 이름
* 영업 소유자 성
* 영업 소유자 제목
* 영업 담당자 전화번호
* 영업 소유자 이메일 주소

각 연락처에 대해 위의 5개의 리드 소유자 필드와 이러한 계정 소유자 필드를 동기화합니다.

* 계정 소유자 이름
* 계정 소유자 성
* 계정 소유자 전자 메일 주소

## Marketo에서 리드 소유자를 변경할 수 있습니까? {#can-i-change-the-lead-owner-in-marketo}

물론이죠. [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md) 흐름 작업.

>[!NOTE]
>
>소유자 정보는 [개인 세부 정보 페이지 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

## 이 데이터로 무엇을 수행할 수 있습니까? {#what-can-i-do-with-this-data}

다음과 같은 많은 이유로 이 데이터를 사용합니다

* 영업 소유자로부터 서명을 받아 개인화된 이메일 전송
* 마케팅을 위해 또는 효과를 분석할 특정 영업 담당자에게 필터링
* Marketo의 지정(및 재지정) 규칙
* 에서 사용 [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md), [SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md), 및 [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 흐름 작업

Marketo에는 뛰어난 Salesforce 동기화가 있습니다. 아무도 그렇게 잘하지 않아!

---
unique-page-id: 2951259
description: 사용자 정의 필드 유형 용어집 - Marketo 문서 - 제품 설명서
title: 사용자 정의 필드 유형 용어집
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
feature: Field Management
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '594'
ht-degree: 2%

---

# 사용자 정의 필드 유형 용어집 {#custom-field-type-glossary}

Marketo에서 사용자 정의 필드를 만들 때 선택할 수 있는 유형 목록이 있습니다.

>[!PREREQUISITES]
>
>[Marketo에서 사용자 지정 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>필드 유형에 따라 필터/트리거 [연산자](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md)가 달라집니다.

>[!NOTE]
>
>대부분의 필드는 문자 수에서 최대치가 아니라 바이트 수만큼 최대치가 됩니다. 그 때문에 각 분야에 대한 명확한 문자 제한을 제공할 수 없습니다. 예외는 **문자열**&#x200B;이며, 최대 길이는 255자입니다.

## 부울 {#boolean}

**예제 이름:**&#x200B;은(는) 고객입니다. 사람들을 고객으로 태그 지정

**예제 값:** True(선택됨)/False(선택되지 않음)

**연산자**: 없음

## 통화 {#currency}

**예제 이름:** 예산 - 회사 예산에 대한 숫자 값을 저장합니다.

**예제 값:** 100

**연산자**: is, is not, between, greater than, less than, least, is empty, is not empty

## Date {#date}

**예제 이름:** 갱신 날짜 - 고객 갱신 날짜를 저장합니다.

**예제 값:** 8/19/14

**연산자**: is, is not, between, 과거, 과거, 미래, 미래, 이후, 시간대, 이후, 이전, 온 또는 후, on 또는 이전 은 비어 있지 않습니다.

## 날짜/시간 {#datetime}

**예제 이름:** 만든 날짜 - 개인을 만든 날짜와 시간을 저장합니다.

**예제 값:** 8/19/14 2:00

**연산자**: is, is not, between, 과거, 과거, 미래, 미래, 이후, 시간대, 이후, 이전, 온 또는 후, on 또는 이전 은 비어 있지 않습니다.

## 이메일 {#email}

**예제 이름:** 대체 전자 메일 - 사용자의 대체 전자 메일 주소를 유지합니다(기본 전자 메일 주소 필드와 같이 이 필드에 실제로 전자 메일을 보낼 수 없으며, 특수 필드임).

**예제 값:** <name@company.com>

**연산자**: is, not, start with, not starts with, contains, not contains, is empty, is not empty

## 부동 {#float}

**예제 이름:** 등급별 포인트 평균 - 개인의 등급별 포인트 평균이나 소수가 있는 다른 숫자 값을 유지합니다.

**예제 값:** 2.47

**연산자**: between, greater than, less than, at least, is empty, is not empty.

## 공식 {#formula}

**예제 이름:** 인사말 - [솔루션에서 이 특수 필드를 사용하여 성별에 따라 인사말](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md)을 확인하세요.

**예제 값:** 연결된 솔루션을 확인합니다.

## 정수 {#integer}

**예제 이름:** 직원 수 - 소수가 필요 없는 숫자 값을 저장합니다.

**예제 값:** 600

**연산자**: is, is not, between, greater than, less than, least, is empty, is not empty

## 비율 {#percent}

**예제 이름:** 구매 가능성 - 백분율 값 저장(CRM측에서 계산됨)

**예제 값:** 85%

**연산자**: is, is not, between, greater than, less than, least, is empty, is not empty

## 전화 {#phone}

**예제 이름:** 대체 전화 - 다른 사용자를 위해 추가 전화 번호를 저장합니다.

**예제 값:** 650-555-5555

**연산자**: is, not, start with, not starts with, contains, not contains, is empty, is not empty

## 점수 {#score}

**예제 이름:** 행동 점수/인구 통계 점수 - 여러 점수 필드를 만들어 다른 특성을 추적합니다.

**예제 값:** 14

**연산자**: is, is not, between, greater than, less than, least, is empty, is not empty

## 문자열 {#string}

**예제 이름:** 중간 이름 - 추가 텍스트 특성을 저장합니다.

**예제 값:** Rose

**연산자**: is, not, start with, not starts with, contains, not contains, is empty, is not empty

## 텍스트 영역 {#text-area}

**예제 이름:** 설명 - 여러 줄 텍스트 입력을 허용하도록 양식에 설명 필드를 추가합니다.

**예제 값:** 이 문서는 훌륭합니다!

**연산자**: is, not, start with, not starts with, contains, not contains, is empty, is not empty

## URL {#url}

**예제 이름:** 블로그 - 개인 블로그 url을 저장하는 필드를 만듭니다.

**예제 값:** &lt;www.myblog.com>

**연산자**: is, not, start with, not starts with, contains, not contains, is empty, is not empty

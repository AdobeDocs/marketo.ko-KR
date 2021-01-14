---
unique-page-id: 2951259
description: 사용자 지정 필드 유형 용어 - Marketing Docs - 제품 설명서
title: 사용자 지정 필드 유형 용어
translation-type: tm+mt
source-git-commit: f865630638e7c0fe6ac2a449e196a7de4fbfeea1
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 0%

---


# 사용자 지정 필드 유형 용어집 {#custom-field-type-glossary}

Marketing에서 사용자 정의 필드를 만들면 선택할 유형 목록이 있습니다.

>[!PREREQUISITES]
>
>[Marketing To에서 사용자 정의 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>필드 유형에 따라 [연산자](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md)가 다릅니다.

>[!NOTE]
>
>대부분의 필드는 문자 수에서의 최대값을 초과하지 않고 바이트 수에서만 최대값을 유지합니다. 따라서 각 필드에 대해 정확한 문자 제한을 제공할 수 없습니다. 예외는 **String**&#x200B;이며 255자로 구성됩니다.

## 부울 {#boolean}

**예 이름:** 고객임 - 고객을 고객으로 태깅합니다.

**예 값:** True(선택됨) / False(선택 취소됨)

**연산자**:없음

## 통화 {#currency}

**예 이름:** 예산 - 회사 예산에 대한 숫자 값을 저장합니다.

**예제 값:** 100

**연산자**:은(는) not, between, greged, less than, at most, is not empty입니다.

## 날짜 {#date}

**예 이름:** 갱신 날짜 - 고객 갱신 날짜 저장

**값 예:** 8/19/14

**연산자**:is, between, between, 과거, 미래의 다음, 시간 프레임, after, before, after, on 또는 after, on 또는 그 이전, 이 중 또는 그 이전, 은 비어 있지 않음

## Datetime {#datetime}

**예 이름:** 만든 날짜 - 인물을 만든 날짜와 시간을 저장합니다.

**값 예:** 8/19/14 2:00

**연산자**:is, between, between, 과거, 미래의 다음, 시간 프레임, after, before, after, on 또는 after, on 또는 그 이전, 이 중 또는 그 이전, 은 비어 있지 않음

## 이메일 {#email}

**예 이름:** 대체 이메일 - 사람들의 대체 이메일 주소를 유지합니다. (기본 이메일 주소 필드처럼 이 필드에 이메일을 실제로 보낼 수 없으며, 이 필드는 특별합니다.)

**값 예:** name@company.com

**연산자**:is not, starts with, not started with, not started with, contains, not contains, is empty가 아님

## {#float} 부동

**예 이름:** 등급 포인트 평균 - 개인의 등급 포인트 평균 또는 소수가 있는 기타 모든 숫자 값을 유지합니다.

**예제 값:** 2.47

**연산자**:better, 보다 큼, 적어도 보다 작음, 적어도 대부분은 비어 있음, 비어 있지 않음

## 공식 {#formula}

**예제 이름:** 분량 -  [솔루션에 있는 이 특수 필드를 사용하여 성에 따라 올바른 ](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) 분포를 얻습니다.

**값 예: 연결된 솔루션** 확인

## 정수 {#integer}

**예 이름:** 직원 수 - 소수가 필요하지 않은 숫자 값을 저장합니다.

**예제 값:** 600

**연산자**:은(는) not, between, greged, less than, at most, is not empty입니다.

## 퍼센트 {#percent}

**예 이름:** 구매 가능성 - 백분율 값 저장(CRM 측에서 계산됨)

**예제 값:** 85%

**연산자**:은(는) not, between, greged, less than, at most, is not empty입니다.

## 전화 {#phone}

**예 이름:** 대체 전화 - 사용자를 위한 추가 전화 번호 저장

**값 예:** 650-555-5555

**연산자**:is not, starts with, not started with, not started with, contains, not contains, is empty가 아님

## 점수 {#score}

**예 이름:** 행동 점수/인구 통계 점수 - 여러 다른 속성을 추적할 여러 점수 필드를 만듭니다.

**예 값:** 14

**연산자**:은(는) not, between, greged, less than, at most, is not empty입니다.

## 문자열 {#string}

**예 이름:** 중간 이름 - 추가 텍스트 속성 저장

**값 예:** 장미

**연산자**:is not, starts with, not started with, not started with, contains, not contains, is empty가 아님

## 텍스트 영역 {#text-area}

**예제 이름:** 주석 - 양식에 주석 필드를 추가하여 여러 줄의 텍스트 입력을 허용합니다.

**값 예:** 이 문서는 환상적입니다!

**연산자**:is not, starts with, not started with, not started with, contains, not contains, is empty가 아님

## URL {#url}

**예 이름:** 블로그 - 개인 블로그 URL을 저장할 필드 만들기

**값 예:** www.myblog.com

**연산자**:is not, starts with, not started with, not started with, contains, not contains, is empty가 아님

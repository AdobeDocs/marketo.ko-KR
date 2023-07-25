---
unique-page-id: 2951259
description: 사용자 정의 필드 유형 용어집 - Marketo 문서 - 제품 설명서
title: 사용자 정의 필드 유형 용어집
exl-id: 495d4deb-28f1-4044-98d3-27c20756fe73
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '583'
ht-degree: 2%

---

# 사용자 정의 필드 유형 용어집 {#custom-field-type-glossary}

Marketo에서 사용자 정의 필드를 만들 때 선택할 수 있는 유형 목록이 있습니다.

>[!PREREQUISITES]
>
>[Marketo에서 사용자 정의 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

>[!TIP]
>
>필드 유형에 따라 필터/트리거 [연산자](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/smart-list-filter-operators-glossary.md) 은(는) 달라집니다.

>[!NOTE]
>
>대부분의 필드는 문자 수에서 최대치가 아니라 바이트 수만큼 최대치가 됩니다. 그 때문에 각 분야에 대한 명확한 문자 제한을 제공할 수 없습니다. 예외는 다음과 같습니다 **문자열**: 최대 255자입니다.

## 부울 {#boolean}

**예제 이름:** 고객인 경우 - 직원을 고객으로 태그 지정

**값 예:** True(선택됨) / False(선택 취소됨)

**연산자**: 없음

## 통화 {#currency}

**예제 이름:** 예산 - 회사 예산에 대한 숫자 값 저장

**값 예:** 10

**연산자**: is, is not, between, greater than, less than, least, at the must, is empty, not empty

## 날짜 {#date}

**예제 이름:** 갱신 일자 - 고객 갱신 일자를 저장합니다.

**값 예:** 8/19/14

**연산자**: is, is not, between, 과거, 과거 이전, 미래, 미래 이후, 시간대, 이후, 이전, 이전 또는 이후, on 또는 이전 이 비어 있지 않습니다.

## 날짜/시간 {#datetime}

**예제 이름:** 생성 날짜 - 개인이 생성된 날짜와 시간을 저장합니다.

**값 예:** 8/19/14 2:00

**연산자**: is, is not, between, 과거, 과거 이전, 미래, 미래 이후, 시간대, 이후, 이전, 이전 또는 이후, on 또는 이전 이 비어 있지 않습니다.

## 이메일 {#email}

**예제 이름:** 대체 이메일 - 직원을 위한 대체 이메일 주소 보관(기본 이메일 주소 필드와 같이 이 필드에 특별한 이메일을 실제로 보낼 수 없음)

**값 예:** name@company.com

**연산자**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## 부동 {#float}

**예제 이름:** 등급 포인트 평균 - 개인의 등급 포인트 평균 또는 소수가 있는 다른 숫자 값을 유지합니다.

**값 예:** 2.47

**연산자**: between, greater than, less than, 최소한 , is empty, is not empty

## 공식 {#formula}

**예제 이름:** 인사말 - 의 이 특수 필드 사용 [적절한 인사말을 받을 수 있는 솔루션](/help/marketo/product-docs/administration/field-management/create-and-use-a-concatenated-string-formula-field.md) 성별에 따라

**값 예:** 연결된 솔루션 확인

## 정수 {#integer}

**예제 이름:** 직원 수 - 소수가 필요하지 않은 숫자 값을 저장합니다.

**값 예:** 600

**연산자**: is, is not, between, greater than, less than, least, at the must, is empty, not empty

## 백분율 {#percent}

**예제 이름:** 구매 가능성 - 백분율 값 저장(CRM측에서 계산됨)

**값 예:** 85%

**연산자**: is, is not, between, greater than, less than, least, at the must, is empty, not empty

## 전화 {#phone}

**예제 이름:** 대체 전화 - 직원을 위한 추가 전화 번호 저장

**예제 값:** 650-555-5555

**연산자**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## 스코어 {#score}

**예제 이름:** 행동 점수 / 인구 통계학적 점수 - 여러 점수 필드를 만들어 다양한 속성을 추적합니다.

**예제 값:** 14

**연산자**: is, is not, between, greater than, less than, least, at the must, is empty, not empty

## 문자열 {#string}

**예제 이름:** 가운데 이름 - 추가 텍스트 속성 저장

**예제 값:** 로즈

**연산자**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## 텍스트 영역 {#text-area}

**예제 이름:** 주석 - 여러 줄 텍스트 입력을 허용하도록 양식에 주석 필드를 추가합니다.

**예제 값:** 이 기사는 환상적이에요!

**연산자**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

## URL {#url}

**예제 이름:** 블로그 - 개인 블로그 URL을 저장하는 필드 만들기

**예제 값:** www.myblog.com

**연산자**: is, is not, starts with, not starts with, contains, not contains, is empty, is not empty

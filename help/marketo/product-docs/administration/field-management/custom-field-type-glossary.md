---
unique-page-id: 2951259
description: 사용자 지정 필드 유형 용어집 - Marketing Docs - 제품 설명서
title: 사용자 지정 필드 유형 용어집
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '657'
ht-degree: 0%

---


# 사용자 지정 필드 유형 용어집 {#custom-field-type-glossary}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Marketing에서 사용자 정의 필드를 만들면 선택할 유형 목록이 있습니다.

>[!PREREQUISITES]
>
>* [Marketing To에서 사용자 지정 필드 만들기](create-a-custom-field-in-marketo.md)

>



>[!TIP]
>
>필드 유형에 따라 필터/트리거 [연산자가](https://docs.marketo.com/display/public/DOCS/Smart+List+Filter+Operators+Glossary) 다릅니다.

>[!NOTE]
>
>대부분의 필드는 문자 수에서 최대 제한이 없지만 대신 바이트 크기로 제한이 없습니다. 따라서 각 필드에 대해 정확한 문자 제한을 제공할 수 없습니다. 단, **문자열**&#x200B;은 255자로 계산됩니다.

## 부울 {#boolean}

**예제 이름:** 고객입니까? - 고객을 고객으로 태깅합니다.

**값 예:** 참(선택)/False(선택 안 함)

**연산자**:없음

## 통화 {#currency}

**예제 이름:** 예산 - 회사 예산에 대한 숫자 값 저장

**값 예:** 100년

**연산자**:is, is not, between, greater than, leak than, at most, is empty 아님

## 날짜 {#date}

**예제 이름:** 갱신 날짜 - 고객 갱신 날짜 저장

**값 예:** 8/19/14

**연산자**:is not, between, between, 과거, 과거, 미래, 이후, 시간 프레임, 뒤, 앞, 뒤, 또는 그 전, 은 비어 있지 않음

## 날짜/시간 {#datetime}

**예제 이름:** 생성 일자 - 개인이 생성된 날짜와 시간을 저장합니다

**값 예:** 8/19/14 2:00

**연산자**:is not, between, between, 과거, 과거, 미래, 이후, 시간 프레임, 뒤, 앞, 뒤, 또는 그 전, 은 비어 있지 않음

## 이메일 {#email}

**예제 이름:** 대체 이메일 - 사람들의 대체 이메일 주소를 유지합니다. (기본 이메일 주소 필드처럼 이 필드에 이메일을 실제로 보낼 수는 없습니다. 즉, 특별한 이메일 주소임)

**값 예:** [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#335d525e5673505c5e43525d4a1d505c5e)

**연산자**:is, is not, starts with, not starts with, not started with, contains, not contains, is empty가 아님

## 부동 {#float}

**예제 이름:** 등급 포인트 평균 - 개인의 등급 포인트 평균 또는 소수가 있는 기타 숫자 값을 유지합니다.

**값 예:** 2.47

**연산자**:between, larger than, 적어도 than, at most, is empty는 비어 있지 않습니다.

## 공식 {#formula}

**예제 이름:** 영업 - [솔루션에 이 특수 필드를 사용하여 성별에 따라 적절한 인사말](create-and-use-a-concatenated-string-formula-field.md) 획득

**값 예:** 연결된 솔루션 확인

## 정수 {#integer}

**예제 이름:** 직원 수 - 소수가 필요하지 않은 숫자 값을 저장합니다.

**값 예:** 600년

**연산자**:is, is not, between, greater than, leak than, at most, is empty 아님

## 백분율 {#percent}

**예제 이름:** 구매 가능성 - 백분율 값 저장(CRM 측에서 계산됨)

**값 예:** 85%

**연산자**:is, is not, between, greater than, leak than, at most, is empty 아님

## 전화 {#phone}

**예제 이름:** 대체 전화 - 사용자를 위한 추가 전화 번호 저장

**값 예:** 650-555-5555

**연산자**:is, is not, starts with, not starts with, not started with, contains, not contains, is empty가 아님

## 점수 {#score}

**예제 이름:** 행동 점수/인구 통계 점수 - 다양한 속성을 추적할 수 있는 여러 점수 필드를 만듭니다.

**값 예:** 14

**연산자**:is, is not, between, greater than, leak than, at most, is empty 아님

## 문자열 {#string}

**예제 이름:** 가운데 이름 - 추가 텍스트 속성 저장

**값 예:** 로즈

**연산자**:is, is not, starts with, not starts with, not started with, contains, not contains, is empty가 아님

## 텍스트 영역 {#text-area}

**예제 이름:** 댓글 - 양식에 주석 필드를 추가하여 여러 줄의 텍스트 입력 가능

**값 예:** 이 기사는 정말 환상적이에요!

**연산자**:is, is not, starts with, not starts with, not started with, contains, not contains, is empty가 아님

## URL {#url}

**예제 이름:** 블로그 - 개인 블로그 URL을 저장할 필드 만들기

**값 예:** www.myblog.com

**연산자**:is, is not, starts with, not starts with, not started with, contains, not contains, is empty가 아님

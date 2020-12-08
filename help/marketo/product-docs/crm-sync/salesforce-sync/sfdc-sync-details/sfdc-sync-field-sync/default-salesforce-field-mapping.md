---
unique-page-id: 4719314
description: 기본 Salesforce 필드 매핑 - Marketing to Docs - 제품 설명서
title: 기본 Salesforce 필드 매핑
translation-type: tm+mt
source-git-commit: 1a29614ec938074902af201b2ffc11cfaa625f7a
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 0%

---


# 기본 Salesforce 필드 매핑 {#default-salesforce-field-mapping}

처음 Marketing to 계정을 Salesforce와 동기화하면 Marketing에서 내장된 Salesforce 필드와 Marketing To 필드 간에 이러한 연결을 자동으로 만듭니다. 또한 Marketing은 리드, 계정, 기회 및 연락처의 사용자 지정 필드를 동기화합니다.

## 리드 필드 {#lead-fields}

| SFDC 필드 | 마케팅 필드 |
|---|---|
| 연간 매출 | 연간 매출 |
| 구/군/시 | 구/군/시 |
| 회사 | 회사 이름 |
| 전환된 날짜 | SFDC 변환 날짜 |
| 국가 | 국가 |
| 만든 날짜 | SFDC 작성 날짜 |
| 설명 | 사람 메모 |
| 이메일 | 이메일 주소 |
| 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 구독 취소 |
| 업계 | 업계 |
| 변환됨 | SFDC가 변환됨 |
| 삭제됨 | SFDC 삭제 |
| 성 | 성 |
| 리드 소스 | 소스 |
| 리드 점수 | 점수 |
| 휴대폰 | 휴대폰 번호 |
| 직원 | 직원 수 |
| 전화 | 전화 번호 |
| 우편 번호 | 우편 번호 |
| 등급 | 등급 |
| 인사말 | 인사말 |
| 시/도 | 주 |
| 상태 | 상태 |
| 거리 | 주소 |
| 제목 | 직함 |
| 웹 사이트 | 웹 사이트 |

## 연락처 필드 {#contact-fields}

| SFDC 필드 | 마케팅 필드 |
|---|---|
| 생년월일 | 생년월일 |
| 만든 날짜 | SFDC 작성 날짜 |
| 연락처 설명 | 사람 메모 |
| 이메일 | 이메일 주소 |
| 비즈니스 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 구독 취소 |
| 삭제됨 | SFDC 삭제 |
| 성 | 성 |
| 리드 소스 | 소스 |
| 리드 점수 | 점수 |
| MailingCity | 구/군/시 |
| MailingCountry | 국가 |
| 우편 번호 | 우편 번호 |
| MailingState | 주 |
| MailingStreet | 주소 |
| 휴대폰 | 휴대폰 번호 |
| 회사 전화 | 전화 번호 |
| 인사말 | 인사말 |
| 제목 | 직함 |

## 계정 필드 {#account-fields}

| SFDC 필드 | 마케팅 필드 |
|---|---|
| 연간 매출 | 연간 매출 |
| 청구 구/군/시 | 청구 구/군/시 |
| 청구 국가 | 청구 국가 |
| 청구 우편 번호 | 청구 우편 번호 |
| 청구 시/도 | 청구 상태 |
| 청구 거리 | 청구 주소 |
| 계정 설명 | 회사 메모 |
| 업계 | 업계 |
| 삭제됨 | SFDC 삭제 |
| 계정 이름 | 회사 이름 |
| 직원 | 직원 수 |
| 계정 전화 | 기본 전화 |
| SIC 코드 | SIC 코드 |
| 계정 사이트 | 사이트 |
| 계정 유형 | SFDC 유형 |
| 웹 사이트 | 웹 사이트 |

## Marketing To의 Salesforce 관련 시스템 필드(읽기 전용) {#salesforce-related-system-fields-in-marketo-read-only}

이러한 필드는 Marketing To에서 만들어지지만 고객이 조정할 수 없습니다.

| 필드 | 설명 |
|---|---|
| SFDC ID | 18자 Salesforce ID |
| SFDC 유형 | 리드 또는 담당자. 비어 있는 경우 리드는 Marketing To에 있는 개인으로만 존재합니다 |
| SFDC 작성 날짜 | SFDC에서 만든 날짜(마켓에서 만든 날짜와 다를 수 있음) |
| SFDC가 삭제됨 | 이전에 SFDC에 있었지만 삭제되었으며 현재 Marketing에서만 살고 있습니다. |

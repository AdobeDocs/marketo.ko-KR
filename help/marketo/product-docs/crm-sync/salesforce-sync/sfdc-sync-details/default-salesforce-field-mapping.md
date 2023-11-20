---
unique-page-id: 4719314
description: 기본 Salesforce 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 Salesforce 필드 매핑
exl-id: d6639733-f85d-4f4c-ac41-5d2a68a9c6b2
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 43%

---

# 기본 Salesforce 필드 매핑 {#default-salesforce-field-mapping}

처음에 Marketo Engage 계정을 Salesforce와 동기화하면 Marketo에서 기본 제공 Salesforce와 Marketo 필드 간에 이러한 연결을 자동으로 만듭니다. Marketo은 리드, 계정, 기회 및 연락처에서 사용자 정의 필드도 동기화합니다.

## 리드 필드 {#lead-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 연간 수익 | 연간 수익 |
| 도시 | 도시 |
| 회사 | 회사 이름 |
| 전환된 날짜 | SFDC 변환일 |
| 국가 | 국가 |
| 만든 날짜 | SFDC 생성일 |
| 설명 | 개인 메모 |
| 이메일 | 이메일 주소 |
| 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 주소 삭제 |
| 산업 | 산업 |
| 전환됨 | SFDC 변환됨 |
| 삭제됨 | SFDC 삭제됨 |
| 성 | 성 |
| 잠재 고객 소스 | 소스 |
| 잠재 고객 점수 | 스코어 |
| 휴대폰 | 휴대폰 번호 |
| 직원 | 직원 수 |
| 전화 | 전화번호 |
| Zip/우편 번호 | 우편 번호 |
| 등급 | 등급 |
| 인사말 | 인사말 |
| 시/도 | 주 |
| 상태 | 상태 |
| 상세 주소 | 주소 |
| 제목 | 직위 |
| 웹 사이트 | 웹 사이트 |

## 연락처 필드 {#contact-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 생일 | 생년월일 |
| 만든 날짜 | SFDC 생성일 |
| 연락처 설명 | 개인 메모 |
| 이메일 | 이메일 주소 |
| 회사 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 주소 삭제 |
| 삭제됨 | SFDC 삭제됨 |
| 성 | 성 |
| 잠재 고객 소스 | 소스 |
| 잠재 고객 점수 | 스코어 |
| 메일링 시티 | 도시 |
| MailingCountry | 국가 |
| 메일링 우편 번호 | 우편 번호 |
| 메일링 상태 | 주 |
| 메일링 스트리트 | 주소 |
| 휴대폰 | 휴대폰 번호 |
| 회사 전화 | 전화번호 |
| 인사말 | 인사말 |
| 제목 | 직위 |

## 계정 필드 {#account-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 연간 수익 | 연간 수익 |
| 청구지 시 | 청구지 시 |
| 청구지 국가 | 청구지 국가 |
| 청구 Zip/우편 번호 | 청구지 우편번호 |
| 청구 시/도 | 청구지 주 |
| 청구지 | 청구지 주소 |
| 계정 설명 | 회사 메모 |
| 산업 | 산업 |
| 삭제됨 | SFDC 삭제됨 |
| 계정 이름 | 회사 이름 |
| 직원 | 직원 수 |
| 계정 전화 | 주요 전화 |
| SIC 코드 | SIC 코드 |
| 계정 사이트 | 사이트 |
| 계정 유형 | SFDC 유형 |
| 웹 사이트 | 웹 사이트 |

## Marketo의 Salesforce 관련 시스템 필드(읽기 전용) {#salesforce-related-system-fields-in-marketo-read-only}

이러한 필드는 Marketo에서 생성되지만 고객이 조정할 수 없습니다.

| 필드 | 설명 |
|---|---|
| SFDC Id | 18자 Salesforce ID |
| SFDC 유형 | 리드 또는 연락처. 비어 있는 경우 잠재 고객은 Marketo의 사용자로만 존재합니다 |
| SFDC 생성일 | SFDC에서 만든 날짜 (Marketo에서 만든 날짜와 다를 수 있음) |
| SFDC가 삭제됨 | SFDC에 있었으나 삭제되었습니다. 이제 Marketo에서만 생활합니다. |

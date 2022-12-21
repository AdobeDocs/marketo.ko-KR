---
unique-page-id: 4719314
description: 기본 Salesforce 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 Salesforce 필드 매핑
exl-id: d6639733-f85d-4f4c-ac41-5d2a68a9c6b2
source-git-commit: 7376804bda915d7ff25cdc50cb78a6686bd36882
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 40%

---

# 기본 Salesforce 필드 매핑 {#default-salesforce-field-mapping}

처음에 Marketo 계정을 Salesforce와 동기화하면 Marketo이 기본 제공 Salesforce 필드와 Marketo 필드 간에 이러한 연결을 자동으로 만듭니다. Marketo은 또한 리드, 계정, 기회 및 연락처에 사용자 지정 필드를 동기화합니다.

## 리드 필드 {#lead-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 연간 수익 | 연간 수익 |
| 시 | 시 |
| 회사 | 회사명 |
| 변환된 날짜 | SFDC 변환일 |
| 국가 | 국가 |
| 작성일 | SFDC 생성 날짜 |
| 설명 | 개인 정보 |
| 이메일 | 이메일 주소 |
| 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 주소 삭제 |
| 산업 | 산업 |
| 전환됨 | SFDC가 변환됨 |
| 삭제된 항목 | SFDC가 삭제됨 |
| 성 | 성 |
| 잠재 고객 소스 | 원문 |
| 잠재 고객 점수 | 스코어 |
| 휴대폰 | 휴대폰 번호 |
| 직원 | 직원 수 |
| 휴대폰 | 전화번호 |
| 우편 번호 | 우편 번호 |
| 등급 | 등급 |
| 인사말 | 인사말 |
| 시/도 | 주 |
| 상태 | 상태 |
| Street | 주소 |
| 제목 | 직위 |
| 웹 사이트 | 웹 사이트 |

## 연락처 필드 {#contact-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 생일 | 출생일 |
| 작성일 | SFDC 생성 날짜 |
| 연락처 설명 | 개인 정보 |
| 이메일 | 이메일 주소 |
| 비즈니스 팩스 | 팩스 번호 |
| 이름 | 이름 |
| 이메일 옵트아웃 | 주소 삭제 |
| 삭제된 항목 | SFDC가 삭제됨 |
| 성 | 성 |
| 잠재 고객 소스 | 원문 |
| 잠재 고객 점수 | 스코어 |
| 메일링 시티 | 시 |
| 메일링 컨트리 | 국가 |
| MailingPostalCode | 우편 번호 |
| 메일링 상태 | 주 |
| 메일링 스트리트 | 주소 |
| 휴대폰 | 휴대폰 번호 |
| 비즈니스 전화 | 전화번호 |
| 인사말 | 인사말 |
| 제목 | 직위 |

## 계정 필드 {#account-fields}

| SFDC 필드 | Marketo 필드 |
|---|---|
| 연간 수익 | 연간 수익 |
| 청구지 시 | 청구지 시 |
| 청구지 국가 | 청구지 국가 |
| 청구 우편 번호 | 청구지 우편번호 |
| 청구 주/도 | 청구지 주 |
| 청구 거리 | 청구지 주소 |
| 계정 설명 | 회사 노트 |
| 산업 | 산업 |
| 삭제된 항목 | SFDC가 삭제됨 |
| 계정 이름 | 회사명 |
| 직원 | 직원 수 |
| 계정 전화 | 메인 전화 |
| SIC 코드 | SIC 코드 |
| 계정 사이트 | 사이트 |
| 계정 유형 | SFDC 유형 |
| 웹 사이트 | 웹 사이트 |

## Marketo의 Salesforce 관련 시스템 필드(읽기 전용) {#salesforce-related-system-fields-in-marketo-read-only}

이러한 필드는 Marketo에서 만들어지지만 고객이 조정할 수 없습니다.

| 필드 | 설명 |
|---|---|
| SFDC Id | 18자 Salesforce Id |
| SFDC 유형 | 리드 또는 연락처. 비어 있는 경우, 리드는 Marketo에 개인으로만 존재합니다 |
| SFDC 생성 날짜 | SFDC에서 만든 날짜(Marketo에서 만든 날짜와 다를 수 있음) |
| SFDC가 삭제됨 | SFDC에 있었지만 삭제되었으며 현재 Marketo에서만 살고 있습니다 |

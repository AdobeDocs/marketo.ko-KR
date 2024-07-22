---
unique-page-id: 2951103
description: 릴리스 노트 - 2013년 2월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2013년 2월
exl-id: 9adfa676-09ea-497a-bcce-42300848b9d8
feature: Release Information
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# 릴리스 노트: 2013년 2월 {#release-notes-february}

2월 릴리스에는 많이 요청된 기능, Apple Safari 지원 및 기타 소규모 개선 사항이 포함되어 있습니다.

## Apple Safari에 대한 공식 지원 {#official-support-for-apple-safari}

Mac 및 Windows용 Apple Safari 최신 버전은 Marketo 리드 관리와 함께 사용할 수 있도록 완전히 지원됩니다. 참고: iOS의 Safari가 완전히 호환되지 않습니다.

## Webhooks 개선 사항 {#webhooks-enhancements}

Webhooks는 URL/페이로드의 토큰을 이스케이프 처리하도록 개선되었으며 타사 시스템(Spark SMB Edition에서는 사용할 수 없음)의 XML/JSON 응답을 구문 분석하여 Marketo 리드 필드를 업데이트할 수도 있습니다.

## 업데이트된 SOAP API 끝점 {#updated-soap-api-endpoint}

기본 SOAP API 끝점이 업데이트되어 관리 -> SOAP API에 표시됩니다. 이 새 끝점을 사용하도록 호출을 업데이트하십시오. 이전 끝점에 대한 API 호출은 더 이상 사용되지 않지만 계속 작동합니다. (Spark SMB Edition에서는 SOAP API를 사용할 수 없음)

## facebook 탭에 대한 모바일 지원 {#mobile-support-for-facebook-tabs}

Marketo에서 게시한 facebook 탭은 모바일 장치를 감지하고 랜딩 페이지로 라우팅합니다. 이렇게 하면 Facebook 탭이 지원되지 않는 모바일 장치(Spark, Standard, Select SMB Editions 및 Marketo Social Marketing에서 사용 가능)에서 사용자가 올바른 콘텐츠를 가져올 수 있습니다.

## 출시 예정: 여러 모델 지원 {#coming-soon-support-for-multiple-models}

향후 릴리스에서 커뮤니티의 RCA에 대한 아이디어#1 투표된 여러 수익 주기 모델을 지원할 수 있는 토대를 마련하고 있습니다. 이번 릴리스에서는 모델 및 단계 선택을 지원하기 위해 [스마트 목록 필터 및 흐름 단계의 선택 항목 추가](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/find-all-leads-in-a-revenue-cycle-model.md)를 비롯한 몇 가지 변경 사항이 표시됩니다. 또한 리드 매출 단계 및 리드 매출 주기 모델 필드를 스마트 목록 리드 그리드 탭에서 이동합니다.

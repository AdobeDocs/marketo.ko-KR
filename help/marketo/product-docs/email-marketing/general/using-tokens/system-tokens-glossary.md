---
unique-page-id: 1147344
description: 시스템 토큰 용어집 - Marketing Docs - 제품 설명서
title: 시스템 토큰 용어집
translation-type: tm+mt
source-git-commit: 1c4c4c62215550a09125f76fb76017348aba2bdf
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---


# 시스템 토큰 용어집 {#system-tokens-glossary}

개인 토큰 외에도, 몇 가지 멋진 시스템 토큰을 사용할 수 있습니다. 여기 있습니다.

>[!NOTE]
>
>계정 시간대 설정은 날짜 및 시간 토큰이 실행되는 시기에 영향을 줍니다.

## system.date {#system-date}

토큰은 다음과 같이 런타임 시 현재 날짜를 렌더링합니다. `{{system.date}}`**2013년 8월 8일**

**작동 방식:**

* [데이터 값](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 흐름 단계 변경
* [흥미로운 순간](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) 흐름 단계
* [작업 흐름](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 단계 만들기
* 이메일 또는 템플릿의 본문

## system.time {#system-time}

토큰은 다음과 같이 런타임에서 현재 시간을 렌더링합니다. `{{system.time}}`**오후 04:34 (GMT -0700)**

**작동 방식:**

* [데이터 값](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 흐름 단계 변경
* [흥미로운 순간](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) 흐름 단계
* [작업 흐름](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 단계 만들기
* 이메일 또는 템플릿의 본문

## system.dateTime {#system-datetime}

토큰은 다음과 같이 런타임 시 현재 날짜 및 시간을 렌더링합니다. `{{system.dateTime}}`**2013-08-08 16:36:13**

**작동 방식:**

* [데이터 값](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 흐름 단계 변경
* [흥미로운 순간](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) 흐름 단계
* [작업 흐름](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) 단계 만들기
* 이메일 또는 템플릿의 본문

## system.forwardToFriendLink {#system-forwardtofriendlink}

이 `{{system.forwardToFriendLink}}` 토큰을 사용하면 이메일에서 &#39;친구 링크 [로 보내기&#39;의 배치를 제어할 수 있습니다](../../../../product-docs/email-marketing/general/functions-in-the-editor/forward-to-a-friend-link-in-emails.md).

**작동 방식:**

* [이메일](add-a-system-token-as-a-link-in-an-email.md) 또는 템플릿의 링크로 시스템 토큰 추가

## system.unsubscribeLink {#system-unsubscribelink}

이 `{{system.unsubscribLink}}` 토큰을 사용하면 이메일 구독 취소 링크의 배치를 제어할 수 있습니다.

**작동 방식:**

* [이메일](add-a-system-token-as-a-link-in-an-email.md) 또는 템플릿의 링크로 시스템 토큰 추가

## system.viewAsWebpageLink {#system-viewaswebpagelink}

이 `{{system.viewAsWebpageLink}}` 토큰을 사용하면 이메일에서 웹 페이지로 보기 링크의 배치를 제어할 수 있습니다.

**사용 방법:**

* [이메일](add-a-system-token-as-a-link-in-an-email.md) 또는 템플릿의 링크로 시스템 토큰 추가

---
unique-page-id: 1147344
description: 시스템 토큰 용어집 - Marketo 문서 - 제품 설명서
title: 시스템 토큰 용어집
exl-id: 8a7694af-4edb-4b32-b408-19d2e7bd596e
feature: Tokens
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 2%

---

# 시스템 토큰 용어집 {#system-tokens-glossary}

사람 토큰 외에도 정말 멋진 시스템 토큰을 사용할 수 있습니다. 여기 있습니다.

>[!NOTE]
>
>계정 시간대 설정은 날짜 및 시간 토큰이 실행되는 시기에 영향을 줍니다.

## system.date {#system-date}

`{{system.date}}` 토큰은 런타임에 현재 날짜를 렌더링합니다. 예: **2013년 8월 08일**

**다음 위치에서 작동:**

* [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"} 흐름 단계
* [관심 있는 순간](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md){target="_blank"} 흐름 단계
* [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} 흐름 단계
* 이메일 또는 템플릿의 본문

## system.time {#system-time}

`{{system.time}}` 토큰은 런타임에 현재 시간을 렌더링합니다. 예: **04:34 오후(GMT -0700)**

**다음 위치에서 작동:**

* [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"} 흐름 단계
* [관심 있는 순간](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md){target="_blank"} 흐름 단계
* [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} 흐름 단계
* 이메일 또는 템플릿의 본문

## system.dateTime {#system-datetime}

`{{system.dateTime}}` 토큰은 다음과 같이 런타임에 현재 날짜 및 시간을 렌더링합니다. **2013-08-08 16:36:13**

**다음 위치에서 작동:**

* [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"} 흐름 단계
* [관심 있는 순간](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md){target="_blank"} 흐름 단계
* [작업 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md){target="_blank"} 흐름 단계
* 이메일 또는 템플릿의 본문

## system.forwardToFriendLink {#system-forwardtofriendlink}

`{{system.forwardToFriendLink}}` 토큰을 사용하면 [의 이메일](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/forward-to-a-friend-link-in-emails.md){target="_blank"}에 있는 &#39;친구 링크로 전달&#39;의 배치를 제어할 수 있습니다.

**다음 위치에서 작동:**

* [시스템 토큰을 전자 메일에 링크로 추가](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"} 또는 템플릿

## system.unsubscribeLink {#system-unsubscribelink}

`{{system.unsubscribeLink}}` 토큰을 사용하면 전자 메일의 구독 취소 링크 배치를 제어할 수 있습니다.

**다음 위치에서 작동:**

* [시스템 토큰을 전자 메일에 링크로 추가](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"} 또는 템플릿

## system.viewAsWebpageLink {#system-viewaswebpagelink}

`{{system.viewAsWebpageLink}}` 토큰을 사용하면 전자 메일의 웹 페이지로 보기 링크 배치를 제어할 수 있습니다.

**작업 대상:**

* [시스템 토큰을 전자 메일에 링크로 추가](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"} 또는 템플릿

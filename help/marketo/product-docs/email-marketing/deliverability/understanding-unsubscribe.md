---
unique-page-id: 7514918
description: 구독 취소 이해 - Marketo 문서 - 제품 설명서
title: 구독 취소 이해
exl-id: 30866dc0-cdac-4e73-8dbf-d4b509012269
feature: Deliverability
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '217'
ht-degree: 1%

---

# 구독 취소 이해 {#understanding-unsubscribe}

실제로 Marketo에는 몇 가지 유형의 기본 제공 구독 취소가 있습니다. 모두 이름과 마찬가지로 사용자 개체의 필드로 표시됩니다.

이러한 모든 필드는 Marketo 구독에 내장되어 있습니다. 모두 부울(확인란) 유형입니다. Forms 또는 [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 흐름 단계.

## 주소 삭제 {#unsubscribed}

표준 구독 취소 페이지에서 사용됩니다. 사용자가 이 상자를 선택하거나 이메일에서 구독 취소 링크를 클릭하는 경우, 더 이상 마케팅 이메일을 받지 않습니다. 그러나 그들은 받을 것이다 [운영 이메일](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

## 마케팅 중단 {#marketing-suspended}

이 필드는 사용자가 사람들을 일시적으로 구독 취소하도록 설정합니다. 수동으로 변경되거나 변경 데이터 값 흐름 단계가 활용되는 경우에만 이 상태를 달성할 수 있습니다.

## 이메일 일시 중단됨 {#email-suspended}

이 상태는 하드 바운스가 발생한 후 24시간 동안 사람이 메일을 보내지 못하게 합니다. 24시간 후에는 다시 우편 발송이 가능합니다.

>[!NOTE]
>
>일시 중단된 이메일은 24시간 기간이 끝난 후에도 계속 확인되므로 역사적으로 이와 같이 표시된 사용자를 참조할 수 있습니다. 해당 사용자가 우편 발송이 가능한지 확인하려면 이메일 일시 중단 시점 후 24시간을 계산하면 됩니다.

## 차단 목록에 추가된 {#blocklisted}

[경쟁사와 같은 사용자에게 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md). 받고 싶은 모든 사람 **아니요** 이메일—운영, 마케팅 등 아무것도 얻지 못해!

![](assets/image2015-5-18-12-3a6-3a40.png)

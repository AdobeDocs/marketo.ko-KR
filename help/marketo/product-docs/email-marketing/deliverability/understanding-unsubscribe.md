---
unique-page-id: 7514918
description: 구독 취소 이해 - Marketing Docs - 제품 설명서
title: 구독 취소 이해
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 0%

---


# 구독 취소 이해 {#understanding-unsubscribe}

실제로 Marketing Cloud에는 몇 가지 다양한 유형의 내장된 구독이 있습니다. 모두 사람 개체의 필드로 표시됩니다(이름).

>[!NOTE]
>
>Marketing은 Blacklist와 Whitelist와 같은 용어를 Adobe 제품의차단 목록에 추가하다 및 허용 목록에 추가하다로 바꾸는 중입니다. 이 업데이트 중에 UI 및 문서 스크린샷의 이전 용어와 설명서 텍스트의 새로운 용어가 표시될 수 있습니다. 혼동을 죄송합니다

이러한 모든 필드는 Marketing To 구독에 내장되어 있습니다. 모두 부울(확인란) 유형입니다. Forms 또는 데이터 값 [변경 흐름 단계에서 사용할](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 수 있습니다.

## 구독 취소 {#unsubscribed}

이는 표준 구독 취소 페이지에서 사용됩니다. 사용자가 이 상자를 확인하거나 이메일의 구독 취소 링크를 클릭하는 경우 더 이상 마케팅 이메일을 받지 않습니다. 그러나 [운영 이메일을 받게 됩니다](../../../product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

## 마케팅 일시 중단 {#marketing-suspended}

이 필드는 사용자가 일시적으로 가입을 해지할 때 설정합니다. 사용자는 수동으로 변경하거나 데이터 값 흐름 변경 단계를 활용하는 경우에만 이 상태를 달성할 수 있습니다.

## 일시 중단된 이메일 {#email-suspended}

이 상태는 하드 바운스가 발생한 후 24시간 동안 메일을 보내는 사람을 차단합니다. 24시간 후에, 그 사람은 다시 우편물 받을 수 있게 될 것입니다.

>[!NOTE]
>
>24시간이 지난 후에도 일시 중단된 이메일은 계속 확인되므로 이전에 이렇게 표시된 사람을 참조할 수 있습니다. 우편물인지 확인하려면 이메일 일시 중단 후 24시간을 계산하면 된다.

## 차단 목록에 추가된 {#blocklisted}

[경쟁](http://docs.marketo.com/x/uwOQ)업체와 같은 사용자에게 적합합니다. 이메일, 운영, 마케팅 등 **어떤 이메일도 받지** 않으려는 사람 그들은 아무것도 얻지 못해!

![](assets/image2015-5-18-12-3a6-3a40.png)


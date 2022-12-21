---
unique-page-id: 7514918
description: 가입 해지 이해 - Marketo 문서 - 제품 설명서
title: 가입 해지 이해
exl-id: 30866dc0-cdac-4e73-8dbf-d4b509012269
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 1%

---

# 가입 해지 이해 {#understanding-unsubscribe}

Marketo에는 실제로 여러 가지 유형의 내장된 구독 취소가 있습니다. 모두 개인 개체의 필드로 표시되며, 이름 과 같습니다.

>[!NOTE]
>
>Marketo은 블랙리스트 및 화이트리스트와 같은 용어를 Adobe 제품차단 목록에 추가하다의 및 허용 목록에 추가하다 게시로 변경하는 중입니다. 이 업데이트 중에 UI 및 설명서 스크린샷에 이전 용어가 표시되고 설명서 텍스트에 새 용어가 표시될 수 있습니다. 혼동을 사과드립니다

이러한 모든 필드는 Marketo 구독에 내장되어 있습니다. 모든 부울(확인란) 유형입니다. Forms 또는 [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 흐름 단계.

## 주소 삭제 {#unsubscribed}

표준 가입 해지 페이지에서 사용됩니다. 사람이 이 상자를 선택하거나 이메일에서 가입 해지 링크를 클릭하면 더 이상 마케팅 이메일을 받지 않습니다. 그러나 그들은 받을 것이다 [운영 이메일](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

## 마케팅 중단 {#marketing-suspended}

이 필드는 임시 가입 해지 시 사람을 배치하기 위해 사용자가 설정합니다. 사용자는 수동으로 변경하거나 데이터 값 흐름 변경 단계를 사용하는 경우에만 이 상태를 달성할 수 있습니다.

## 전자 메일 일시 중단 {#email-suspended}

이 상태는 하드 바운스가 발생한 후 24시간 동안 메일링을 차단합니다. 24시간 후에, 그 사람은 다시 우편 배달이 될 것입니다.

>[!NOTE]
>
>이메일 일시 중단은 24시간 기간이 끝난 후에도 계속 확인되므로 이전에 이메일 일시 중단으로 표시된 사람을 참조할 수 있습니다. 그 사람이 우편 배달되는지 확인하려면, 이메일 정지 후 24시간을 계산하면 된다.

## 차단 목록에 추가된 {#blocklisted}

[경쟁 업체 같은 사용자를 위해 이 기능을 사용합니다](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md). 원하는 사람 **아니요** 이메일—운영, 마케팅 등 그들은 아무것도 얻지 못한다!

![](assets/image2015-5-18-12-3a6-3a40.png)

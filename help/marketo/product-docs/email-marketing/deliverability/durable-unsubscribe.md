---
unique-page-id: 10094576
description: 내구성 구독 취소 - Marketo 문서 - 제품 설명서
title: 내구성 구독 취소
exl-id: e03a5a01-7395-45b3-8351-7931ec413236
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---

# 내구성 구독 취소 {#durable-unsubscribe}

Marketo은 &quot;내구성&quot;을 위해 구독 취소 기능의 동작을 개선했습니다. 마스터 이메일 상태를 추가했습니다. 이 상태는 개인 세부 사항 레코드에 표시되는 구독 취소 플래그와 별개입니다.

가입 해지 플래그가 false에서 true로 설정되어 있으면 마스터 이메일 상태가 업데이트되고, 변경 사항이 동일한 이메일 주소를 사용하는 다른 사람에게 전파됩니다. 한 사람이 제거 및 다시 생성되거나, 동일한 이메일 주소로 새 레코드가 만들어지는 경우 가입 해지 플래그가 설정됩니다 **not** 덮어씁니다.

>[!NOTE]
>
>영구 가입 해지는 전체 Marketo 데이터베이스의 모든 파티션에서 작동합니다.

## 가입 해지 플래그를 True에서 False로 업데이트(예: 개인 재가입)합니다 {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

한 사람이 다시 구독할 수 있는 방법에는 몇 가지가 있습니다.

Salesforce에서, **clear** 리드/연락처 레코드의 이메일 옵트아웃 필드. 이 옵션은 Marketo과 동기화됩니다.

![](assets/one.png)

Marketo에서, **clear** 개인 레코드의 정보 탭에 있는 가입 해지된 상자입니다.

![](assets/two.png)

실행 **데이터 값 변경** 하나 이상의 사용자에게 아래와 같이 플로우 단계를 수행합니다.

![](assets/three.png)

SOAP API를 통해 기존 사용자를 업데이트합니다.

## 새 사람 생성 {#creating-a-new-person}

새 사람이 만들어지면 Marketo에서 마스터 이메일 상태 테이블에 대해 확인합니다. 이전에 해당 사용자의 구독을 취소한 경우 구독을 취소할 레코드를 업데이트합니다.

## 이메일 주소 변경 {#changing-an-email-address}

개인의 이메일 주소를 가입 해지된 이메일 주소로 변경하면 해당 사용자는 가입 해지됩니다. 이 변경 사항은 Marketo 또는 Salesforce에서 발생할 수 있습니다.

가입 해지된 이메일 주소를 가입 이메일 주소로 변경하면 해당 사용자는 가입 상태가 됩니다.

## 재구독 {#re-subscribing}

가입을 해지하면 동일한 이메일 주소를 사용하는 모든 사람이 구독 취소되는 것과 마찬가지로 재가입도 동일한 이메일 주소를 사용하는 모든 사람에게 실제로 다시 구독하게 됩니다.

## 활동 로그 {#activity-log}

에 대한 데이터 값 변경 정의 _updateLeadEmailStatus_ 및 _resetLeadEmailStatus_ 에서 찾을 수 있습니다. [이 커뮤니티 문서](https://nation.marketo.com/t5/Knowledgebase/Durable-Unsubscribe-Activity-Log/ta-p/252688).

>[!MORELIKETHIS]
>
>[가입 해지 이해](/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md)

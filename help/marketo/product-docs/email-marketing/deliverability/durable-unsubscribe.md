---
unique-page-id: 10094576
description: 지속적인 구독 취소 - Marketing Docs - 제품 설명서
title: 지속적인 구독 취소
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---


# 지속적인 구독 취소 {#durable-unsubscribe}

Marketing has enhanced the behavior of the unsubscription functionality to make it &quot;durable.&quot; 개인 정보 기록에 표시되는 구독 취소 플래그 와는 별개의 마스터 이메일 상태가 추가되었습니다.

구독 취소 플래그가 false에서 true로 설정된 경우 마스터 이메일 상태가 업데이트되고 변경 내용이 동일한 이메일 주소를 사용하는 다른 사람에게 전파됩니다. 사용자가 제거되고 다시 만들어지거나, 동일한 이메일 주소로 새 레코드가 만들어지면, 구독 취소 플래그를 덮어쓰지 **않습니다** .

>[!NOTE]
>
>영구 가입 해지는 전체 Marketing To 데이터베이스의 모든 파티션에서 작동합니다.

## 가입 해지 플래그를 True에서 False로 업데이트(예: 사람 재가입) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

한 사람이 다시 구독할 수 있는 몇 가지 방법이 있다.

Salesforce에서 리드/연락처 레코드의 이메일 옵트아웃 필드를 **지웁니다** . Marketing To와 동기화됩니다.

![](assets/one.png)

Marketing에서 개인 레코드의 정보 탭에서 구독되지 않은 상자를 **지웁니다** .

![](assets/two.png)

하나 이상의 **사용자에 대해 아래와 같이 데이터 값** 변경 흐름 단계를 실행합니다.

![](assets/three.png)

SOAP API를 통해 기존 사람을 업데이트합니다.

## 새 사람 만들기 {#creating-a-new-person}

새 사람을 만들면 Marketing에서 마스터 이메일 상태 테이블에 대해 확인합니다. 이전에 구독이 해지된 경우 구독을 취소할 레코드를 업데이트합니다.

## 이메일 주소 변경 {#changing-an-email-address}

개인의 이메일 주소를 가입이 취소된 이메일 주소로 변경하면 해당 사람의 가입이 취소됩니다. 이러한 변경 사항은 Marketing To 또는 Salesforce에서 발생할 수 있습니다.

가입되지 않은 이메일 주소를 가입한 이메일 주소로 변경하면 해당 사람도 가입하게 됩니다.

## 재구독 {#re-subscribing}

구독을 취소하면 동일한 이메일 주소를 사용하는 모든 사용자가 구독을 취소하게 되므로 동일한 이메일 주소를 사용하는 모든 사용자가 다시 구독하게 됩니다.

## 활동 로그 {#activity-log}

updateLeadEmailStatus *및* resetLeadEmailStatus *에 대한 데이터 값 변경 정의는* 이 커뮤니티 아티클에서 찾을 수 [있습니다](http://nation.marketo.com/t5/Knowledgebase/Durable-Unsubscribe-Activity-Log/ta-p/252688).

>[!MORELIKETHIS]
>
>[구독 취소 이해](understanding-unsubscribe.md)


---
description: 스마트 캠페인에서 SMS 옵션 사용 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에서 SMS 옵션 사용
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: c3bad3c7d32259a9989227c1d6fa43bc693dd814
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# 스마트 캠페인에서 SMS 옵션 사용 {#using-sms-options-in-a-smart-campaign}

이후 [sms 메시지 만들기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message-2.md){target="_blank"}, 스마트 캠페인 내의 스마트 목록 트리거 및 필터를 사용하여 이점을 얻고자 합니다.

>[!NOTE]
>
>SMS 메시지를 보내려는 경우 [특정 문서](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md) 그러게요.

>[!PREREQUISITES]
>
>SMS 트리거/필터는 [Vibes 서비스가 활성화되었습니다.](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md).

## SMS 트리거 {#sms-triggers}

<table>
  <tr>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-1.png"></td>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-2.png"></td>
  </tr>
</table>

다음은 몇 가지 예입니다.

다음 **SMS 메시지 반송** 트리거는 SMS 메시지가 반송될 때 이메일 전송과 같은 흐름을 시작합니다.

다음 **비디오 구독 목록** 트리거는 사용자가 구독할 때 흐름을 시작합니다.

다음 **SMS 메시지의 링크 클릭** 트리거는 사용자가 SMS 메시지의 링크를 클릭하면 흐름을 시작합니다.

## SMS 필터 {#sms-filters}

<table>
  <tr>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-3.png"></td>
    <td><img src="assets/using-sms-options-in-a-smart-campaign-4.png"></td>
  </tr>
</table>

다음 **구독 중인 비디오 목록** 다음 권한이 있는 모든 사람을 찾습니다. *이제까지* 비디오 구독 중. 삭제된 사람이 흐름에서 생략되더라도 여기에는 구독 취소자와 삭제된 사람이 모두 포함됩니다. 이 필터는 보고에 가장 적합합니다.

그와 대조적으로 **바이브 목록 멤버** 필터 찾기 _모든 사용자_ 현재 Vibes를 구독하고 있으며 스마트 캠페인 또는 목록에서 사용하기에 가장 적합합니다.

>[!NOTE]
>
>모든 SMS 필터에는 **활동 날짜** 기본적으로 제약 조건.

## SMS 흐름 단계 {#sms-flow-steps}

선택할 수 있는 SMS 흐름 단계는 세 가지가 있습니다.

![](assets/using-sms-options-in-a-smart-campaign-5.png)

<table>
<tbody>
  <tr>
    <td style="width:25%">SMS 메시지 보내기</td>
    <td>이 흐름 작업은 Marketo Smart List에서 사용자 옵트인 Vibes 구독 목록을 구독하는 사람에게 메시지를 보냅니다. 가입 프로세스가 시작되지 않습니다. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md">자세히 알아보기</a>.</td>
  </tr>

<tr>
    <td style="width:25%">비디오 목록 구독</td>
    <td>이 흐름 작업은 사용자가 선택한 Vibes 획득 캠페인을 통해 SMS 구독 프로세스를 시작합니다. 그런 다음 Vibes가 확인 메시지를 보내며, 수신자는 옵트인을 확인하기 위해 24시간 이내에 "Y"로 회신해야 합니다. 사용자가 옵트인하면 연결된 Vibes 구독 목록의 구성원이 됩니다.</td>
  </tr>
  <tr>
    <td style="width:25%">비디오 목록에서 구독 취소</td>
    <td>이 플로우 작업은 옵트인 Vibes 구독 목록에서 각 사용자의 구독을 취소합니다. 사용자가 코드에 "STOP"을 입력하면 개인 레코드가 업데이트되어 더 이상 Vibes 구독 목록의 멤버가 아니라는 것을 반영합니다.</td>
  </tr>
  </tbody>
</table>

>[!NOTE]
>
>다음 **비디오 목록 구독** 및 **비디오 목록에서 구독 취소** 흐름에는 서로 다른 요구 사항이 있습니다. 대상 **구독**, Vibes 목록 및 Vibes 획득 캠페인을 선택해야 합니다. 대상 **구독 취소**, 바이브 목록만 필요합니다.

>[!MORELIKETHIS]
>
>* [SMS 메시지 보내기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md)
>* [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)

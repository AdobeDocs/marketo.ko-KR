---
description: 스마트 캠페인에서 SMS 옵션 사용 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에서 SMS 옵션 사용
feature: Mobile Marketing
exl-id: 199b7cae-86d2-42fe-8934-10aa780f4454
source-git-commit: dae00c6877e638ae60305122f3f3e17b3c922e10
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# 스마트 캠페인에서 SMS 옵션 사용 {#using-sms-options-in-a-smart-campaign}

[SMS 메시지를 만들고](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"} 나면 Smart Campaign 내의 Smart List 트리거 및 필터를 사용하여 혜택을 얻을 수 있습니다.

>[!NOTE]
>
>SMS 메시지를 보내려는 경우 [특정 문서](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md){target="_blank"}가 있습니다.

>[!PREREQUISITES]
>
>SMS 트리거/필터는 [Vibes 서비스를 사용하도록 설정한 경우](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md){target="_blank"}에만 나타납니다.

## SMS 트리거 {#sms-triggers}

<table style="width:600px">
  <tr>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-1.png"></td>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-2.png"></td>
  </tr>
</table>

다음은 몇 가지 예입니다.

**SMS 메시지 반송** 트리거는 SMS 메시지가 반송될 때 전자 메일 전송과 같은 흐름을 시작합니다.

**비디오 구독 목록** 트리거는 사용자가 구독할 때 흐름을 시작합니다.

**SMS 메시지의 링크를 클릭** 트리거는 사용자가 SMS 메시지의 링크를 클릭할 때 흐름을 시작합니다.

## SMS 필터 {#sms-filters}

<table style="width:600px">
  <tr>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-3.png"></td>
    <td style="width:50%"><img src="assets/using-sms-options-in-a-smart-campaign-4.png"></td>
  </tr>
</table>

**Vibes 목록 구독** 필터는 *ever*&#x200B;이(가) Vibes 구독 중인 모든 사용자를 찾습니다. 삭제된 사람이 흐름에서 생략되더라도 여기에는 구독 취소자와 삭제된 사람이 모두 포함됩니다. 이 필터는 보고에 가장 적합합니다.

반대로 **Vibes 목록 구성원** 필터는 현재 Vibes를 구독한 _모든 사용자_&#x200B;를 찾아 스마트 캠페인이나 목록에서 사용하기에 가장 적합합니다.

>[!NOTE]
>
>모든 SMS 필터에는 기본적으로 **활동 날짜** 제한이 포함됩니다.

## SMS 흐름 단계 {#sms-flow-steps}

선택할 수 있는 SMS 흐름 단계는 세 가지가 있습니다.

![](assets/using-sms-options-in-a-smart-campaign-5.png)

<table>
<tbody>
  <tr>
    <td style="width:20%"><b>SMS 메시지 보내기</b></td>
    <td>이 흐름 작업은 Marketo Smart List에서 사용자 옵트인 Vibes 구독 목록을 구독하는 사람에게 메시지를 보냅니다. 가입 프로세스가 시작되지 않습니다. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md">자세히 알아보기</a>.</td>
  </tr>

<tr>
    <td style="width:20%"><b>비디오 목록 구독</b></td>
    <td>이 흐름 작업은 사용자가 선택한 Vibes 획득 캠페인을 통해 SMS 구독 프로세스를 시작합니다. 그런 다음 Vibes가 확인 메시지를 보내며, 수신자는 옵트인을 확인하기 위해 24시간 이내에 "Y"로 회신해야 합니다. 사용자가 옵트인하면 연결된 Vibes 구독 목록의 구성원이 됩니다.</td>
  </tr>
  <tr>
    <td style="width:20%"><b>비디오 목록에서 구독 취소</b></td>
    <td>이 플로우 작업은 옵트인 Vibes 구독 목록에서 각 사용자의 구독을 취소합니다. 사용자가 코드에 "STOP"을 입력하면 개인 레코드가 업데이트되어 더 이상 Vibes 구독 목록의 멤버가 아니라는 것을 반영합니다.</td>
  </tr>
  </tbody>
</table>

>[!NOTE]
>
>**Vibes 목록 구독** 및 **Vibes 목록 구독 취소** 흐름의 요구 사항이 다릅니다. **구독**&#x200B;의 경우 Vibes 목록 및 Vibes 획득 캠페인을 선택해야 합니다. **구독 취소**&#x200B;의 경우 보기 목록만 필요합니다.

>[!MORELIKETHIS]
>
>* [SMS 메시지 보내기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md){target="_blank"}
>* [스마트 캠페인용 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}
>* [스마트 캠페인용 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md){target="_blank"}

---
description: SMS에 대한 흐름 단계 추가 - Marketo 문서 - 제품 설명서
title: SMS에 대한 흐름 단계 추가
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: cd09ad43c08855af63131aa385c4fd406c963926
workflow-type: tm+mt
source-wordcount: '373'
ht-degree: 0%

---

# SMS에 대한 흐름 단계 추가 {#add-a-flow-step-for-sms}

Marketo Engage에는 SMS 스마트 캠페인에서 사용할 수 있는 세 가지 흐름 단계가 있습니다.

* **SMS 메시지 보내기** - 이 흐름 작업은 Marketo Smart List에서 사용자 옵트인 Vibes 구독 목록을 구독하는 사람에게 메시지를 보냅니다. 가입 프로세스가 시작되지 않습니다.
* **비디오 목록 구독** - 이 흐름 작업은 사용자가 선택한 Vibes 획득 캠페인을 통해 SMS 구독 프로세스를 시작합니다. 그런 다음 Vibes가 확인 메시지를 보냅니다. 수신자는 24시간 내에 옵트인을 확인하려면 &quot;Y&quot;라고 답장해야 합니다. 사용자가 옵트인하면 연결된 Vibes 구독 목록의 구성원이 됩니다.
* **비디오 목록에서 구독 취소** - 이 흐름 작업은 옵트인 Vibes 구독 목록에서 각 사용자의 구독을 취소합니다. 사용자가 코드에 대해 &quot;중지&quot;를 입력하면 개인 레코드가 업데이트되어 더 이상 Vibes 구독 목록의 구성원이 아님을 반영합니다.

>[!NOTE]
>
>SMS 메시지를 보낼 때:
>
>* Marketo은 전화 번호로 중복 제거됩니다. 따라서 여러 사람이 동일한 전화 번호를 사용하는 경우 한 사람만 Vibes 구독 목록에 가입되어 있는 경우 메시지를 받게 됩니다. 데이터 중복 제거는 Marketo 프로그램 수준이 아닌 Vibes 구독 목록 수준에서 수행됩니다.
>* Marketo은 차단 목록에 추가된 또는 마케팅 중단 대상자에게 보내지 않습니다.

플로우 단계 설정에 대한 일반적인 내용은 [스마트 캠페인에 플로우 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

SMS 사용에 대한 기본 사항은 다음과 같습니다.

1. 내 Marketo에서 **마케팅 활동**.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. SMS 흐름을 추가할 Smart Campaign을 찾아 선택합니다.

   스크린샷

1. 스마트 목록 탭에서 원하는 트리거(예: &quot;작성된 양식&quot;)를 선택합니다.

   스크린샷

1. 다음에서 **플로우** 탭을 흐름 단계 위로 드래그합니다(예: **SMS 메시지 보내기**). 드롭다운에서 SMS 메시지 및 바이브 목록을 선택합니다.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >Vibes 목록 선택기는 Smart List에서 이미 식별된 대상에 대한 추가 필터 역할을 하여 해당 Vibes 목록에 속하는 리드만 타겟팅합니다.
   >
   >다음 **비디오 목록 구독** 및 **비디오 목록에서 구독 취소** 흐름에는 서로 다른 요구 사항이 있습니다. 대상 **구독**, Vibes 목록 및 Vibes 획득 캠페인을 선택해야 합니다. 대상 **구독 취소**, 바이브 목록만 필요합니다.

---
description: SMS 메시지 보내기 - Marketo 문서 - 제품 설명서
title: SMS 메시지 보내기
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 6731d6fca4b6547f1f709e45f32f766e0e0e30b4
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 0%

---

# SMS 메시지 보내기 {#send-a-vibes-sms-message}

다음을 수행함: [이(가) 내 SMS 메시지를 만들었습니다.](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message-2.md), 이제 전송할 때입니다. 일괄 처리 또는 트리거 캠페인을 통해 전송할 수 있습니다.

>[!NOTE]
>
>SMS 메시지를 보낼 때:
>
>* Marketo Engage이 전화 번호별로 중복 제거됩니다. 따라서 여러 사람이 동일한 전화 번호를 사용하는 경우 한 사람만 Vibes 구독 목록에 가입되어 있는 경우 메시지를 받게 됩니다. 데이터 중복 제거는 Marketo 프로그램 수준이 아닌 Vibes 구독 목록 수준에서 수행됩니다.
>* Marketo은 차단 목록에 추가된 또는 마케팅 중단 대상자에게 보내지 않습니다.
>* Vibes 모바일 데이터베이스 목록에 없는 경우 구독을 취소한 사용자에게는 SMS 메시지가 전송되지 않습니다.

## 일괄 SMS 보내기 {#send-a-batch-sms}

1. 내 Marketo에서 **마케팅 활동**.

   ![](assets/send-an-sms-message-1.png)

1. 원하는 스마트 캠페인을 찾아 선택합니다.

   ![](assets/send-an-sms-message-2.png)

1. 다음을 클릭합니다. **스마트 목록** sms에 대한 대상자를 탭하고 정의합니다. 이 예에서는 &quot;Adobe&quot;가 회사로 나열된 데이터베이스의 모든 사용자에게 를 보냅니다.

   ![](assets/send-an-sms-message-3.png)

1. 다음에서 **플로우** 탭, 위로 드래그 **SMS 메시지 보내기**. 드롭다운에서 원하는 SMS 메시지 및 보기 목록을 선택합니다.

   ![](assets/send-an-sms-message-4.png)

   >[!NOTE]
   >
   >Vibes 목록 선택기는 Smart List에서 이미 식별된 대상자에 대한 추가 필터 역할을 하여 해당 Vibes 목록에 속하는 사람만 타겟팅합니다.

1. 다음을 클릭합니다. **예약** SMS를 탭하고 예약합니다.

   ![](assets/send-an-sms-message-5.png)

## 트리거 SMS 보내기 {#send-a-trigger-sms}

1. 내 Marketo에서 **마케팅 활동**.

   ![](assets/send-an-sms-message-6.png)

1. 원하는 스마트 캠페인을 찾아 선택합니다.

   ![](assets/send-an-sms-message-7.png)

1. 다음을 클릭합니다. **스마트 목록** 탭에서 원하는 트리거를 선택하고 해당 값을 정의합니다. 이 예제에서는 **양식 작성**.

   ![](assets/send-an-sms-message-8.png)

1. 다음에서 **플로우** 탭, 위로 드래그 **SMS 메시지 보내기**. 드롭다운에서 원하는 SMS 메시지 및 보기 목록을 선택합니다.

   ![](assets/send-an-sms-message-9.png)

   >[!NOTE]
   >
   >Vibes 목록 선택기는 Smart List에서 이미 식별된 대상자에 대한 추가 필터 역할을 하여 해당 Vibes 목록에 속하는 사람만 타겟팅합니다.

1. 다음을 클릭합니다. **예약** 탭을 선택한 다음 **활성화**.

   ![](assets/send-an-sms-message-10.png)

>[!MORELIKETHIS]
>
>* [비디오 메시지 만들기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-a-vibes-sms-message.md)
>* Vibes 흐름 단계


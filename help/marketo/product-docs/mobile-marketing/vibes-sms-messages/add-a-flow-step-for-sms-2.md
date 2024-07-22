---
description: SMS에 대한 흐름 단계 추가 - Marketo 문서 - 제품 설명서
title: SMS에 대한 흐름 단계 추가
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: fee2d692acd8d54f2e308e2d5edc9876d13d5a4d
workflow-type: tm+mt
source-wordcount: '377'
ht-degree: 0%

---

# SMS에 대한 흐름 단계 추가 {#add-a-flow-step-for-sms}

Marketo Engage에는 SMS 스마트 캠페인에서 사용할 수 있는 세 가지 흐름 단계가 있습니다.

<table>
<tbody>
  <tr>
    <td style="width:25%">SMS 메시지 보내기</td>
    <td>이 흐름 작업은 Marketo Smart List에서 사용자 옵트인 Vibes 구독 목록을 구독하는 사람에게 메시지를 보냅니다. 가입 프로세스가 시작되지 않습니다. <a href="/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-a-vibes-sms-message.md">자세히 알아보기</a>.</td>
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
>SMS 메시지를 보낼 때:
>
>* Marketo은 전화 번호로 중복 제거됩니다. 따라서 여러 사람이 동일한 전화 번호를 사용하는 경우 한 사람만 Vibes 구독 목록에 가입되어 있는 경우 메시지를 받게 됩니다. 데이터 중복 제거는 Marketo 프로그램 수준이 아닌 Vibes 구독 목록 수준에서 수행됩니다.
>* Marketo은 차단 목록에 추가된 또는 마케팅 중단 대상자에게 보내지 않습니다.

흐름 단계 설정에 대한 일반 정보는 [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)를 참조하십시오.

SMS 사용에 대한 기본 사항은 다음과 같습니다.

1. 내 Marketo에서 **마케팅 활동**&#x200B;을 클릭합니다.

   ![](assets/add-a-flow-step-for-sms-1.png)

1. SMS 흐름을 추가할 Smart Campaign을 찾아 선택합니다.

   스크린샷

1. 스마트 목록 탭에서 원하는 트리거(예: &quot;작성된 양식&quot;)를 선택합니다.

   스크린샷

1. **흐름** 탭에서 흐름 단계(예: **SMS 메시지 보내기**) 위로 끌어서 놓습니다. 드롭다운에서 SMS 메시지 및 바이브 목록을 선택합니다.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >Vibes 목록 선택기는 Smart List에서 이미 식별된 대상에 대한 추가 필터 역할을 하여 해당 Vibes 목록에 속하는 리드만 타겟팅합니다.
   >
   >**Vibes 목록 구독** 및 **Vibes 목록 구독 취소** 흐름의 요구 사항이 다릅니다. **구독**&#x200B;의 경우 Vibes 목록 및 Vibes 획득 캠페인을 선택해야 합니다. **구독 취소**&#x200B;의 경우 보기 목록만 필요합니다.

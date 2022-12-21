---
unique-page-id: 11379045
description: SMS - Marketo 문서 - 제품 설명서에 대한 흐름 단계 추가
title: SMS용 흐름 단계 추가
exl-id: 8e96f6ad-43c9-4d64-8cb6-241664956d72
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---

# SMS용 흐름 단계 추가 {#add-a-flow-step-for-sms}

Marketo에는 SMS 스마트 캠페인에서 사용할 수 있는 세 가지 플로우 단계가 있습니다.

* **SMS 메시지 보내기** - 이 흐름 작업은 사용자가 선택한 Vides 구독 목록에 가입한 Marketo 스마트 목록의 사람에게 메시지를 보냅니다. 구독 프로세스가 시작되지 않습니다.
* **보기 목록에 가입** - 이 흐름 작업은 사용자가 선택한 Video Acquisition 캠페인을 통해 SMS 구독 프로세스를 시작합니다. 그런 다음 확인 메시지를 보냅니다. 수신자는 구독 프로세스를 완료하려면 수신자에게 회신해야 합니다.
* **방문 목록에서 가입 해지** - 이 흐름 작업은 사용자가 선택한 방문 구독 목록에서 각 개인의 가입을 해지합니다.

>[!NOTE]
>
>SMS 메시지를 보낼 때:
>
>* Marketo 전화 번호별 중복 제거. 따라서 여러 사람이 같은 전화번호를 가지고 있다면 한 사람만 메시지를 받게 됩니다.
>* Marketo은 차단 목록에 추가된 또는 마케팅 일시 중지된 사람에게 보내지 않습니다.


흐름 단계 설정에 대한 일반적인 내용은 [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md).

SMS 사용에 대한 기본 사항은 다음과 같습니다.

1. 내 Marketo에서 **마케팅 활동**.

   ![](assets/image2016-7-28-11-3a41-3a17.png)

1. SMS 흐름을 추가할 스마트 캠페인을 찾습니다. 을(를) 클릭합니다. **흐름** 탭.

   ![](assets/image2016-7-28-11-3a43-3a41.png)

1. 흐름 위로 드래그합니다(예: ). **SMS 메시지 보내기**. 드롭다운에서 SMS 메시지 및 방문 목록을 선택합니다.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >방문 목록 선택기는 스마트 목록에서 이미 식별된 대상에 대한 추가 필터 역할을 수행하여 해당 방문 목록에 속하는 리드만 타깃팅합니다.
   >
   >다음 **보기 목록에 가입** 및 **방문 목록에서 가입 해지** 흐름에는 서로 다른 요구 사항이 있습니다. 대상 **구독**, 보기 목록 및 시각적 획득 캠페인을 선택해야 합니다. 대상 **구독 취소**&#x200B;에는 보기 목록만 필요합니다.

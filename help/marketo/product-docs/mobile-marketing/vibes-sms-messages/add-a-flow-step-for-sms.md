---
unique-page-id: 11379045
description: SMS - Marketing To Docs - 제품 설명서에 대한 흐름 단계 추가
title: SMS용 흐름 단계 추가
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '283'
ht-degree: 0%

---


# SMS {#add-a-flow-step-for-sms}에 대한 흐름 단계 추가

Marketing에는 SMS 스마트 캠페인에 사용할 수 있는 3가지 흐름 단계가 있습니다.

* **SMS 메시지**  보내기 - 이 흐름 작업은 사용자가 선택한 Vibe 구독 목록에 가입한 Marketing Cloud의 사용자에게 메시지를 보냅니다. 구독 프로세스가 시작되지 않습니다.
* **동영상 목록 구독**  - 이 흐름 작업은 사용자가 선택한 Videes Acquisition 캠페인을 통해 SMS 구독 프로세스를 시작합니다. 그러면 Videes가 확인 메시지를 전송합니다.수신자는 회신을 통해 가입 절차를 완료해야 합니다.
* **동영상 목록 구독 취소**  - 이 흐름 작업은 사용자가 선택한 Vides 구독 목록에서 각 사람의 가입을 해지합니다.

>[!NOTE]
>
>SMS 메시지를 보낼 때:
>
>* 전화 번호별 Marketing to 중복 제거. 따라서 여러 사람이 같은 전화 번호를 갖고 있으면 한 명만 메시지를 받게 됩니다.
>* Marketing To는 마케팅차단 목록에 추가된이 일시 중지된 사람에게 전송되지 않습니다.

>



흐름 단계 설정에 대한 일반적인 내용은 [스마트 캠페인에 흐름 단계 추가](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)를 참조하십시오.

SMS 사용에 대한 기본 사항은 다음과 같습니다.

1. 내 마케팅에서 **마케팅 활동**&#x200B;을 클릭합니다.

   ![](assets/image2016-7-28-11-3a41-3a17.png)

1. SMS 흐름을 추가할 스마트한 캠페인을 찾습니다. **흐름** 탭을 클릭합니다.

   ![](assets/image2016-7-28-11-3a43-3a41.png)

1. 흐름 위로 드래그합니다(예: **SMS 메시지 보내기**). 드롭다운에서 SMS 메시지와 Vides 목록을 선택합니다.

   ![](assets/send-sms-message-hands.jpg)

   >[!NOTE]
   >
   >비브 목록 선택기는 스마트 목록에 이미 식별된 대상에 대한 추가 필터 역할을 수행하여 해당 비브 목록에 속하는 리드만 타깃팅합니다.
   >
   >
   >**Subscribe to Vibe List** 및 **Visbe List** 흐름의 가입 해지는 서로 다른 요구 사항을 갖습니다. **가입**&#x200B;의 경우, 방문 목록 및 Vides 획득 캠페인을 선택해야 합니다. **가입 해지**&#x200B;의 경우 Vibes 목록만 필요합니다.


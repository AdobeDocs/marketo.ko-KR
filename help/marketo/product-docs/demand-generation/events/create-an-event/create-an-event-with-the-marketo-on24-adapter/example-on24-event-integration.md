---
unique-page-id: 10096679
description: ON24 이벤트 통합 예 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 통합 예
exl-id: 9d34d1bf-1ff8-4b26-906e-4a6bb9d5f3f6
feature: Events
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '361'
ht-degree: 0%

---

# ON24 이벤트 통합 예 {#example-on-event-integration}

다음은 ON24 웨비나에 대한 캠페인 등 샘플 이벤트입니다. 이벤트를 작성할 때는 캠페인을 실행하기 전에 테스트해야 합니다.

## 마케팅 활동에서 새 이벤트 만들기 {#create-a-new-event-in-marketing-activities}

1. **[!UICONTROL New]** > **[!UICONTROL New Program]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-12-22-15-3a35-3a15.png)

1. 이벤트가 활성화될 **[!UICONTROL Campaign Folder]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-12-22-15-3a39-3a51.png)

1. 이벤트에 대한 **[!UICONTROL Name]**&#x200B;을(를) 입력하십시오.

   ![](assets/image2015-12-22-15-3a43-3a4.png)

1. **[!UICONTROL Event]**&#x200B;을(를) **[!UICONTROL Program Type]**(으)로 선택합니다.

   ![](assets/image2015-12-22-15-3a44-3a41.png)

1. **[!UICONTROL Webinar]**&#x200B;을(를) 이벤트의 **[!UICONTROL Channel]**(으)로 선택합니다.

   ![](assets/image2015-12-22-15-3a46-3a34.png)

1. **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-12-22-15-3a48-3a20.png)

## 초대(일괄 캠페인)  {#invite-batch-campaign}

* **스마트 목록** - 이벤트에 초대할 사용자를 정의합니다.
* **흐름**

   * 이메일 보내기 - 로컬 에셋 이메일인 경우, EventName.EmailName 명명 규칙이 적용됩니다. 글로벌 이메일을 사용할 수도 있습니다.
   * 진행 상태 변경 - 웨비나 > 초대로 설정합니다.

* **일정** - 초대를 보낼 날짜를 설정합니다.

## 등록/확인(캠페인 트리거) {#registration-confirmation-trigger-campaign}

* **스마트 목록**

   * **[!UICONTROL Fills Out Form]**&#x200B;을(를) 기반으로 캠페인을 트리거합니다. **[!UICONTROL Add Constraint]**&#x200B;을(를) 사용하여 양식이 있는 랜딩 페이지를 포함해야 합니다. 특히 양식이 여러 랜딩 페이지에서 사용되는 경우 더 그렇습니다.

>[!CAUTION]
>
>이벤트에 대한 사용자를 등록하려면 Marketo 양식을 사용하고, 등록 데이터를 Marketo에 푸시하려면 적절한 API 통합이 포함된 Marketo이 아닌 양식을 사용해야 합니다. 이는 [!UICONTROL Event Partner] 통합의 성공에 매우 중요합니다. **참고**: Marketo이 아닌 랜딩 페이지에서 Marketo 양식을 사용하는 경우 트리거는 **[!UICONTROL Fills Out Form]**&#x200B;을(를) 사용하는 [!UICONTROL Form Name]이(가) 됩니다.

![](assets/image2015-12-22-15-3a50-3a22.png)

* **흐름**

   * **진행 중 상태 변경** - 웨비나 > 등록됨으로 설정합니다. **주의**: 자식 캠페인을 설정할 때 이 흐름 단계가 필요합니다. 개인의 진행 상태가 **등록됨**(으)로 변경되면 Marketo에서 등록 정보를 ON24로 푸시합니다.

   * **전자 메일 보내기** - 확인 전자 메일(**Operational**(으)로 설정되어 등록된 구독 취소자가 계속 받을 수 있도록 함).

![](assets/image2015-12-22-15-3a52-3a9.png)

**참고**: 등록 오류가 있는 사용자가 반환되면 전자 메일 확인이 수신되지 않습니다.

## 미리 알림(일괄 캠페인) {#reminder-batch-campaign}

* **스마트 목록** - **프로그램 구성원**&#x200B;을(를) 사용하여 필터링하고 상태를 **등록됨**(으)로 설정합니다.

* **흐름** - 전자 메일(미리 알림 전자 메일)을 보냅니다.

**참고**: 초대를 받았지만 아직 등록하지 않은 사람에게 유사한 캠페인을 사용하여 *다른* 후속 전자 메일을 보낼 수 있습니다.

## 후속 캠페인(일괄 처리 또는 트리거 캠페인) {#follow-up-campaign-batch-or-trigger-campaign}

* **스마트 목록** - 프로그램 상태의 변경 내용에 따라 트리거됩니다.

![](assets/image2015-12-22-15-3a57-3a25.png)

* **흐름** - 전자 메일을 보냅니다. 프로그램 상태에 따라 다양한 이메일을 보내려면 선택 사항을 사용하십시오.

![](assets/ten.png)

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}

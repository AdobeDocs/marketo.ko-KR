---
unique-page-id: 17728023
description: ' [!DNL Zoom] - Marketo 문서 - 제품 설명서를 사용하여 이벤트 만들기'
title: ' [!DNL Zoom](으)로 이벤트 만들기'
exl-id: 6a2aec58-902c-4e40-ab59-9cc33ec83cea
feature: Events
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '531'
ht-degree: 0%

---

# [!DNL Zoom]&#x200B;(으)로 이벤트 만들기 {#create-an-event-with-zoom}

>[!PREREQUISITES]
>
>* [추가 [!DNL Zoom] as a [!DNL LaunchPoint] 서비스](/help/marketo/product-docs/administration/additional-integrations/add-zoom-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 참여를 추적하려면 적절한 [흐름 동작](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)을 설정하십시오.

먼저 [!DNL Zoom]에서 웨비나를 만듭니다. [!DNL Zoom] 만들기의 특정 설정은 Marketo에서 사용되며, 일부는 [!DNL Zoom]에서만 사용됩니다.

Marketo 이벤트를 만들고 [!DNL Zoom] 웨비나를 이 이벤트와 연결하면 시스템에서 등록 및 참석 정보를 공유할 수 있습니다. 웨비나를 만드는 데 도움이 필요하면 [시작 [!DNL Zoom] 웨비나](https://support.zoom.us/hc/en-us/articles/200917029-Getting-Started-With-Webinar)를 참조하십시오.

웨비나에 대한 다음 정보를 입력하면 어댑터를 통해 Marketo으로 가져옵니다. 이 정보를 변경하는 경우 Marketo에서 변경 사항을 보려면 이벤트 작업 아래의 &quot;웨비나 공급자에서 새로 고침&quot; 링크를 클릭해야 합니다.

**제목 및 설명**

* **웨비나 이름** - 웨비나 이름을 입력합니다. 이 이름은 Marketo에서 볼 수 있습니다.

* **설명**(선택 사항) - 웨비나에 대한 설명을 입력합니다. 설명은 Marketo에서 볼 수 있습니다.

**날짜 및 시간**

* **시작 날짜** - 시작 날짜를 입력하십시오. 이 화면은 Marketo에서 볼 수 있습니다.

* **시작 시간** - 시작 시간을 입력하십시오. 이 화면은 Marketo에서 볼 수 있습니다.

* **기간** - 기간을 입력하십시오. 시작 시간 및 종료 시간은 Marketo에서 볼 수 있습니다.

* **표준 시간대** - 적용 가능한 표준 시간대를 선택합니다. 이 화면은 Marketo에서 볼 수 있습니다.

* **되풀이 웨비나**- 선택하지 않은 상태로 유지합니다.

* **등록** - 등록이 필요하도록 하려면 이 확인란을 선택하십시오. Marketo 양식/랜딩 페이지를 사용하여 [!DNL Zoom]에 푸시될 등록 정보를 캡처합니다.

>[!NOTE]
>
>Marketo은 현재 반복 웨비나를 지원하지 않습니다. 각 Marketo 이벤트와 [!DNL Zoom] 웨비나 사이에 단일 세션을 설정해야 합니다.

![](assets/overview2.png)

>[!TIP]
>
>통합에 영향을 주지 않는 [!DNL Zoom]에서 구성할 추가 필드가 있습니다. 이러한 필드에 대한 자세한 내용은 [[!DNL Zoom] 웨비나 도움말 센터](https://support.zoom.us/hc/en-us/sections/200324965-Video-Webinar)를 참조하십시오.

이제 Marketo으로 뛰어들어 보겠습니다!

1. 이벤트를 선택합니다. **[!UICONTROL Event Actions]**&#x200B;을(를) 클릭하고 **[!UICONTROL Event Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-5-14-14-3a53-3a10-1.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 형식은 **웨비나**&#x200B;여야 합니다.

1. **[!UICONTROL Zoom]** 목록에서 **[!UICONTROL Event Partner]** 선택.

   ![](assets/eventsettings1.png)

1. 이벤트를 연결할 [!DNL Zoom] 계정을 선택하십시오.

   ![](assets/selectaccount.png)

1. 웨비나를 선택합니다.

   ![](assets/selectevent.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/eventsettingssave.png)

   훌륭합니다! 이제 이벤트가 [!DNL Zoom]에 의해 동기화되고 예약됩니다.

   >[!NOTE]
   >
   >Marketo이 보내는 필드는 이름, 성, 이메일 주소입니다.

   >[!TIP]
   >
   >확인 전자 메일을 이 고유 URL로 채우려면 전자 메일에 `{{member.webinar url}}` 토큰을 사용하십시오. 확인 URL이 전송되면 이 토큰은 개인의 고유한 확인 URL로 자동으로 확인됩니다.
   >
   >등록 및 구독 취소 가능성이 있는 사람이 여전히 확인 정보를 받도록 하려면 확인 이메일을 **작동**(으)로 설정하십시오.

   **[!UICONTROL Change Program Status]**&#x200B;이(가) &quot;등록됨&quot;으로 설정되면 웨비나에 등록한 사용자는 [!UICONTROL New Status] 흐름 단계를 통해 웨비나 공급자에게 푸시됩니다. 다른 상태는 사용자를 밀어내지 않습니다. 또한 **[!UICONTROL Change Program Status]** 흐름 단계를 #1, **[!UICONTROL Send Email]** 흐름 단계를 #2 합니다.

   ![](assets/goto-webinar-1.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 발송하지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용합니다.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그렇게 오래 기다린 후에도 아무것도 표시되지 않으면 이벤트의 **요약** 탭에 있는 이벤트 작업 메뉴에서 **웨비나 공급자에서 새로 고침**&#x200B;을 선택한 다음 화면 오른쪽 하단에 있는 새로 고침 아이콘을 클릭합니다.

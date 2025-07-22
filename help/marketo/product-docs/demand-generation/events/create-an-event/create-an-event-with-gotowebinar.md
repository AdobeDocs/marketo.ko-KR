---
unique-page-id: 2949874
description: ' [!DNL GotoWebinar] - Marketo 문서 - 제품 설명서를 사용하여 이벤트 만들기'
title: ' [!DNL GotoWebinar] (으)로 이벤트 만들기'
exl-id: c0f0a202-e416-4523-b7d6-dbcfafc536cd
feature: Events
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '486'
ht-degree: 0%

---

# [!DNL GotoWebinar]&#x200B;(으)로 이벤트 만들기 {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [추가 [!DNL GoToWebinar] as a [!DNL LaunchPoint] 서비스](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 참여를 추적하려면 적절한 [흐름 동작](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)을 설정하십시오.

먼저 [!DNL GoToWebinar]에서 웨비나를 만듭니다. [!DNL GoToWebinar] 만들기의 특정 설정은 Marketo에서 사용되며 일부는 [!DNL GoToWebinar]에서만 사용됩니다.

Marketo 이벤트를 만들고 [!DNL GoToWebinar]을(를) 연결하면 시스템에서 등록 및 참석 정보를 공유할 수 있습니다.

다음은 Marketo에서 사용하는 설정 목록입니다.

## 제목 및 설명 {#title-and-description}

**[!UICONTROL Title]** - 웨비나의 이름을 입력합니다. 이 이름은 Marketo에서 볼 수 있습니다.

**[!UICONTROL Description]**(선택 사항) - 웨비나에 대한 설명을 입력합니다. 설명은 Marketo에서 볼 수 있습니다.

![](assets/image2015-5-28-15-3a1-3a36.png)

## 날짜 및 시간 {#date-time}

웨비나에 대한 다음 정보를 입력하면 어댑터를 통해 Marketo으로 가져옵니다. 이 정보를 변경하는 경우 **[!UICONTROL Refresh from Webinar Provider]** 아래의 &quot;**[!UICONTROL Event Actions]**&quot; 링크를 클릭해야 Marketo에서 변경 사항을 볼 수 있습니다.

**[!UICONTROL Start Date]** - 시작 날짜를 입력하십시오. 이 화면은 Marketo에서 볼 수 있습니다.

**[!UICONTROL Start Time]** - 시작 시간을 입력하십시오. 이 화면은 Marketo에서 볼 수 있습니다.

**[!UICONTROL End Time]** - 종료 시간을 입력하십시오. 이 화면은 Marketo에서 볼 수 있습니다.

**[!UICONTROL Webinar Time Zone]** - 적용 가능한 표준 시간대를 선택합니다. Marketo에서 볼 수 있습니다.

**[!UICONTROL Type]** - **[!UICONTROL One Session]**(으)로 설정.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketo은 현재 반복 웨비나를 지원하지 않습니다. 각 Marketo 이벤트와 [!DNL GoToWebinar] 웨비나 사이에 단일 세션을 설정해야 합니다.

>[!TIP]
>
>추가 [!DNL GoToWebinar] 도움이 필요한 경우 [도움말 사이트](https://support.logmeininc.com/gotowebinar)를 방문하세요.

이제 Marketo으로 뛰어들어 보겠습니다!

1. 이벤트를 선택합니다. **[!UICONTROL Event Actions]**&#x200B;을(를) 클릭하고 **[!UICONTROL Event Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 형식은 **웨비나**&#x200B;여야 합니다.

1. **[!UICONTROL GoToWebinar]** 목록에서 **[!UICONTROL Event Partner]** 선택.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. 계정을 선택합니다.

   ![](assets/rtaimage-2.png)

1. 웨비나를 선택합니다.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. 훌륭합니다! 이제 이벤트가 **[!DNL GoToWebinar]**&#x200B;에 의해 동기화되고 예약됩니다.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >Marketo이 보내는 필드는 이름, 성, 이메일 주소입니다. 이러한 필드는 필수이며 비워둘 수 없습니다.

   >[!TIP]
   >
   >확인 전자 메일을 이 고유 URL로 채우려면 전자 메일에 `{{member.webinar url}}` 토큰을 사용하십시오. 확인 URL이 전송되면 이 토큰은 개인의 고유한 확인 URL로 자동으로 확인됩니다.
   >
   >등록 및 구독 취소 가능성이 있는 사람이 여전히 확인 정보를 받도록 하려면 확인 이메일을 **작동**(으)로 설정하십시오.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 발송하지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용합니다.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그렇게 오래 기다린 후에도 아무 것도 표시되지 않으면 이벤트의 **[!UICONTROL Refresh from Webinar Provider]** 탭에 있는 [!UICONTROL Event Actions] 메뉴에서 **[!UICONTROL Summary]**&#x200B;을(를) 선택하십시오.

[!UICONTROL Change Program Status]이(가) &quot;등록됨&quot;으로 설정되면 웨비나에 등록한 사용자는 [!UICONTROL New Status] 흐름 단계를 통해 웨비나 공급자에게 푸시됩니다. 다른 상태는 사용자를 밀어내지 않습니다. 또한 [!UICONTROL Change Program Status] 흐름 단계를 #1, [!UICONTROL Send Email] 흐름 단계를 #2 합니다.

## 일정 보기  {#viewing-the-schedule}

프로그램 일정 보기에서 이벤트의 달력 항목을 클릭합니다. 일정은 화면 오른쪽에 보시면 됩니다.

>[!NOTE]
>
>이벤트 일정을 변경하려면 [!DNL GoToWebinar]에 웨비나를 편집해야 합니다.

![](assets/image2015-5-14-15-3a3-3a13.png)

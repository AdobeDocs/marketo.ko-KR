---
unique-page-id: 2949874
description: GotoWebinar - Marketing Docs - 제품 설명서를 사용하여 이벤트 만들기
title: gotoWebinar를 사용하여 이벤트 만들기
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---


# gotoWebinar를 사용하여 이벤트 만들기 {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [LaunchPoint 서비스로 GoToWebinar 추가](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 [흐름](http://docs.marketo.com/display/DOCS/Flow+Actions)작업을 설정하여 참여 추적


먼저 GoToWebinar에서 웨비나를 만듭니다. GoToWebinar 만들기의 특정 설정은 Marketing에서 사용되며 일부 설정은 GoToWebinar에서만 사용됩니다.

Marketing 이벤트를 만들고 GoToWebinar를 연결한 후 시스템에서 등록 및 참석 정보를 공유할 수 있습니다. GoToWebinar 만들기에 대한 도움말은 GoToWebinar [사용 안내서를 참조하십시오](http://docs.marketo.com/display/docs/assets/gotowebinar-user-guide.pdf).

아래는 Marketing To에서 사용하는 설정 목록입니다.

## 제목 및 설명 {#title-and-description}

**웨비나 이름** - 웨비나의 이름을 입력합니다. 이 이름은 Marketing에서 볼 수 있습니다.

**설명** (선택 사항) - 웨비나에 대한 설명을 입력합니다. 설명은 Marketing To에서 볼 수 있습니다.

![](assets/image2015-5-28-15-3a1-3a36.png)

## 날짜 및 시간 {#date-time}

`Enter the following information for your webinar and it will be pulled into Marketo via the`어댑터. 이 정보를 변경하는 경우, 마케터가 변경 사항을 보려면&#x200B;**이벤트 작업**&#x200B;아래에 있는 &quot;웨비나 ****&#x200B;제공자에서 새로 고침&quot; 링크를 클릭해야 합니다.

**시작 날짜** - 시작 날짜를 입력합니다. Marketing To에서 볼 수 있습니다.

**시작 시간** - 시작 시간을 입력합니다. Marketing To에서 볼 수 있습니다.

**종료 시간** - 종료 시간을 입력합니다. Marketing To에서 볼 수 있습니다.

**시간대** - 해당 시간대를 선택합니다. Marketing To에서 볼 수 있습니다.

**-** set을 **하나의 세션으로 입력합니다**.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketing에서는 현재 반복되는 웨비나를 지원하지 않습니다. 각 Marketing To 이벤트와 GoToWebinar 웨비나 간에 단일 세션을 설정해야 합니다.

>[!TIP]
>
>통합에 영향을 주지 않는 추가 필드가 GoToWebinar에서 구성됩니다. 이러한 필드에 대한 자세한 내용은 [GoToWebinar 사용자](http://docs.marketo.com/display/docs/assets/gotowebinar-user-guide.pdf) 안내서를 참조하십시오. 이러한 필드는 이 문서에서 다루지 않습니다. 추가 GoToWebinar 도움말이 필요한 경우 도움말 [사이트를 방문하십시오](http://support.logmeininc.com/gotowebinar).

이제 Marketing Cloud로 넘어갑시다!

1. 이벤트를 선택합니다. [ **이벤트 작업** ]을 클릭하고 [ **이벤트 설정]을 선택합니다**.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 **웨비나여야 합니다**.

1. 이벤트 **파트너** 목록에서 **GoToWebinar를** **** 선택합니다.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. 계정을 선택합니다.

   ![](assets/rtaimage-2.png)

1. 웨비나를 선택합니다.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. 저장을 **클릭합니다**.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. 훌륭해! 이제 이벤트가 동기화되고 GoToWebinar에 의해 **예약됩니다**.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >Marketing에서 보내는 필드는 다음과 같습니다.이름, 성, 이메일 주소. 이러한 필드는 필수 항목이며 비워 둘 수 없습니다.

   >[!TIP]
   >
   >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
   >
   >등록 및 구독 취소 **** 사용자가 확인 정보를 계속 받을 수 있도록 확인 이메일을 작동 방식으로 설정합니다.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >데이터가 Marketing Cloud에 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그래도 아무 것도 표시되지 않으면 이벤트의 [ **요약** ] 탭에 있는 [이벤트 작업] 메뉴의 [웨비나 공급자 **** ]에서 [새로 고침]을 선택합니다.

웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 프로그램 상태 변경 흐름 단계를 통해 웨비나 제공자로 푸시됩니다. 다른 신분은 그 사람을 밀어주지 않는다. 또한 프로그램 상태 변경 플로우 단계 #1과 이메일 보내기 흐름 단계 2를 설정해야 합니다.

## 일정 보기  {#viewing-the-schedule}

프로그램 [예약 보기에서](http://docs.marketo.com/display/docs/program+schedule+view)이벤트의 달력 항목을 클릭합니다. 화면 오른쪽에 스케쥴이 보입니다

>[!NOTE]
>
>이벤트 일정을 변경하려면 GoToWebinar의 웨비나를 편집해야 합니다.

![](assets/image2015-5-14-15-3a3-3a13.png)

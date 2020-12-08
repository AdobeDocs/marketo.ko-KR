---
unique-page-id: 2949870
description: ReadyTalk - Marketing Docs - 제품 설명서를 사용하여 이벤트 만들기
title: ReadyTalk를 사용하여 이벤트 만들기
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '444'
ht-degree: 0%

---


# ReadyTalk를 사용하여 이벤트 만들기 {#create-an-event-with-readytalk}

>[!PREREQUISITES]
>
>* [LaunchPoint 서비스로 ReadyTalk 추가](/help/marketo/product-docs/administration/additional-integrations/add-readytalk-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 [흐름](http://docs.marketo.com/display/DOCS/Flow+Actions)작업을 설정하여 참여 추적


먼저 ReadyTalk 컨퍼런스 센터에서 이벤트를 설정합니다. 도움이 필요한 경우 ReadyTalk 리소스 [센터를 확인하십시오.](https://www.readytalk.com/resources/readytalk)  등록 유형을 선택할 때 회의 전에 **사전 등록을 선택합니다**. 회의 *시간에*&#x200B;등록을 선택하면 Marketing에서 사용자의 등록됨 상태를 **캡처하지** *않고* 웨비나가 종료된후개인 상태에서만수신됩니다.

이메일 **을 통해 새로운 등록 정보를** 선택하지 않은 상태로 둡니다.

![](assets/image2015-5-28-21-3a18-3a39.png)

ReadyTalk를 사용하여 확인 이메일을 보내는 경우 설명을 추가해야 합니다. 완료되면 ReadyTalk에 이벤트를 저장합니다.

>[!NOTE]
>
>연산자 지원 이벤트를 예약하려면 컨퍼런스 센터 홈 화면 왼쪽에 있는 **요청 이벤트 서비스** 링크를 클릭하여 이벤트 팀과 이벤트를 예약합니다.

이제 이벤트를 Marketing To에 연결할 준비가 되었습니다.

1. 이벤트를 선택한 다음 **이벤트 작업**, 마지막으로 [ **이벤트 설정]을 클릭합니다.**

   ![](assets/image2015-5-18-12-3a46-3a47.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 **웨비나여야 합니다.**

1. 이벤트 **파트너 아래에서** ReadyTalk를 **선택합니다**.

   ![](assets/image2015-5-18-12-3a47-3a59.png)

1. 로그인 **에서** ReadyTalk 로그인을 선택합니다.

   ![](assets/image2015-5-18-12-3a48-3a48.png)

1. 이벤트 **에서**&#x200B;연결할 이벤트를 선택한 다음 **저장을 클릭합니다**.

   ![](assets/image2015-5-18-12-3a51-3a35.png)

   좋아! 이제 이벤트가 동기화됩니다.

   >[!NOTE]
   >
   >Marketing에서 보내는 필드는 다음과 같습니다.이름, 성, 이메일 주소.

   >[!TIP]
   >
   >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
   >
   >확인 이메일을 작동 방식으로 설정하여 등록을 취소하는 사람이 확인 정보를 받을 수 있도록 합니다.

   ![](assets/readytalk.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >데이터가 Marketing Cloud에 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그래도 아무 것도 표시되지 않으면 이벤트의 [ **요약** ] 탭에 있는 [이벤트 작업] 메뉴의 [웨비나 공급자 **** ]에서 [새로 고침]을 선택합니다.

## 일정 보기  {#viewing-the-schedule}

프로그램 [예약 보기에서](http://docs.marketo.com/display/docs/program+schedule+view)이벤트의 달력 항목을 클릭합니다. 화면 오른쪽에 스케쥴이 보이실 겁니다

![](assets/image2015-5-18-12-9-58.png)

웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 프로그램 상태 변경 흐름 단계를 통해 웨비나 제공자로 푸시됩니다. 다른 신분은 그 사람을 밀어주지 않는다. 또한 프로그램 상태 변경 플로우 단계 #1과 이메일 보내기 흐름 단계 2를 설정해야 합니다.

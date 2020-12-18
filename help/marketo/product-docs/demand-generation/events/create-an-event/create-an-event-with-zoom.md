---
unique-page-id: 17728023
description: 확대/축소 - Marketing To Docs - 제품 설명서로 이벤트 만들기
title: 확대/축소를 사용하여 이벤트 만들기
translation-type: tm+mt
source-git-commit: c8a77dc84c023e05fbb442f575269aac108ffb29
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---


# {#create-an-event-with-zoom} 확대/축소가 있는 이벤트 만들기

>[!PREREQUISITES]
>
>* [LaunchPoint 서비스로 확대/축소 추가](/help/marketo/product-docs/administration/additional-integrations/add-zoom-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 [흐름 작업](http://docs.marketo.com/display/DOCS/Flow+Actions)을 설정하여 참여를 추적합니다.


먼저 확대/축소에 웨비나를 만듭니다. 확대/축소 만들기의 특정 설정은 Marketing To에서 사용하며, 일부는 확대/축소에서만 사용됩니다.

Marketing 이벤트를 만들고 Zoom 웨비나를 여기에 연결한 후 시스템에서 등록 및 참석 정보를 공유할 수 있습니다. 웨비나를 만드는 데 도움이 필요하면 [확대/축소 웨비나 시작하기](https://support.zoom.us/hc/en-us/articles/200917029-Getting-Started-With-Webinar)를 참조하십시오.

웨비나에 다음 정보를 입력하면 어댑터를 통해 Marketing To로 이동합니다. 이 정보를 변경하는 경우 마케터가 변경 사항을 보려면 이벤트 작업 아래의 &quot;웨비나 공급자로부터 새로 고침&quot; 링크를 클릭해야 합니다.

**제목 및 설명**

* **웨비나 이름**  - 웨비나의 이름을 입력합니다. 이 이름은 Marketing To에서 볼 수 있습니다.

* **설명** (선택 사항) - 웨비나에 대한 설명을 입력합니다. 설명은 Marketing To에서 볼 수 있습니다.

**날짜 및 시간**

* **시작 날짜**  - 시작 날짜를 입력합니다. Marketing To에서 볼 수 있습니다.

* **시작 시간**  - 시작 시간을 입력합니다. Marketing To에서 볼 수 있습니다.

* **기간**  - 기간을 입력합니다. 시작 시간과 종료 시간이 Marketing To에서 볼 수 있습니다.

* **시간대**  - 해당 시간대를 선택합니다. Marketing To에서 볼 수 있습니다.

* **반복 웨비나** - 선택 취소합니다.

* **등록**  - 이 확인란을 선택하여 등록해야 합니다. Marketing To 양식/랜딩 페이지를 사용하여 확대/축소로 푸시될 등록 정보를 캡처합니다.

>[!NOTE]
>
>Marketing에서는 현재 반복되는 웨비나를 지원하지 않습니다. 각 Marketing To 이벤트와 확대/축소 웨비나 간에 단일 세션을 설정해야 합니다.

![](assets/overview2.png)

>[!TIP]
>
>통합에 영향을 주지 않는 확대/축소에 구성할 추가 필드가 있습니다. 이러한 필드에 대한 자세한 내용은 [확대/축소 웨비나 도움말 센터](https://support.zoom.us/hc/en-us/sections/200324965-Video-Webinar)를 참조하십시오.

이제 Marketing Cloud로 넘어갑시다!

1. 이벤트를 선택합니다. **이벤트 작업**&#x200B;을 클릭하고 **이벤트 설정**&#x200B;을 선택합니다.

   ![](assets/image2015-5-14-14-3a53-3a10-1.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 **웨비나**&#x200B;이어야 합니다.

1. **이벤트** **파트너** 목록에서 **확대/축소**&#x200B;를 선택합니다.

   ![](assets/eventsettings1.png)

1. 이벤트를 연결할 확대/축소 계정을 선택합니다.

   ![](assets/selectaccount.png)

1. 웨비나를 선택합니다.

   ![](assets/selectevent.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/eventsettingssave.png)

   훌륭해! 이제 이벤트가 동기화되고 확대/축소에 의해 예약됩니다.

   >[!NOTE]
   >
   >Marketing에서 보내는 필드는 다음과 같습니다.이름, 성, 이메일 주소.

   >[!TIP]
   >
   >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오.`{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
   >
   >등록 및 구독을 취소할 수 있는 사용자가 여전히 확인 정보를 받을 수 있도록 확인 이메일을 **운영**&#x200B;으로 설정합니다.

   웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 **프로그램 상태 변경** 흐름 단계를 통해 웨비나 공급자로 푸시됩니다. 다른 신분은 그 사람을 밀어붙일 수 없다. 또한 **프로그램 상태 변경** 플로우 단계 #1 및 **이메일 보내기** 흐름 단계를 #2.

   ![](assets/goto-webinar-1.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >데이터가 Marketing Cloud에 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그래도 아무 것도 표시되지 않을 때까지 기다린 후 이벤트의 **요약** 탭에 있는 이벤트 작업 메뉴에서 **웨비나 공급자에서 새로 고침**&#x200B;을 선택합니다.

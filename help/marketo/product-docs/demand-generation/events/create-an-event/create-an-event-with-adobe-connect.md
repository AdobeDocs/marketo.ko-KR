---
unique-page-id: 2949865
description: Adobe Connect - Marketing To Docs - 제품 설명서를 사용하여 이벤트 만들기
title: Adobe Connect으로 이벤트 만들기
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '399'
ht-degree: 0%

---


# Adobe Connect {#create-an-event-with-adobe-connect}으로 이벤트 만들기

Adobe Connect과 동기화하면 Marketing Cloud 내의 웨비나 등록 및 참석을 관리할 수 있으므로 참여를 추적하지 않아도 됩니다.

>[!PREREQUISITES]
>
>* [Adobe Connect 및 Marketing To 연결](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)


먼저 Adobe Connect에서 회의 또는 세미나를 만들었는지 확인합니다. 도움이 필요한 경우 [Adobe Connect 사용 안내서](http://help.adobe.com/en_US/connect/9.0/using/index.html)를 확인하십시오. Adobe Connect에서 만든 회의와 세미나는 Marketing To에서 자격 증명을 입력할 때 지정한 폴더 아래에 만들어야 합니다. 회의 또는 세미나를 만든 후 확인 이메일 및 ICS 파일에 사용할 관련 물류 정보(전화 번호 등)를 메모해 둡니다.

>[!NOTE]
>
>현재 **은(는) Adobe Connect 온사이트를 지원하지 않습니다**.

1. 새 이벤트의 홈에서 **이벤트 작업**&#x200B;을 선택한 다음 **이벤트 설정**&#x200B;을 선택합니다.

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >드롭다운에 **이벤트 설정**&#x200B;이 표시되지 않으면 &quot;적용 대상&quot;에서 웨비나&#x200B;**이 선택된**&#x200B;이벤트가 이벤트 채널에 있는지 확인합니다.

1. **이벤트 파트너**&#x200B;에서 **Adobe Connect**&#x200B;을 선택합니다.

   ![](assets/event-settings-adobe-connect.png)

1. **로그인** ID를 선택하고 **이벤트**&#x200B;를 선택합니다.

   ![](assets/event-settings-select-event-adobe-connect.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/event-settings-overview.png)

   좋아! 이제 Adobe Connect 이벤트가 Marketing To 이벤트와 동기화됩니다.

   >[!NOTE]
   >
   >Marketing에서 보내는 필드는 다음과 같습니다.이름, 성, 이메일 주소.

   >[!TIP]
   >
   >이메일에 개인의 고유 URL을 삽입하려면 다음 토큰을 사용하십시오.`{{member.webinar url}}`. 이메일이 전송되면 이 토큰은 Adobe Connect에서 발송된 개인의 고유한 확인 URL을 자동으로 확인합니다.
   >
   >등록 및 구독을 취소할 수 있는 사용자가 여전히 확인 정보를 받을 수 있도록 확인 이메일을 **운영**&#x200B;으로 설정합니다.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >데이터가 Marketing Cloud에 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그래도 아무 것도 표시되지 않을 때까지 기다린 후 이벤트의 [요약] 탭에 있는 [이벤트 작업] 메뉴에서 **웨비나 공급자에서 새로 고침**&#x200B;을 선택합니다.

   >[!MORELIKETHIS]
   >
   > * [LaunchPoint 서비스로 Adobe Connect 추가](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
   > * [이벤트 채널 편집](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md)


새 상태가 &quot;등록됨&quot;으로 설정된 경우 웨비나에 등록한 사람은 프로그램 상태 변경 흐름 단계를 통해 웨비나 제공자에게 푸시됩니다. 다른 신분은 그 사람을 밀어붙일 수 없다. 또한 프로그램 상태 변경 플로우 단계 #1 및 이메일 흐름 보내기 단계를 #2.

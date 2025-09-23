---
unique-page-id: 2949865
description: Adobe Connect - Marketo 문서 - 제품 설명서를 사용하여 이벤트 만들기
title: Adobe Connect로 이벤트 만들기
exl-id: 196b1640-9cfd-4485-9bc4-e907d3ac1f16
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '383'
ht-degree: 3%

---

# Adobe Connect로 이벤트 만들기 {#create-an-event-with-adobe-connect}

Adobe Connect과 동기화하면 Marketo 내에서 웨비나 등록 및 출석을 관리할 수 있으므로 참여가 추적 취소되지 않습니다.

>[!PREREQUISITES]
>
>* [Adobe Connect 및 Marketo 연결](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)

먼저 Adobe Connect에서 회의 또는 세미나를 만들었는지 확인합니다. 도움이 필요하면 [Adobe Connect 사용 안내서](https://help.adobe.com/en_US/connect/9.0/using/index.html)를 확인하십시오.

Adobe Connect에서 만드는 모임 및 세미나는 Marketo에 자격 증명을 입력할 때 지정한 폴더 아래에 만들어야 합니다. 회의나 세미나를 만든 후에는 확인 이메일과 ICS 파일에 사용할 관련 물류 정보(전화 번호 등)를 기록해 두십시오.

>[!CAUTION]
>
>이벤트 호스트로서 앱 내에서 가입하고 참석자에게 전송된 링크를 통해 **not**&#x200B;해야 합니다.

>[!NOTE]
>
>현재는 Adobe Connect 온사이트를 지원하지 않습니다.

1. 새 이벤트의 홈에서 **[!UICONTROL Event Actions]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Event Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >드롭다운에 **[!UICONTROL Event Settings]**&#x200B;이(가) 표시되지 않으면 이벤트의 채널에 &quot;**[!UICONTROL Event with Webinar]**&quot;에서 선택한 [!UICONTROL Applies to]이(가) 있는지 확인하십시오.

1. **[!UICONTROL Event Partner]**&#x200B;에서 **[!UICONTROL Adobe Connect]**&#x200B;을(를) 선택합니다.

   ![](assets/event-settings-adobe-connect.png)

1. **[!UICONTROL Login]** ID를 선택하고 **[!UICONTROL Event]**&#x200B;을(를) 선택합니다.

   ![](assets/event-settings-select-event-adobe-connect.png)

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/event-settings-overview.png)

   좋네! 이제 Adobe Connect 이벤트가 Marketo 이벤트와 동기화됩니다.

   >[!NOTE]
   >
   >Marketo이 보내는 필드는 이름, 성, 이메일 주소입니다.

   >[!TIP]
   >
   >이메일에 사용자의 고유 URL을 삽입하려면 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 이메일을 전송하면 이 토큰은 개인의 고유한 확인 URL을 Adobe Connect에서 자동으로 확인합니다.
   >
   >등록 및 구독 취소 가능성이 있는 사람이 여전히 확인 정보를 받도록 하려면 확인 이메일을 **작동**(으)로 설정하십시오.

   [!UICONTROL Change Program Status]이(가) &quot;등록됨&quot;으로 설정되면 웨비나에 등록한 사용자는 [!UICONTROL New Status] 흐름 단계를 통해 웨비나 공급자에게 푸시됩니다. 다른 상태는 사용자를 밀어내지 않습니다. 또한 [!UICONTROL Change Program Status] 흐름 단계를 #1, [!UICONTROL Send Email] 흐름 단계를 #2 합니다.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 발송하지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용합니다.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그렇게 오래 기다린 후에도 아무 것도 표시되지 않으면 이벤트의 요약 탭에 있는 이벤트 작업 메뉴에서 **[!UICONTROL Refresh from Webinar Provider]**&#x200B;을(를) 선택하십시오.

   >[!MORELIKETHIS]
   >
   >* [서비스로 Adobe Connect 추가 [!DNL LaunchPoint] 서비스](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
   >* [이벤트 채널 편집](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md)

---
unique-page-id: 2949865
description: Adobe Connect을 사용하여 이벤트 만들기 - Marketo 문서 - 제품 설명서
title: Adobe Connect으로 이벤트 만들기
exl-id: 196b1640-9cfd-4485-9bc4-e907d3ac1f16
source-git-commit: d81a4a3caa12c5ec642afadf9328b3825bde6fed
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 0%

---

# Adobe Connect으로 이벤트 만들기 {#create-an-event-with-adobe-connect}

Adobe Connect과 동기화할 경우 Marketo 내에서 웨비나 등록 및 참석 여부를 관리할 수 있으므로 참여가 추적되지 않습니다.

>[!PREREQUISITES]
>
>* [Adobe Connect 및 Marketo 연결](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)


먼저 Adobe Connect에서 모임 또는 세미나를 만들었는지 확인합니다. 도움이 필요하면 다음을 확인하십시오 [Adobe Connect 사용 안내서](https://help.adobe.com/en_US/connect/9.0/using/index.html).

Adobe Connect에서 만드는 모임 및 세미나는 Marketo에 자격 증명을 입력할 때 지정한 폴더 아래에 만들어야 합니다. 회의나 세미나를 만든 후 확인 전자 메일 및 ICS 파일에 사용할 관련 물류 정보(예: 전화 번호)를 메모하십시오.

>[!CAUTION]
>
>이벤트 호스트로서 앱 내에서 그리고 **not** 참석자에게 전송된 링크를 통해

>[!NOTE]
>
>현재는 Adobe Connect 온사이트를 지원하지 않습니다.

1. 새 이벤트의 홈에서 **이벤트 작업**, 그런 다음 **이벤트 설정**.

   ![](assets/image2015-1-30-15-3a34-3a28.png)

   >[!NOTE]
   >
   >표시되지 않으면 **이벤트 설정** 드롭다운에서 이벤트의 채널이 **웨비나를 사용하는 이벤트** 적용 대상 아래에서 선택됩니다.

1. 아래 **이벤트 파트너**, 선택 **Adobe Connect**.

   ![](assets/event-settings-adobe-connect.png)

1. 을(를) 선택합니다 **로그인** ID를 선택하고 **이벤트**.

   ![](assets/event-settings-select-event-adobe-connect.png)

1. 클릭 **저장**.

   ![](assets/event-settings-overview.png)

   좋아! 이제 Adobe Connect 이벤트가 Marketo 이벤트와 동기화됩니다.

   >[!NOTE]
   >
   >Marketo에서 전송하는 필드는 다음과 같습니다. 이름, 성, 이메일 주소.

   >[!TIP]
   >
   >이메일에 개인의 고유 URL을 삽입하려면 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 이메일이 전송되면 이 토큰은 Adobe Connect에서 개인의 고유 확인 URL을 자동으로 확인합니다.
   >
   >확인 이메일을 (으)로 설정합니다. **운영** 등록 및 가입 해지될 수 있는 사람이 여전히 확인 정보를 받도록 합니다.

   웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 프로그램 상태 변경 흐름 단계를 통해 웨비나 공급자에 푸시됩니다. 다른 상태는 사람을 밀어주지 않습니다. 또한 프로그램 상태 변경 플로우 단계 #1 및 이메일 흐름 전송 단계를 #2.

   ![](assets/adobe.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 기다리는 동안 아무것도 표시되지 않는 경우 **웨비나 공급자에서 새로 고침** 이벤트 요약 탭의 이벤트 작업 메뉴에서 를 클릭합니다.

   >[!MORELIKETHIS]
   >
   >* [Adobe Connect as a LaunchPoint Service 추가](/help/marketo/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.md)
   >* [이벤트 채널 편집](/help/marketo/product-docs/demand-generation/events/understanding-events/edit-an-event-channel.md)


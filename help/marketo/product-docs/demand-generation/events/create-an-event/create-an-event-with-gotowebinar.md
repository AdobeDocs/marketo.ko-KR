---
unique-page-id: 2949874
description: GotoWebinar - Marketo 문서 - 제품 설명서로 이벤트 만들기
title: GotoWebinar를 사용하여 이벤트 만들기
exl-id: c0f0a202-e416-4523-b7d6-dbcfafc536cd
source-git-commit: 8b0625a7192a80986bc4295726cd13473493ddd7
workflow-type: tm+mt
source-wordcount: '543'
ht-degree: 0%

---

# GotoWebinar를 사용하여 이벤트 만들기 {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [LaunchPoint 서비스로 GoToWebinar 추가](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 [흐름 작업](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)참여를 추적합니다


먼저 GoToWebinar에서 웨비나를 만듭니다. GoToWebinar 만들기의 특정 설정은 Marketo에서 사용되며, 일부는 GoToWebinar에서만 사용됩니다.

Marketo 이벤트를 만들고 GoToWebinar를 연결된 후에는 시스템에서 등록 및 참석 정보를 공유할 수 있습니다.

다음은 Marketo에서 사용하는 설정 목록입니다.

## 제목 및 설명 {#title-and-description}

**웨비나 이름** - 웨비나의 이름을 입력합니다. 이 이름은 Marketo에서 볼 수 있습니다.

**설명** (선택 사항) - 웨비나에 대한 설명을 입력합니다. 이 설명은 Marketo에서 볼 수 있습니다.

![](assets/image2015-5-28-15-3a1-3a36.png)

## 날짜 및 시간 {#date-time}

웨비나에 다음 정보를 입력하면 어댑터를 통해 Marketo으로 가져옵니다. 이 정보를 변경할 경우 &quot; 링크를 클릭해야 합니다.**웨비나 공급자에서 새로 고침**&#x200B;아래에 **이벤트 작업**: Marketo에서 변경 사항을 확인합니다.

**시작 날짜** - 시작 날짜를 입력합니다. 이 콘텐츠는 Marketo에서 볼 수 있습니다.

**시작 시간** - 시작 시간을 입력합니다. 이 콘텐츠는 Marketo에서 볼 수 있습니다.

**종료 시간** - 종료 시간을 입력합니다. 이 콘텐츠는 Marketo에서 볼 수 있습니다.

**시간대** - 해당 시간대를 선택합니다. Marketo에서 볼 수 있습니다.

**유형 -** 설정 **하나의 세션**.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketo은 현재 되풀이하는 웨비나를 지원하지 않습니다. 각 Marketo 이벤트와 GoToWebinar 웨비나 사이에 단일 세션을 설정해야 합니다.

>[!TIP]
>
>추가 GoToWebinar 도움말이 필요한 경우 해당 웹 사이트를 방문하십시오. [도움말 사이트](https://support.logmeininc.com/gotowebinar).

이제, Marketo으로 뛰어들자!

1. 이벤트를 선택합니다. 클릭 **이벤트 작업** 및 **이벤트 설정**.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 다음과 같아야 합니다. **웨비나**.

1. 선택 **GoToWebinar** 에서 **이벤트 파트너** 목록.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. 계정을 선택합니다.

   ![](assets/rtaimage-2.png)

1. 웨비나를 선택합니다.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. 클릭 **저장**.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. 훌륭해요! 이제 이벤트가 동기화되고 **GoToWebinar**.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >Marketo에서 전송하는 필드는 다음과 같습니다. 이름, 성, 이메일 주소. 이러한 필드는 필수 항목이며 비워 둘 수 없습니다.

   >[!TIP]
   >
   >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
   >
   >확인 이메일을 (으)로 설정합니다. **운영** 등록 및 가입 해지될 수 있는 사람이 여전히 확인 정보를 받도록 합니다.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 기다리는 동안 아무것도 표시되지 않는 경우 **웨비나 공급자에서 새로 고침** 이벤트 작업 메뉴에서 **요약** 이벤트의 탭.

웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 프로그램 상태 변경 흐름 단계를 통해 웨비나 공급자에 푸시됩니다. 다른 상태는 사람을 밀어주지 않습니다. 또한 프로그램 상태 변경 플로우 단계 #1 및 이메일 흐름 전송 단계를 #2.

## 일정 보기  {#viewing-the-schedule}

프로그램 예약 보기에서 이벤트의 달력 항목을 클릭합니다. 화면 오른쪽에는 스케줄이 표시됩니다.

>[!NOTE]
>
>이벤트 일정을 변경하려면 GoToWebinar에서 웨비나를 편집해야 합니다.

![](assets/image2015-5-14-15-3a3-3a13.png)

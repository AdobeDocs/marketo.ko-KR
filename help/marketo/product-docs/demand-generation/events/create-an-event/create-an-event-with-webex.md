---
unique-page-id: 2949863
description: WebEx - Marketing Docs - 제품 설명서를 사용하여 이벤트 만들기
title: WebEx를 사용하여 이벤트 만들기
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '940'
ht-degree: 0%

---


# WebEx를 사용하여 이벤트 만들기 {#create-an-event-with-webex}

>[!PREREQUISITES]
>
>* [WebEx를 LaunchPoint 서비스로 추가](/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 [흐름](http://docs.marketo.com/display/DOCS/Flow+Actions)작업을 설정하여 참여 추적


먼저 WebEx 이벤트 센터에서 Webex 이벤트를 만듭니다. Marketing Cloud는 통합에 대해 특정 설정 및 필드만 사용하며, 곧 진행할 예정입니다. WebEx용으로 구성할 수 있는 기타 필드는 [WebEx 이벤트 센터 사용자 안내서에 설명되어 있습니다](http://www.cisco.com/c/dam/en/us/td/docs/collaboration/meeting_center/wbs298/wx_ec_host_ug.pdf).

## 기본 정보 {#basic-information}

* **이벤트 이름 -** 이 이름은 Marketing To에서 볼 수 있습니다.
* **목록에 없음 확인란**

   * 이벤트를 나열하지 **않는** 것이 좋습니다. 이렇게 하면 모든 사람이 Marketing To 랜딩 페이지를 통해 등록할 수 있습니다. Marketing To 이외의 메커니즘을 통해 등록한 사람은 이벤트가 끝난 후, 그리고 이벤트에 참석한 경우에만 Marketing To에 표시됩니다.
   * 이벤트 목록을 선택하면 이벤트 센터 웹 사이트를 방문하는 모든 사용자의 이벤트 목록 페이지에 표시됩니다.

* **등록 -** &quot;필수&quot;로 설정하려면 이 상자를 선택합니다. Marketing To 양식/랜딩 페이지를 사용하여 WebEx로 푸시될 등록 정보를 캡처하게 됩니다.
* **이벤트 암호**- (선택 사항) 이 필드를 사용하는 경우 확인 이메일에 반드시 포함해야 합니다.

![](assets/image2015-5-28-13-3a30-3a55.png)

## 날짜 및 시간 {#date-time}

* **시작 날짜** - 시작 날짜를 입력합니다. Marketing To에서 볼 수 있습니다.

* **시작 시간** - 시작 시간을 입력합니다. Marketing To에서 볼 수 있습니다.

* **예상 기간** - 이벤트 기간을 지정합니다. Marketing To에서 볼 수 있습니다.

* **시간대** - 해당 시간대를 입력합니다. Marketing Cloud에서 볼 수 있습니다.

![](assets/image2015-5-28-13-3a37-3a39.png)

## 오디오 컨퍼런스 설정 {#audio-conference-settings}

이러한 설정은 WebEx에만 있습니다. Adobe Marketing Cloud에서 사용하지 않거나 볼 수 있지만 웨비나에서는 중요한 것일 수 있으므로 다시 확인하십시오.

## 이벤트 설명 및 옵션  {#event-description-options}

다음 옵션은 Marketing To에서 사용하거나 볼 수 있습니다. 다른 필드는 WebEx에만 있습니다.

* **설명** - 설명을 입력합니다. 이것은 Marketing To에서 볼 수 있지만 수정할 수 없습니다.
* **이벤트 후 설문 조사** - 현재 Marketing To에서 WebEx 이벤트 후 설문 조사에 대한 정보를 캡처할 수 없습니다.
* **대상 URL** - (선택 사항) 세션이 끝난 후 표시할 대상 URL로 사용할 마케팅 랜딩 페이지의 URL을 입력할 수 있습니다.

![](assets/image2015-5-28-13-3a48-3a49.png)

## 참석자 및 등록 {#attendees-registration}

사용자는 Marketing To 이벤트를 사용하여 초대 목록, 등록 양식 및 기타 이메일을 제어합니다. 다음을 포함하여 Marketing To에서 다른 기능을 지원하지 않습니다.

* **최대 등록자 수** - 현재 Marketing-WebEx 통합을 사용하여 지원되지 **않습니다** .  Marketing To의 승인 대기 중 진행 상태를 사용하여 등록자에 대한 수동 승인을 사용할 수 있습니다.

* **등록 ID 필요** - 현재 Marketing-WebEx 통합을 사용하여 지원됩니다. Marketing을 사용하여 이벤트에 대한 확인 이메일을 보낼 수 있습니다. 사용자가 등록하면 이벤트에 입장하는 데 사용하는 고유한 URL이 수신됩니다.

   >[!TIP]
   >
   >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
   >
   >등록 및 구독 취소 **** 사용자가 확인 정보를 계속 받을 수 있도록 확인 이메일을 작동 방식으로 설정합니다.

* **등록 암호** - (선택 사항) 현재 Marketing-WebEx 통합을 사용하여 지원되지 않습니다.
* **승인 규칙** - 현재 Marketing-WebEx 통합을 사용하여 지원되지 않습니다. 그러나 Marketing에서 스마트 캠페인을 사용하여 승인을 제어할 수 있습니다.

![](assets/image2015-5-28-14-3a4-3a41.png)

### 발표자 및 패널리스트 {#presenters-panelists}

이 섹션에 구성된 정보는 Marketing To로 전달되지 않습니다.

### 이메일 메시지 {#email-messages}

Marketing Cloud를 사용하여 등록자, 확인 이메일 등으로 이메일을 보냅니다. 이 섹션에서 아무 것도 구성할 필요가 없습니다. WebEx에서 이메일 메시지 옵션을 비활성화(선택 취소)합니다.

![](assets/image2015-5-28-14-3a9-3a14.png)

>[!NOTE]
>
>Marketing-WebEx 통합에서는 WebEx에서 확인 이메일 전송을 지원할 수 없습니다. 확인을 Marketing To를 통해 보내야 합니다. 이벤트를 예약한 후에는 이벤트 정보를 Marketing To 확인 이메일에 복사하고 이메일을 **운영됨으로 설정해야 합니다**.

이제 Marketing To로 바로 이동할 준비가 되었습니다.

1. 만든 이벤트를 선택합니다. 이벤트 **작업** 드롭다운을 엽니다. [ **이벤트 설정]을 선택합니다.**

   ![](assets/image2015-5-14-16-3a7-3a31.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 **웨비나여야 합니다**.

1. 이벤트 **파트너**&#x200B;아래에서 **WebEx를 선택합니다**.

   ![](assets/image2015-1-30-13-3a58-3a2.png)

1. 로그인 **에서** WebEx 로그인을 선택합니다.

   ![](assets/image2015-5-18-12-3a2-3a26.png)

1. 이벤트 **에서**&#x200B;새로 만든 WebEx 이벤트를 선택합니다. 그런 다음 백업 페이지(선택 사항)를 선택하고 **저장을 클릭합니다**.

   ![](assets/image2015-5-14-16-3a15-3a55.png)

1. WebEx 이벤트의 백업 페이지(선택 사항)를 선택합니다. 승인된 마케팅 랜딩 페이지의 드롭다운에서 선택하거나 비마케팅 랜딩 페이지의 URL을 입력합니다.

   >[!TIP]
   >
   >이벤트 시작 시간 전에 사용자 지정 이벤트 URL을 클릭하는 경우 특정 페이지로 멤버를 안내하는 백업 페이지를 설정합니다.

   >[!NOTE]
   >
   >Marketing에서 보내는 필드는 다음과 같습니다.이름, 성, 이메일 주소.

   ![](assets/webex.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 보내지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용하십시오.

   >[!TIP]
   >
   >데이터가 Marketing Cloud에 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그래도 아무 것도 표시되지 않으면 이벤트의 [ **요약** ] 탭에 있는 [이벤트 작업] 메뉴의 [웨비나 공급자 **** ]에서 [새로 고침]을 선택합니다.

달콤해 이제 WebEx 이벤트가 Marketing To 이벤트와 동기화됩니다.  웨비나에 등록한 사람은 새 상태가 &quot;등록됨&quot;으로 설정된 경우 프로그램 상태 변경 흐름 단계를 통해 웨비나 제공자로 푸시됩니다. 다른 신분은 그 사람을 밀어주지 않는다. 또한 프로그램 상태 변경 플로우 단계 #1과 이메일 보내기 흐름 단계 2를 설정해야 합니다.

## 일정 보기  {#viewing-the-schedule}

프로그램 [예약 보기에서](http://docs.marketo.com/display/docs/program+schedule+view)이벤트의 달력 항목을 클릭합니다. 화면 오른쪽에 스케쥴이 보이실 겁니다

![](assets/image2015-5-14-16-3a21-3a41.png)

>[!NOTE]
>
>이벤트 일정을 변경하려면 WebEx에서 웨비나를 편집해야 합니다.

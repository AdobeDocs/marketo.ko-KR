---
description: Webex - Marketo 문서 - 제품 설명서를 사용하여 이벤트 만들기
title: Webex를 사용하여 이벤트 만들기
hide: true
hidefromtoc: true
feature: Events
source-git-commit: e21450610146eea3a14761a7365a35d9cacee523
workflow-type: tm+mt
source-wordcount: '921'
ht-degree: 0%

---

# Webex를 사용하여 이벤트 만들기 {#create-an-event-with-webex}

>[!PREREQUISITES]
>
>* [Webex를 LaunchPoint 서비스로 추가](/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 설정 [흐름 작업](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md) 참여를 추적하려면
>* Webex 이벤트(클래식)를 사용하고 있는지 확인합니다.

먼저,에서 웨비나를 만듭니다. [Webex](https://www.webex.com/){target="_blank"}. Event in the Webex Event Center. Marketo only uses specific settings and fields for your integration, which we'll go through shortly. Other fields that you might want to configure for Webex are explained in the [Webex Event Center User Guide](https://www.cisco.com/c/dam/en/us/td/docs/collaboration/meeting_center/wbs298/wx_ec_host_ug.pdf){target="_blank"}.

>[!IMPORTANT]
>
>Marketo Engage은 Webex 이벤트(클래식)에서 만든 이벤트만 지원합니다. Marketo은 현재 Webex 이벤트(신규)에서 생성된 이벤트를 지원하지 않습니다.

## 기본 정보 {#basic-information}

* **이벤트 이름 -** 이 이름은 Marketo에서 볼 수 있습니다.
* **목록에 없는 확인란**

   * 다음을 수행하는 것이 좋습니다 **아님** 이벤트를 나열합니다. 이렇게 하면 모든 사용자가 Marketo 랜딩 페이지를 통해 등록할 수 있습니다. Marketo 이외의 메커니즘을 통해 등록한 사용자는 이벤트가 완료된 후 이벤트에 참석한 경우에만 Marketo에 표시됩니다.
   * 이벤트를 나열하도록 선택하면 이벤트 센터 웹 사이트를 방문하는 모든 사용자의 이벤트 목록 페이지에 표시됩니다.

* **등록 -** &quot;필수&quot;로 설정하려면 이 상자를 선택합니다. Marketo 양식/랜딩 페이지를 사용하여 Webex에 푸시될 등록 정보를 캡처합니다.
* **이벤트 암호**- (선택 사항) 이 필드를 사용하는 경우 확인 이메일에 포함해야 합니다!

![](assets/image2015-5-28-13-3a30-3a55.png)

## 날짜 및 시간 {#date-time}

* **시작일** - 시작 날짜를 입력합니다. 이 화면은 Marketo에서 볼 수 있습니다.

* **시작 시간** - 시작 시간을 입력합니다. 이 화면은 Marketo에서 볼 수 있습니다.

* **예상 기간** - 이벤트 기간을 지정합니다. 이 화면은 Marketo에서 볼 수 있습니다.

* **시간대** - 적용 가능한 시간대를 입력합니다. 이 화면은 Marketo에서 볼 수 있습니다.

![](assets/image2015-5-28-13-3a37-3a39.png)

## 오디오 전화 회의 설정 {#audio-conference-settings}

이러한 설정은 Webex에만 있습니다. 이 템플릿은 Marketo에서 사용하거나 볼 수 없지만 웨비나에 중요할 수 있으므로 다시 확인하십시오.

## 이벤트 설명 및 옵션  {#event-description-options}

다음 옵션은에서 사용하거나 Marketo에서 볼 수 있습니다. 다른 필드는 Webex에만 있습니다.

* **설명** - 설명을 입력합니다. Marketo에서는 볼 수 있지만 수정할 수 없습니다.
* **이벤트 후 설문 조사** - Marketo은 현재 Webex 사후 설문 조사에 대한 정보를 캡처할 수 없습니다.
* **대상 URL** - (선택 사항) 세션이 종료된 후 표시할 대상 URL 역할을 할 Marketo 랜딩 페이지의 URL을 입력할 수 있습니다.

![](assets/image2015-5-28-13-3a48-3a49.png)

## 참석자 및 등록 {#attendees-registration}

Marketo 이벤트를 사용하여 초대 목록, 등록 양식 및 기타 이메일을 제어합니다. Marketo에서는 다음을 포함한 다른 기능을 지원하지 않습니다.

* **최대 등록자 수** - 현재 **아님** Marketo-Webex 통합을 사용하여 지원됩니다.  등록자의 수동 승인은 Marketo의 승인 보류 중 진행 상태를 사용하여 사용할 수 있습니다.

* **등록 ID 필요** - 현재 Marketo-Webex 통합을 사용하여 지원됩니다. Marketo을 사용하여 이벤트에 대한 확인 이메일을 보낼 수 있습니다. 등록하면 이벤트를 입력하는 데 사용하는 고유한 URL이 수신됩니다.

  >[!TIP]
  >
  >확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL이 전송되면 이 토큰은 개인의 고유한 확인 URL로 자동으로 확인됩니다.
  >
  >확인 이메일을 다음으로 설정 **운영** 등록하고 구독을 취소할 수 있는 사람이 여전히 확인 정보를 받도록 합니다.

* **등록 암호** - (선택 사항) 현재 Marketo-Webex 통합을 사용하여 지원되지 않습니다.
* **승인 규칙** - 현재 Marketo-Webex 통합을 사용할 수 없습니다. 하지만 Marketo에서 스마트 캠페인을 사용하여 승인을 제어할 수 있습니다.

![](assets/image2015-5-28-14-3a4-3a41.png)

### 발표자 및 패널 {#presenters-panelists}

이 섹션에 구성된 정보는 Marketo에 전달되지 않습니다.

### 이메일 메시지 {#email-messages}

Marketo을 사용하여 등록자에게 이메일, 확인 이메일 등을 발송합니다. 이 섹션에서는 아무것도 구성할 필요가 없습니다. Webex 내에서 이메일 메시지 옵션을 비활성화(선택 취소)합니다.

![](assets/image2015-5-28-14-3a9-3a14.png)

>[!NOTE]
>
>Marketo-Webex 통합은 Webex에서 확인 이메일 전송을 지원할 수 없습니다. 확인 메일은 Marketo을 통해 전송되어야 합니다. 이벤트를 예약한 후에는 이벤트 정보를 Marketo 확인 이메일에 복사하고 이메일을 다음으로 설정하십시오. **운영**.

이제 Marketo에 뛰어들 준비가 되었습니다!

1. 만든 이벤트를 선택합니다. 를 엽니다. **이벤트 작업** 드롭다운. 선택 **이벤트 설정.**

   ![](assets/image2015-5-14-16-3a7-3a31.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 다음과 같아야 합니다. **웨비나**.

1. 아래 **이벤트 파트너**, 선택 **Webex**.

   ![](assets/image2015-1-30-13-3a58-3a2.png)

1. 아래 **로그인** Webex 로그인을 선택합니다.

   ![](assets/image2015-5-18-12-3a2-3a26.png)

1. 아래 **이벤트**&#x200B;새로 만든 Webex 이벤트를 선택합니다. 그런 다음 선택적 백업 페이지를 선택하고 **저장**.

   ![](assets/image2015-5-14-16-3a15-3a55.png)

1. Webex 이벤트에 대한 선택적 백업 페이지를 선택합니다. 승인된 Marketo 랜딩 페이지의 드롭다운에서 선택하거나 Marketo이 아닌 랜딩 페이지의 URL을 입력합니다.

   >[!TIP]
   >
   >멤버가 이벤트 시작 시간 전에 사용자 지정 이벤트 URL을 클릭하는 경우 특정 페이지로 이동하도록 백업 페이지를 설정합니다.

   >[!NOTE]
   >
   >Marketo이 보내는 필드는 이름, 성, 이메일 주소입니다.

   ![](assets/webex.png)

   >[!CAUTION]
   >
   >중첩된 이메일 프로그램을 사용하여 확인 이메일을 발송하지 마십시오. 위에 표시된 대로 이벤트 프로그램의 스마트 캠페인을 대신 사용합니다.

   >[!TIP]
   >
   >Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그렇게 오래 기다린 후에도 여전히 아무것도 표시되지 않으면 을(를) 선택합니다 **웨비나 공급자에서 새로 고침** 의 이벤트 작업 메뉴에서 **요약** 이벤트 탭

잘됐네! 이제 Webex 이벤트가 Marketo 이벤트와 동기화됩니다. 웨비나에 등록하는 사람은 새 상태가 &quot;등록됨&quot;으로 설정되면 프로그램 상태 변경 흐름 단계를 통해 웨비나 공급자에게 푸시됩니다. 다른 상태는 사용자를 밀어내지 않습니다. 또한 프로그램 상태 변경 흐름 단계 #1 및 이메일 전송 흐름 단계 를 #2 합니다.

## 일정 보기  {#viewing-the-schedule}

프로그램 일정 보기에서 이벤트의 달력 항목을 클릭합니다. 일정표는 화면 오른쪽에 있습니다!

![](assets/image2015-5-14-16-3a21-3a41.png)

>[!NOTE]
>
>이벤트 일정을 변경하려면 Webex에서 웨비나를 편집해야 합니다.

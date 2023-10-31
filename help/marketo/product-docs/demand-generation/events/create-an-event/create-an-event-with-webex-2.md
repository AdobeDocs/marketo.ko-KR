---
description: Webex - Marketo 문서 - 제품 설명서를 사용하여 이벤트 만들기
title: Webex를 사용하여 이벤트 만들기
hide: true
hidefromtoc: true
feature: Events
source-git-commit: 286e1b7b563be70e932206adec6f80b4877b7953
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 0%

---

# Webex를 사용하여 이벤트 만들기 {#create-an-event-with-webex}

>[!PREREQUISITES]
>
>* [Webex를 LaunchPoint 서비스로 추가](/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md)
>* [새 이벤트 프로그램 만들기](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* 적절한 설정 [흐름 작업](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md) 참여를 추적하려면

## 웨비나 예약 {#schedule-a-webinar}

먼저,에서 웨비나를 만듭니다. [Webex](https://www.webex.com/){target="_blank"}. Marketo Engage only uses specific settings and fields for your integration, which we'll go through shortly. For additional information, please see the [Webex Webinars Help Documentation](https://help.webex.com/en-us/landing/ld-7srxjs-WebexWebinars/Webex-Webinars){target="_blank"}.

>[!NOTE]
>
>Webex에서 기본 설정을 선택했지만 Marketo Engage에서 웨비나 이름, 시작/종료 날짜 및 시간, 시간대 및 설명 정보만 볼 수 있습니다.

### 기본 정보 {#basic-information}

![](assets/create-an-event-with-webex-1.png)

* **주제**: 이벤트 이름이며 Marketo에서 볼 수 있습니다.
* **날짜 및 시간**: 시작/종료 날짜, 시작/종료 시간, 기간 및 시간대는 모두 Marketo에서 볼 수 있습니다.
* **최대 참석자 수**: 지원되는 Webex 기능은 최대 참석자 수에 따라 결정됩니다.
* **참석자를 위한 웹캐스트 보기**: 웨비나가 모든 참석자에게 라이브로 스트리밍되도록 하려면 이 옵션을 선택합니다.
* **토론자**: 웨비나에서 특정 사람을 패널리스트로 초대합니다.
* **웨비나 주제**: 패널 구성원에게 전송된 이메일 초대에 컨텍스트를 제공하려면 이 항목을 채웁니다.

### 보안 {#security}

![](assets/create-an-event-with-webex-2.png)

* **웨비나 암호**: (선택 사항) 이 필드를 사용하는 경우 확인 이메일에 포함해야 합니다.
* **패널 암호**: (선택 사항) 이 필드를 사용하는 경우 웨비나 의제에 포함해야 합니다.
* **계정 필요**: 참석자를 Webex 계정이 있는 사람으로만 제한합니다.

### 오디오 연결 옵션 {#audio-connection-options}

![](assets/create-an-event-with-webex-3.png)

* **오디오 연결 유형**: 웨비나 참여자가 웨비나의 오디오 부분에 결합하는 방법을 선택합니다.
* **시작 및 종료 톤**: 웨비나에 들어가거나 종료할 때 사용자가 원하는 사운드를 선택합니다(전화 오디오 연결 필요).
* **패널 음소거**: 원하는 패널 음소거 설정을 선택합니다.

### 고급 옵션 {#advanced-options}

![](assets/create-an-event-with-webex-4.png)

* **자동녹음**: 웨비나를 자동으로 기록하려면 이 옵션을 선택합니다.
* **연습 세션**: 웨비나가 시작될 때 연습 세션이 시작되도록 하려면 이 옵션을 선택합니다.
* **브레이크아웃 세션**: 브레이크아웃 세션을 사용하면 웨비나가 시작되기 전에 패널 및 참석자를 미리 할당하거나 웨비나 동안 패널 및 참석자가 참여하도록 할 수 있습니다.
* **웨비나 시리즈**: 웨비나 시리즈에 추가하면 공개 여부에 관계없이 웨비나를 볼 수 있습니다.
* **등록**: 참석자가 참석하기 전에 등록하고 호스트 승인을 받아야 합니다.
* **이메일 미리 알림**: 웨비나가 시작되기 15분에서 최대 2일 전까지 이메일 미리 알림을 선택합니다.
* **웨비나 옵션**: 웨비나 참여자가 사용할 수 있는 기능을 결정합니다.
* **참가자 권한**: 참가자 권한은 웨비나 참가자가 사용할 수 있는 작업을 결정합니다.

>[!NOTE]
>
>Marketo-Webex 통합은 Webex에서 확인 이메일 전송을 지원할 수 없습니다. 확인 메일은 Marketo을 통해 전송되어야 합니다. 이벤트를 예약한 후에는 이벤트 정보를 Marketo 확인 이메일에 복사하고 이메일을 다음으로 설정하십시오. _운영_.

이제 Marketo Engage에 뛰어들 준비가 되었습니다!

## Marketo Engage과 이벤트 동기화 {#sync-your-event-with-marketo-engage}

1. Marketo에서 만든 이벤트 프로그램을 찾아 선택합니다. 다음에서 **이벤트 작업** 드롭다운, 선택 **이벤트 설정**.

   ![](assets/create-an-event-with-webex-5.png)

   >[!NOTE]
   >
   >선택한 이벤트의 채널 유형은 다음과 같아야 합니다. **웨비나**.

1. 다음에서 **이벤트 파트너** 드롭다운, 선택 **Webex 웨비나**.

   ![](assets/create-an-event-with-webex-6.png)

1. 다음에서 **로그인** 드롭다운에서 Webex 로그인을 선택합니다.

   ![](assets/create-an-event-with-webex-7.png)

1. 다음에서 **이벤트** 드롭다운에서 Webex 이벤트를 선택합니다.

   ![](assets/create-an-event-with-webex-8.png)

1. 웨비나 세부 정보가 채워집니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/create-an-event-with-webex-9.png)

이제 Webex 이벤트가 Marketo 이벤트와 동기화됩니다. 웨비나에 등록하는 사람은 를 통해 웨비나 공급자에게 푸시됩니다. _프로그램 상태 변경_ 새 상태가 &quot;등록됨&quot;으로 설정된 경우 흐름 단계. 다른 상태는 사용자를 밀어내지 않습니다. 다음을 확인하십시오. _프로그램 상태 변경_ 플로우 단계 #1 및 _이메일 보내기_ 흐름 단계 #2.

## 참고할 사항 {#things-to-note}

* 중첩된 이메일 프로그램 을 사용하여 확인 이메일을 발송하지 마십시오. 대신 이벤트 프로그램의 스마트 캠페인을 사용하십시오.

* Marketo에 데이터가 표시되는 데 최대 48시간이 걸릴 수 있습니다. 그렇게 오래 기다린 후에도 여전히 아무것도 표시되지 않으면 **웨비나 공급자에서 새로 고침** 다음에서 **이벤트 작업** 드롭다운 **요약** 이벤트 프로그램 탭

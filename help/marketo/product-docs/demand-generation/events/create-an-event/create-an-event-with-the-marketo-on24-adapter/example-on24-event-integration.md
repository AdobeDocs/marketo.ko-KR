---
unique-page-id: 10096679
description: ON24 이벤트 통합 예 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 통합 예
exl-id: 9d34d1bf-1ff8-4b26-906e-4a6bb9d5f3f6
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '387'
ht-degree: 0%

---

# ON24 이벤트 통합 예 {#example-on-event-integration}

다음은 ON24 웨비나에 대한 캠페인을 포함한 샘플 이벤트입니다. 이벤트를 빌드할 때 캠페인을 실행하기 전에 먼저 테스트하십시오.

## 마케팅 활동에서 새 이벤트 만들기 {#create-a-new-event-in-marketing-activities}

1. 선택 **새로 만들기** > **새 프로그램**.

   ![](assets/image2015-12-22-15-3a35-3a15.png)

1. 선택 **캠페인 폴더** 이 이벤트가 발생할 위치.

   ![](assets/image2015-12-22-15-3a39-3a51.png)

1. 을(를) 입력합니다. **이름** 를 반환합니다.

   ![](assets/image2015-12-22-15-3a43-3a4.png)

1. 선택 **이벤트** 로서의 **프로그램 유형**.

   ![](assets/image2015-12-22-15-3a44-3a41.png)

1. 선택 **웨비나** 로서의 **채널** 를 반환합니다.

   ![](assets/image2015-12-22-15-3a46-3a34.png)

1. Click **Create**.

   ![](assets/image2015-12-22-15-3a48-3a20.png)

## 초대(배치 캠페인)  {#invite-batch-campaign}

* **Smart List** - 이벤트에 초대할 대상을 정의합니다.
* **흐름**

   * 이메일 보내기 - 로컬 자산 이메일인 경우 다음과 같은 이름 지정 규칙이 있습니다. EventName.EmailName입니다. 글로벌 이메일을 사용할 수도 있습니다.
   * 진행 상태 변경 - 웨비나 > 초대됨으로 설정합니다.

* **예약** - 초대장 전송 날짜를 설정합니다.

## 등록/확인(트리거 캠페인) {#registration-confirmation-trigger-campaign}

* **Smart List**

   * 캠페인을 트리거하는 기준 **양식 채우기**. 를 사용하여 양식이 상주하는 랜딩 페이지를 포함해야 합니다 **제한 추가**&#x200B;특히 양식을 여러 랜딩 페이지에서 사용하는 경우 발생합니다.

>[!CAUTION]
>
>Marketo에 등록 데이터를 푸시하려면 Marketo 양식을 사용하여 이벤트를 위한 사람을 등록하거나, 적합한 API 통합을 통해 Marketo 이외의 양식을 등록해야 합니다. 이는 이벤트 파트너 통합의 성공에 중요합니다. **참고**: Marketo이 아닌 랜딩 페이지에서 Marketo 양식을 사용하는 경우 트리거가 다음과 같습니다 **양식 채우기** ( 양식 이름 사용)

![](assets/image2015-12-22-15-3a50-3a22.png)

* **흐름**

   * **진행 상태 변경** - 웨비나 > 등록됨으로 설정합니다. **주의**: 이 흐름 단계는 하위 캠페인을 설정할 때 필요합니다. 개인의 진행 상태가 **등록**&#x200B;에서 Marketo은 등록 정보를 ON24로 푸시합니다.

   * **이메일 보내기** - 확인 이메일(으로 설정됨) **운영** 이렇게 하면, 등록한 가입 해지된 사람들이 여전히 그 돈을 받게 됩니다.

![](assets/image2015-12-22-15-3a52-3a9.png)

**참고**: 등록 오류가 표시된 사람이 반환되면 전자 메일 확인이 수신되지 않습니다.

## 미리 알림(배치 캠페인) {#reminder-batch-campaign}

* **Smart List** - 을 사용하여 필터링 **프로그램 멤버** 상태를 로 설정합니다. **등록**.

* **흐름** - 전자 메일 보내기(미리 알림 전자 메일).

**참고**: 유사한 캠페인을 사용하여 *different* 초대되었지만 아직 등록하지 않은 사람에게 후속 이메일을 보내주십시오.

## 후속 캠페인(배치 또는 트리거 캠페인) {#follow-up-campaign-batch-or-trigger-campaign}

* **Smart List** - 프로그램 상태 변경 사항을 기반으로 트리거합니다.

![](assets/image2015-12-22-15-3a57-3a25.png)

* **흐름** - 이메일 전송. 프로그램 상태에 따라 다양한 이메일을 보내려면 선택 사항을 사용하십시오.

![](assets/ten.png)

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}

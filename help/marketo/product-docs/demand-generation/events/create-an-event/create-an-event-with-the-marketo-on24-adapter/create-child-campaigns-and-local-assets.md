---
unique-page-id: 10096675
description: 하위 캠페인 및 로컬 자산 만들기 - Marketo 문서 - 제품 설명서
title: 하위 캠페인 및 로컬 자산 만들기
exl-id: 272105e1-43d6-455c-a533-aae65e859384
source-git-commit: 40cfdddac66b7cd90e33bedf11888a7c5e3b38c9
workflow-type: tm+mt
source-wordcount: '688'
ht-degree: 1%

---

# 하위 캠페인 및 로컬 자산 만들기 {#create-child-campaigns-and-local-assets}

>[!IMPORTANT]
>
>2022년 8월부터 ON24는 더 이상 새로운 Marketo 통합을 지원하지 않습니다. 이 문서의 정보는 기존 사용자에게만 적용됩니다.

Design Studio를 사용하여 하위 캠페인 및 로컬 자산을 만듭니다.

## 랜딩 페이지 및 양식 {#landing-page-and-form}

사람들이 ON24에 제대로 등록되도록 하려면 Marketo 양식에 다음 필드를 포함해야 합니다.

* 이름
* 성
* 이메일 주소

다음 필드를 ON24에 푸시할 수도 있습니다.

* 회사명
* 직위

등록 캠페인에 적절한 흐름 단계가 추가되면 사람들이 ON24로 푸시되고 등록됨으로 표시됩니다. 양식에 다른 필드를 추가할 수 있으며 이 정보는 개인 세부 정보 레코드의 일부로서 Marketo에 캡처됩니다.

>[!CAUTION]
>
>성공적인 통합을 위해 Marketo 양식을 사용하여 이벤트에 모집단을 등록하거나 Marketo에 등록 데이터를 푸시하려면 적절한 API 통합이 있는 비Marketo 양식을 사용해야 합니다.

## 이메일 및 URL 토큰 {#emails-and-url-tokens}

Marketo을 사용하여 초대, 확인, 후속 조치 및 감사 이메일을 만듭니다.

## Marketo 확인 이메일 및 URL 토큰 {#marketo-confirmation-email-and-url-token}

Marketo을 사용하여 이벤트에 대한 확인 이메일을 전송합니다. 등록하면 이벤트를 입력하는 데 사용할 고유 URL을 받게 됩니다.

>[!NOTE]
>
>확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL을 전송하면 이 토큰이 사람의 고유 확인 URL로 자동으로 확인됩니다.
>
>확인 이메일 유형을 로 설정합니다. **운영** 등록 대상자가 가입 해지 상태인 경우에도 확인 정보를 수신하도록 하기 위한 것입니다.

>[!TIP]
>
>확인, 미리 알림 또는 후속 이메일을 보내도록 ON24를 구성할 수 있습니다. 자세한 내용은 [ON24 도움말 사이트](https://www.on24.com/live-webcast-elite/) 추가 정보.

## 등록 하위 캠페인 요구 사항 {#registration-child-campaign-requirements}

이벤트에는 하나 이상의 하위 캠페인이 포함되어 있으며, 이러한 캠페인이 모두 함께 작동하여 프로그램 상태를 통해 사람을 이동하며 이벤트 성과를 추적할 수 있습니다.

하위 캠페인의 예로는 초대 캠페인, 등록 캠페인 및 후속 캠페인이 있습니다.

>[!CAUTION]
>
>어댑터가 작업을 수행하려면 등록 캠페인을 만들어야 합니다. 이 캠페인은 양식을 채우는 사람이 트리거해야 하며 첫 번째 단계는 개인의 프로그램 상태를 **등록**. 그러면 캠페인이 확인 이메일을 보냅니다. 자세한 내용은 이 문서의 나머지 부분 을 참조하십시오.

**등록/확인(트리거 캠페인)**

* Smart List
* 트리거 기준 **양식 채우기**. 를 사용하여 양식이 상주하는 랜딩 페이지를 포함해야 합니다 **제한 추가**&#x200B;특히 여러 랜딩 페이지에서 동일한 양식을 사용할 경우,

>[!CAUTION]
>
>Marketo에 등록 데이터를 푸시하려면 Marketo 양식을 사용하여 사용자를 이벤트에 등록하거나 Marketo이 아닌 양식을 적절한 API 통합에 사용해야 합니다. 이는 이벤트 파트너 통합의 성공에 매우 중요합니다.

>[!NOTE]
>
>Marketo이 아닌 랜딩 페이지에서 Marketo 양식을 사용하는 경우 트리거가 다음과 같습니다 **양식 채우기** ( 양식 이름 사용)

![](assets/image2015-12-22-15-3a20-3a51.png)

**흐름**

* **프로그램 상태 변경** - 웨비나 -> 등록됨으로 설정합니다.

이 흐름 단계는 하위 캠페인을 설정할 때 첫 번째 흐름 단계로 필요합니다. 개인의 프로그램 상태가 등록됨으로 변경되면 Marketo은 등록 정보를 ON24로 푸시합니다. 다른 상태는 사람을 밀어주지 않습니다.

* **이메일 보내기** - 확인 이메일. 이 전자 메일을 로 설정 **운영** 그래서 등록을 취소한 사람들이 여전히 그 돈을 받도록 하여라.

다음 **이메일 보내기** 흐름 단계 MUST는 두 번째 단계여야 합니다. 확인 전자 메일에는 `{{member.webinar url}}`: ON24에서 Marketo으로 다시 전송된 정보로 채워집니다.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>Marketo에서 작업이 수행되는 순서 때문에 이러한 흐름 단계의 순서가 중요합니다. 다음 **프로그램 상태 변경** 단계는 사용자를 ON24로 보내 등록하며 고유 URL이 생성됩니다. 그런 다음 를 사용하여 이 고유 URL이 포함된 확인 이메일을 보낼 수 있습니다 `{{member.webinar URL}}` 토큰.
>
>등록 오류가 표시된 사람이 반환되면 전자 메일 확인 메시지를 받지 않습니다.

다음 단계는 다음과 같습니다. [ON24 이벤트 통합 테스트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md).

>[!MORELIKETHIS]
>
>* [Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
>* [웨비나 프로그램 상태 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md)


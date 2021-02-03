---
unique-page-id: 10096675
description: 하위 캠페인 및 로컬 자산 만들기 - 마케팅 문서 - 제품 설명서
title: 하위 캠페인 및 로컬 자산 만들기
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '667'
ht-degree: 0%

---


# 하위 캠페인 만들기 및 로컬 자산 {#create-child-campaigns-and-local-assets}

Design Studio를 사용하여 하위 캠페인과 로컬 에셋을 만듭니다.

## 랜딩 페이지 및 양식 {#landing-page-and-form}

사람들이 ON24에 제대로 등록되도록 하려면 마케팅 양식(Marketing To Form)에 다음 필드를 포함해야 합니다.

* 이름
* 성
* 이메일 주소

다음 필드를 ON24로 푸시할 수도 있습니다.

* 회사 이름
* 직함

적절한 흐름 단계가 등록 캠페인에 추가되면 사람들이 ON24로 푸시되어 등록으로 표시됩니다. 양식에 다른 필드를 추가할 수 있으며 해당 정보는 개인 세부 정보 레코드의 일부로서 Marketing에서 캡처됩니다.

>[!CAUTION]
>
>성공적인 통합을 위해 마케터 양식을 사용하여 이벤트에 대한 사용자를 등록하거나, 적절한 API 통합이 있는 비마케팅 양식을 사용하여 등록 데이터를 Marketing에 푸시해야 합니다.

## 이메일 및 URL 토큰 {#emails-and-url-tokens}

Marketing To를 사용하여 초대, 확인, 후속 조치 및 감사 이메일을 만듭니다.

## 마케팅 확인 이메일 및 URL 토큰 {#marketo-confirmation-email-and-url-token}

Marketing을 사용하여 이벤트에 대한 확인 이메일을 보냅니다. 등록하면 이벤트에 입력할 때 사용할 고유한 URL을 받게 됩니다.

>[!NOTE]
>
>확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오.`{{member.webinar url}}`. 확인 URL을 전송하면 이 토큰은 사용자의 고유 확인 URL로 자동 확인됩니다.
>
>확인 전자 메일 유형을 **운영**&#x200B;으로 설정하여 등록하는 사람이 구독을 취소하더라도 확인 정보를 수신하도록 합니다.

>[!TIP]
>
>확인, 미리 알림 또는 후속 이메일을 전송하도록 ON24를 구성할 수 있습니다. 자세한 내용은 [ON24 도움말 사이트](https://webcastelitehelp.on24.com)를 참조하십시오.

## 등록 하위 캠페인 요구 사항 {#registration-child-campaign-requirements}

이벤트에는 하나 이상의 하위 캠페인이 포함되어 있습니다. 이 모든 캠페인은 프로그램 상태를 통해 사람들을 이동시키고 이벤트 성과를 추적할 수 있습니다.

하위 캠페인의 예는 초대 캠페인, 등록 캠페인 및 후속 캠페인입니다.

>[!CAUTION]
>
>어댑터가 작업을 수행하려면 등록 캠페인을 만들어야 합니다. 이 캠페인은 양식을 채우는 사람에 의해 트리거되어야 하며 첫 번째 단계는 프로그램 상태를 **등록됨**&#x200B;으로 변경해야 합니다. 그러면 캠페인이 확인 이메일을 보냅니다. 자세한 내용은 이 문서의 나머지 부분을 참조하십시오.

**등록/확인(트리거 캠페인)**

* 스마트 목록
* **양식 채우기**&#x200B;를 기반으로 트리거합니다. 특히 동일한 양식이 여러 랜딩 페이지에서 사용되는 경우 **제한 추가**&#x200B;를 사용하여 양식이 유지되는 랜딩 페이지를 포함해야 합니다.

>[!CAUTION]
>
>사용자 등록 데이터를 Marketing To로 푸시하려면 Marketing 양식을 사용하여 이벤트에 등록하거나, 적절한 API 통합이 있는 비 Marketing 양식을 사용해야 합니다. 이는 이벤트 파트너 통합의 성공에 매우 중요합니다.

>[!NOTE]
>
>Marketing이 아닌 랜딩 페이지에서 Marketing To 양식을 사용하는 경우 트리거는 양식 이름으로 **양식 채우기**&#x200B;가 됩니다.

![](assets/image2015-12-22-15-3a20-3a51.png)

**흐름**

* **프로그램 상태 변경**  - 웨비나 -> 등록됨으로 설정합니다.

이 흐름 단계는 하위 캠페인을 설정할 때 첫 번째 흐름 단계로 필요합니다. 개인의 프로그램 상태가 등록됨으로 변경되면 Marketing은 등록 정보를 ON24로 푸시합니다. 다른 신분은 그 사람을 밀어붙일 수 없다.

* **이메일**  보내기 - 확인 이메일. 등록한 구독 취소 사용자가 계속 받을 수 있도록 이 이메일을 **운영**&#x200B;으로 설정합니다.

**이메일 보내기** 흐름 단계는 두 번째 단계여야 합니다. 확인 이메일에는 ON24에서 Marketing To로 다시 전송된 정보로 채워지는 `{{member.webinar url}}`이 포함되어 있습니다.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>Marketing To에서 작업이 수행되는 순서 때문에 이러한 흐름 단계의 순서가 중요합니다. **프로그램 상태 변경** 단계는 사용자를 ON24로 전송하여 등록하면 고유한 URL이 생성됩니다. 그런 다음 `{{member.webinar URL}}` 토큰을 사용하여 이 고유 URL을 포함하는 확인 이메일을 보낼 수 있습니다.
>
>등록 오류가 발생하면 확인 이메일을 받지 못합니다.

다음 단계는 [ON24 이벤트 통합 테스트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md)입니다.

>[!MORELIKETHIS]
>
>* [Marketing ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
>* [웨비나 프로그램 상태 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md)


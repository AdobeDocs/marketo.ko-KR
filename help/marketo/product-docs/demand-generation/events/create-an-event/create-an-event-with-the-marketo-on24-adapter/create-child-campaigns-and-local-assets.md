---
unique-page-id: 10096675
description: 하위 캠페인 만들기 및 로컬 Assets - Marketo 문서 - 제품 설명서
title: 하위 캠페인 및 로컬 자산 만들기
exl-id: 272105e1-43d6-455c-a533-aae65e859384
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '650'
ht-degree: 3%

---

# 하위 캠페인 및 로컬 자산 만들기 {#create-child-campaigns-and-local-assets}

Design Studio를 사용하여 하위 캠페인 및 로컬 에셋을 만듭니다.

## 랜딩 페이지 및 양식 {#landing-page-and-form}

사람들이 ON24에 제대로 등록되었는지 확인하려면 Marketo 양식에 다음 필드가 포함되어야 합니다.

* 이름
* 성
* 이메일 주소

다음 필드를 ON24에 푸시할 수도 있습니다.

* 회사 이름
* 직위

등록 캠페인에 적절한 흐름 단계가 추가되면 사람들이 ON24로 푸시되고 등록됨으로 표시됩니다. 양식에 다른 필드를 추가할 수 있으며 정보는 개인 세부 정보 레코드의 일부로 Marketo에 캡처됩니다.

>[!CAUTION]
>
>성공적인 통합을 위해서는 Marketo 양식을 사용하여 이벤트에 대한 직원을 등록하거나 적절한 API 통합이 포함된 Marketo이 아닌 양식을 사용하여 등록 데이터를 Marketo에 푸시해야 합니다.

## 이메일 및 URL 토큰 {#emails-and-url-tokens}

Marketo을 사용하여 초대, 확인, 후속 조치 및 감사 이메일을 만듭니다.

## Marketo 확인 이메일 및 URL 토큰 {#marketo-confirmation-email-and-url-token}

Marketo을 사용하여 이벤트에 대한 확인 이메일을 보냅니다. 개인이 등록할 때 이벤트를 입력하는 데 사용할 고유 URL을 수신하게 됩니다.

>[!NOTE]
>
>확인 전자 메일을 이 고유 URL로 채우려면 전자 메일에 `{{member.webinar url}}` 토큰을 사용하십시오. 확인 URL을 전송하면 이 토큰은 개인의 고유 확인 URL로 자동으로 확인됩니다.
>
>확인 전자 메일의 형식을 **작동**(으)로 설정하여 등록한 사람이 구독을 취소하더라도 확인 정보를 받도록 합니다.

>[!TIP]
>
>확인, 미리 알림 또는 후속 이메일을 보내도록 ON24를 구성할 수 있습니다. 자세한 내용은 [ON24 도움말 사이트](https://support.on24.com/hc/en-us/categories/26127314569115-Webcast-Elite){target="_blank"}를 참조하십시오.

## 등록 하위 캠페인 요구 사항 {#registration-child-campaign-requirements}

이벤트에는 프로그램 상태를 통해 사람들을 이동하고 이벤트의 성과를 추적할 수 있도록 모두 함께 작동하는 하나 이상의 하위 캠페인이 포함되어 있습니다.

어린이 캠페인의 예로는 초대 캠페인, 등록 캠페인 및 후속 캠페인이 있습니다.

>[!CAUTION]
>
>어댑터가 작업을 수행하려면 등록 캠페인을 만들어야 합니다. 이 캠페인은 양식을 작성하는 사람에 의해 트리거되어야 하며 첫 번째 단계에서는 해당 사람의 프로그램 상태를 **등록됨**(으)로 변경해야 합니다. 그러면 캠페인에서 확인 이메일을 보냅니다. 자세한 내용은 이 문서의 나머지 부분을 참조하십시오.

**등록/확인(캠페인 트리거)**

* 스마트 목록
* **양식 작성**&#x200B;을 기반으로 트리거합니다. **제약 조건 추가**&#x200B;를 사용하여 양식이 있는 랜딩 페이지를 포함해야 합니다. 특히 동일한 양식을 여러 랜딩 페이지에서 사용하는 경우 더 그렇습니다.

>[!CAUTION]
>
>이벤트에 대한 직원을 등록하려면 Marketo 양식을 사용하고, 등록 데이터를 Marketo에 푸시하려면 적절한 API 통합이 포함된 비 Marketo 양식을 사용해야 합니다. 이는 이벤트 파트너 통합의 성공에 매우 중요합니다.

>[!NOTE]
>
>Marketo이 아닌 랜딩 페이지에서 Marketo 양식을 사용하는 경우 트리거는 **[!UICONTROL Fills out Form]**&#x200B;을(를) 사용하여 [!UICONTROL Form Name]이(가) 됩니다.

![](assets/image2015-12-22-15-3a20-3a51.png)

**흐름**

* **[!UICONTROL Change Program Status]** - 웨비나 -> 등록됨으로 설정합니다.

이 흐름 단계는 하위 캠페인을 설정할 때 첫 번째 흐름 단계로 필요합니다. 개인의 프로그램 상태가 등록됨으로 변경되면 Marketo에서 등록 정보를 ON24로 푸시합니다. 다른 상태는 사용자를 밀어내지 않습니다.

* **[!UICONTROL Send Email]** - 확인 전자 메일. 등록된 구독 취소자가 계속 받을 수 있도록 이 전자 메일을 **Operational**(으)로 설정하십시오.

**[!UICONTROL Send Email]** 흐름 단계는 두 번째 단계여야 합니다. 확인 이메일에는 ON24에서 Marketo으로 다시 전송된 정보로 채워진 `{{member.webinar url}}`이(가) 포함되어 있습니다.

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>Marketo에서 작업이 수행되는 순서 때문에 이러한 흐름 단계의 순서가 중요합니다. **[!UICONTROL Change Program Status]** 단계에서 ON24로 사람을 보내 등록하면 고유한 URL이 생성됩니다. 그런 다음 `{{member.webinar URL}}` 토큰을 사용하여 이 고유한 URL이 포함된 확인 전자 메일을 보낼 수 있습니다.
>
>등록 오류가 있는 사람이 반환되면 이메일 확인을 받지 못합니다.

다음 단계는 [ON24 이벤트 통합을 테스트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target="_blank"}하는 것입니다.

>[!MORELIKETHIS]
>
>* [Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target="_blank"}
>* [웨비나 프로그램 상태 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target="_blank"}

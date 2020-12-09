---
unique-page-id: 10096675
description: 하위 캠페인 및 로컬 자산 만들기 - 마케팅 문서 - 제품 설명서
title: 하위 캠페인 및 로컬 자산 만들기
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '673'
ht-degree: 0%

---


# 하위 캠페인 및 로컬 자산 만들기 {#create-child-campaigns-and-local-assets}

Design Studio를 사용하여 하위 캠페인과 로컬 자산을 만듭니다.

## 랜딩 페이지 및 양식 {#landing-page-and-form}

사람들이 ON24에 제대로 등록되었는지 확인하려면 Marketing Cloud 양식에 다음 필드를 포함해야 합니다.

* 이름
* 성
* 이메일 주소

다음 필드를 ON24로 푸시할 수도 있습니다.

* 회사 이름
* 직함

올바른 흐름 단계가 등록 캠페인에 추가되면 사람들이 ON24로 푸시되고 등록으로 표시됩니다. 양식에 다른 필드를 추가할 수 있으며 해당 정보는 개인 세부 정보 레코드의 일부로서 Marketing To에서 캡처됩니다.

>[!CAUTION]
>
>성공적인 통합을 위해 Marketing 양식을 사용하여 이벤트에 대한 사용자를 등록하거나, 적절한 API 통합이 있는 비 Marketing 양식을 사용하여 등록 데이터를 Marketing To로 푸시해야 합니다.

## 이메일 및 URL 토큰 {#emails-and-url-tokens}

Marketing을 사용하여 초대, 확인, 후속 조치 및 감사 이메일을 만듭니다.

## 마케팅 확인 이메일 및 URL 토큰 {#marketo-confirmation-email-and-url-token}

Marketing을 사용하여 이벤트에 대한 확인 이메일을 보냅니다. 등록하면 이벤트에 입장할 때 사용할 고유한 URL을 받게 됩니다.

>[!NOTE]
>
>**미리 알림**
>
>확인 이메일을 이 고유 URL로 채우려면 이메일에 다음 토큰을 사용하십시오. `{{member.webinar url}}`. 확인 URL을 전송하면 이 토큰은 사용자의 고유한 확인 URL로 자동 확인됩니다.
>
>확인 이메일의 유형을 **운영** 계정으로 설정하여 등록한 사람이 구독 취소 상태에서도 확인 정보를 받을 수 있도록 합니다.

>[!TIP]
>
>확인, 미리 알림 또는 후속 이메일을 보내도록 ON24를 구성할 수 있습니다. 자세한 내용은 [ON24 도움말](http://webcastelitehelp.on24.com) 사이트를 참조하십시오.

## 등록 하위 캠페인 요구 사항 {#registration-child-campaign-requirements}

이벤트에는 하나 이상의 하위 캠페인이 포함되어 있습니다. 이 모든 캠페인은 프로그램 상태를 통해 사람들을 이동시키고 이벤트 성과를 추적할 수 있습니다.

하위 캠페인의 예는 초대 캠페인, 등록 캠페인 및 후속 캠페인입니다.

>[!CAUTION]
>
>어댑터가 작업을 수행하려면 등록 캠페인을 만들어야 합니다. 이 캠페인은 양식을 채우는 사람이 트리거해야 하며 첫 번째 단계는 개인의 프로그램 상태를 **등록으로 변경해야 합니다**. 그러면 캠페인이 확인 이메일을 보냅니다. 자세한 내용은 이 문서의 나머지 부분을 참조하십시오.

**등록/확인(트리거 캠페인)**

* 스마트 목록
* 양식 채우기 **를 기반으로 트리거합니다**. 특히 여러 랜딩 페이지에서 동일한 양식을 사용하는 경우, 제한 **추가**&#x200B;기능을 사용하여 양식에서 살아 있는 랜딩 페이지를 포함해야 합니다.

>[!CAUTION]
>
>Marketing To 양식을 사용하여 이벤트에 대한 사용자를 등록하거나, 적절한 API 통합을 통해 비 Marketing 양식을 사용하여 등록 데이터를 Marketing To로 푸시해야 합니다. 이는 이벤트 파트너 통합의 성공에 매우 중요합니다.

>[!NOTE]
>
>Marketing이 아닌 랜딩 페이지에서 Marketing To 양식을 사용하는 경우, 트리거가 양식 **이름으로 양식** 채우기 기능을 사용하게 됩니다.

![](assets/image2015-12-22-15-3a20-3a51.png)

**흐름**

* **프로그램 상태 변경** - 웨비나 -> 등록됨으로 설정합니다.

이 흐름 단계는 하위 캠페인을 설정할 때 첫 번째 흐름 단계로 필요합니다. 개인의 프로그램 상태가 [등록됨]으로 변경되면 Marketing에서 등록 정보를 ON24로 푸시합니다. 다른 신분은 그 사람을 밀어주지 않는다.

* **이메일** 보내기 - 확인 이메일. 등록된 구독되지 않은 사람들이 계속 **수신하도록 이** 이메일을 작동 방식으로 설정합니다.

이메일 **보내기** 흐름 단계는 두 번째 단계여야 합니다. 확인 이메일에는 ON24에서 Marketing To로 다시 전송된 정보로 채워지는 정보가 포함되어 있습니다. `{{member.webinar url}}`

![](assets/image2015-12-22-15-3a29-3a50.png)

>[!NOTE]
>
>Marketing에서 작업이 수행되는 순서대로 인해 이러한 흐름 단계의 순서가 중요합니다. 프로그램 상태 **변경** 단계는 등록하도록 사람을 ON24로 전송하며 고유한 URL이 생성됩니다. 그런 다음 토큰을 사용하여 이 고유 URL이 포함된 확인 이메일을 보낼 수 `{{member.webinar URL}}` 있습니다.
>
>등록 오류가 표시된 사람은 이메일 확인을 받지 않습니다.

다음 단계는 ON24 이벤트 통합을 [테스트하는 것입니다](test-your-on24-event-integration.md).

>[!MORELIKETHIS]
>
>* [Marketing ON24 어댑터 이벤트 이해](understanding-marketo-on24-adapter-events.md)
>* [ON24 이벤트 통합 예](example-on24-event-integration.md)
>* [웨비나 프로그램 상태 이해](understanding-webinar-program-statuses.md)
>* [ON24 이벤트 통합 테스트](test-your-on24-event-integration.md)

>




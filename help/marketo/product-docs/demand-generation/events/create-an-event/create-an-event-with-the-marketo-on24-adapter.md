---
unique-page-id: 10096656
description: Marketing ON24 어댑터 - Marketing To Docs - 제품 설명서로 이벤트 만들기
title: Marketing ON24 어댑터로 이벤트 만들기
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 0%

---


# Marketing ON24 어댑터 {#create-an-event-with-the-marketo-on-adapter}로 이벤트 만들기

## {#before-you-begin} 시작 전

Marketing에서 이벤트를 만들기 위한 기본 블록과 권장 순서에 익숙해야 합니다. 다음 Marketing To 개념에 대한 작업 지식도 가지고 있어야 합니다.

* [Marketing ](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md) To Programas와 Events의 차이점
* [채널](../../../../product-docs/administration/tags/create-a-program-channel.md)
* [로컬 에셋](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md)
* [하위 ](https://docs.marketo.com/x/IRCa) 캠페인 및  [프로그램 상태](../../../../product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md)

>[!NOTE]
>
>Marketing API에 대한 자세한 내용은 [Marketing API 설명서](http://developers.marketo.com/documentation/rest/)를 참조하십시오.

## 사전 요구 사항 {#prerequisites}

Marketing ON24 통합을 사용하려면 다음이 필요합니다.

* **ON24 웹 캐스트**  구독 - 현재 구독이 없는 경우 ON24에 직접 문의하십시오. **참고**:ON24 Hosted Edition이 필요합니다. ON24 이벤트 관리는 필요하지 않습니다.

* **ON24에 대한 관리자 권한**  - 이 커넥터를 사용하고 ON24 시스템에서 손님을 만들려면 이 커넥터를 제공해야 합니다.
* **ON24 연결 자격**  증명 - 통합을 사용하려면 Marketing에 이 정보를 입력해야 합니다.사용자 이름, 암호, 클라이언트 ID 및 클라이언트 키. 자격 증명에 대한 도움이 필요한 경우 ON24 계정 관리자 또는 ON24 지원에 문의하십시오.
* **등록 양식**  - 등록 데이터와 등록자 정보가 Marketing To로 전달되도록 적절한 API와 함께 Marketing To 양식 또는 비 Marketing To 양식을 사용합니다.
* **등록 하위 캠페인 - ** 이벤트 파트너 통합이 작동하려면 마케팅 이벤트에서 등록 하위 캠페인을 만들고 제대로 구성해야 합니다.

## 프로세스 흐름 {#process-flow}

Marketing To On24 어댑터로 이벤트를 만들려면 다음 단계를 수행합니다.

1. [Marketing To에 ON24 자격 증명 입력](create-an-event-with-the-marketo-on24-adapter/enter-your-on24-credentials-in-marketo.md)
1. [ON24에서 웨비나 이벤트 만들기](create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md)
1. [웨비나와 이벤트 설정 구성 및 마케팅 동기화](create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md)
1. [하위 캠페인 및 로컬 자산 만들기](create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md)
1. [ON24 이벤트 통합 테스트](create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md)
1. [ON24 이벤트 통합 예](create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
1. [웨비나 프로그램 상태 이해](create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md)
1. [ON24 이벤트 등록 업데이트](create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md)

>[!MORELIKETHIS]
>
>* [Marketing ON24 어댑터 이벤트 이해](create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)

>




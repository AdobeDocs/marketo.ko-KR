---
unique-page-id: 10096656
description: Marketo ON24 Adapter를 사용하여 이벤트 만들기 - Marketo 문서 - 제품 설명서
title: Marketo ON24 어댑터를 사용하여 이벤트 만들기
exl-id: a240ff72-b12f-4e3a-8e14-94fddb02f944
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '313'
ht-degree: 0%

---

# Marketo ON24 어댑터를 사용하여 이벤트 만들기 {#create-an-event-with-the-marketo-on-adapter}

Marketo에서 이벤트를 만들기 위한 빌딩 블록 및 권장 시퀀스 를 잘 알고 있어야 합니다. 또한 다음 Marketo 개념에 대한 작업 지식도 있어야 합니다.

* [Marketo 프로그램](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)이벤트 및 {target=&quot;_blank&quot;} 및 그 사이의 차이점
* [채널](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target=&quot;_blank&quot;}
* [로컬 자산](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md){target=&quot;_blank&quot;}
* [하위 캠페인](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target=&quot;_blank&quot;} 및 [프로그램 상태](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md){target=&quot;_blank&quot;}

>[!NOTE]
>
>자세한 내용은 [Marketo API 설명서](https://developers.marketo.com/documentation/rest/)Marketo API에 대한 자세한 내용은 {target=&quot;_blank&quot;} 를 참조하십시오.

## 전제 조건 {#prerequisites}

Marketo ON24 통합을 사용하려면 다음이 필요합니다.

* **ON24 웹캐스트 구독** - 현재 구독이 없는 경우 ON24에 직접 문의하십시오. **참고**: ON24 Hosted Edition이 필요합니다. ON24 이벤트 관리가 필요하지 않습니다.

* **ON24에 대한 관리자 권한** - 이 커넥터를 사용하고 ON24 시스템에서 고객을 만들려면 이 커넥터가 필요합니다.
* **ON24 연결 자격 증명** - 통합을 사용하려면 Marketo에 이 정보를 입력해야 합니다. 사용자 이름, 암호, 클라이언트 ID 및 클라이언트 키 자격 증명에 대한 도움이 필요한 경우 ON24 계정 관리자 또는 ON24 지원에 문의하십시오.
* **등록 양식** - 등록 데이터 및 등록자 정보가 Marketo에 전달되도록 하려면 적절한 API와 함께 Marketo 양식 또는 Marketo 이외의 양식을 사용하십시오.
* **하위 캠페인 등록** - 이벤트 파트너 통합이 작동하려면 Marketo 이벤트에서 등록 하위 캠페인을 만들고 올바르게 구성해야 합니다.

## 프로세스 흐름 {#process-flow}

다음 단계에 따라 Marketo On24 어댑터를 사용하여 이벤트를 만듭니다.

1. [24에서 웨비나 이벤트 만들기](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md){target=&quot;_blank&quot;}
1. [이벤트 설정 구성 및 Marketo과 웨비나 동기화](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md){target=&quot;_blank&quot;}
1. [하위 캠페인 및 로컬 자산 만들기](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md){target=&quot;_blank&quot;}
1. [ON24 이벤트 통합 테스트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md){target=&quot;_blank&quot;}
1. [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target=&quot;_blank&quot;}
1. [웨비나 프로그램 상태 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md){target=&quot;_blank&quot;}
1. [ON24 이벤트 등록 업데이트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target=&quot;_blank&quot;}

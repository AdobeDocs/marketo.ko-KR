---
unique-page-id: 10096677
description: ON24 이벤트 통합 테스트 - 마케팅 문서 - 제품 설명서
title: ON24 이벤트 통합 테스트
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---


# ON24 이벤트 통합 테스트 {#test-your-on-event-integration}

이벤트 통합을 철저히 테스트하십시오.

## 첫 번째 캠페인 {#recommended-test-sequence-before-running-your-first-campaign}을(를) 실행하기 전에 권장 테스트 시퀀스

1. 이벤트의 등록 양식을 작성하고 유효한 이메일 주소를 사용하여 테스트합니다.
1. Marketing To 이벤트의 회원 격자에 **Registered** 상태로 테스트 이름이 표시되는지 확인합니다.
1. 테스트 이름이 ON24에 **Registered**&#x200B;로 표시되는지 확인합니다.
1. 테스트 이름을 등록하는 데 사용한 유효한 이메일 주소가 확인 이메일을 이벤트 수신했으며 고유 URL이 이메일에서 확인되었는지 확인합니다.

   >[!NOTE]
   >
   >각 등록자의 이메일에 고유 URL이 표시되도록 하려면 확인 이메일에 `{{member.webinar url}}` 토큰을 사용해야 합니다.

## 이벤트 {#after-the-event} 이후

다음은 이벤트가 발생한 후 데이터가 업데이트되는 방법입니다.

* Marketing은 매일 밤 ON24에서 참석자 데이터를 검색합니다.
* 참석자 데이터가 Marketing과 ON24 간에 동기화되면 Marketing에서 회원 상태를 [참석자], [주문형 참석] 또는 [표시 안 함]으로 업데이트합니다. 이벤트의 **요약** 탭에서 이벤트 상태가 **이벤트 완료**&#x200B;로 업데이트됩니다.

>[!MORELIKETHIS]
>
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
>* [Marketing ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)


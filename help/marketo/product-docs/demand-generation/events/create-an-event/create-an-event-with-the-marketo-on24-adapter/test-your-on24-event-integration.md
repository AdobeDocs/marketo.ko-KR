---
unique-page-id: 10096677
description: ON24 이벤트 통합 테스트 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 통합 테스트
exl-id: 8326b81e-abf7-4615-9a0b-b0a579be8bb8
source-git-commit: 40cfdddac66b7cd90e33bedf11888a7c5e3b38c9
workflow-type: tm+mt
source-wordcount: '211'
ht-degree: 0%

---

# ON24 이벤트 통합 테스트 {#test-your-on-event-integration}

>[!IMPORTANT]
>
>2022년 8월부터 ON24는 더 이상 새로운 Marketo 통합을 지원하지 않습니다. 이 문서의 정보는 기존 사용자에게만 적용됩니다.

이벤트 통합을 철저하게 테스트하십시오.

## 첫 번째 캠페인을 실행하기 전에 권장되는 테스트 시퀀스 {#recommended-test-sequence-before-running-your-first-campaign}

1. 이벤트의 등록 양식을 작성하고 유효한 이메일 주소를 사용하여 테스트하십시오.
1. 테스트 이름이 **등록** 상태는 Marketo 이벤트의 멤버십 그리드에 있습니다.
1. 테스트 이름이 **등록** ON24.
1. 테스트 이름을 등록하는 데 사용한 유효한 이메일 주소가 이벤트에 확인 이메일을 수신하고 고유 URL이 이메일에서 해결되었는지 확인합니다.

   >[!NOTE]
   >
   >를 사용해야 합니다 `{{member.webinar url}}` 각 등록자의 이메일에 고유 URL을 표시하기 위해 확인 이메일에 있는 토큰.

## 이벤트 후 {#after-the-event}

다음은 이벤트가 발생한 후 데이터를 업데이트하는 방법입니다.

* Marketo은 매일 밤 ON24에서 참석자 데이터를 검색합니다.
* Marketo과 ON24 간에 참석자 데이터가 동기화되면 Marketo은 구성원 상태를 참석함, 참석함 또는 [표시 안 함]으로 업데이트합니다. 이벤트 **요약** 탭에서 이벤트 상태가으로 업데이트됩니다. **이벤트 완료**.

>[!MORELIKETHIS]
>
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
>* [Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)


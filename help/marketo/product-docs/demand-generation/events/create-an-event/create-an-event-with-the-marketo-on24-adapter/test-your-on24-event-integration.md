---
unique-page-id: 10096677
description: ON24 이벤트 통합 테스트 - Marketo 문서 - 제품 설명서
title: ON24 이벤트 통합 테스트
exl-id: 8326b81e-abf7-4615-9a0b-b0a579be8bb8
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '191'
ht-degree: 0%

---

# ON24 이벤트 통합 테스트 {#test-your-on-event-integration}

이벤트 통합을 철저히 테스트해야 합니다.

## 첫 번째 캠페인을 실행하기 전에 권장되는 테스트 시퀀스 {#recommended-test-sequence-before-running-your-first-campaign}

1. 이벤트의 등록 양식을 작성하고 유효한 이메일 주소를 사용하여 테스트하십시오.
1. Marketo 이벤트의 멤버십 그리드에서 테스트 이름이 **등록됨** 상태로 표시되는지 확인하십시오.
1. 테스트 이름이 ON24에서도 **등록됨**(으)로 표시되는지 확인하십시오.
1. 테스트 이름을 등록하는 데 사용한 유효한 이메일 주소가 이벤트에 확인 이메일을 받았으며 고유 URL이 이메일에서 확인되었는지 확인합니다.

   >[!NOTE]
   >
   >각 등록자의 전자 메일에 고유한 URL을 표시하려면 확인 전자 메일에 `{{member.webinar url}}` 토큰을 사용해야 합니다.

## 이벤트 후 {#after-the-event}

다음은 이벤트 발생 후 데이터가 업데이트되는 방법입니다.

* Marketo은 매일 밤 ON24에서 참석자 데이터를 검색합니다.
* Marketo과 ON24 간에 참석자 데이터가 동기화되면 Marketo은 멤버십 상태를 참석함, 온디맨드 참석함 또는 표시 없음으로 업데이트합니다. 이벤트의 **요약** 탭에서 이벤트 상태가 **이벤트 완료**(으)로 업데이트됩니다.

>[!MORELIKETHIS]
>
>* [ON24 이벤트 통합 예](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md){target="_blank"}
>* [Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}

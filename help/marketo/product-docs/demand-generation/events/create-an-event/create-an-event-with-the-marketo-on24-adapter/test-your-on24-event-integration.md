---
unique-page-id: 10096677
description: ON24 이벤트 통합 테스트 - Marketing Docs - 제품 설명서
title: ON24 이벤트 통합 테스트
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---


# ON24 이벤트 통합 테스트 {#test-your-on-event-integration}

이벤트 통합을 철저히 테스트하십시오.

## 첫 번째 캠페인을 실행하기 전에 권장되는 테스트 시퀀스 {#recommended-test-sequence-before-running-your-first-campaign}

1. 이벤트의 등록 양식을 작성하고 유효한 이메일 주소를 사용하여 테스트합니다.
1. Marketing To 이벤트의 **멤버십** 격자에 등록된 상태로 테스트 이름이 표시되는지 확인합니다.
1. 테스트 이름이 ON24에 **등록됨으로** 표시되는지 확인합니다.
1. 테스트 이름을 등록하는 데 사용한 유효한 이메일 주소가 이벤트에 확인 이메일을 수신했으며 이메일에서 고유 URL이 해결되었는지 확인합니다.

   >[!NOTE]
   >
   >각 등록자의 이메일에 고유 URL이 표시되려면 확인 이메일에 `{{member.webinar url}}` 토큰을 사용해야 합니다.

## 이벤트 후 {#after-the-event}

다음은 이벤트가 발생한 후 데이터가 업데이트되는 방법입니다.

* Marketing은 매일 밤 ON24에서 참석자 데이터를 검색합니다.
* 참석자 데이터가 Marketing과 ON24 간에 동기화되면 Marketing에서 회원 상태를 [참석자], [주문형] 또는 [표시 안 함]으로 업데이트합니다. 이벤트의 [ **요약** ] 탭에서 이벤트 상태가 [ **이벤트 완료]로 업데이트됩니다**.

>[!NOTE]
>
>**관련 문서**
>
>* [ON24 이벤트 통합 예](example-on24-event-integration.md)
>* [Marketing ON24 어댑터 이벤트 이해](understanding-marketo-on24-adapter-events.md)

>




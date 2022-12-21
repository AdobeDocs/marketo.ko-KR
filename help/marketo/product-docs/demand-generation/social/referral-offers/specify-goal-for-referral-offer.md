---
unique-page-id: 2359791
description: 추천 오퍼에 대한 목표 지정 - Marketo 문서 - 제품 설명서
title: 추천 오퍼에 대한 목표 지정
exl-id: 9869eb66-53df-4ea8-903f-e6650add8da2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 0%

---

# 추천 오퍼에 대한 목표 지정 {#specify-goal-for-referral-offer}

다음 경우에 [참조 오퍼 만들기](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)를 채울 목표를 정의해야 합니다. 목표는 페이지 방문 또는 등록과 같이 웹 페이지의 개인 활동에서 정의할 수 있습니다. 을(를) 사용할 수도 있습니다 [사용자 지정 JavaScript 이벤트](/help/marketo/product-docs/demand-generation/social/social-functions/conversion-script-for-custom-events.md).

또는 Marketo에서 스마트 목록 트리거를 사용하여 참조된 사람에 대해 기회를 만드는 등의 이정표를 기다릴 수 있습니다.

목표 예:

* 방문 횟수 10회
* 5회 등록
* 1회 추천 기회 생성
* 중상거래 구매
* 5회의 참조 웨비나 참석자

1. 이동 **마케팅 활동**.

   ![](assets/ma.png)

1. 추천 오퍼를 선택하고 을 클릭합니다. **초안 편집**.

   ![](assets/image2014-9-19-15-3a6-3a35.png)

1. 참조 오퍼 편집기에서 **앱 설정** > **오퍼 세부 사항**.

   ![](assets/image2014-9-19-15-3a6-3a44.png)

1. 아래 **설정**&#x200B;에서 이벤트 유형을 선택합니다 **이행 목표** 드롭다운.

   ![](assets/image2014-9-19-15-3a6-3a56.png)

>[!TIP]
>
>를 사용할 계획이라면 **레퍼러에 신용 제공** 흐름 단계를 선택해야 합니다. **Smart List 트리거** 를 이행 목표 유형으로 여기에 입력합니다.

* 참조 방문: 오퍼 참가자는 친구로부터 오퍼를 호스팅하는 페이지로의 각 방문에 대한 크레딧을 받습니다.
* 참조 등록: 제안 참가자는 그 제안에 등록한 친구마다 크레딧을 받는다.
* 스마트 목록 트리거: 오퍼 참가자는 [스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md) 트리거 [스마트 캠페인](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md). 예를 들어 참조 잠재 고객이 웨비나에 등록할 때 발생하는 트리거를 사용할 수 있습니다.

* 사용자 지정 JavaScript 이벤트: 오퍼 참가자는 페이지에서 정의된 JavaScript 이벤트를 트리거하는 각 친구에 대한 크레딧을 받습니다. 자세한 내용은 [사용자 지정 이벤트에 대한 전환 스크립트](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!NOTE]
>
>스마트 캠페인에서 소셜 활동을 모니터링하는 새로운 필터 및 트리거가 있습니다. 자세한 내용은 [소셜 활동용 트리거 및 필터 사용](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!MORELIKETHIS]
>
>다음 작업을 수행할 수 있습니다. [등록 및 이행 이메일 선택](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md) 참조 오퍼에서 을 보내려면

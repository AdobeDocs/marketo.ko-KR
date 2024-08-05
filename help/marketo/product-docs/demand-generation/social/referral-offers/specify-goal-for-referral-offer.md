---
unique-page-id: 2359791
description: 추천 오퍼 목표 지정 - Marketo 문서 - 제품 설명서
title: 추천 오퍼에 대한 목표 지정
exl-id: 9869eb66-53df-4ea8-903f-e6650add8da2
feature: Social
source-git-commit: 6c3f803104c550227aec25376778147ff92aaab9
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 0%

---

# 추천 오퍼에 대한 목표 지정 {#specify-goal-for-referral-offer}

[추천 오퍼를 만들](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md) 때 이행 목표를 정의해야 합니다. 목표는 페이지 방문 또는 등록과 같이 웹 페이지의 개인 활동으로 정의할 수 있습니다. [사용자 지정 JavaScript 이벤트](/help/marketo/product-docs/demand-generation/social/social-functions/conversion-script-for-custom-events.md)를 사용할 수도 있습니다.

>[!IMPORTANT]
>
>2024년 7월 31일에 이 기능의 사용 중단 프로세스를 시작했습니다. 더 이상 새 자산을 만들 수 없습니다. 기존 자산은 2025년 1월 31일까지 계속 작동합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

또는 Marketo Engage에서 스마트 목록 트리거를 사용하여 참조된 사용자에 대해 만들어지는 기회와 같은 이정표를 기다릴 수 있습니다.

목표 예:

* 10회 참조 방문
* 5 참조 등록
* 1개의 참조 영업 기회 생성됨
* 2 관련 전자 상거래 구매
* 5명의 참조 웨비나 참석자

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/ma.png)

1. 추천 오퍼를 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-19-15-3a6-3a35.png)

1. 추천 오퍼 편집기에서 **앱 설정** > **오퍼 세부 정보**(으)로 이동합니다.

   ![](assets/image2014-9-19-15-3a6-3a44.png)

1. **설정**&#x200B;의 **이행 목표** 드롭다운에서 이벤트 유형을 선택합니다.

   ![](assets/image2014-9-19-15-3a6-3a56.png)

>[!TIP]
>
>**레퍼러에 크레딧 제공** 흐름 단계를 사용하려면 여기에서 이행 목표 유형으로 **스마트 목록 트리거**&#x200B;를 선택해야 합니다.

* 참조된 방문 횟수: 오퍼 참가자는 친구로부터 오퍼를 호스팅하는 페이지까지의 각 방문에 대해 크레딧을 받습니다.
* 참조된 등록: 오퍼 참가자는 오퍼에 등록한 각 친구에 대해 크레딧을 받습니다.
* 스마트 목록 트리거: 오퍼 참가자는 [스마트 캠페인](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md)에서 [스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md) 트리거의 조건을 충족하는 각 친구에 대한 크레딧을 받습니다. 예를 들어 참조된 잠재 고객이 웨비나에 등록하면 실행되는 트리거를 사용할 수 있습니다.

* 사용자 지정 JavaScript 이벤트: 오퍼 참가자는 페이지에서 정의된 JavaScript 이벤트를 트리거하는 각 친구에 대해 크레딧을 받습니다. [사용자 지정 이벤트에 대한 변환 스크립트](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md)를 참조하십시오.

>[!NOTE]
>
>스마트 캠페인에서 소셜 활동을 모니터링하는 데 사용할 수 있는 새로운 필터 및 트리거가 있습니다. [소셜 활동에 트리거 및 필터 사용](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md)을 참조하세요.

>[!MORELIKETHIS]
>
>다음으로 [가입 및 이행 이메일을 선택하여](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md)추천 오퍼에서 보낼 수 있습니다.

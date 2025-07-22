---
unique-page-id: 10097867
description: 웹 Personalization 활동에 대한 스마트 목록 정의 - Marketo 문서 - 제품 설명서
title: 웹 Personalization 활동에 대한 스마트 목록 정의
exl-id: 9987f922-f50c-47b3-aef6-230326b094fc
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 0%

---

# [!DNL Web Personalization]개 활동에 대한 스마트 목록 정의 {#define-a-smart-list-for-web-personalization-activities}

스마트 캠페인에서 스마트 목록을 정의하는 경우 필터 및 트리거에서 [!DNL Web Personalization] 활동을 사용할 수 있습니다. 여기에서 [!DNL Web Personalization] call to action(캠페인)를 클릭한 모든 사용자를 캡처하려고 합니다.

트리거를 사용하여 전자 메일 또는 경고를 보내거나 [!DNL Web Personalization] call to action을 클릭하고 참여한 방문자를 기준으로 값 또는 점수를 변경합니다. [!DNL Web Personalization] call to action을 클릭한 리드를 필터링하고 볼 수도 있습니다.

1. 스마트 캠페인에서 **[!UICONTROL Smart List]** 탭을 클릭합니다.

   ![](assets/image2016-2-9-10-3a49-3a18.png)

   >[!NOTE]
   >
   >스마트 목록은 놀라운 일을 할 수 있습니다. [스마트 목록 딥 다이브](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md)에서 자세히 알아보세요.

1. 트리거를 검색한 다음 트리거를 캔버스로 드래그하여 놓습니다.

   ![](assets/image2016-6-8-9-3a24-3a24.png)

   >[!NOTE]
   >
   >트리거가 있는 스마트 캠페인이 트리거 모드에서 실행됩니다. 트리거된 이벤트와 추가된 필터에 따라 한 번에 한 사람씩 실행됩니다.

1. 드롭다운을 클릭하고 연산자를 선택합니다.

   ![](assets/image2016-6-7-11-3a10-3a8.png)

   >[!CAUTION]
   >
   >빨강 구불구불한 선은 오류를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않게 되고 실행되지 않습니다.

1. 트리거 정의.

   ![](assets/image2016-6-7-11-3a12-3a23.png)

1. 필요에 따라 필터를 추가합니다.

   ![](assets/image2016-6-7-11-3a14-3a20.png)

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 스마트 캠페인에서 트리거는 맨 위에 있습니다. 트리거되면 필터 기준을 충족하는 사람만 플로우를 통과합니다.

   >[!NOTE]
   >
   >여러 트리거를 사용하면 트리거 중 하나가 활성화되면 사람이 플로우로 이동합니다.

   사람들 집합에서 동시에 캠페인을 실행하려면 [Smart Campaign용 스마트 목록을 정의하는 방법을 알아보세요 | 일괄 처리 ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인용 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >* [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >* [예측 콘텐츠 활동에 대한 스마트 목록 정의](/help/marketo/product-docs/predictive-content/define-a-smart-list-for-predictive-content-activities.md)

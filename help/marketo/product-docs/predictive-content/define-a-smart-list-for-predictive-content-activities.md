---
unique-page-id: 10097873
description: 예측 콘텐츠 활동에 대한 스마트 목록 정의 - Marketo 문서 - 제품 설명서
title: 예측 콘텐츠 활동을 위한 스마트 목록 정의
exl-id: 2c72b215-8c0b-48b4-8492-8e3fe832fae9
feature: Predictive Content
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '289'
ht-degree: 0%

---

# 예측 콘텐츠 활동을 위한 스마트 목록 정의 {#define-a-smart-list-for-predictive-content-activities}

스마트 캠페인에서 스마트 목록을 정의할 때 트리거 및 필터에서 예측 콘텐츠 활동을 사용할 수 있습니다. [리치 미디어 템플릿](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md), [콘텐츠 추천 막대](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md) 또는 [전자 메일](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-in-emails.md)을 통해 예측 콘텐츠를 클릭하는 모든 사용자에 대해 작업을 트리거할 수 있습니다.

1. 스마트 캠페인에서 **[!UICONTROL Smart List]** 탭으로 이동합니다.

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >스마트 목록은 놀라운 일을 할 수 있습니다. 자세한 내용은 [스마트 목록 상세 정보](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md)를 참조하세요.

1. 트리거를 검색한 다음 캔버스로 드래그하여 놓습니다.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >트리거가 있는 스마트 캠페인이 트리거 모드에서 실행됩니다. 트리거된 이벤트와 추가된 필터에 따라 한 번에 한 사람씩 실행됩니다.

1. **[!UICONTROL Name]** 드롭다운을 클릭하고 연산자를 선택합니다.

   ![](assets/smart-list-dropdown-hands.png)

1. 트리거 정의.

   ![](assets/smart-lislt-select-content-hands.png)

1. **[!UICONTROL Type]** 제약 조건을 추가합니다.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. 스마트 목록에 필요한 소스를 선택합니다.

   ![](assets/pc-add-constraint.png)

1. 예측 콘텐츠에 전자 메일 원본을 사용하는 경우 **[!UICONTROL Clicks Link in Email]** 트리거를 추가하십시오. 전자 메일을 선택하고 **[!UICONTROL Is Predictive]**(으)로 정의된 **[!UICONTROL true]** 제약 조건을 추가하십시오.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. 필요에 따라 다른 필터를 추가합니다.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 스마트 캠페인에서 트리거는 맨 위에 있습니다. 트리거되면 필터 기준을 충족하는 사람만 플로우를 통과합니다.

   >[!NOTE]
   >
   >여러 트리거를 사용하면 트리거 중 하나라도 활성화되면 사람이 플로우로 이동합니다.

   사람들 집합에서 동시에 캠페인을 실행하려면 [일괄 스마트 캠페인에 대한 스마트 목록을 정의하는 방법](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)을 알아보세요.

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인용 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >* [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >* [웹 Personalization 활동에 대한 스마트 목록 정의](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >* [웹 리치 미디어에 대한 예측 콘텐츠 사용](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >* [콘텐츠 추천 막대 사용](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md)

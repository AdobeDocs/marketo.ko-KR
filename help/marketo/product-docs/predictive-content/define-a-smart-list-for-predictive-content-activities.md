---
unique-page-id: 10097873
description: 예측 컨텐츠 활동에 대한 스마트 목록 정의 - Marketo 문서 - 제품 설명서
title: 예측 컨텐츠 활동에 대한 스마트 목록 정의
exl-id: 2c72b215-8c0b-48b4-8492-8e3fe832fae9
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '300'
ht-degree: 0%

---

# 예측 컨텐츠 활동에 대한 스마트 목록 정의 {#define-a-smart-list-for-predictive-content-activities}

스마트 캠페인에서 스마트 목록을 정의할 때 트리거 및 필터에 예측 컨텐츠 활동을 사용할 수 있습니다. 를 통해 예측 컨텐츠를 클릭하는 모든 사용자에 대해 작업을 트리거할 수 있습니다 [리치 미디어 템플릿](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md), [컨텐츠 권장 사항 막대](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md)또는 [이메일](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-in-emails.md).

1. 스마트 캠페인에서 **Smart List** 탭.

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >스마트 리스트는 놀라운 일을 할 수 있습니다. 자세한 내용은 [스마트 목록 심층 검색](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md).

1. 트리거를 검색한 다음 캔버스에 끌어다 놓습니다.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >트리거가 있는 스마트 캠페인은 트리거 모드에서 실행됩니다. 트리거된 이벤트와 추가된 필터를 기반으로 한 번에 한 사람씩 실행됩니다.

1. 을(를) 클릭합니다. **이름** 드롭다운을 클릭하고 연산자를 선택합니다.

   ![](assets/smart-list-dropdown-hands.png)

1. 트리거를 정의합니다.

   ![](assets/smart-lislt-select-content-hands.png)

1. 추가 **유형** 제한.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. 스마트 목록에 필요한 소스를 선택합니다.

   ![](assets/pc-add-constraint.png)

1. 예측 컨텐츠에 이메일 소스를 사용하는 경우 **이메일의 클릭 링크** 트리거합니다. 이메일을 선택하고 을(를) 추가합니다 **예측** 제약으로 정의됨 **true**.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. 필요에 따라 다른 필터를 추가합니다.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 스마트 캠페인에서 트리거가 맨 위에 표시됩니다. 트리거되면 필터 기준을 충족하는 사용자만 흐름을 통과합니다.

   >[!NOTE]
   >
   >여러 트리거를 사용할 때 트리거 중 하나가 활성화되면 한 사람이 플로우에 도달합니다.

   한 세트의 사용자에 대해 캠페인을 동시에 실행하려면 다음을 학습합니다 [일괄 처리 스마트 캠페인에 대한 스마트 목록 정의](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >* [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >* [웹 개인화 활동에 대한 스마트 목록 정의](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >* [웹 리치 미디어용 Predictive Content 활성화](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >* [컨텐츠 권장 사항 막대 활성화](/help/marketo/product-docs/predictive-content/enabling-predictive-content/enable-the-content-recommendation-bar.md)


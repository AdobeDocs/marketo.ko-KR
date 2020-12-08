---
unique-page-id: 10097873
description: 예측 컨텐츠 활동에 대한 스마트 목록 정의 - 마케팅 문서 - 제품 설명서
title: 예측 컨텐츠 활동에 대한 스마트 목록 정의
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 0%

---


# 예측 컨텐츠 활동에 대한 스마트 목록 정의 {#define-a-smart-list-for-predictive-content-activities}

>[!NOTE]
>
>구매 날짜에 따라 마케팅 구독에 마케팅 토 예측 컨텐츠 또는 컨텐츠가 포함될 수 있습니다`<sup>AI</sup>`. 예측 컨텐츠를 사용하는 사용자의 경우 Marketing에서는 2018년 4월 30일까지 컨텐츠`<sup>AI</sup>` 분석 기능을 활성화합니다. 이러한 기능을 해당 날짜 이상으로 유지하려면 마케팅 고객 성공 관리자에게 문의하여 Marketing Cloud 콘텐츠로 업그레이드하십시오`<sup>AI</sup>`.

스마트 캠페인에서 스마트 목록을 정의할 때 트리거 및 필터에서 예측 컨텐츠 활동을 사용할 수 있습니다. 리치 미디어 템플릿 [,](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)컨텐츠 권장 사항 막대 [](enabling-predictive-content/enable-the-content-recommendation-bar.md)또는 이메일을 통해 예측 컨텐츠를 클릭하는 모든 사용자에 대한 동작을 트리거할 수 있습니다.

1. 스마트 캠페인에서 **스마트 목록** 탭으로 이동합니다.

   ![](assets/smart-list-1.png)

   >[!NOTE]
   >
   >**딥 다이브**
   >
   >
   >스마트한 목록을 통해 멋진 작품을 만들 수 있습니다. 자세한 내용은 [스마트한 목록을 참조하십시오](../../product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md).

1. 트리거를 검색한 다음 캔버스에 드래그하여 놓습니다.

   ![](assets/smart-list-drag-trigger-hands.png)

   >[!NOTE]
   >
   >트리거가 있는 스마트 캠페인은 트리거 모드에서 실행됩니다. 트리거된 이벤트 및 추가된 필터를 기반으로 한 시간에 한 사람씩 실행됩니다.

1. 이름 **드롭다운을** 클릭하고 연산자를 선택합니다.

   ![](assets/smart-list-dropdown-hands.png)

1. 트리거를 정의합니다.

   ![](assets/smart-lislt-select-content-hands.png)

1. 유형 **제한을** 추가합니다.

   ![](assets/clicks-predictive-content-add-constraint-hands.png)

1. 스마트 목록에 필요한 소스를 선택합니다.

   ![](assets/pc-add-constraint.png)

1. 예측 컨텐츠에 이메일 소스를 사용하는 경우 **이메일의 클릭 수 링크 **트리거를 추가합니다. 이메일을 선택하고 **true로 정의된 예측** 제한 **을 추가합니다**.

   ![](assets/clicks-link-in-email-trigger-hands.png)

1. 필요에 따라 다른 필터를 추가합니다.

   ![](assets/clicked-predictive-content-filter.png)

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 스마트 캠페인에서 트리거가 맨 위에 표시됩니다. 트리거되면 필터 기준을 만족하는 사람만 흐름을 따라 이동합니다.

   >[!NOTE]
   >
   >여러 개의 트리거를 사용하는 경우 트리거가 하나라도 활성화되면 사람이 흐름을 따라 이동합니다.

   [일괄 처리 스마트 캠페인에 대한 스마트 목록 정의](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)

   >[!NOTE]
   >
   >**관련 문서**
   >
   >    
   >    
   >    * [스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리](../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md)
   >    * [스마트 캠페인에 흐름 단계 추가](../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)
   >    * [웹 개인화 활동에 대한 스마트 목록 정의](../../product-docs/web-personalization/working-with-web-campaigns/define-a-smart-list-for-web-personalization-activities.md)
   >    * [웹 리치 미디어용 예측 컨텐츠 사용](enabling-predictive-content/enable-predictive-content-for-web-rich-media.md)
   >    * [컨텐츠 권장 사항 막대 활성화](enabling-predictive-content/enable-the-content-recommendation-bar.md)


동시에 여러 사람 집합에서 캠페인을 실행하려면 방법을 알아봅니다.
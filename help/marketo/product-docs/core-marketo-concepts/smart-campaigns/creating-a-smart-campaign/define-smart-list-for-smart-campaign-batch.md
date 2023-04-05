---
unique-page-id: 1146940
description: 스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리
exl-id: 0e0061a9-df24-4cf6-8f1e-09ff0ee62efa
source-git-commit: 56d3d05d5462c79f32f507655266e3bfa0cc6846
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---

# 스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리 {#define-smart-list-for-smart-campaign-batch}

스마트 목록은 보고서, 목록 또는 스마트 캠페인이든, 포함할 &quot;사람&quot;(사람)을 정의하는 Marketo 전체의 메커니즘입니다. 다음은 배치 캠페인에 대한 스마트 목록을 정의하는 방법입니다.

1. 스마트 캠페인을 선택한 다음 **Smart List**.

   ![](assets/define-smart-list-for-smart-campaign-batch-1.png)

1. 필터를 검색하고 캔버스에 드래그하여 놓습니다. 여러 필터에 대해 이 작업을 반복합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-2.png)

   >[!NOTE]
   >
   >필터만 있는 스마트 캠페인이 실행됩니다. **일괄 처리** 모드. 필터를 기반으로 자격이 있는 사용자를 찾아서 흐름을 통해 모두 한 번에 실행합니다.

   >[!NOTE]
   >
   >스마트 캠페인을 로그인하는 트리거를 추가하여 라이브 이벤트를 기반으로 한 번에 한 명씩에서 스마트 캠페인을 실행할 수 있습니다 **트리거** 모드.

1. 드롭다운을 클릭하고 선택한 필터에 대한 필터 연산자를 선택합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-3.png)

   >[!CAUTION]
   >
   >빨간색 선은 오류 또는 누락된 정보를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않으며 실행되지 않습니다.

1. 필터 값을 입력합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-4.png)

   >[!NOTE]
   >
   >기본적으로 ALL Smart List 규칙을 만족하는 사용자는 자격을 갖습니다. 캠페인 요구 사항에 맞게 수정할 수 있습니다. 체크 아웃  [복잡한 논리를 위한 스마트 목록 규칙](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md) 추가 정보

   한 번에 한 사람이 라이브 이벤트를 트리거하려면 다음을 학습합니다 [스마트 캠페인에 대한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md).

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인에 대한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
   >* [스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)


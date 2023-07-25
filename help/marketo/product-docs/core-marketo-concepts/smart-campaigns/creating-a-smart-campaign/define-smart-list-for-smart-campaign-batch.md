---
unique-page-id: 1146940
description: 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리
exl-id: 0e0061a9-df24-4cf6-8f1e-09ff0ee62efa
feature: Smart Campaigns
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---

# 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리 {#define-smart-list-for-smart-campaign-batch}

스마트 목록은 보고서, 목록 또는 스마트 캠페인인지 여부와 관계없이 포함할 &quot;사용자&quot;(사용자)를 정의하는 Marketo 전체의 메커니즘입니다. 다음은 일괄 캠페인을 위한 스마트 목록을 정의하는 방법입니다.

1. 스마트 캠페인을 선택한 다음 **스마트 목록**.

   ![](assets/define-smart-list-for-smart-campaign-batch-1.png)

1. 검색할 필터를 입력하고 캔버스로 드래그 앤 드롭합니다. 여러 필터에 대해 이 작업을 반복합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-2.png)

   >[!NOTE]
   >
   >필터만 있는 스마트 캠페인은에서 실행됩니다 **일괄 처리** 모드. 데이터베이스에서 필터를 기반으로 자격을 부여하는 사람을 찾아서 해당 필터 모두를 한 번에 통과시킵니다.

   >[!NOTE]
   >
   >트리거를 추가하여 실시간 이벤트를 기반으로 한 한 번에 한 명씩 스마트 캠페인을 실행하여 Smart Campaign을 실행할 수 있습니다 **트리거** 모드.

1. 드롭다운을 클릭하고 선택한 필터에 대한 필터 연산자를 선택합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-3.png)

   >[!CAUTION]
   >
   >빨간색 구불구불한 선은 오류나 누락된 정보를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않고 실행되지 않습니다.

1. 필터 값을 입력합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-4.png)

   >[!NOTE]
   >
   >기본적으로 모든 스마트 목록 규칙을 충족하는 사람은 자격이 있습니다. 이는 캠페인 요구 사항에 맞게 수정할 수 있습니다. 체크아웃  [복잡한 논리에 대한 스마트 목록 규칙](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md) 자세히 알아보십시오.

   한 번에 한 사람씩 라이브 이벤트를 트리거하려면 다음 방법을 알아보세요. [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md).

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
   >* [스마트 캠페인에 플로우 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)

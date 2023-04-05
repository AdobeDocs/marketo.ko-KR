---
unique-page-id: 1146942
description: 스마트 캠페인에 대한 스마트 목록 정의 | 트리거 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에 대한 스마트 목록 정의 | 트리거
exl-id: 14d9b15e-864a-47ef-8f39-3d65e6036a82
source-git-commit: 56d3d05d5462c79f32f507655266e3bfa0cc6846
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# 스마트 캠페인에 대한 스마트 목록 정의 | 트리거 {#define-smart-list-for-smart-campaign-trigger}

트리거를 추가하여 라이브 이벤트를 기반으로 한 한 번에 한 명씩 스마트 캠페인을 실행합니다.

1. 스마트 캠페인에서 **Smart List** 탭.

   ![](assets/define-smart-list-for-smart-campaign-trigger-1.png)

1. 원하는 트리거를 검색하고 캔버스에 드래그하여 놓습니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-2.png)

   >[!NOTE]
   >
   >트리거가 포함된 스마트 캠페인이 실행됩니다 **트리거** 모드. 트리거된 이벤트 및 추가 필터를 기반으로 한 번에 한 사람씩 실행됩니다.

   >[!IMPORTANT]
   >
   >트리거 캠페인 스마트 목록에서 부울 필드를 사용할 때, 캠페인을 실행하는 동안 필드가 제대로 평가되도록 명시적으로 &#39;false&#39;로 설정해야 합니다.

1. 드롭다운을 클릭하고 연산자를 선택합니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-3.png)

   >[!CAUTION]
   >
   >빨간색 선은 오류 또는 누락된 정보를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않으며 실행되지 않습니다.

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 Smart Campaign에서 트리거는 맨 위에 있고 트리거가 되면 필터 기준을 충족하는 사용자만 흐름을 받습니다.

1. 트리거를 정의합니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-4.png)

   >[!NOTE]
   >
   >여러 트리거를 사용할 경우 한 사람이 플로우를 통과합니다 **임의** 트리거 중 하나가 활성화됩니다.

한 세트의 사용자에 대해 캠페인을 동시에 실행하려면 다음을 학습합니다 [스마트 캠페인에 대한 스마트 목록 정의 | 일괄 처리](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md).

>[!MORELIKETHIS]
>
>[스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md)

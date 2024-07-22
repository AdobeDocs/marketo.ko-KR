---
unique-page-id: 1146942
description: 스마트 캠페인을 위한 스마트 목록 정의 | 트리거 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인을 위한 스마트 목록 정의 | 트리거
exl-id: 14d9b15e-864a-47ef-8f39-3d65e6036a82
feature: Smart Campaigns
source-git-commit: c3aa1a29b084cb1c1add9d22cdbfc23bdcf7512b
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 0%

---

# 스마트 캠페인을 위한 스마트 목록 정의 | 트리거 {#define-smart-list-for-smart-campaign-trigger}

트리거를 추가하여 실시간 이벤트를 기반으로 한 한 번에 한 명씩 스마트 캠페인을 실행합니다.

>[!CAUTION]
>
>활성 캠페인에 대한 스마트 목록 또는 흐름 단계를 편집하면 기능이 중단될 수 있습니다. 그렇게 하기로 선택한 경우 신중하게 진행하십시오.

1. 스마트 캠페인에서 **[!UICONTROL 스마트 목록]** 탭을 클릭합니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-1.png)

1. 원하는 트리거를 검색하고 캔버스로 드래그하여 놓습니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-2.png)

   >[!NOTE]
   >
   >트리거가 있는 스마트 캠페인이 _트리거_ 모드에서 실행됩니다. 트리거된 이벤트 및 추가 필터를 기반으로 한 번에 한 사람에서 실행됩니다.

   >[!IMPORTANT]
   >
   >트리거 캠페인 스마트 목록에서 부울 필드를 사용할 때, 필드를 캠페인 실행 중에 제대로 평가하려면 명시적으로 &#39;false&#39;로 설정해야 합니다.

1. 드롭다운을 클릭하고 연산자를 선택합니다.

   ![](assets/define-smart-list-for-smart-campaign-trigger-3.png)

   >[!CAUTION]
   >
   >빨간색 구불구불한 선은 오류나 누락된 정보를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않고 실행되지 않습니다.

   >[!TIP]
   >
   >트리거와 필터가 모두 있는 Smart Campaign에서 트리거는 맨 위에 있으며, 트리거가 트리거되면 필터 기준을 충족하는 사용자만 플로우를 통과합니다.

1. 트리거 정의.

   ![](assets/define-smart-list-for-smart-campaign-trigger-4.png)

   >[!NOTE]
   >
   >트리거가 여러 개인 경우, 트리거 중 _ANY_ 하나가 활성화되면 한 사람이 흐름을 통과합니다.

사람들 집합에서 동시에 캠페인을 실행하려면 [Smart Campaign용 스마트 목록을 정의하는 방법을 알아보세요 | 일괄 처리 ](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-batch.md){target="_blank"}.

>[!MORELIKETHIS]
>
>[스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

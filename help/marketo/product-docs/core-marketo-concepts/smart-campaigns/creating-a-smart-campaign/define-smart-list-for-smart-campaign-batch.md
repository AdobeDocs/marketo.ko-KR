---
unique-page-id: 1146940
description: 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리
exl-id: 0e0061a9-df24-4cf6-8f1e-09ff0ee62efa
feature: Smart Campaigns
source-git-commit: c3aa1a29b084cb1c1add9d22cdbfc23bdcf7512b
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 0%

---

# 스마트 캠페인을 위한 스마트 목록 정의 | 일괄 처리 {#define-smart-list-for-smart-campaign-batch}

스마트 목록은 보고서, 목록 또는 스마트 캠페인인지 여부와 관계없이 포함할 &quot;사용자&quot;(사용자)를 정의하는 Marketo Engage 전반의 메커니즘입니다. 다음은 일괄 캠페인을 위한 스마트 목록을 정의하는 방법입니다.

>[!CAUTION]
>
>활성 캠페인에 대한 스마트 목록 또는 흐름 단계를 편집하면 기능이 중단될 수 있습니다. 그렇게 하기로 선택한 경우 신중하게 진행하십시오.

1. 스마트 캠페인을 선택한 다음 **[!UICONTROL 스마트 목록]**.

   ![](assets/define-smart-list-for-smart-campaign-batch-1.png)

1. 검색할 필터를 입력하고 캔버스로 드래그 앤 드롭합니다. 여러 필터에 대해 이 작업을 반복합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-2.png)

   >[!NOTE]
   >
   >필터만 있는 스마트 캠페인은에서 실행됩니다 _일괄 처리_ 모드. 데이터베이스에서 필터를 기반으로 자격을 부여하는 사람을 찾아서 해당 필터 모두를 한 번에 통과시킵니다.

   >[!NOTE]
   >
   >트리거를 추가하여 실시간 이벤트를 기반으로 한 한 번에 한 명씩 스마트 캠페인을 실행하여 Smart Campaign을 실행할 수 있습니다 _트리거_ 모드.

1. 드롭다운을 클릭하고 선택한 필터에 대한 필터 연산자를 선택합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-3.png)

   >[!CAUTION]
   >
   >빨간색 구불구불한 선은 오류나 누락된 정보를 나타냅니다. 수정하지 않으면 캠페인이 유효하지 않고 실행되지 않습니다.

1. 필터 값을 입력합니다.

   ![](assets/define-smart-list-for-smart-campaign-batch-4.png)

   >[!NOTE]
   >
   >기본적으로 모든 스마트 목록 규칙을 충족하는 사람은 자격이 있습니다. 이는 캠페인 요구 사항에 맞게 수정할 수 있습니다. 체크아웃  [복잡한 논리에 대한 스마트 목록 규칙](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"} 자세히 알아보십시오.

   한 번에 한 사람씩 라이브 이벤트를 트리거하려면 다음 방법을 알아보세요. [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}.

   >[!MORELIKETHIS]
   >
   >* [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"}
   >* [스마트 캠페인에 플로우 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

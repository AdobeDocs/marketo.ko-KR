---
unique-page-id: 1146980
description: 흐름 단계에서 선택 항목 추가 사용 - Marketo 문서 - 제품 설명서
title: 플로우 단계에서 선택 항목 추가 사용
exl-id: 50ffcd60-48ee-4341-94d8-170c63bc9ecb
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 7%

---

# 플로우 단계에서 선택 항목 추가 사용 {#use-add-choice-in-a-flow-step}

>[!PREREQUISITES]
>
>[스마트 캠페인에 흐름 단계 추가](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md){target="_blank"}

&quot;선택 항목 추가&quot;를 사용하면 플로우 단계를 사용하여 세부 정보를 선택할 때 &#39;종속됨&#39;이라고 말할 수 있습니다.

1. 스마트 캠페인의 **[!UICONTROL Flow]** 탭에서 흐름 단계를 추가한 다음 **[!UICONTROL Add Choice]**&#x200B;을(를) 클릭합니다.

   ![](assets/use-add-choice-in-a-flow-step-1.png)

1. 선택 조건을 선택합니다.

   ![](assets/use-add-choice-in-a-flow-step-2.png)

1. 선택 연산자를 선택하고 선택 값을 입력합니다. 기준 또는 선택을 설정합니다.

   ![](assets/use-add-choice-in-a-flow-step-3.png)

1. 선택 항목에 대한 흐름 단계 값을 입력합니다.

   ![](assets/use-add-choice-in-a-flow-step-4.png)

   >[!CAUTION]
   >
   >선택 흐름 단계의 조건 부분에서 토큰이 _not_ 작동합니다.

1. 위의 단계를 반복하여 여러 선택 항목을 추가한 다음 기본값을 추가/조정합니다.

   ![](assets/use-add-choice-in-a-flow-step-5.png)

   >[!TIP]
   >
   >흐름 단계를 —Do Nothing—으로 설정할 수 있으며, 이 경우 해당 선택에 대해 아무 작업도 수행되지 않습니다.

   >[!CAUTION]
   >
   >첫 번째 일치 선택 사항만 흐름 단계에 적용됩니다. [흐름 작업에서 &quot;선택 항목 추가&quot;를 다시 정렬하는 방법](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}을 알아보세요.

   잘됐네! 이제 각 선택 사항에 대해 여러 개의 스마트 캠페인을 만드는 대신 흐름 단계 선택 사항을 사용하여 단일 스마트 캠페인을 만들 수 있습니다.

   >[!MORELIKETHIS]
   >
   >[흐름 단계에서 선택 항목 추가 순서 바꾸기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/reorder-add-choice-in-a-flow-step.md){target="_blank"}

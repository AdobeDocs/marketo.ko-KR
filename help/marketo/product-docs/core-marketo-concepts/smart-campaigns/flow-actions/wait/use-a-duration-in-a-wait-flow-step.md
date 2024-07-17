---
unique-page-id: 1146978
description: 대기 흐름 단계에서 기간 사용 - Marketo 문서 - 제품 설명서
title: 대기 흐름 단계에서 기간 사용
exl-id: 7b13d225-78ba-4ef1-9ff5-0f6acde6e5ff
feature: Smart Campaigns
source-git-commit: 12f2399859c784095cc2c1df772c66c649106ba3
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---

# 대기 흐름 단계에서 기간 사용 {#use-a-duration-in-a-wait-flow-step}

대기 흐름 단계를 사용하여 특정 기간 동안 Smart Campaign을 통해 개인의 여정을 일시 중지할 수 있습니다. 요일 및 종료 시간에 대한 기준을 지정할 수도 있습니다.

1. 스마트 캠페인 **[!UICONTROL 흐름]** 탭에서 **[!UICONTROL 대기]** 흐름 단계 위로 끌어서 놓습니다.

   ![](assets/use-a-duration-in-a-wait-flow-step-1.png)

1. 일시 중지할 기간을 입력하십시오.

   ![](assets/use-a-duration-in-a-wait-flow-step-2.png)

1. 다 됐습니다! 플로우는 지정된 기간 동안 일시 중지됩니다. 고급 옵션의 경우 오른쪽에 있는 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/use-a-duration-in-a-wait-flow-step-3.png)

1. 대기 단계가 종료되는 요일을 지정합니다.

   ![](assets/use-a-duration-in-a-wait-flow-step-4.png)

1. 시간을 지정할 수도 있습니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/use-a-duration-in-a-wait-flow-step-5.png)

   >[!NOTE]
   >
   >**예**
   >
   >한 사람이 금요일 오후 5시에 스마트 캠페인을 트리거합니다. 대기 단계는 48시간으로 앞당겨지며 월-금 오전 9시에 종료되어야 합니다.
   >
   >그 결과 해당 사용자는 **월요일 오전 9시**&#x200B;에 플로우가 계속됩니다. 이것은 48시간 후 첫 번째 M-F 날짜입니다.

   >[!NOTE]
   >
   >사용된 기간, 날짜, 시간 및 일은 모두 구독 시간대를 기준으로 합니다.

   >[!MORELIKETHIS]
   >
   >* [대기 흐름 단계에서 특정 날짜 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
   >* [대기 흐름 단계에서 날짜 토큰 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-date-token-in-a-wait-flow-step.md){target="_blank"}

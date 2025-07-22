---
unique-page-id: 1146997
description: 대기 흐름 단계에서 날짜 토큰 사용 - Marketo 문서 - 제품 설명서
title: 대기 흐름 단계에서 날짜 토큰 사용
exl-id: d161922b-ce90-4e65-9282-d3bb866c1d94
feature: Smart Campaigns
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '205'
ht-degree: 0%

---

# 대기 흐름 단계에서 날짜 토큰 사용 {#use-a-date-token-in-a-wait-flow-step}

대기 흐름 단계를 사용하여 날짜 토큰을 사용하는 특정 날짜까지 Smart Campaign을 통해 개인의 여정을 일시 중지할 수 있습니다. 종료 날짜를 며칠 단위로 수정할 수도 있습니다.

>[!NOTE]
>
>이는 트리거 캠페인에만 적용됩니다. 일괄 캠페인에서는 이 기능을 사용할 수 없습니다.

1. 스마트 캠페인 **[!UICONTROL Flow]** 탭에서 **[!UICONTROL Wait]** 흐름 단계 위로 끌어서 놓습니다.

   ![](assets/use-a-date-token-in-a-wait-flow-step-1.png)

1. 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/use-a-date-token-in-a-wait-flow-step-2.png)

1. **[!UICONTROL Type]** 드롭다운에서 **[!UICONTROL Date Token]**&#x200B;을(를) 선택합니다.

   ![](assets/use-a-date-token-in-a-wait-flow-step-3.png)

1. [!UICONTROL Date token]을(를) 선택하여 대기 단계가 종료되는 시기를 지정하십시오.

   * `{{my._____}}`
   * `{{lead.______}}`
   * `{{company.______}}`
   * `{{system._______}}`

   ![](assets/use-a-date-token-in-a-wait-flow-step-4.png)

1. 현재 또는 다음 연도에 발생하는 날짜의 다음 기념일까지 대기하려면 상자를 선택합니다.

   ![](assets/use-a-date-token-in-a-wait-flow-step-5.png)

   >[!TIP]
   >
   >생일 또는 계약 시작 날짜와 같이 과거의 날짜를 참조하는 날짜 토큰에 이 옵션을 사용합니다.

1. 종료 일자를 지정된 일수로 수정할 수 있습니다(선택적).

   ![](assets/use-a-date-token-in-a-wait-flow-step-6.png)

   >[!NOTE]
   >
   >정수 필드를 나타내는 `{{lead.` 또는 `{{company.` 토큰이나 숫자 유형의 `{{my.` 토큰을 사용하여 일 수를 지정할 수도 있습니다.

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/use-a-date-token-in-a-wait-flow-step-7.png)

   >[!MORELIKETHIS]
   >
   >* [대기 흐름 단계에서 기간 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md){target="_blank"}
   >* [대기 흐름 단계에서 특정 날짜 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}

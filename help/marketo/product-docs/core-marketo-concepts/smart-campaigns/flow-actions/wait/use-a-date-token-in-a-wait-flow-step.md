---
unique-page-id: 1146997
description: 대기 흐름 단계에서 날짜 토큰 사용 - Marketo 문서 - 제품 설명서
title: 대기 흐름 단계에서 날짜 토큰 사용
exl-id: d161922b-ce90-4e65-9282-d3bb866c1d94
feature: Smart Campaigns
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '213'
ht-degree: 0%

---

# 대기 흐름 단계에서 날짜 토큰 사용 {#use-a-date-token-in-a-wait-flow-step}

대기 흐름 단계를 사용하여 날짜 토큰을 사용하는 특정 날짜까지 Smart Campaign을 통해 개인의 여정을 일시 중지할 수 있습니다. 종료 날짜를 며칠 단위로 수정할 수도 있습니다.

>[!NOTE]
>
>이는 트리거 캠페인에만 적용됩니다. 일괄 캠페인에서는 이 기능을 사용할 수 없습니다.

1. 스마트 캠페인에서 **[!UICONTROL 플로우]** 탭, 위로 드래그 **[!UICONTROL 대기]** 흐름 단계.

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. 다음에서 **[!UICONTROL 유형]** 드롭다운, 선택 **[!UICONTROL 날짜 토큰]**.

   ![](assets/image2014-9-22-14-3a8-3a41.png)

1. 대기 단계가 종료되는 시기를 지정하려면 날짜 토큰을 선택하십시오.

   * `{{my._____}}`
   * `{{lead.______}}`
   * `{{company.______}}`
   * `{{system._______}}`

   ![](assets/image2014-9-22-14-3a9-3a33.png)

1. 현재 또는 다음 연도에 발생하는 날짜의 다음 기념일까지 대기하려면 상자를 선택합니다.

   ![](assets/image2014-9-22-14-3a9-3a37.png)

   >[!TIP]
   >
   >생일 또는 계약 시작 날짜와 같이 과거의 날짜를 참조하는 날짜 토큰에 이 옵션을 사용합니다.

1. 종료 일자를 지정된 일수로 수정할 수 있습니다(선택적).

   ![](assets/image2014-9-22-14-3a9-3a57.png)

   >[!NOTE]
   >
   >를 사용하여 일 수를 지정할 수도 있습니다. `{{lead.` 또는 `{{company.` 정수 필드를 나타내는 토큰 또는 `{{my.` 숫자 유형의 토큰.

1. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!MORELIKETHIS]
   >
   >* [대기 흐름 단계에서 기간 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md){target="_blank"}
   >* [대기 흐름 단계의 특정 날짜 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}

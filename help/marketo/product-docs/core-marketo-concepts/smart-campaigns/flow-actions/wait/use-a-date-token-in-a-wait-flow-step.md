---
unique-page-id: 1146997
description: 대기 흐름 단계에서 날짜 토큰 사용 - Marketo 문서 - 제품 설명서
title: 대기 흐름 단계에서 날짜 토큰 사용
exl-id: d161922b-ce90-4e65-9282-d3bb866c1d94
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---

# 대기 흐름 단계에서 날짜 토큰 사용 {#use-a-date-token-in-a-wait-flow-step}

대기 흐름 단계를 사용하여 날짜 토큰을 사용하는 특정 날짜까지 스마트 캠페인을 통해 개인의 여정을 일시 중단할 수 있습니다. 일부 일 수로 종료 날짜를 수정할 수도 있습니다.

>[!NOTE]
>
>이 기능은 캠페인을 트리거하는 경우에만 적용됩니다. 배치 캠페인에서는 이 기능을 사용할 수 없습니다.

1. 스마트 캠페인에서 **흐름** 탭에서 위로 드래그합니다. **대기** 흐름 단계.

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. 오른쪽에 있는 톱니바퀴 아이콘을 클릭합니다.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. 에서 **유형** 드롭다운에서 을 선택합니다. **날짜 토큰**.

   ![](assets/image2014-9-22-14-3a8-3a41.png)

1. 대기 단계가 종료될 시기를 지정할 날짜 토큰을 선택합니다.

   * `{{my._____}}`
   * `{{lead.______}}`
   * `{{company.______}}`
   * `{{system._______}}`

   ![](assets/image2014-9-22-14-3a9-3a33.png)

1. 현재 또는 다음 달력 연도에 발생하는 날짜의 다음 기념일까지 기다리려면 상자를 선택합니다.

   ![](assets/image2014-9-22-14-3a9-3a37.png)

   >[!TIP]
   >
   >생일 또는 계약 시작 날짜와 같이 과거 날짜를 참조하는 날짜 토큰에 이 옵션을 사용합니다.

1. 지정한 일 수로 종료 일자를 수정할 수 있습니다(선택적).

   ![](assets/image2014-9-22-14-3a9-3a57.png)

   >[!NOTE]
   >
   >를 사용하여 일 수를 지정할 수도 있습니다 `{{lead.` 또는 `{{company.` 정수 필드 또는 `{{my.` 숫자 유형의 토큰.

1. 클릭 **저장**.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!MORELIKETHIS]
   >
   >* [대기 흐름 단계에서 기간 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md)
   >* [대기 흐름 단계에서 특정 날짜 사용](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md)


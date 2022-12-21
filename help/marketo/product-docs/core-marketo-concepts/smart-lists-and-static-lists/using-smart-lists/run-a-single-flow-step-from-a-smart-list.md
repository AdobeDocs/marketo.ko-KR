---
unique-page-id: 557322
description: 스마트 목록에서 단일 흐름 단계 실행 - Marketo 문서 - 제품 설명서
title: 스마트 목록에서 단일 흐름 단계 실행
exl-id: 1ac5795b-1906-4f94-bd0a-570d55c9357b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 1%

---

# 스마트 목록에서 단일 흐름 단계 실행 {#run-a-single-flow-step-from-a-smart-list}

1회 전용 흐름 단계를 실행하려는 경우 전체 스마트 캠페인을 만드는 대신 스마트 목록 내에서 단일 흐름 단계를 사용할 수 있습니다.

>[!PREREQUISITES]
>
>[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-1.png)

1. 사람이 있는 목록 또는 스마트 목록을 선택한 다음 **사람** 탭.

   ![](assets/smartlistpeopletab-hands.png)

   >[!TIP]
   >
   >스마트 목록과 정적 목록 모두 이 기능이 있습니다.

1. 클릭 **모두 선택**. 를 사용할 수도 있습니다 **Ctrl/Cmd** 을(를) 클릭하여 수동으로 몇 개의 레코드를 선택합니다.

   ![](assets/smartlist-selectallhand.png)

   >[!NOTE]
   >
   >결과가 여러 페이지에 걸쳐 있는 경우 **모두 선택** 모든 페이지에서 모든 사람을 선택합니다.

1. 아래 **개인** **작업**&#x200B;을(를) 선택한 흐름 단계를 선택합니다. 이 예제에서는 [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md).

   ![](assets/personactions-hands.png)

1. 찾기 및 선택 **속성**. 이 예에서는 &quot;California&quot;라는 주가 있는 모든 사용자를 선택하고 &quot;CA&quot;로 변경합니다.

   ![](assets/runaction-hands.png)

1. 새 값 입력. 클릭 **지금 실행**.

   ![](assets/runactionnewvalue-hands.png)

1. 많은 사람의 데이터 값을 변경하는 경우 숫자를 입력하여 변경 내용을 확인해야 할 수 있습니다. 클릭 **Go For It**.

   ![](assets/changedatavalue.jpg)

멋진 일! 오른쪽 상단 모서리에는 단일 흐름 단계의 상태가 표시됩니다.

![](assets/completesingleflowaction.jpg)

완료되면 목록을 새로 고치면 업데이트된 정보가 표시됩니다.

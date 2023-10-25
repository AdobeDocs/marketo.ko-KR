---
unique-page-id: 557322
description: 스마트 목록에서 단일 흐름 단계 실행 - Marketo 문서 - 제품 설명서
title: 스마트 목록에서 단일 흐름 단계 실행
exl-id: 1ac5795b-1906-4f94-bd0a-570d55c9357b
feature: Smart Lists
source-git-commit: 8a5903fa5313e34f448f833f20ab8e3624cf23e6
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 1%

---

# 스마트 목록에서 단일 흐름 단계 실행 {#run-a-single-flow-step-from-a-smart-list}

일회성 흐름 단계를 실행하려는 경우 전체 스마트 캠페인을 만드는 대신 스마트 목록 내에서 단일 흐름 단계를 사용할 수 있습니다.

>[!PREREQUISITES]
>
>[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}

1. 다음으로 이동 **[!UICONTROL 마케팅 활동]**.

   ![](assets/login-marketing-activities-1.png)

1. 목록 또는 대상이 있는 스마트 목록을 선택한 다음 **[!UICONTROL 사람]** 탭.

   ![](assets/smartlistpeopletab-hands.png)

   >[!TIP]
   >
   >정적 목록과 스마트 목록 모두에 이 기능이 있습니다.

1. 클릭 **[!UICONTROL 모두 선택]**. 다음을 사용할 수도 있습니다. **Ctrl/Cmd** 을(를) 클릭하여 몇 개의 레코드를 수동으로 선택합니다.

   ![](assets/smartlist-selectallhand.png)

   >[!NOTE]
   >
   >결과가 여러 페이지에 걸쳐 있는 경우 **[!UICONTROL 모두 선택]** 은(는) 모든 페이지에서 모든 사람을 선택합니다.

1. 아래 **[!UICONTROL 개인 작업]**&#x200B;원하는 플로우 단계를 선택합니다. 이 예제에서는 를 [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md){target="_blank"}.

   ![](assets/personactions-hands.png)

1. 다음을 찾아 선택 **[!UICONTROL 속성]**. 이 예제에서는 주 &quot;California&quot;가 있는 모든 사람을 &quot;CA&quot;로 변경합니다.

   ![](assets/runaction-hands.png)

1. 새 값 입력. 클릭 **[!UICONTROL 지금 실행]**.

   ![](assets/runactionnewvalue-hands.png)

1. 많은 수의 사용자에 대한 데이터 값을 변경하는 경우 숫자를 입력하여 변경 내용을 확인해야 할 수 있습니다. 클릭 **[!UICONTROL 시도해 보십시오.]**.

   ![](assets/changedatavalue.jpg)

멋진 작품이야! 오른쪽 상단 모서리에 단일 흐름 단계의 상태가 표시됩니다.

![](assets/completesingleflowaction.jpg)

완료되면 목록을 새로 고치면 업데이트된 정보가 표시됩니다.

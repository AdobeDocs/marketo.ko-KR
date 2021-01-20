---
unique-page-id: 557322
description: 스마트 목록에서 단일 흐름 단계 실행 - 마케팅 문서 - 제품 설명서
title: 스마트 목록에서 단일 흐름 단계 실행
translation-type: tm+mt
source-git-commit: 5b9f48c98464c79bcdca2e335f6a4a2edce98ce4
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---


# 스마트 목록 {#run-a-single-flow-step-from-a-smart-list}에서 단일 흐름 단계 실행

일회성 전용 흐름 단계를 실행하려면 전체 스마트 캠페인을 만드는 대신 스마트 목록 내에서 단일 흐름 단계를 사용할 수 있습니다.

>[!PREREQUISITES]
>
>[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/login-marketing-activities-1.png)

1. 포함된 사람과 함께 목록 또는 스마트 목록을 선택한 다음 **사람** 탭으로 이동합니다.

   ![](assets/smartlistpeopletab-hands.png)

   >[!TIP]
   >
   >스마트 목록뿐만 아니라 정적 목록에도 이 기능이 있습니다.

1. **모두 선택**&#x200B;을 클릭합니다. **Ctrl/Cmd**&#x200B;를 사용하고 을 클릭하여 몇 개의 레코드를 수동으로 선택할 수도 있습니다.

   ![](assets/smartlist-selectallhand.png)

   >[!NOTE]
   >
   >결과가 여러 페이지에 걸쳐 있는 경우 **모두 선택**&#x200B;을 클릭하면 모든 페이지의 모든 사용자가 선택됩니다.

1. **Person** **Actions**&#x200B;에서 원하는 흐름 단계를 선택합니다. 이 예에서는 [데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)을 사용합니다.

   ![](assets/personactions-hands.png)

1. **특성**&#x200B;을 찾아 선택합니다. 이 예에서는 &quot;California&quot; 상태가 있는 모든 사용자를 &quot;CA&quot;로 변경합니다.

   ![](assets/runaction-hands.png)

1. 새 값을 입력합니다. **지금 실행**&#x200B;을 클릭합니다.

   ![](assets/runactionnewvalue-hands.png)

1. 많은 사람의 데이터 값을 변경하는 경우 숫자를 입력하여 변경 사항을 확인해야 합니다. **이동**&#x200B;을 클릭합니다.

   ![](assets/changedatavalue.jpg)

멋진 작품! 오른쪽 상단 모서리에 단일 흐름 단계의 상태가 표시됩니다.

![](assets/completesingleflowaction.jpg)

완료되면 목록을 새로 고치면 업데이트된 정보가 표시됩니다.

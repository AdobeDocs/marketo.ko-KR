---
title: 스마트 캠페인 이해
description: 일괄 처리 이해 및 스마트 캠페인 트리거
exl-id: 54f38ecc-1b4c-4944-9f42-d8c1190c99d0
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 0%

---

# 일괄 처리 이해 및 스마트 캠페인 트리거

<br> 

스마트 캠페인에는 두 가지 유형이 있습니다.일괄 처리 및 트리거를 참조하십시오.

## Batch Smart Campaign

배치 캠페인은 특정 시간에 실행되며 특정 사용자 집합에 한 번에 모두 영향을 줍니다. 예를 들어, 캘리포니아에 살고 있는 데이터베이스에 있는 모든 사람에게 이메일을 보내는 것입니다.

일괄 처리 스마트 캠페인에는 스마트 목록 섹션(즉, 트리거가 없음)에만 필터가 있습니다.

![이미지 원](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-1.png)

**[!UICONTROL Schedule]** 탭을 클릭하면 스마트 캠페인이 &quot;일괄 처리&quot;로 설정되어 있는지 확인합니다.

![이미지 2](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-2.png)

**스마트 캠페인 일괄 처리**

* 일별, 주별, 월별 등 반복용으로 예약할 수 있습니다. 한 번만 실행하면 됩니다.
* [프로그램 일정 보기](https://docs.marketo.com/display/DOCS/Navigating+the+Program+Schedule+View)에 표시됩니다.
* 스마트 캠페인 내의 &quot;대기&quot; 단계 이후의 모든 항목은 보기에 포함되지 않습니다.

## 스마트 캠페인 트리거

트리거 스마트 캠페인은 트리거된 이벤트를 기반으로 한 번에 한 명에게 영향을 줍니다. 트리거의 예는 이메일의 링크를 클릭하는 것입니다.

스마트 캠페인이 스마트 목록 섹션 내에서 하나 이상의 트리거를 사용하는 경우 모드는 자동으로 트리거로 설정됩니다.

![이미지 3](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-3.png)

**[!UICONTROL Schedule]** 탭을 클릭하면 스마트 캠페인이 &quot;트리거&quot;로 설정되어 있는지 확인합니다.

![이미지 4](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-4.png)

**스마트 캠페인 트리거**

* 재귀용으로 예약할 수 없습니다. 활성 또는 비활성 상태로만 설정할 수 있습니다.
* 둘 이상의 트리거를 설정할 수 있습니다. 그러나 _임의의_ 트리거가 실행되는 경우 캠페인 작업이 실행됩니다.

>[!TIP]
>
>[활동 로그](https://docs.marketo.com/display/DOCS/Locate+the+Activity+Log+for+a+Person)를 사용하여 스마트 캠페인 내에서 단계별로 발생한 상황을 확인합니다. 개인 세부 정보 페이지의 마지막 탭에서 활동 로그를 찾을 수 있습니다.

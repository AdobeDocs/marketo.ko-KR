---
unique-page-id: 4718683
description: 단계 승인 및 수익 모델에 리드 할당 - Marketo 문서 - 제품 설명서
title: 단계 승인 및 수익 모델에 리드 지정
exl-id: 0c93dfe4-8950-444c-a65b-080620816ba2
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---

# 단계 승인 및 수익 모델에 리드 지정 {#approving-stages-and-assigning-leads-to-a-revenue-model}

가져오기 **수익 모델** 기존 가망 고객을 추가하고 새 가망 고객에 대한 지정 규칙을 생성하여 실행.

## 단계 승인 {#approving-stages}

리드를 추가하기 전에 모델의 단계를 승인하겠습니다.

1. 로 이동 **분석** 영역입니다.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 승인할 단계가 있는 모델을 선택합니다.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. 아래 **모델 작업**, 선택 **단계 승인**.

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. 경고 메시지가 표시됩니다. 클릭 **리드 할당**.

   ![](assets/image2015-4-28-17-3a5-3a39.png)

훌륭합니다! 계속해서 해당 리드를 할당해 보겠습니다.

## 기존 리드 할당 {#assigning-existing-leads}

[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 리드 데이터베이스에서 모델의 한 단계에 대한 리드를 식별합니다.

1. 다음 작업을 완료하면 [이(가) 내 스마트 목록을 만들었습니다.](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)를 클릭하고 **잠재 고객** 탭.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. 클릭 **모두 선택** 잠재 고객을 선택합니다.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. 를 엽니다. **잠재 고객 작업** 드롭다운 및 선택 **특별 광고**. 클릭 **수익 단계 변경**.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. 올바른 항목 선택 **모델** 및 올바른 **단계**. 클릭 **지금 실행**.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. 모든 잠재 고객이 모델의 다양한 단계에 할당될 때까지 반복합니다.

잘됐네! 단계에 신규 가망 고객을 지정하는 방법을 지정하려면 지정 규칙을 생성합니다.

>[!NOTE]
>
>모델이 Approved Stages 상태인 경우 리드의 활동 로그에 Change Revenue Stage 이벤트가 표시되지 않습니다. 모델이 완전히 승인된 경우 리드를 현재 있는 동일한 단계로 이동하면 이 흐름 단계를 건너뜁니다.

## 신규 가망 고객: 지정 규칙 생성  {#new-leads-create-assignment-rules}

1. 클릭 **Marketo 홈** 다시 선택한 다음 를 선택합니다. **분석**.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 트리에서 모델을 클릭한 다음 **모델 작업** 메뉴, 선택 **할당 규칙**.

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. 할당 규칙에 기본 선택 항목이 두 개 이상 있는 경우 다음을 클릭하십시오. **단계**&#x200B;을(를) 만든 다음 을(를) 클릭합니다 **선택 항목 추가**.

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## 할당 규칙 예 {#example-assignment-rule}

Lead Score 규칙을 만들어 최소 점수가 있는 새로운 Lead 를 적절한 단계에 할당합니다.

1. 아래 **If**, 선택 **잠재 고객 스코어**. 그런 다음 선택 **최소**.

   ![](assets/image2015-4-29-13-3a27-3a8.png)

1. 입력 **40** 필드에서 을(를) 선택하고 **영업 리드** 스테이지. 클릭 **저장** 완료를 위해.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>모델을 승인하려면에 있는 도움말 페이지를 참조하십시오. **[수익 모델 승인 및 승인 취소](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/approve-unapprove-a-revenue-model.md)**.

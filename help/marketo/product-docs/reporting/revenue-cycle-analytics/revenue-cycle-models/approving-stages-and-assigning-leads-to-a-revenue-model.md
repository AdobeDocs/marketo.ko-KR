---
unique-page-id: 4718683
description: 단계 승인 및 매출 모델에 리드 할당 - Marketo 문서 - 제품 설명서
title: 단계 승인 및 수익 모델에 리드 지정
exl-id: 0c93dfe4-8950-444c-a65b-080620816ba2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---

# 단계 승인 및 수익 모델에 리드 지정 {#approving-stages-and-assigning-leads-to-a-revenue-model}

다운로드 **매출 모델** 기존 리드를 추가하고 신규 리드에 대한 지정 규칙을 만들어 실행

## 단계 승인 {#approving-stages}

리드를 추가하기 전에 모델의 단계를 승인하겠습니다.

1. 로 이동합니다. **Analytics** 영역.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 단계를 승인할 모델을 선택합니다.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. 아래 **모델 작업**, 선택 **단계 승인**.

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. 당신은 경고를 받게 될 것입니다. click **리드 할당**.

   ![](assets/image2015-4-28-17-3a5-3a39.png)

훌륭해요! 계속 진행하여 이러한 리드를 할당해 보겠습니다.

## 기존 리드 할당 {#assigning-existing-leads}

[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 리드 데이터베이스에서 모델의 한 단계에 대한 리드를 식별하기 위한 것입니다.

1. 일단 [스마트 목록을 만들었습니다.](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)를 클릭하고 **리드** 탭.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. 클릭 **모두 선택** 를 클릭하여 리드를 선택합니다.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. 를 엽니다. **리드 작업** 드롭다운 및 선택 **특수**. 클릭 **매출 단계 변경**.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. 올바른 을 선택합니다. **모델** 그리고 **단계**. 클릭 **지금 실행**.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. 모든 리드가 모델의 여러 단계에 지정될 때까지 이 작업을 반복합니다.

좋아요! 새 리드가 단계에 지정되는 방법을 지정하려면 할당 규칙을 만듭니다.

>[!NOTE]
>
>모델이 승인된 단계 상태에 있으면 리드의 활동 로그에 매출 단계 변경 이벤트가 표시되지 않습니다. 모델이 완전히 승인된 경우 현재 있는 동일한 단계로 리드를 이동하는 경우 이 흐름 단계를 건너뜁니다.

## 새로운 리드: 할당 규칙 만들기  {#new-leads-create-assignment-rules}

1. 클릭 **Marketo 홈** 다시 한 번 선택한 다음 **Analytics**.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 트리에서 모델을 클릭한 다음 **모델 작업** 메뉴, 선택 **할당 규칙**.

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. 할당 규칙에 기본 선택 항목이 두 개 이상인 경우 **단계**&#x200B;을 선택하고 을 클릭합니다. **선택 추가**.

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## 할당 규칙 예 {#example-assignment-rule}

리드 점수 규칙을 만들어 최소 점수가 있는 새 리드를 적절한 단계에 지정합니다.

1. 아래 **If**, 선택 **리드 점수**. 그런 다음 **적어도**.

   ![](assets/image2015-4-29-13-3a27-3a8.png)

1. Enter 키 **40** 필드에서 을(를) 선택하고 을(를) 선택합니다. **영업 리드** 무대. 클릭 **저장** 을 클릭하여 완료합니다.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>모델을 승인하려면 다음 위치에서 도움말 페이지를 참조하십시오. **[수익 모델 승인 및 승인 취소](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/approve-unapprove-a-revenue-model.md)**.

---
unique-page-id: 4718683
description: 단계 승인 및 수익 모델에 리드 할당 - 마케팅 문서 - 제품 설명서
title: 단계 승인 및 수익 모델에 리드 지정
translation-type: tm+mt
source-git-commit: cb7df3dd38275837f8ab05ce846c2c68ab78462f
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---


# 단계 승인 및 수익 모델에 리드 할당 {#approving-stages-and-assigning-leads-to-a-revenue-model}

기존 리드를 추가하고 새 리드에 대한 할당 규칙을 만들어 **매출 모델**&#x200B;을 시작하고 실행합니다.

## 단계 승인 {#approving-stages}

리드를 추가하기 전에 모델의 단계를 승인하겠습니다.

1. **분석** 영역으로 이동합니다.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 스테이지를 승인할 모델을 선택합니다.

   ![](assets/image2015-4-28-17-3a10-3a3.png)

1. **모델 작업**&#x200B;에서 **단계 승인**&#x200B;을 선택합니다.

   ![](assets/image2015-4-28-17-3a12-3a37.png)

1. 당신은 경고를 받게 될 것입니다.**리드 할당**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-28-17-3a5-3a39.png)

훌륭해! 다른 리드를 지정하여

## 기존 리드 할당 {#assigning-existing-leads}

[리드 ](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 데이터베이스에서 모델의 한 단계에 대한 리드를 식별하는 스마트 목록을 만듭니다.

1. [스마트 목록](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)을 만들었으면 **리드** 탭을 클릭합니다.

   ![](assets/image2015-4-29-11-3a37-3a30.png)

1. **모두 선택**&#x200B;을 클릭하여 리드를 선택합니다.

   ![](assets/image2015-4-29-11-3a39-3a39.png)

1. **리드 작업** 드롭다운을 열고 **특별**&#x200B;을 선택합니다. **매출 단계 변경**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-29-11-3a40-3a38.png)

1. 올바른 **모델** 및 올바른 **스테이지**&#x200B;를 선택합니다. **지금 실행**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-29-11-3a43-3a41.png)

1. 모든 리드가 모델의 다양한 단계에 할당될 때까지 반복합니다.

좋아요! 새 리드가 스테이지에 할당되는 방식을 지정하려면 할당 규칙을 만듭니다.

>[!NOTE]
>
>모델이 승인된 단계 상태인 경우 리드의 활동 로그에 매출 단계 변경 이벤트가 표시되지 않습니다. 모델이 완전히 승인된 경우 현재 있는 동일한 단계로 리드를 이동하면 이 흐름 단계를 건너뜁니다.

## 새 리드:할당 규칙 만들기 {#new-leads-create-assignment-rules}

1. **Marketing To Home**&#x200B;을 다시 클릭한 다음 **Analytics**&#x200B;를 선택합니다.

   ![](assets/image2015-4-28-17-3a8-3a8.png)

1. 트리에서 모델을 클릭한 다음 **모델 작업** 메뉴에서 **할당 규칙**&#x200B;을 선택합니다.

   ![](assets/image2015-4-29-11-3a52-3a17.png)

1. 할당 규칙에 기본 선택 항목이 두 개 이상인 경우 **스테이지**&#x200B;를 클릭한 다음 **선택 추가**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-29-12-3a5-3a46.png)

## 할당 규칙 예 {#example-assignment-rule}

리드 점수 규칙을 만들어 최소 점수가 있는 새 리드를 적절한 단계에 지정합니다.

1. **If**&#x200B;에서 **리드 점수**&#x200B;를 선택합니다. 그런 다음 **적어도**&#x200B;을 선택합니다.

   ![](assets/image2015-4-29-13-3a27-3a8.png)

1. 필드에 **40**&#x200B;을 입력하고 **영업 리드**&#x200B;을 스테이지로 선택합니다. **저장**&#x200B;을 클릭하여 완료합니다.

   ![](assets/image2015-4-29-14-3a4-3a23.png)

>[!MORELIKETHIS]
>
>모델을 승인하려면 **[매출 모델 승인 및 승인 취소](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/approve-unapprove-a-revenue-model.md)**&#x200B;에 있는 도움말 페이지를 읽으십시오.

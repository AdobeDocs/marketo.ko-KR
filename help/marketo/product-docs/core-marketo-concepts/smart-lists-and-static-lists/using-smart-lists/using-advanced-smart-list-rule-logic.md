---
unique-page-id: 1146901
description: 고급 스마트 목록 규칙 논리 사용 - Marketo 문서 - 제품 설명서
title: 고급 스마트 목록 규칙 논리 사용
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---

# 고급 스마트 목록 규칙 논리 사용 {#using-advanced-smart-list-rule-logic}

스마트 목록 내의 여러 필터에 스마트 목록 규칙 논리를 적용하여 필요한 정확한 사람을 찾을 수 있습니다. 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* [스마트 목록에 필터 찾기 및 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
>* [스마트 목록 필터 정의](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md)


>[!NOTE]
>
>고급 필터 로직은 스마트 목록에 필터가 3개 이상 있는 경우에만 사용할 수 있습니다.

## 스마트 목록에 논리 추가 {#add-logic-to-a-smart-list}

기본적으로 스마트 목록에는 일치하는 사람이 있습니다 **모두** 필터(필터 1) _및_ 2개 _및_ 3) 규칙 논리를 변경하여 일치하는 사람을 찾을 수 있습니다 **임의** 정의된 필터(필터 1) _또는_ 2개 _또는_ 3) 또는 고급 필터 사용(필터 1 _및_ 2개 _또는_ 3)

이 예에서, 캘리포니아에 있는 사람을 찾겠다고 가정해 보겠습니다 _및_ 점수가 최소 50점 _또는_ &quot;Sales Qualified&quot; 상태로 설정됩니다.

1. 선택 **고급 필터 사용** 드롭다운

   ![](assets/one.png)

   >[!NOTE]
   >
   >사용 **고급** 필터는 스마트 목록 멤버로 스마트 목록을 만들 필요가 없습니다. 이렇게 하면 성능을 최적화할 수 있습니다.

1. 다음 **고급 필터** 텍스트 상자에 &quot;and&quot;가 모든 필터 사이의 기본값으로 표시됩니다.

   ![](assets/two-2.png)

1. &quot;2 및 3&quot; 주위에 괄호 쌍을 입력합니다.

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >규칙 논리를 입력할 때 &quot;or&quot; 앞에 &quot;and&quot;를 사용해야 합니다.

1. &quot;2와 3&quot; 사이의 &quot;and&quot;를 &quot;or&quot;로 변경합니다.

   ![](assets/four-1.png)

## &quot;And&quot; 및 &quot;Or 혼합 시 괄호를 사용하십시오. {#use-parentheses-when-mixing-and-and-or}

&quot;and&quot; 및 &quot;or&quot; 논리를 혼합하려면 의도를 명확히 하기 위해 괄호를 사용해야 합니다.

![](assets/advancedfilters-parent.png)

## 필요한 경우 4개 이상의 필터에 중첩된 괄호를 사용하십시오 {#use-nested-parentheses-for-four-or-more-filters-if-needed}

목적에 따라 4개 이상의 필터를 사용할 때 중첩된 괄호를 추가해야 할 수 있습니다.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>잘못된 규칙을 입력하면 규칙 아래에 빨간색 선이 표시됩니다. 텍스트 위로 스크롤하여 관련 오류 메시지를 확인합니다.

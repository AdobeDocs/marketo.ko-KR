---
unique-page-id: 1146901
description: 고급 스마트 목록 규칙 논리 사용 - Marketo 문서 - 제품 설명서
title: 고급 스마트 목록 규칙 논리 사용
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
feature: Smart Lists
source-git-commit: 8a5903fa5313e34f448f833f20ab8e3624cf23e6
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 0%

---

# 고급 스마트 목록 규칙 논리 사용 {#using-advanced-smart-list-rule-logic}

스마트 목록 내의 여러 필터에 스마트 목록 규칙 논리를 적용하여 필요한 정확한 사람을 찾을 수 있습니다. 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>* [스마트 목록에 필터 찾기 및 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}
>* [스마트 목록 필터 정의](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md){target="_blank"}

>[!NOTE]
>
>고급 필터 논리는 스마트 목록에 필터가 3개 이상 있는 경우에만 사용할 수 있습니다.

## 스마트 목록에 논리 추가 {#add-logic-to-a-smart-list}

기본적으로 스마트 목록은 **[!UICONTROL 모두]** 필터(필터 1 _및_ 2 _및_ 3)와 일치하는 사람을 찾습니다. 규칙 논리를 변경하여 정의된 필터(필터 1 _or_ 2 _or_ 3)의 **[!UICONTROL ANY]**&#x200B;와 일치하는 사용자를 찾거나 고급 필터(필터 1 _and_ 2 _or_ 3)를 사용할 수 있습니다.

이 예에서는 캘리포니아 _and_&#x200B;에서 최소 50점 _or_&#x200B;의 점수를 받고 &quot;판매 적격&quot; 상태의 사람들을 찾고자 한다고 가정해 보겠습니다.

1. 드롭다운에서 **[!UICONTROL 고급 필터 사용]**&#x200B;을 선택합니다.

   ![](assets/one.png)

   >[!NOTE]
   >
   >**[!UICONTROL 고급]** 필터를 사용하면 스마트 목록 필터를 사용하여 스마트 목록을 만들 필요가 줄어듭니다. 이렇게 하면 성능이 최적화됩니다.

1. **[!UICONTROL 고급 필터]** 텍스트 상자에 모든 필터 사이의 기본값으로 &quot;and&quot;가 표시됩니다.

   ![](assets/two-2.png)

1. &quot;2와 3&quot; 주위에 괄호를 한 쌍을 입력합니다.

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >규칙 논리를 입력할 때 &quot;or&quot; 앞에 &quot;and&quot;를 사용해야 합니다.

1. &quot;2와 3&quot; 사이의 &quot;and&quot;를 &quot;or&quot;로 변경합니다.

   ![](assets/four-1.png)

## &quot;And&quot; 및 &quot;Or&quot;를 혼합할 때 괄호 사용 {#use-parentheses-when-mixing-and-and-or}

&quot;and&quot;와 &quot;or&quot; 논리를 혼합하려면 의도를 명확하게 하기 위해 괄호가 필요합니다.

![](assets/advancedfilters-parent.png)

## 필요한 경우 4개 이상의 필터에 대해 중첩된 괄호 사용 {#use-nested-parentheses-for-four-or-more-filters-if-needed}

의도에 따라 4개 이상의 필터를 사용할 때 중첩된 괄호를 추가해야 할 수 있습니다.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>잘못된 규칙을 입력하면 규칙 아래에 빨간색 선이 표시됩니다. 텍스트를 스크롤하여 관련 오류 메시지를 확인합니다.

---
unique-page-id: 1146901
description: 고급 스마트 목록 규칙 논리 사용 - 마케팅 문서 - 제품 설명서
title: 고급 스마트 목록 규칙 논리 사용
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '288'
ht-degree: 0%

---


# 고급 스마트 목록 규칙 논리 사용 {#using-advanced-smart-list-rule-logic}

스마트 목록 내의 여러 필터에 스마트 목록 규칙 논리를 적용하여 필요한 사람을 정확하게 찾을 수 있습니다. 방법

>[!PREREQUISITES]
>
>* [스마트 목록에 필터 찾기 및 추가](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
>* [스마트 목록 필터 정의](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md)

>



>[!NOTE]
>
>고급 필터 로직은 스마트 목록에 3개 이상의 필터가 있는 경우에만 사용할 수 있습니다.

## 스마트 목록에 논리 추가 {#add-logic-to-a-smart-list}

기본적으로 스마트 목록은 **ALL** 필터(필터 1 *및* 2 *및* 3)와 일치하는 사람을 찾습니다. 정의된 필터(필터 1 *또는* 2 *또는* 3)의 **ANY**&#x200B;와 일치하는 사람을 찾도록 규칙 논리를 변경하거나 고급 필터(필터 1 *및* 2 *또는 *3)를 사용할 수 있습니다.

이 예에서는 &quot;Sales Qualified&quot; 상태의 점수가 최소 50점 *또는*&#x200B;인 캘리포니아 *과*&#x200B;에 있는 사람을 찾고자 합니다.

1. 드롭다운에서 **Use** **Advanced** **filters**&#x200B;를 선택합니다.

   ![](assets/one.png)

   >[!NOTE]
   >
   >**고급** 필터를 사용하면 스마트 목록 멤버 필터로 스마트 목록을 만들 필요가 없습니다. 이는 성능을 최적화하는 데 도움이 됩니다.

1. **고급** **filters** 텍스트 상자는 모든 필터 사이에 기본값으로 &quot;and&quot;를 표시합니다.

   ![](assets/two-2.png)

1. &quot;2 및 3&quot; 주위에 괄호 쌍을 입력합니다.

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >규칙 논리를 입력할 때 &quot;or&quot; 앞에 &quot;and&quot;를 사용해야 합니다.

1. &quot;2~3&quot; 사이의 &quot;and&quot;를 &quot;or&quot;로 변경합니다.

   ![](assets/four-1.png)

## &quot;And&quot; 및 &quot;Or {#use-parentheses-when-mixing-and-and-or} 혼합할 때 괄호를 사용합니다.

&quot;and&quot; 및 &quot;or&quot; 논리를 혼합하려면 의도를 명확히 하기 위해 괄호가 필요합니다.

![](assets/advancedfilters-parent.png)

## 필요한 경우 4개 이상의 필터에 중첩된 괄호를 사용합니다 {#use-nested-parentheses-for-four-or-more-filters-if-needed}

목적에 따라 4개 이상의 필터를 사용할 때 괄호를 중첩된 괄호를 추가해야 할 수도 있습니다.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>잘못된 규칙을 입력하면 규칙 아래에 빨간색 선이 표시됩니다. 텍스트 위로 스크롤하여 관련 오류 메시지를 확인합니다.


---
unique-page-id: 2949413
description: 스마트 목록 필터에 제한 추가 - Marketo 문서 - 제품 설명서
title: 스마트 목록 필터에 제한 추가
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# 스마트 목록 필터에 제한 추가 {#add-a-constraint-to-a-smart-list-filter}

스마트 목록을 만들 때 일부 필터에는 &quot;제한&quot;이라는 고급 옵션이 있습니다. 이러한 조건은 검색 범위를 더 좁히는 데 도움이 되도록 필터 및 트리거에 추가할 수 있는 추가 조건입니다.

이 예에서 **[데이터 값이 변경됨](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** MQL에서 SQL으로 상태가 변경된 사람을 찾기 위한 필터입니다.

>[!PREREQUISITES]
>
>* [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
>* [스마트 목록에서 &quot;변경된 데이터 값&quot; 필터 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md)
>


1. 이동 **마케팅 활동**.

   ![](assets/ma-1.png)

1. 제약 조건을 추가할 필터가 있는 스마트 목록을 선택하고 **Smart List** 탭.

   ![](assets/two-3.png)

1. 아래 **제한 추가**, 선택 **이전 값**.

   ![](assets/three-3.png)

1. 을(를) 입력합니다. **이전 값**. 이 예에서는 MQL을 사용합니다.

   ![](assets/four-2.png)

1. 아래 **제한 추가**, 선택 **새 값**.

   ![](assets/five.png)

1. 을(를) 입력합니다. **새 값**. 이 예제에서는 SQL을 사용합니다.

   ![](assets/six.png)

1. 잘했어요! 을(를) 클릭합니다. **사람** 모든 사람들이 **상태** 다음에서 변경 **MQL** to **SQL** 지난 30일 동안

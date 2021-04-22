---
unique-page-id: 2949413
description: 스마트 목록 필터에 제한 추가 - Marketo 문서 - 제품 설명서
title: 스마트 목록 필터에 제한 추가
exl-id: 5345019c-55e7-4afd-b583-90f1a687a71c
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# 스마트 목록 필터 {#add-a-constraint-to-a-smart-list-filter}에 제한 추가

스마트 목록을 만들 때 일부 필터에는 &quot;제한 조건&quot;이라는 고급 옵션이 있습니다. 필터 및 트리거에 추가하여 검색 범위를 더 좁힐 수 있는 추가 조건입니다.

이 예에서 **[데이터 값 변경됨](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** 필터에 일부 제한을 추가하여 상태가 MQL에서 SQL으로 변경된 사람을 찾습니다.

>[!PREREQUISITES]
>
>* [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
>* [스마트 목록에서 &quot;변경된 데이터 값&quot; 필터 사용](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-the-data-value-changed-filter-in-a-smart-list.md)

>



1. **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/ma-1.png)

1. 제약 조건을 추가할 필터가 있는 스마트 목록을 선택하고 **스마트 목록** 탭을 클릭합니다.

   ![](assets/two-3.png)

1. **제한 추가**&#x200B;에서 **이전 값**&#x200B;을 선택합니다.

   ![](assets/three-3.png)

1. **이전 값**&#x200B;을 입력합니다. 이 예에서는 MQL을 사용합니다.

   ![](assets/four-2.png)

1. **제약 조건 추가**&#x200B;에서 **새 값**&#x200B;을 선택합니다.

   ![](assets/five.png)

1. **새 값**&#x200B;을 입력합니다. 이 예에서는 SQL을 사용합니다.

   ![](assets/six.png)

1. 잘했다! **사람** 탭을 클릭하여 지난 30일 동안 **MQL**&#x200B;에서 **SQL**&#x200B;으로 **상태**&#x200B;가 변경된 모든 사람을 확인합니다.

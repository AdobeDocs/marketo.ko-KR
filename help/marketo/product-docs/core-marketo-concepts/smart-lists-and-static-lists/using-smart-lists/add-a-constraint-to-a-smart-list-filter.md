---
unique-page-id: 2949413
description: 스마트 목록 필터 - 마케팅 문서 - 제품 문서에 제한 추가
title: 스마트 목록 필터에 제한 추가
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---


# 스마트 목록 필터에 제한 추가 {#add-a-constraint-to-a-smart-list-filter}

스마트 목록을 만들 때 일부 필터에는 *제한이라는 고급 옵션이 있습니다. *필터 및 트리거에 추가하여 검색 범위를 더 좁힐 수 있는 추가 조건입니다.

이 예에서는 MQL에서 SQL으로 상태가 변경된 사람을 찾기 위해 ** [데이터 값 변경됨](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** 필터에 일부 제약 조건을 추가하겠습니다.

>[!PREREQUISITES]
>
>* [스마트 목록 만들기](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
>* [스마트 목록에서 &quot;변경된 데이터 값&quot; 필터 사용](use-the-data-value-changed-filter-in-a-smart-list.md)

>



1. 마케팅 활동 **으로 이동합니다**.

   ![](assets/ma-1.png)

1. 제약 조건을 추가할 필터가 있는 스마트 목록을 선택하고 **스마트 목록** 탭을 클릭합니다.

   ![](assets/two-3.png)

1. 제한 **추가**&#x200B;아래에서 **이전 값을 선택합니다**.

   ![](assets/three-3.png)

1. 이전 값을 **입력합니다**. 이 예에서는 MQL을 사용합니다.

   ![](assets/four-2.png)

1. 제한 **추가**&#x200B;아래에서 **새 값**&#x200B;을 선택합니다.

   ![](assets/five.png)

1. 새 값 **을 입력합니다**. 이 예에서는 SQL을 사용합니다.

   ![](assets/six.png)

1. 잘했다! 지난 30일 동안 **MQL** 에서 **** SQL로 상태 **변경** 을 **수행한 모든 사용자를 보려면** 사람 탭을 클릭합니다.


---
unique-page-id: 2952636
description: 사용자 지정 논리 - Marketo 문서 - 제품 설명서로 중복 사용자 찾기
title: 사용자 지정 논리로 중복 사용자 찾기
exl-id: e268ca34-03a3-403a-8869-4e2b60bba05c
feature: Smart Lists
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '124'
ht-degree: 0%

---

# 사용자 지정 논리로 중복 사용자 찾기 {#find-duplicate-people-with-custom-logic}

Marketo Engage에는 이메일 주소를 일치시켜 중복 사용자를 찾는 시스템 스마트 목록이 있습니다. 다른 필드를 사용하여 와(과) 중복되는 항목을 찾으려면 다음 방법을 사용하십시오.

>[!PREREQUISITES]
>
>[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}

1. **[!UICONTROL Marketing Activities]** 영역으로 이동합니다.

![](assets/ma-2.png)

1. 스마트 목록을 선택하고 **[!UICONTROL Smart List]** 탭을 클릭합니다.

   ![](assets/two-4.png)

1. **[!UICONTROL Duplicate Fields]** 필터를 찾아 캔버스로 드래그합니다.

   ![](assets/three-4.png)

1. 사용 가능한 네 가지 옵션 중 하나를 선택합니다.

   * [!UICONTROL Email Address]
   * [!UICONTROL Full Name]
   * [!UICONTROL Last Name]
   * [!UICONTROL Updated At]

   >[!NOTE]
   >
   >이메일 주소를 제외한 모든 필드는 대/소문자를 구분합니다. 따라서 전체 이름 필드에 &quot;john doe&quot;를 사용하면 John Doe에 대한 결과가 _not_&#x200B;됩니다.

   ![](assets/four-2.png)

   완료! 이전에 선택한 필드에서 값이 같은 사람을 찾으려면 스마트 목록을 실행합니다.

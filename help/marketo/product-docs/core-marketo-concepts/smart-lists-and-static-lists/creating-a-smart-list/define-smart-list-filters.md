---
unique-page-id: 557316
description: 스마트 목록 필터 정의 - Marketo 문서 - 제품 설명서
title: 스마트 목록 필터 정의
exl-id: ab08c5be-0afa-46d5-9f29-99e1f6b99dea
feature: Smart Lists
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# 스마트 목록 필터 정의 {#define-smart-list-filters}

>[!PREREQUISITES]
>
>* [스마트 목록 만들기](create-a-smart-list.md)
>* [스마트 목록 필터 찾기 및 추가](find-and-add-filters-to-a-smart-list.md)

이제 다음을 수행합니다 [스마트 목록을 만들었습니다.](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 및 [추가된 필터](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md) 이를 위해 필터를 정의해 보겠습니다. 방법은 다음과 같습니다.

계속해서 예를 들어 캘리포니아에 있는 점수가 50이 넘는 모든 사람을 찾기 위해 이러한 필터를 정의해 보겠습니다.

1. 다음으로 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-1.png)

1. 스마트 목록을 선택하고 **스마트 목록** 탭.

   ![](assets/smarlist-choosefilters.png)

1. 찾기 및 선택 **CA** 대상: **시/도** 필터.

   ![](assets/smartlistdefinefilters.png)

   >[!NOTE]
   >
   >두 항목을 모두 저장할 수 있습니다 **캘리포니아** 및 **CA**. 두 값을 모두 필터링하려면 다음을 포함하십시오. _모두_ 캘리포니아주 출신, 배우기  [스마트 목록 필터에 여러 값 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-multiple-values-to-a-smart-list-filter.md).

1. 을(를) 선택합니다 **보다 큼** 연산자 및 enter **50**.

   ![](assets/smartlistfilter-personscore.png)

>[!TIP]
>
>데이터베이스에 불완전한 전자 메일 주소가 포함된 레코드가 있을 수 있다고 생각되면(예: &quot;@adobe.com&quot;) **2** &quot;포함&quot; 연산자를 사용하는 경우 이메일 주소 필터 가 표시됩니다. &quot;contains @adobe.com&quot;가 있는 필터 하나와 &quot;contains adobe.com&quot;이 있는 필터 하나 (@ 기호 제외).

이제 스마트 목록을 만들고 필터를 추가/정의하는 방법을 알 수 있습니다.

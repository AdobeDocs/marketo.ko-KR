---
unique-page-id: 557316
description: 스마트 목록 필터 정의 - Marketo 문서 - 제품 설명서
title: 스마트 목록 필터 정의
exl-id: ab08c5be-0afa-46d5-9f29-99e1f6b99dea
source-git-commit: 4b1b91a933a7a6d103fe0d44ece9ea95759edc5f
workflow-type: tm+mt
source-wordcount: '183'
ht-degree: 0%

---

# 스마트 목록 필터 정의 {#define-smart-list-filters}

>[!PREREQUISITES]
>
>* [스마트 목록 만들기](create-a-smart-list.md)
>* [스마트 목록에 필터 찾기 및 추가](find-and-add-filters-to-a-smart-list.md)


이제 네가 [스마트 목록을 만들었습니다.](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) 및 [추가된 필터](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md) 필터를 정의하겠습니다. 방법은 다음과 같습니다.

이 예제를 계속 진행하여 점수가 50점이 넘는 캘리포니아주 모든 사람을 찾기 위한 필터를 정의하겠습니다.

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-1.png)

1. 스마트 목록을 선택하고 을(를) 클릭합니다. **Smart List** 탭.

   ![](assets/smarlist-choosefilters.png)

1. 찾기 및 선택 **CA** 대상 **주/도** 필터.

   ![](assets/smartlistdefinefilters.png)

   >[!NOTE]
   >
   >둘 다 저장할 수 있습니다 **캘리포니아** 및 **CA**. 두 값을 필터링하고 _모두_ 캘리포니아 출신, 방법 알아보기  [스마트 목록 필터에 여러 값 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-multiple-values-to-a-smart-list-filter.md).

1. 을(를) 선택합니다 **보다 큼** 연산자 및 입력 **50**.

   ![](assets/smartlistfilter-personscore.png)

>[!TIP]
>
>데이터베이스에 불완전한 이메일 주소(예: &quot;@adobe.com&quot;)가 포함된 레코드가 있을 경우 **2개** 포함 연산자를 사용하는 경우 이메일 주소 필터를 사용합니다. &quot;contains @adobe.com&quot; 및 &quot;contains adobe.com&quot;(@ 기호는 제외)이 포함된 별도의 필터가 있는 하나.

이제 스마트 목록을 만들고 필터를 추가/정의하는 방법을 알 수 있습니다.

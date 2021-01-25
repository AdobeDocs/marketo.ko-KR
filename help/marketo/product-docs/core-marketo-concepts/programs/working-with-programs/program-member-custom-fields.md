---
unique-page-id: 37355569
description: 프로그램 멤버 사용자 정의 필드 - 마케팅 문서 - 제품 설명서
title: 프로그램 회원 사용자 정의 필드
translation-type: tm+mt
source-git-commit: 07f713ece9832b7696451001f61c6a3b45b4a94a
workflow-type: tm+mt
source-wordcount: '374'
ht-degree: 0%

---


# 프로그램 멤버 사용자 정의 필드 {#program-member-custom-fields}

프로그램 멤버 사용자 정의 필드를 사용하여 각 멤버에 대한 프로그램 특정 데이터를 수집할 수 있습니다. 이 플러그인은 다음 제품에서 사용할 수 있습니다.마케팅 양식, 스마트 목록 필터 및 트리거, 스마트 캠페인 흐름 작업. 이 데이터는 프로그램의 멤버 탭에서 볼 수 있습니다.

## 프로그램 멤버 사용자 정의 필드 {#create-a-program-member-custom-field} 만들기

1. Marketing에서 **관리**&#x200B;를 클릭합니다.

   ![](assets/one.png)

1. **필드 관리**&#x200B;를 클릭합니다.

   ![](assets/two.png)

1. **새 사용자 지정 필드**&#x200B;를 클릭합니다.

   ![](assets/three.png)

1. 객체 드롭다운을 클릭하고 원하는 객체를 선택합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >개인 및 프로그램 멤버 사용자 정의 필드는 동일한 이름을 공유할 수 없습니다.

1. 나머지 필드를 채우고 **만들기**&#x200B;를 클릭합니다.

   ![](assets/five.png)

   >[!NOTE]
   >
   >프로그램 멤버 사용자 정의 필드에 지원되는 유형은 다음과 같습니다.boolean, date, datetime, float, integer, string, URL. [필드 유형에 대해 자세히 알아보십시오](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md).

## 개체 설명 {#object-descriptions}

| 개체 | 설명 |
|---|---|
| 회사 | 사람과 연관된 회사의 이름. |
| 기회 | 기회는 개인 또는 고객과 연관되거나 향후 판매 가능성으로 연결될 수 있습니다. 일반적으로 CRM이나 API를 통해 Marketing에 입장합니다. |
| Person | 마케팅 캠페인을 통해 Marketing 데이터베이스에 있는 개인 |
| 프로그램 회원 | 프로그램 회원이기도 한 사람 |

## 트리거 및 필터 {#triggers-and-filters}

[트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md) 및/또는 [filters](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)를 통해 스마트 목록에 있는 이 프로그램 관련 데이터를 활용할 수 있습니다.

![](assets/six.png)

## {#things-to-know}을(를) 알아야 하는 사항

* 프로그램 멤버 사용자 정의 필드는 로컬 자산에서만 사용할 수 있습니다. 특정 프로그램에 연결할 방법이 없으므로 Design Studio에서는 지원되지 않습니다.
* 프로그램 멤버 사용자 정의 필드가 포함된 양식(또는 양식이 있는 랜딩 페이지)은 Design Studio로 복제/이동할 수 없습니다.
* 프로그램 멤버 사용자 정의 필드는 토큰으로 사용할 수 없습니다.
* Program Member 객체에는 최대 20개의 사용자 정의 필드가 있을 수 있습니다. 이러한 필드는 모든 프로그램에서 사용할 수 있습니다.
* 프로그램 멤버를 제거하면 해당 프로그램 멤버 사용자 정의 필드에 데이터가 있는 경우 해당 필드에서 데이터가 지워집니다.
* 데이터를 보려면 프로그램의 멤버 탭을 클릭하고 해당 필드를 포함하는 사용자 정의 보기를 만듭니다.
* [list](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)및 [API](https://developers.marketo.com/)를 통해 가져오고 내보낼 수 있습니다.
* 두 사람을 병합하면 우승자의 프로그램 멤버 사용자 정의 필드 데이터가 사용됩니다. 그러나 승자가 없는 경우는 패자의 가치를 매긴다.

>[!MORELIKETHIS]
>
>[Marketing To에서 사용자 정의 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

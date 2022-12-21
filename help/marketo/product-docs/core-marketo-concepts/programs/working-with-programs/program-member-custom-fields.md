---
unique-page-id: 37355569
description: 프로그램 구성원 사용자 지정 필드 - Marketo 문서 - 제품 설명서
title: 프로그램 구성원 사용자 정의 필드
exl-id: 66b5dac6-015f-4907-8c82-78c932102463
source-git-commit: 56f429dabf19c4425c68b0dcd745621681a038ae
workflow-type: tm+mt
source-wordcount: '427'
ht-degree: 1%

---

# 프로그램 구성원 사용자 정의 필드 {#program-member-custom-fields}

프로그램 멤버 사용자 정의 필드를 사용하면 각 멤버에 대한 프로그램별 데이터를 수집할 수 있습니다. 다음 위치에서 사용할 수 있습니다. Marketo 양식, 스마트 목록 필터 및 트리거, Smart Campaign 흐름 작업. 이 데이터는 프로그램의 멤버 탭에서 볼 수 있습니다.

>[!NOTE]
>
>현재 프로그램 구성원 사용자 지정 필드에는 Salesforce 캠페인 구성원 필드와 통합되지 않습니다.

## 프로그램 멤버 사용자 정의 필드 만들기 {#create-a-program-member-custom-field}

1. Marketo에서 **관리**.

   ![](assets/one.png)

1. 클릭 **필드 관리**.

   ![](assets/two.png)

1. 클릭 **새 사용자 지정 필드**.

   ![](assets/three.png)

1. 개체 드롭다운을 클릭하고 원하는 개체를 선택합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >개인 및 프로그램 구성원 사용자 지정 필드는 동일한 이름을 공유할 수 없습니다.

1. 나머지 필드를 작성하고 **만들기**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >프로그램 멤버 사용자 정의 필드에 지원되는 유형은 다음과 같습니다. 부울, 날짜, datetime, float, 정수, 문자열, URL. [필드 유형에 대해 자세히 알아보기](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md){target=&quot;_blank&quot;}.

## 개체 설명 {#object-descriptions}

| 오브젝트 | 설명 |
|---|---|
| 회사 | 사람과 연관된 회사의 이름입니다. |
| 기회 | 잠재 미래 판매로 개인 또는 계정과 연관된 기회가 있을 수 있습니다. 일반적으로 CRM 또는 API를 통해 Marketo에 액세스합니다. |
| 개인 | 마케팅 캠페인을 통해 참여하는 Marketo 데이터베이스의 개인입니다. |
| 프로그램 구성원 | 프로그램의 회원이기도 한 사람 |

## 트리거 및 필터 {#triggers-and-filters}

를 통해 스마트 목록에서 이 프로그램별 데이터를 활용할 수 있습니다 [트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target=&quot;_blank&quot;} 및/또는 [필터](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target=&quot;_blank&quot;}.

![](assets/six.png)

## 알아야 할 사항 {#things-to-know}

* 프로그램 멤버 사용자 지정 필드는 로컬 자산에서만 사용할 수 있습니다. 특정 프로그램에 연결할 방법이 없으므로 Design Studio에서는 지원되지 않습니다.
* 프로그램 구성원 사용자 지정 필드가 포함된 양식(또는 양식이 있는 랜딩 페이지)을 Design Studio로 복제/이동할 수 없습니다.
* 프로그램 멤버 개체에는 최대 20개의 사용자 지정 필드가 있을 수 있습니다. 이러한 필드는 모든 프로그램에서 사용할 수 있습니다.
* 프로그램 멤버를 제거할 때 해당 프로그램 멤버 사용자 정의 필드에 데이터가 있으면 해당 필드에서 데이터가 스크러빙됩니다.
* 데이터를 보려면 프로그램의 멤버 탭을 클릭하고 해당 필드를 포함하는 사용자 지정 보기를 만듭니다.
* 를 통해 가져오기 및 내보내기 [list](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md){target=&quot;_blank&quot;} 및 [API](https://developers.marketo.com/){target=&quot;_blank&quot;}이 지원됩니다. 정적 목록이 아니라 프로그램 구성원 목록에서만 작업을 내보냅니다.
* 두 사람을 병합하면 우승자의 프로그램 구성원 사용자 지정 필드 데이터가 사용됩니다. 그러나 승자가 없는 경우는 패자의 가치만 사용하게 된다.
* 프로그램 구성원 정보 필드에 변경 유형을 사용할 수 없습니다.
* &quot;포함&quot; 스마트 목록 제약 조건은 프로그램 구성원 사용자 지정 필드에 대해 지원되지 않습니다.

>[!MORELIKETHIS]
>
>[Marketo에서 사용자 지정 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target=&quot;_blank&quot;}

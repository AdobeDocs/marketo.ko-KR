---
unique-page-id: 37355569
description: 프로그램 멤버 사용자 정의 필드 - Marketo 문서 - 제품 설명서
title: 프로그램 멤버 사용자 정의 필드
exl-id: 66b5dac6-015f-4907-8c82-78c932102463
feature: Programs
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 1%

---

# 프로그램 멤버 사용자 정의 필드 {#program-member-custom-fields}

프로그램 멤버 사용자 정의 필드를 사용하면 각 멤버에 대한 프로그램별 데이터를 수집할 수 있습니다. Marketo Forms, 스마트 목록 필터 및 트리거, 스마트 Campaign 흐름 작업에서 사용할 수 있습니다. 데이터는 프로그램의 구성원 탭에서 볼 수 있습니다.

## 프로그램 멤버 사용자 정의 필드 만들기 {#create-a-program-member-custom-field}

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/one.png)

1. 클릭 **[!UICONTROL 필드 관리]**.

   ![](assets/two.png)

1. 클릭 **[!UICONTROL 새 사용자 정의 필드]**.

   ![](assets/three.png)

1. 객체 드롭다운을 클릭하고 원하는 객체를 선택합니다.

   ![](assets/four.png)

   >[!NOTE]
   >
   >사용자 및 프로그램 구성원 사용자 정의 필드는 같은 이름을 공유할 수 없습니다.

1. 나머지 필드를 입력한 다음 **[!UICONTROL 만들기]**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >프로그램 멤버 사용자 정의 필드에 지원되는 유형은 부울, 날짜, 날짜, 시간, 부동 소수점, 정수, 문자열, URL입니다. [필드 유형에 대해 자세히 알아보기](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md){target="_blank"}.

## 오브젝트 설명 {#object-descriptions}

| 오브젝트 | 설명 |
|---|---|
| 회사 | 사용자와 연계된 회사의 이름. |
| 기회 | 영업 기회는 잠재적인 향후 판매로 개인 또는 계정과 연관될 수 있습니다. 일반적으로 CRM을 통해 또는 API를 통해 Marketo에 들어갑니다. |
| 개인 | 마케팅 캠페인을 통해 참여하는 Marketo 데이터베이스의 개인입니다. |
| 프로그램 구성원 | 프로그램 멤버이기도 한 사람 |

## 트리거 및 필터 {#triggers-and-filters}

다음을 통해 스마트 목록에서 이 프로그램별 데이터를 활용할 수 있습니다. [트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"} 및/또는 [필터](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}.

![](assets/six.png)

## 알아야 할 사항 {#things-to-know}

* 프로그램 멤버 사용자 정의 필드는 로컬 에셋에서만 사용할 수 있습니다. 특정 프로그램에 연결할 방법이 없으므로 Design Studio에서 지원되지 않습니다.
* 프로그램 멤버 사용자 정의 필드가 포함된 양식(또는 양식이 있는 랜딩 페이지)은 Design Studio로 복제/이동할 수 없습니다.
* [동기화할 수 있음](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md){target="_blank"} 캠페인 멤버 사용자 정의 필드가 있는 프로그램 멤버 사용자 정의 필드.
* 프로그램 멤버 개체에는 최대 20개의 사용자 지정 필드가 있을 수 있습니다. 이들 필드는 모든 프로그램에서 사용할 수 있습니다.
* 프로그램의 구성원을 제거할 때 프로그램 구성원 사용자 지정 필드에 데이터가 있으면 해당 필드에서 데이터가 스크러빙됩니다.
* 데이터를 보려면 프로그램에서 멤버 탭을 클릭하고 해당 필드를 포함하는 사용자 지정 보기를 만듭니다.
* 을 통해 가져오기 및 내보내기 [목록](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md){target="_blank"} 및 [API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/home){target="_blank"} 이 지원됩니다. 내보내기는 정적 목록이 아니라 프로그램 멤버 목록에서만 작동합니다.
* 두 사람을 병합하면 우승자의 프로그램 멤버 사용자 정의 필드 데이터가 사용됩니다. 하지만 승자에게 없는 것이 있으면 패자의 값이 쓰인다.
* 프로그램 구성원 정보 필드에는 유형 변경이 허용되지 않습니다.
* &quot;포함&quot; 스마트 목록 제약 조건은 프로그램 멤버 사용자 정의 필드에 지원되지 않습니다.

>[!MORELIKETHIS]
>
>* [Marketo에서 사용자 정의 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target="_blank"}
>
>* [프로그램 구성원 사용자 정의 필드 동기화](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md){target="_blank"}

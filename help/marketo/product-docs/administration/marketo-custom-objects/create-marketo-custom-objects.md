---
unique-page-id: 10093192
description: Marketo 사용자 지정 개체 만들기 - Marketo 문서 - 제품 설명서
title: Marketo 사용자 지정 개체 만들기
exl-id: d68b41e1-a12b-436f-aad7-42c7264cd901
source-git-commit: 99b11e17e9c2255a19c658b166e7b38c45cf1001
workflow-type: tm+mt
source-wordcount: '704'
ht-degree: 0%

---

# Marketo 사용자 지정 개체 만들기 {#create-marketo-custom-objects}

Marketo의 사용자 지정 개체를 사용하여 비즈니스에 따른 지표를 추적합니다. 이것은 자동차, 교육 과정 등 캠페인을 실행하기 위해 Marketo에서 모델링하고 싶은 모든 것이 될 수 있습니다.

>[!NOTE]
>
>일대다 또는 다대다 기준으로 작동하도록 사용자 정의 개체를 설정할 수 있습니다. 초기 개체를 같은 방법으로 만들지만, 개체에 필드를 추가하기 시작할 때는 단계가 다릅니다. 자세한 내용은  [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) 추가 정보.

>[!NOTE]
>
>사용자 지정 객체가 승인되면 링크 또는 중복 제거 필드를 생성, 편집 또는 삭제할 수 없습니다.

## 일대다 구조에 대한 사용자 지정 개체 만들기 {#create-a-custom-object-for-a-one-to-many-structure}

이 예는 일대다 구조에 사용할 Car 사용자 지정 개체를 보여줍니다. 나중에 다대다 구조에 사용할 코스 사용자 지정 객체와 중간 개체를 만듭니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-marketo-custom-objects-1.png)

1. 클릭 **Marketo 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-2.png)

1. 클릭 **새 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-3.png)

   >[!NOTE]
   >
   >Marketo 사용자 정의 개체 탭에는 오른쪽의 모든 사용자 정의 개체와, 가장 최근 업데이트에서의 레코드 수 및 필드 수를 포함하여 승인된 모든 개체 세부 사항이 표시됩니다.

1. 표시 이름을 입력합니다. API 이름 및 복수 이름이 자동으로 채워집니다. 설명을 입력합니다(선택 사항).

   ![](assets/create-marketo-custom-objects-4.png)

   >[!NOTE]
   >
   >이러한 필드를 만들 때는 편집할 수 있지만 저장한 후에는 복수 이름 필드와 **리드 세부 정보에 표시** 슬라이더.

1. 가져오기 **리드 세부 정보에 표시** 표시할 슬라이더 **표시** 데이터베이스 페이지에서 사용자 지정 객체 데이터를 보려는 경우 클릭 **저장**.

   ![](assets/create-marketo-custom-objects-5.png)

1. 사용자 지정 개체 정보는 입력한 내용을 표시합니다. 초안 상태에 있습니다.

   ![](assets/create-marketo-custom-objects-6.png)

   다음 단계는 필드를 [사용자 지정 개체 작성](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md).

   >[!NOTE]
   >
   >목록 가져오기 또는 [API](https://developers.marketo.com/documentation/rest/).

## 다대다 구조에 대한 사용자 지정 개체 만들기 {#create-a-custom-object-for-a-many-to-many-structure}

이 예에서는 사람/회사와 교육 과정 간에 다대다 관계를 만드는 데 사용할 교육 과정 사용자 지정 개체를 보여줍니다. 완료되면 중간 개체를 만들어 데이터베이스의 사용자나 회사에 연결합니다.

>[!NOTE]
>
>다대다 관계의 경우 사용자 지정 개체에 링크를 만들 필요가 없습니다. 대신 중간 개체에 두 개의 링크를 추가합니다(아래 참조).

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-marketo-custom-objects-7.png)

1. 클릭 **Marketo 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-8.png)

1. 클릭 **새 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-9.png)

1. 표시 이름을 입력합니다. API 이름 및 복수 이름이 자동으로 채워집니다. 설명을 입력합니다(선택 사항).

   ![](assets/create-marketo-custom-objects-10.png)

   >[!NOTE]
   >
   >이러한 필드를 만들 때는 편집할 수 있지만 저장한 후에는 복수 이름 필드와 **리드 세부 정보에 표시** 슬라이더.

1. 가져오기 **리드 세부 정보에 표시** 표시할 슬라이더 **표시** 데이터베이스 페이지에서 사용자 지정 객체 데이터를 보려는 경우 클릭 **저장**.

   ![](assets/create-marketo-custom-objects-11.png)

1. 사용자 지정 개체 정보는 입력한 내용을 표시합니다. 초안 상태에 있습니다.

   ![](assets/create-marketo-custom-objects-12.png)

   >[!NOTE]
   >
   >목록 가져오기 또는 [API](https://developers.marketo.com/documentation/rest/).

다음 단계는 중간 개체를 만드는 것입니다(아래 참조). 하지만 그 전에 필드에 연결된 필드를 만들어야 합니다.

## 중간 객체 만들기 {#create-an-intermediary-object}

중간 객체를 사용하여 사용자 정의 객체를 사용자나 회사에 연결합니다. 이 예제에서는 교육 과정 사용자 정의 객체의 교육 과정을 데이터베이스의 사용자나 회사에 연결하는 데 사용됩니다.

>[!NOTE]
>
>일대다 사용자 정의 개체 구조에 중간 개체를 만들 필요는 없습니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/create-marketo-custom-objects-13.png)

1. 클릭 **Marketo 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-14.png)

1. 클릭 **새 사용자 지정 개체**.

   ![](assets/create-marketo-custom-objects-15.png)

1. 표시 이름을 입력합니다. API 이름 및 복수 이름이 자동으로 채워집니다. 설명을 입력합니다(선택 사항).

   ![](assets/create-marketo-custom-objects-16.png)

   >[!NOTE]
   >
   >이러한 필드를 만들 때는 편집할 수 있지만, 저장한 후에는 복수 이름 필드와 리드 세부 정보 표시 슬라이더만 편집할 수 있습니다.

1. 가져오기 **리드 세부 정보에 표시** 표시할 슬라이더 **표시** 데이터베이스 페이지에서 사용자 지정 객체 데이터를 보려는 경우 클릭 **저장**.

   ![](assets/create-marketo-custom-objects-17.png)

1. 사용자 지정 개체 정보는 입력한 내용을 표시합니다. 초안 상태에 있습니다.

   다음 단계는 다음을 수행하는 것입니다. [링크 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md) 중간 객체를 개인/회사 및 사용자 정의 객체에 연결하기 위해

>[!MORELIKETHIS]
>
>* [Marketo 사용자 지정 개체 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Marketo 사용자 지정 개체 링크 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)


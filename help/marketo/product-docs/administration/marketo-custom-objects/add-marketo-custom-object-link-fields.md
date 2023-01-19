---
unique-page-id: 10097613
description: Marketo 사용자 지정 개체 링크 필드 추가 - Marketo 문서 - 제품 설명서
title: Marketo 사용자 지정 개체 링크 필드 추가
exl-id: e7537d79-9fca-4966-881a-9d7d312008e2
source-git-commit: a51ee0b2b513d50febbffd7e3a72874c5ef4679c
workflow-type: tm+mt
source-wordcount: '599'
ht-degree: 0%

---

# Marketo 사용자 지정 개체 링크 필드 추가 {#add-marketo-custom-object-link-fields}

사용자 지정 개체를 만들 때 사용자 지정 개체 레코드를 올바른 상위 레코드에 연결하려면 링크 필드를 제공해야 합니다.

* 일대다 사용자 지정 구조의 경우 사용자 지정 객체의 링크 필드를 사용하여 개인이나 회사에 연결합니다.
* 다대다 구조의 경우 두 개의 링크 필드를 사용합니다. 이 필드는 별도로 생성된 중간 객체(사용자 정의 객체의 유형)와 연결되어 있습니다. 한 링크는 데이터베이스의 사용자나 회사에 연결되고 다른 링크는 사용자 지정 개체에 연결됩니다. 이 경우 링크 필드는 사용자 지정 개체 자체에 없습니다.

## 일대다 구조에 대한 링크 필드 만들기 {#create-a-link-field-for-a-one-to-many-structure}

다음은 일대다 구조에 대한 사용자 지정 개체에서 링크 필드를 만드는 방법입니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/add-marketo-custom-object-link-fields-1.png)

1. 클릭 **Marketo 사용자 지정 개체**.

   ![](assets/add-marketo-custom-object-link-fields-2.png)

1. 목록에서 사용자 지정 개체를 선택합니다.

   ![](assets/add-marketo-custom-object-link-fields-3.png)

1. 에서 **필드** 탭, **새 필드**.

   ![](assets/add-marketo-custom-object-link-fields-4.png)

1. 링크 필드에 이름을 지정하고 선택적 설명을 추가합니다. 링크 데이터 유형을 선택해야 합니다.

   ![](assets/add-marketo-custom-object-link-fields-5.png)

   >[!CAUTION]
   >
   >사용자 지정 개체가 승인되면 다시 돌아가서 링크 또는 중복 제거 필드를 생성, 편집 또는 삭제할 수 없습니다.

1. 링크 개체가 리드(개인)에 대한 것인지 아니면 회사에 대한 것인지 선택합니다.

   ![](assets/add-marketo-custom-object-link-fields-6.png)

   >[!NOTE]
   >
   >리드를 선택하면 목록에 ID, 이메일 주소 및 사용자 지정 필드가 표시됩니다.
   >
   >회사를 선택하면 목록에 ID 및 사용자 지정 필드가 표시됩니다.

1. 연결할 링크 필드를 새 필드의 상위로 선택합니다.

   ![](assets/add-marketo-custom-object-link-fields-7.png)

   >[!NOTE]
   >
   >링크 필드는 문자열 필드 유형만 지원됩니다.

1. 클릭 **저장.**

   ![](assets/add-marketo-custom-object-link-fields-8.png)

## 다대다 구조에 대한 링크 필드 만들기 {#create-a-link-field-for-a-many-to-many-structure}

다음은 다대다 구조에서 사용할 중간 개체에서 링크 필드를 만드는 방법입니다.

>[!PREREQUISITES]
>
>이미 중간 개체 및 연결하려는 사용자 정의 개체를 만들었어야 합니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/add-marketo-custom-object-link-fields-9.png)

1. 클릭 **Marketo 사용자 지정 개체**.

   ![](assets/add-marketo-custom-object-link-fields-10.png)

1. 필드를 추가할 중간 개체를 선택합니다.

   ![](assets/add-marketo-custom-object-link-fields-11.png)

1. 에서 **필드** 탭, **새 필드**.

   ![](assets/add-marketo-custom-object-link-fields-12.png)

1. 두 개의 링크 필드를 만들어야 합니다. 한 번에 하나씩 만듭니다. 먼저 데이터베이스 목록 구성원의 필드 이름을 지정합니다(예: leadID). 선택적 설명을 추가합니다. 링크 데이터 유형을 선택해야 합니다.

   ![](assets/add-marketo-custom-object-link-fields-13.png)

   >[!CAUTION]
   >
   >사용자 지정 개체가 승인되면 다시 돌아가서 링크 또는 중복 제거 필드를 생성, 편집 또는 삭제할 수 없습니다.

1. 데이터베이스에서 링크 개체를 선택합니다(이 경우 Lead).

   ![](assets/add-marketo-custom-object-link-fields-14.png)

1. 연결할 링크 필드(이 경우 ID)를 선택합니다.

   ![](assets/add-marketo-custom-object-link-fields-15.png)

   >[!NOTE]
   >
   >링크 필드는 문자열 필드 유형만 지원됩니다.

1. 클릭 **저장.**

   ![](assets/add-marketo-custom-object-link-fields-16.png)

1. 사용자 지정 개체에 대한 두 번째 링크(이 예제, courseID)에 대해 이 프로세스를 반복합니다. 링크 개체 이름은 물론, 링크 필드는 courseID입니다. 코스 사용자 정의 객체를 이미 만들고 승인했으므로 드롭다운 메뉴에서 이러한 선택을 사용할 수 있습니다.

   ![](assets/add-marketo-custom-object-link-fields-17.png)

1. 등록 ID 또는 등급과 같이 중간 개체에 사용할 다른 필드를 만듭니다.

## 사용자 정의 개체 사용 {#using-custom-objects}

다음 단계는 스마트 캠페인의 필터에서 이러한 사용자 지정 개체를 사용하는 것입니다. 다대다 관계를 사용하여 여러 사람/회사 및 여러 사용자 지정 개체를 선택할 수 있습니다. 아래 예에서는 이러한 기준과 일치하는 데이터베이스의 모든 사용자가 나열됩니다. 교육 과정 사용자 정의 객체에서 가져온 교육 과정 이름 필드는 중간 객체에서 가져옵니다.

![](assets/add-marketo-custom-object-link-fields-18.png)

>[!MORELIKETHIS]
>
>* [Marketo 사용자 지정 개체 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Marketo 사용자 지정 개체 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
>* [Marketo 사용자 지정 개체 필드 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)


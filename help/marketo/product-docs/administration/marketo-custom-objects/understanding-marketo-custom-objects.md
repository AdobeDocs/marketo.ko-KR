---
unique-page-id: 10093188
description: Marketo 사용자 지정 개체 이해 - Marketo 문서 - 제품 설명서
title: Marketo 사용자 정의 오브젝트 이해
exl-id: f18b1689-c7bc-4da0-8326-7b29733d527d
feature: Custom Objects
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '689'
ht-degree: 2%

---

# Marketo 사용자 정의 오브젝트 이해 {#understanding-marketo-custom-objects}

사용자 지정 개체를 사용하여 비즈니스와 관련된 지표를 추적합니다.

>[!AVAILABILITY]
>
>모든 Marketo Engage 사용자가 이 기능을 구입한 것은 아닙니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

사용자 지정 개체를 스마트 캠페인의 필터 및 트리거로 사용합니다. 예:

* **필터**: 특정 차량 브랜드의 소유자에게만 전자 메일을 보냅니다.
* **트리거**: 사용자 지정 개체가 개인 또는 회사에 추가되면 전자 메일을 보냅니다.

일대다 또는 다대다 관계에서 사용자 지정 개체를 설정할 수 있습니다. 예:

* **일대다**: 한 사람이 여러 대의 자동차를 소유합니다.
* **다대다**: 과정 카탈로그에서 여러 과정에 여러 학생이 등록되었습니다

일대다 구조는 단일 링크 필드를 사용하여 사용자 지정 개체를 개인 또는 회사에 연결합니다.

다대다 사용자 지정 개체는 중간 개체의 일부인 두 개의 링크 필드를 사용합니다. 한 링크 필드는 개인이나 회사에 연결되고 다른 링크 필드는 강의 카탈로그와 같은 사용자 지정 개체에 연결됩니다. 이 중간 개체에는 연결의 특성을 더 정의하는 강의 등급이나 참석 날짜와 같은 추가 사용자 정의 필드가 포함될 수 있습니다.

>[!TIP]
>
>사용자 인터페이스 내에서 CSV(쉼표로 구분된 값)를 사용하여 사용자 지정 개체를 가져와서 데이터 샘플을 테스트하고 유효성을 검사합니다. 그런 다음 API를 사용하여 모든 파일을 업로드합니다.

>[!CAUTION]
>
>사용자 지정 개체는 복원할 수 없으므로 삭제하기 전에 더 이상 필요하지 않은지 확인하십시오.

## Marketo 사용자 지정 개체 액세스 {#accessing-marketo-custom-objects}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/understanding-marketo-custom-objects-1.png)

1. **[!UICONTROL Marketo Custom Objects]**&#x200B;를 클릭합니다.

   ![](assets/understanding-marketo-custom-objects-2.png)

1. Marketo 사용자 지정 개체 디스플레이는 오른쪽에 모든 사용자 지정 개체를 나열하지만, 기본 격자에 있는 승인된 개체만 나열합니다.

   ![](assets/understanding-marketo-custom-objects-3.png)

   >[!NOTE]
   >
   >표에는 객체 이름, 레코드 수, 필드 수 및 가장 최근 업데이트 날짜가 표시됩니다.

   >[!TIP]
   >
   >Marketo은 이러한 필드를 자동으로 업데이트하지만 레코드 열에서 아이콘을 클릭하여 표시를 새로 고칠 수 있습니다.

1. 오른쪽의 개체 이름을 클릭하여 세부 정보 페이지를 엽니다.

   ![](assets/understanding-marketo-custom-objects-4.png)

## 개인과 연관된 사용자 정의 객체 보기 {#view-custom-objects-associated-to-a-person}

사용자 지정 개체 구조를 만든 후 특정 사용자 지정 개체 데이터를 업로드하면 사용자 지정 개체의 링크 필드를 사용하여 사용자 지정 개체가 자동으로 데이터베이스의 사용자와 연결됩니다. 개인 세부 정보 페이지의 [!UICONTROL Custom Objects] 탭에서 정보를 볼 수 있습니다.

1. **[!UICONTROL Database]**(으)로 이동합니다.

   ![](assets/understanding-marketo-custom-objects-5.png)

1. 데이터베이스를 열고 **[!UICONTROL People]** 탭을 클릭합니다. 사용자 지정 개체에 연결한 개인의 레코드를 두 번 클릭합니다.

   ![](assets/understanding-marketo-custom-objects-6.png)

1. 사용자 세부 정보 페이지에서 **[!UICONTROL Custom Objects]** 탭을 클릭합니다. 드롭다운에서 객체를 선택합니다.

   ![](assets/understanding-marketo-custom-objects-7.png)

1. 이제 해당 사용자와 연결된 해당 유형의 모든 사용자 지정 개체 목록을 볼 수 있습니다.

   ![](assets/understanding-marketo-custom-objects-8.png)

   >[!NOTE]
   >
   >개인 레코드에서 사용자 지정 개체 탭에는 ID별로 내림차순으로 정렬된 최대 100개의 레코드가 표시될 수 있습니다.

## 회사에서 사용자 정의 객체 사용 {#using-custom-objects-with-companies}

회사에 연결된 사용자 지정 오브젝트는 CRM에서 회사를 동기화하거나 API를 사용하여 회사를 명시적으로 만드는 경우 가장 잘 작동합니다. 또한 링크 필드로 회사 ID를 사용하는 것이 좋습니다.

CRM 또는 Marketo 전용 레코드의 레코드인 Marketo에 여러 명이 있는 경우 회사에 연결된 사용자 지정 오브젝트는 둘 이상의 개별 레코드와 연결되지 않습니다. 여러 명이 아래에 있는 회사는 회사가 CRM에서 동기화되거나 API를 사용하여 회사를 명시적으로 만들 경우에만 지원되기 때문입니다.

사용자 지정 개체는 단일 레코드에만 직접 연결할 수 있습니다. 즉, 사용자 지정 개체 유형이 회사 필드로 연결된 경우 Marketo의 REST API를 사용하여 회사를 관리하는 경우 CRM에서 연락처 변환을 사용하거나 externalCompanyId 필드를 사용하여 개인 레코드가 회사에 연결되었는지 확인해야 합니다. 회사 레코드에 명시적으로 연결되지 않은 개인 레코드의 경우 회사를 사용하여 연결된 사용자 정의 오브젝트는 회사 필드의 값이 여러 사람에게 공유되더라도 단일 레코드에 임의로 연결됩니다.

자세한 내용은 [사용자 지정 개체 데이터 가져오기](/help/marketo/product-docs/administration/marketo-custom-objects/import-custom-object-data.md)를 참조하십시오.

>[!MORELIKETHIS]
>
>* [Marketo 사용자 지정 개체 만들기](/help/marketo/product-docs/administration/marketo-custom-objects/create-marketo-custom-objects.md)
>* [사용자 지정 개체 승인](/help/marketo/product-docs/administration/marketo-custom-objects/approve-a-custom-object.md)
>* [Marketo 사용자 지정 개체 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Marketo 사용자 지정 개체 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Marketo 사용자 지정 개체 필드 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)
>* [사용자 지정 개체 데이터 가져오기](/help/marketo/product-docs/administration/marketo-custom-objects/import-custom-object-data.md)

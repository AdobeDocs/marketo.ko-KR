---
unique-page-id: 10093688
description: Marketo 사용자 지정 개체 필드 추가 - Marketo 문서 - 제품 설명서
title: Marketo 사용자 지정 개체 필드 추가
exl-id: 6d776d97-93e2-4708-9ce5-2172e02b71c3
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '293'
ht-degree: 0%

---

# Marketo 사용자 지정 개체 필드 추가 {#add-marketo-custom-object-fields}

사용자 지정 개체를 만든 후에는 비즈니스 요구 사항에 맞게 필드를 추가해야 합니다.

필드는 사용자 지정 개체에서 사용하는 특정 정보를 정의합니다. 링크 필드에는 사용자 지정 개체를 연결하는 특별한 작업이 있으며, [별도의 문서](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md).

1. 클릭 **관리**, 및 **데이터베이스 관리**, 선택 **Marketo 사용자 지정 개체**.

   ![](assets/image2016-1-18-9-3a2-3a6.png)

1. 오른쪽에 필드를 추가할 개체를 선택합니다.

   ![](assets/image2016-1-18-9-3a5-3a3.png)

1. 에서 **필드** 탭, **새 필드**.

   ![](assets/image2015-9-15-16-3a53-3a40.png)

   >[!NOTE]
   >
   >위에 표시된 세 필드는 사용자 지정 개체를 만들 때 Marketo에 의해 자동으로 만들어집니다. Marketo에서는 이러한 필드를 자동으로 관리하므로 편집하거나 삭제할 수 없습니다.

1. 표시 이름과 설명을 입력합니다.

   ![](assets/image2015-10-5-11-3a35-3a48.png)

   >[!NOTE]
   >
   >API 이름은 승인될 때까지 편집할 수 있습니다.

1. 이제 목록에서 적절한 데이터 유형을 선택합니다.

   ![](assets/image2015-10-5-11-3a37-3a24.png)

1. 새 필드를 고유 식별자로 사용하려면 데이터 중복 제거 슬라이더를 위로 가져옵니다. 클릭 **저장** 을 클릭하여 끝내십시오.

   ![](assets/image2015-10-5-11-3a40-3a12.png)

   >[!TIP]
   >
   >데이터 중복 제거 필드는 사용자 지정 개체를 검색, 업데이트 또는 삭제하는 데 사용할 수 있습니다. 모든 사용자 지정 객체 정의에는 적어도 하나(3개 이하)의 데이터 중복 제거 필드가 포함되어야 합니다.

1. 필요한 다른 필드를 추가합니다.

   >[!NOTE]
   >
   >일대다 구조를 만드는 경우 사용자 지정 개체에 링크 필드를 추가해야 합니다. 다대다 구조의 경우 사용자 지정 개체에 링크 필드가 필요하지 않지만 중간 개체에 두 개의 링크 필드를 추가해야 합니다. 자세한 내용은 [Marketo 사용자 지정 개체 링크 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md) 링크 필드를 만들려면 및 [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) 사용자 정의 개체 유형에 대한 자세한 내용을 참조하십시오.

>[!MORELIKETHIS]
>
>* [Marketo 사용자 지정 개체 링크 필드 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Marketo 사용자 지정 개체 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Marketo 사용자 지정 개체 필드 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)
>* [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)


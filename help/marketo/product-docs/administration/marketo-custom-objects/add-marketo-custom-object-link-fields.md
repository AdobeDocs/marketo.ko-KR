---
unique-page-id: 10097613
description: 마케팅 to 사용자 지정 개체 링크 필드 추가 - 마케팅 문서 - 제품 설명서
title: 마케팅을 사용자 지정 개체 링크 필드에 추가
translation-type: tm+mt
source-git-commit: f865630638e7c0fe6ac2a449e196a7de4fbfeea1
workflow-type: tm+mt
source-wordcount: '601'
ht-degree: 0%

---


# 마케팅을 사용자 지정 개체 링크 필드 추가 {#add-marketo-custom-object-link-fields}

사용자 지정 개체를 만들 때 사용자 지정 개체 레코드를 올바른 상위 레코드에 연결하려면 링크 필드를 제공해야 합니다.

* 일대다 사용자 정의 구조의 경우 사용자 정의 객체의 링크 필드를 사용하여 사용자나 회사에 연결합니다.
* 다대다 구조의 경우 두 개의 링크 필드를 사용하여 별도로 생성된 중간 객체(사용자 정의 객체의 유형)와 연결됩니다. 한 링크는 데이터베이스의 사용자 또는 회사에 연결되고 다른 링크는 사용자 지정 객체에 연결됩니다. 이 경우 링크 필드가 사용자 지정 객체 자체에 없습니다.

## 일대다 구조 {#create-a-link-field-for-a-one-to-many-structure}에 대한 링크 필드 만들기

사용자 지정 개체에서 일대다 구조에 대한 링크 필드를 만드는 방법을 설명합니다.

1. **관리**&#x200B;를 클릭하고 **데이터베이스 관리**&#x200B;에서 **마케팅 사용자 지정 개체**&#x200B;를 선택합니다.

   ![](assets/image2016-1-18-13-3a25-3a11.png)

1. 목록에서 사용자 지정 객체를 선택합니다.

   ![](assets/image2016-1-14-15-3a6-3a2.png)

1. **필드** 탭에서 **새 필드**&#x200B;를 클릭합니다.

   ![](assets/image2015-9-17-14-3a9-3a19.png)

1. 링크 필드의 이름을 지정하고 선택적 설명을 추가합니다. 링크 데이터 유형을 선택해야 합니다.

   ![](assets/image2015-10-5-13-3a24-3a57.png)

   >[!CAUTION]
   >
   >사용자 지정 객체가 승인되면 이전 상태로 돌아가 링크 또는 중복 제거 필드를 생성, 편집 또는 삭제할 수 없습니다.

1. 링크 객체가 리드(개인) 또는 회사에 해당하는지 선택합니다.

   ![](assets/image2015-10-5-13-3a28-3a1.png)

   >[!NOTE]
   >
   >리드를 선택하면 ID, 이메일 주소 및 목록에 있는 모든 사용자 지정 필드가 표시됩니다.
   >
   >회사를 선택하면 ID와 사용자 정의 필드가 목록에 표시됩니다.

1. 새 필드의 상위로 연결할 링크 필드를 선택합니다.

   ![](assets/image2015-10-5-13-3a30-3a6.png)

   >[!NOTE]
   >
   >링크 필드에는 문자열 필드 유형만 지원됩니다.

1. **저장을 클릭합니다.**

   ![](assets/image2015-10-5-13-3a34-3a0.png)

## 다대다 구조 {#create-a-link-field-for-a-many-to-many-structure}에 대한 링크 필드 만들기

다음은 다대다 구조에서 사용할 수 있도록 중간 개체에 링크 필드를 만드는 방법입니다.

>[!PREREQUISITES]
>
>중간 객체와 연결하려는 사용자 정의 객체를 이미 생성한 상태여야 합니다.

1. **관리**&#x200B;를 클릭하고 **데이터베이스 관리**&#x200B;에서 **마케팅 사용자 지정 개체**&#x200B;를 선택합니다.

   ![](assets/image2016-1-18-9-3a8-3a14.png)

1. 필드를 추가할 중간 객체를 선택합니다.

   ![](assets/image2016-1-18-9-3a10-3a29.png)

1. **필드** 탭에서 **새 필드**&#x200B;를 클릭합니다.

   ![](assets/image2016-1-18-9-3a31-3a43.png)

1. 2개의 링크 필드를 만들어야 합니다. 한 번에 하나씩 만들 수 있습니다. 먼저 데이터베이스 목록 구성원의 필드 이름을 지정합니다(예: leadID). 선택적 설명을 추가합니다. 링크 데이터 유형을 선택해야 합니다.

   ![](assets/image2016-1-18-9-3a38-3a59.png)

   >[!CAUTION]
   >
   >사용자 지정 객체가 승인되면 이전 상태로 돌아가 링크 또는 중복 제거 필드를 생성, 편집 또는 삭제할 수 없습니다.

1. 데이터베이스에서 링크 개체를 선택합니다(이 경우 리드).

   ![](assets/image2016-1-18-9-3a50-3a48.png)

1. 연결할 링크 필드(이 경우 ID)를 선택합니다.

   ![](assets/image2016-1-18-9-3a53-3a54.png)

   >[!NOTE]
   >
   >링크 필드에는 문자열 필드 유형만 지원됩니다.

1. **저장을 클릭합니다.**

   ![](assets/image2016-1-18-9-3a55-3a18.png)

1. 이 예제에서는 courseID라는 사용자 지정 객체에 대한 두 번째 링크에 대해 이 프로세스를 반복합니다. 링크 개체 이름은 강좌이고 링크 필드는 courseID입니다. 강좌 사용자 정의 개체를 이미 만들고 승인했으므로 드롭다운 메뉴에서 이러한 선택 항목을 사용할 수 있습니다.

   ![](assets/image2016-1-18-9-3a57-3a46.png)

1. 등록 ID 또는 등급과 같이 중간 개체에 사용할 다른 필드를 만듭니다.

## 사용자 지정 개체 사용 {#using-custom-objects}

다음 단계는 스마트 캠페인의 필터에서 이러한 사용자 지정 개체를 사용하는 것입니다. 다대다 관계를 통해 여러 사람/회사 및 여러 사용자 정의 개체를 선택할 수 있습니다. 아래 예에서 이러한 기준과 일치하는 데이터베이스의 모든 사람이 나열됩니다. 강좌 사용자 정의 개체에서 강좌 이름 필드를 가져오며 등록 등급은 중간 개체에서 가져옵니다.

![](assets/image2016-1-14-15-3a57-3a59.png)

>[!MORELIKETHIS]
>
>* [마케팅을 사용자 지정 개체 필드에 추가](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [마케팅 사용자 지정 개체 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [마케팅 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
>* [마케팅 사용자 지정 개체 필드 편집 및 삭제](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)


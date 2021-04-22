---
unique-page-id: 11378713
description: 사용자 정의 개체 변경 트리거 - Marketo 문서 - 제품 설명서
title: 사용자 정의 개체 변경 트리거
exl-id: a2a3d82f-33ae-4191-b114-dbbf944a66c8
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---

# 사용자 지정 개체 변경 {#trigger-off-custom-object-changes} 트리거

>[!NOTE]
>
>이 기능은 다음과 같은 경우에만 사용할 수 있습니다.
>
>* Orion 인프라스트럭처 고객
>* 기본 Salesforce 또는 Microsoft Dynamics 통합을 통해 동기화된 사용자 정의 개체가 아니라 Marketo 사용자 정의 개체에서만 사용할 수 있습니다.
>* 필터가 아니라 트리거로서

>
>
사용자 지정 개체 변경 트리거를 사용하도록 설정하려면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

스마트 캠페인의 스마트 목록에서 사용자 지정 개체가 개인 또는 회사에 추가될 때 흐름 작업을 트리거할 수 있습니다. 사용자 지정 개체의 *change*&#x200B;를 트리거로 사용하는 스마트 목록을 만들 수도 있습니다. 예를 들어, 강좌 이름이 업데이트되면 이메일을 보내는 데 이 아이콘을 사용합니다.

>[!NOTE]
>
>사용자 지정 개체 레코드가 변경되면 활동 로그 항목이 만들어지지 않습니다.

1. Marketo에서 **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/image2016-7-25-15-3a49-3a52.png)

1. 기존 스마트 캠페인을 만들거나 열고 스마트 목록을 선택합니다.

   ![](assets/image2016-7-25-16-3a9-3a19.png)

1. 필요한 트리거를 검색하고 캔버스로 드래그합니다.

   ![](assets/image2016-7-25-16-3a16-3a43.png)

1. 트리거 속성을 선택합니다.

   ![](assets/image2016-7-25-16-3a21-3a42.png)

1. 제한을 설정할 수도 있습니다.

   ![](assets/image2016-9-6-14-3a25-3a22.png)

1. 여기 있습니다. 변경 내용이 자동으로 저장됩니다.

   ![](assets/image2016-9-6-14-3a25-3a54.png)

   >[!NOTE]
   >
   >* [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
   >* [Marketo 사용자 정의 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)


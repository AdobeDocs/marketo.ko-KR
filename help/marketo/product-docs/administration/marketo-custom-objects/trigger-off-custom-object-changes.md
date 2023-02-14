---
unique-page-id: 11378713
description: 사용자 지정 개체 변경 트리거 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 변경 트리거
exl-id: a2a3d82f-33ae-4191-b114-dbbf944a66c8
source-git-commit: 99b11e17e9c2255a19c658b166e7b38c45cf1001
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 0%

---

# 사용자 지정 개체 변경 트리거 {#trigger-off-custom-object-changes}

>[!NOTE]
>
>이 기능은 다음과 같은 경우에만 사용할 수 있습니다.
>
>* Orion 인프라스트럭처의 고객
>* 기본 Salesforce 또는 Microsoft Dynamics 통합을 통해 동기화된 사용자 지정 개체가 아닌 Marketo 사용자 지정 개체에서만 사용하는 경우
>* 필터가 아닌 트리거입니다
>
>연락처 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support) 사용자 지정 객체 변경 트리거를 사용하도록 설정합니다.

스마트 캠페인의 스마트 목록에서 사용자 지정 개체가 개인 또는 회사에 추가되면 흐름 작업을 트리거할 수 있습니다. 를 사용하는 스마트 목록을 만들 수도 있습니다 *변경* 사용자 지정 개체에서 트리거로 사용됩니다. 예를 들어, 교육 과정 이름이 업데이트될 때 이 코드를 사용하여 이메일을 보냅니다.

>[!NOTE]
>
>사용자 지정 개체 레코드가 변경되면 활동 로그 항목이 생성되지 않습니다.

1. Marketo에서 **마케팅 활동.**

   ![](assets/trigger-off-custom-object-changes-1.png)

1. 기존 스마트 캠페인을 만들거나 열고 스마트 목록을 선택합니다.

   ![](assets/trigger-off-custom-object-changes-2.png)

1. 필요한 트리거를 검색하고 캔버스로 드래그합니다.

   ![](assets/trigger-off-custom-object-changes-3.png)

1. 트리거 속성을 선택합니다.

   ![](assets/trigger-off-custom-object-changes-4.png)

1. 구속을 설정할 수도 있습니다.

   ![](assets/trigger-off-custom-object-changes-5.png)

1. 그리고 여기 있어요 변경 사항이 자동으로 저장됩니다.

   ![](assets/trigger-off-custom-object-changes-6.png)

   >[!NOTE]
   >
   >* [스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)
   >* [Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)


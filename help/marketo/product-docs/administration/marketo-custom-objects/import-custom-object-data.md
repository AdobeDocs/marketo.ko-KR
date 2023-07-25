---
unique-page-id: 10099680
description: 사용자 지정 개체 데이터 가져오기 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 데이터 가져오기
exl-id: ee11199a-57ca-47ec-8f59-8384a93ea05e
feature: Custom Objects
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 0%

---

# 사용자 지정 개체 데이터 가져오기 {#import-custom-object-data}

사용자 지정 개체 데이터를 데이터베이스로 쉽게 가져올 수 있습니다. 회사에서 사용자 지정 개체를 사용하는 경우 다음을 참조하십시오 [회사에서 사용자 정의 객체 사용](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md#using-custom-objects-with-companies) 추가 정보.

1. 내 Marketo에서 **[!UICONTROL 데이터베이스]**.

   ![](assets/import-custom-object-data-1.png)

1. 클릭 **[!UICONTROL 신규]** 및 선택 **[!UICONTROL 사용자 지정 개체 데이터 가져오기]**.

   ![](assets/import-custom-object-data-2.png)

1. 클릭 **[!UICONTROL 찾아보기]** 를 클릭하여 데이터 파일을 찾습니다. 파일 형식(이 예제에서는 쉼표로 구분된 값)을 선택합니다.

   ![](assets/import-custom-object-data-3.png)

1. 다음 항목 선택 [!UICONTROL 사용자 지정 개체].

   ![](assets/import-custom-object-data-4.png)

1. 다음 항목 선택 [!UICONTROL 중복 제거 모드] 드롭다운에서 을 클릭합니다. 클릭 **[!UICONTROL 다음]**.

   ![](assets/import-custom-object-data-5.png)

   >[!NOTE]
   >
   >사용자 지정 개체 레코드를 만들거나 업데이트할 때 중복 제거 필드를 고유 식별자로 사용합니다. 이 예에서는 의 데이터 중복 제거 필드를 사용합니다. **자동차** 사용자 지정 개체 - vin(차량 ID 번호). 사용자 지정 개체 레코드만 업데이트하는 경우 [!UICONTROL Marketo Guid] (으)로 [!UICONTROL 중복 제거 모드].

1. 각 열을 Marketo 필드에 매핑하고 드롭다운에서 선택합니다.

   ![](assets/import-custom-object-data-6.png)

   >[!NOTE]
   >
   >파일의 값이 일치하는 필드의 유형(예: 텍스트, 정수 등)과 일치하는지 확인하십시오. 그렇지 않으면 파일이 거부됩니다.

1. 클릭 **[!UICONTROL 다음]**.

   ![](assets/import-custom-object-data-7.png)

1. 클릭 **[!UICONTROL 가져오기]**.

   ![](assets/import-custom-object-data-8.png)

   >[!NOTE]
   >
   >사용자 지정 개체의 크기 제한은 100MB입니다.

   >[!TIP]
   >
   >에 이메일 주소를 입력합니다. **[!UICONTROL 경고 보내기]** 가져오기가 완료되면 필드 및 Marketo에서 이메일을 보내드립니다!

1. 화면 오른쪽 위 모서리에는 가져오기가 실행되는 동안 알림이 표시되고, 가져오기가 완료되면 최종 결과가 표시됩니다.

   ![](assets/import-custom-object-data-9.png)

   예이!

>[!MORELIKETHIS]
>
>[Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)

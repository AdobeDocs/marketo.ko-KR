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

사용자 지정 개체 데이터를 데이터베이스로 쉽게 가져올 수 있습니다. 회사에 사용자 지정 개체를 사용하는 경우 자세한 내용은 [회사에 사용자 지정 개체 사용](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md#using-custom-objects-with-companies)을 참조하십시오.

1. 내 Marketo에서 **[!UICONTROL 데이터베이스]**(으)로 이동합니다.

   ![](assets/import-custom-object-data-1.png)

1. **[!UICONTROL 새로 만들기]**&#x200B;를 클릭하고 **[!UICONTROL 사용자 지정 개체 데이터 가져오기]**&#x200B;를 선택합니다.

   ![](assets/import-custom-object-data-2.png)

1. 데이터 파일을 찾으려면 **[!UICONTROL 찾아보기]**&#x200B;를 클릭하세요. 파일 형식(이 예제에서는 쉼표로 구분된 값)을 선택합니다.

   ![](assets/import-custom-object-data-3.png)

1. [!UICONTROL 사용자 지정 개체]를 선택하십시오.

   ![](assets/import-custom-object-data-4.png)

1. 드롭다운에서 [!UICONTROL 중복 제거 모드]를 선택합니다. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/import-custom-object-data-5.png)

   >[!NOTE]
   >
   >사용자 지정 개체 레코드를 만들거나 업데이트할 때 중복 제거 필드를 고유 식별자로 사용합니다. 이 예제에서는 **car** 사용자 지정 개체 - vin(차량 ID 번호)의 중복 제거 필드를 사용합니다. 사용자 지정 개체 레코드만 업데이트하는 경우 [!UICONTROL Marketo Guid]를 [!UICONTROL 중복 제거 모드] (으)로 선택할 수 있습니다.

1. 각 열을 Marketo 필드에 매핑하고 드롭다운에서 선택합니다.

   ![](assets/import-custom-object-data-6.png)

   >[!NOTE]
   >
   >파일의 값이 일치하는 필드의 유형(예: 텍스트, 정수 등)과 일치하는지 확인하십시오. 그렇지 않으면 파일이 거부됩니다.

1. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/import-custom-object-data-7.png)

1. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/import-custom-object-data-8.png)

   >[!NOTE]
   >
   >사용자 지정 개체의 크기 제한은 100MB입니다.

   >[!TIP]
   >
   >**[!UICONTROL 알림 보내기]** 필드에 전자 메일 주소를 입력하면 가져오기가 완료되면 Marketo에서 전자 메일을 보냅니다!

1. 화면 오른쪽 위 모서리에는 가져오기가 실행되는 동안 알림이 표시되고, 가져오기가 완료되면 최종 결과가 표시됩니다.

   ![](assets/import-custom-object-data-9.png)

   예이!

>[!MORELIKETHIS]
>
>[Marketo 사용자 지정 개체 이해](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)

---
unique-page-id: 1147120
description: 스프레드시트에서 프로그램으로 구성원 가져오기 - Marketo 문서 - 제품 설명서
title: 스프레드시트에서 프로그램으로 구성원 가져오기
exl-id: 09c597bb-d28a-463b-8340-ff22d2e0fa02
feature: Programs
source-git-commit: e49860ae611f2f77789bb491aeccbee46a911a2c
workflow-type: tm+mt
source-wordcount: '164'
ht-degree: 0%

---

# 스프레드시트에서 프로그램으로 구성원 가져오기 {#import-members-from-a-spreadsheet-into-a-program}

프로그램의 구성원이 자동으로 되는 사람 목록을 가져올 수 있습니다. 할 일이 있습니다.

## CSV 파일 준비 {#prepare-your-csv-file}

1. 아래 예제와 같이 Excel에서 표준 CSV 파일을 만듭니다.

   ![](assets/image2014-9-18-14-3a33-3a4.png)

   >[!CAUTION]
   >
   >날짜를 날짜 필드로 가져올 때 다음 형식을 사용하십시오. 9/29/24 (월/일/년).

## CSV를 Marketo으로 가져오기 {#import-your-csv-into-marketo}

1. 프로그램에서 **[!UICONTROL 구성원]** 섹션으로 이동합니다.

   ![](assets/image2014-9-18-15-3a3-3a57.png)

1. **[!UICONTROL 구성원 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-18-15-3a38-3a14.png)

1. CSV를 선택하고 **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/importlist1.png)

1. 목록의 데이터 값을 해당 Marketo 필드에 매핑하고 **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/importlist12.png)

   >[!NOTE]
   >
   >가져오지 않을 필드가 있으면 Marketo 필드 드롭다운 메뉴에서 **[!UICONTROL 무시]**&#x200B;를 선택합니다.

1. 목록의 **[!UICONTROL 구성원 상태]**&#x200B;를 선택하십시오.

   ![](assets/image2014-9-18-15-3a41-3a32.png)

1. **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-18-15-3a44-3a19.png)

1. Marketo 가져오기가 완료될 때까지 기다린 다음 확인 대화 상자를 닫습니다.

   ![](assets/image2014-9-18-15-3a44-3a37.png)

   잘됐네! 가져온 새 구성원이 표시됩니다.

   ![](assets/image2014-9-18-15-3a45-3a16.png)

>[!MORELIKETHIS]
>
>[구성원 관리 및 보기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/manage-and-view-members.md){target="_blank"}

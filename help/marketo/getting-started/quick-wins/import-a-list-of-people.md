---
unique-page-id: 2359418
description: 사람 목록 가져오기 - Marketo 문서 - 제품 설명서
title: 사람 목록 가져오기
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
feature: Getting Started
source-git-commit: 292626741d3b2334da104a515c3e968fb340706a
workflow-type: tm+mt
source-wordcount: '581'
ht-degree: 0%

---

# 사람 목록 가져오기 {#import-a-list-of-people}

## 임무: 무역 전시회 참석자의 스프레드시트 목록을 데이터베이스로 가져오기 {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}

이 자습서에서는 스프레드시트 파일에서 Marketo으로 사람들을 가져오는 방법을 배웁니다.

## 1단계: 스프레드시트 다운로드 및 편집 {#step-download-and-edit-a-spreadsheet}

1. 시작하려면 연습 스프레드시트 파일([**tradeshow-participants.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv){target="_blank"})을 컴퓨터에 다운로드합니다.

   ![](assets/import-a-list-of-people-1.png)

   >[!NOTE]
   >
   >날짜를 가져올 때 다음 형식을 사용하십시오. **9/21/20**(월/일/년)

   >[!NOTE]
   >
   >가져오는 모든 날짜/시간 필드는 중앙 시간으로 처리됩니다. 다른 시간대에 날짜/시간 필드가 있는 경우 Excel 공식을 사용하여 중부 표준시(아메리카/시카고)로 변환할 수 있습니다.

1. 자신의 이름, 성, 실제 이메일 주소(따라서 다음 미션에서 보낼 육성 이메일을 받을 수 있음) 및 직함을 추가합니다. 파일을 컴퓨터에 저장합니다.

   ![](assets/import-a-list-of-people-2.png)

   >[!CAUTION]
   >
   >* 이메일 주소에 ASCII 문자만 포함되어 있는지 확인하십시오.
   >
   >* Marketo은 이모지가 포함된 이메일 주소를 **지원하지 않습니다**.
   >
   >* CSV를 통해 `NULL` 값을 가져오면 사용자의 [활동 로그](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.md){target="_blank"}, _필드가 이미 비어 있는 경우에도_&#x200B;의 숫자 필드에 대한 &quot;데이터 값 변경&quot;이 생성될 수 있습니다. &quot;변경된 데이터 값&quot; 필터 또는 &quot;데이터 값 변경&quot; 트리거를 사용하는 [스마트 캠페인](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md){target="_blank"}이 있는 경우 데이터가 실제로 변경되지 않더라도 사람들이 해당 캠페인에 대한 자격을 얻을 수 있습니다. [제약 조건](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md){target="_blank"}을 사용하여 가져올 때 해당 캠페인에 적합한 사람이 없도록 할 수 있습니다.

## 2단계: 프로그램 만들기 {#step-create-a-program}

1. **[!UICONTROL 마케팅 활동]** 영역으로 이동합니다.

   ![](assets/import-a-list-of-people-3.png)

1. **학습** 폴더를 선택한 다음 **[!UICONTROL 새로 만들기]**&#x200B;에서 **[!UICONTROL 새 프로그램]**&#x200B;을 클릭하세요.

   ![](assets/import-a-list-of-people-4.png)

1. **이름** 프로그램 &quot;내 Tradeshow Program&quot;을 선택하고 **[!UICONTROL 프로그램 유형]**&#x200B;에 대해 &quot;이벤트&quot;를 선택합니다.

   ![](assets/import-a-list-of-people-5.png)

1. **[!UICONTROL 채널]**&#x200B;에 대해 **[!UICONTROL Tradeshow]**&#x200B;을(를) 선택하고 **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/import-a-list-of-people-6.png)

>[!NOTE]
>
>이벤트 프로그램은 특정 날짜에 발생합니다. [**이벤트**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md){target="_blank"}&#x200B;에 대해 자세히 알아보세요.

## 3단계: 스프레드시트를 Marketo으로 가져오기 {#step-import-your-spreadsheet-into-marketo}

1. **내 Tradeshow 프로그램**&#x200B;에서 **[!UICONTROL 새로 만들기]**&#x200B;를 클릭하고 **[!UICONTROL 새 로컬 자산]**&#x200B;을 선택합니다.

   ![](assets/import-a-list-of-people-7.png)

1. **[!UICONTROL 목록]**&#x200B;을 선택하세요.

   ![](assets/import-a-list-of-people-8.png)

1. **이름** &quot;Tradeshow 참석자&quot; 목록을 표시하고 **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   ![](assets/import-a-list-of-people-9.png)

1. **[!UICONTROL Tradeshow 참석자]** 목록에서 **[!UICONTROL 작업 나열]**&#x200B;을 클릭하고 **[!UICONTROL 목록 가져오기]**&#x200B;를 선택합니다.

   ![](assets/import-a-list-of-people-10.png)

   >[!CAUTION]
   >
   >자체 CSV 파일을 사용하는 경우 UTF-8, UTF-16, Shift-JIS 또는 EUC-JP로 인코딩되어 있는지 확인하십시오.

   >[!NOTE]
   >
   >CSV 파일의 크기 제한은 100MB입니다.

1. **[!UICONTROL 컴퓨터의** tradeshow-participants.csv **스프레드시트 파일을 찾아보고**&#x200B;[!UICONTROL &#x200B;다음&#x200B;]&#x200B;**을 클릭합니다.]**

   ![](assets/import-a-list-of-people-11.png)

   >[!NOTE]
   >
   >목록 가져오기 모드에서 **[!UICONTROL 새 사용자 및 업데이트 건너뛰기]**&#x200B;를 선택하면 기존 사용자 레코드에 영향을 주지 않거나 활동을 기록하지 않습니다. 마케팅 활동에 사용할 기존 직원의 사전 필터링된 빠른 정적 목록을 원하는 경우 이 모드를 사용하십시오. 이 모드를 선택하면 다음 작업이 수행됩니다.
   >
   > * 새 사용자 만들기 건너뛰기
   > * 개인 필드 업데이트 건너뛰기
   > * 활동 로깅 건너뛰기

1. [!UICONTROL 목록 열] 필드를 해당 Marketo 필드에 매핑하고 **[!UICONTROL 다음]**&#x200B;을(를) 클릭합니다.

   ![](assets/import-a-list-of-people-12.png)

   >[!TIP]
   >
   >최상의 자동 매핑 결과를 얻으려면 열 헤더가 항상 필드와 정확히 일치해야 합니다(대/소문자 구분). 사용자 정의 필드를 사용하고 있는데 드롭다운에 표시되지 않으면 돌아가서 [만들고](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target="_blank"} 옵션이 될 수 있도록 하십시오.

   >[!NOTE]
   >
   >가져오지 않을 필드가 있으면 Marketo 필드 드롭다운 메뉴에서 **무시**&#x200B;를 선택합니다.

1. **[!UICONTROL 획득 프로그램]**&#x200B;에 대해 **내 박람회 프로그램**&#x200B;을 선택한 다음 **[!UICONTROL 가져오기]**&#x200B;를 클릭합니다.

   ![](assets/import-a-list-of-people-13.png)

1. 직원들이 가져올 때까지 기다린 다음 가져오기 진행률 팝업을 닫습니다.

   ![](assets/import-a-list-of-people-14.png)

1. **내 Tradeshow 프로그램**&#x200B;으로 돌아가 **[!UICONTROL 구성원]** 탭을 클릭하세요. 방금 가져온 모든 사람을 볼 수 있습니다.

   ![](assets/import-a-list-of-people-15.png)

>[!NOTE]
>
>프로그램 멤버십을 추적하여 프로그램의 성공을 분석할 수 있습니다. [**프로그램**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target="_blank"}&#x200B;에 대해 자세히 알아보세요.

## 임무 완료 {#mission-complete}

박람회 참석자가 이제 Marketo 프로그램의 구성원입니다!

<br> 

[◄ 미션 4: 이메일 자동 응답](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[미션 6: 물방울, 물방울, ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

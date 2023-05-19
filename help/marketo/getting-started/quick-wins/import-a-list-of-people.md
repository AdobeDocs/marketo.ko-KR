---
unique-page-id: 2359418
description: 사람 목록 가져오기 - Marketo 문서 - 제품 설명서
title: 사람 목록 가져오기
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
source-git-commit: 80512816eaf0a70a3f10a50c34aeea14edd9046b
workflow-type: tm+mt
source-wordcount: '490'
ht-degree: 0%

---

# 사람 목록 가져오기 {#import-a-list-of-people}

## 임무: 무역 전시회 참석자의 스프레드시트 목록을 데이터베이스로 가져오기 {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}

이 자습서에서는 스프레드시트 파일에서 Marketo으로 사람들을 가져오는 방법을 배웁니다.

## 1단계: 스프레드시트 다운로드 및 편집 {#step-download-and-edit-a-spreadsheet}

1. 시작하려면 연습 스프레드시트 파일( )을 다운로드하십시오.[**tradeshow-contensent.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv){target="_blank"})을 클릭하여 컴퓨터에 업로드하십시오.

   ![](assets/import-a-list-of-people-1.png)

   >[!NOTE]
   >
   >날짜를 가져올 때 다음 형식을 사용하십시오. **9/21/20** (월/일/년).

   >[!NOTE]
   >
   >가져오는 모든 날짜/시간 필드는 중앙 시간으로 처리됩니다. 다른 시간대에 날짜/시간 필드가 있는 경우 Excel 공식을 사용하여 중부 표준시(아메리카/시카고)로 변환할 수 있습니다.

1. 자신의 이름, 성, 실제 이메일 주소(따라서 다음 미션에서 보낼 육성 이메일을 받을 수 있음) 및 직함을 추가합니다. 파일을 컴퓨터에 저장합니다.

   ![](assets/import-a-list-of-people-2.png)

   >[!CAUTION]
   >
   >Marketo은 **아님** 이모지가 포함된 이메일 주소를 지원합니다.

## 2단계: 프로그램 만들기 {#step-create-a-program}

1. 로 이동 **[!UICONTROL 마케팅 활동]** 영역입니다.

   ![](assets/import-a-list-of-people-3.png)

1. 다음 항목 선택 **학습** 폴더를 선택한 다음 아래에 **[!UICONTROL 신규]** 클릭 **[!UICONTROL 새 프로그램]**.

   ![](assets/import-a-list-of-people-4.png)

1. **이름** 프로그램 &quot;내 Tradeshow Program&quot;을 선택하고 **[!UICONTROL 프로그램 유형]**.

   ![](assets/import-a-list-of-people-5.png)

1. 선택 **[!UICONTROL 박람회]** 대상: **[!UICONTROL 채널]** 및 클릭 **[!UICONTROL 만들기]**.

   ![](assets/import-a-list-of-people-6.png)

>[!NOTE]
>
>이벤트 프로그램은 특정 날짜에 발생합니다. 자세히 알아보기 [**이벤트**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md){target="_blank"}.

## 3단계: 스프레드시트를 Marketo으로 가져오기 {#step-import-your-spreadsheet-into-marketo}

1. 위치 **내 박람회 프로그램**, 클릭 **[!UICONTROL 신규]** 및 선택 **[!UICONTROL 새 로컬 자산]**.

   ![](assets/import-a-list-of-people-7.png)

1. 선택 **[!UICONTROL 목록]**.

   ![](assets/import-a-list-of-people-8.png)

1. **이름** &quot;Tradeshow Audiences&quot; 목록 및 클릭 **[!UICONTROL 만들기]**.

   ![](assets/import-a-list-of-people-9.png)

1. 내 **[!UICONTROL 박람회 참석자]** 목록, 클릭 **[!UICONTROL 작업 나열]** 및 선택 **[!UICONTROL 목록 가져오기]**.

   ![](assets/import-a-list-of-people-10.png)

   >[!CAUTION]
   >
   >자체 CSV 파일을 사용하는 경우 UTF-8, UTF-16, Shift-JIS 또는 EUC-JP로 인코딩되어 있는지 확인하십시오.

   >[!NOTE]
   >
   >CSV 파일의 크기 제한은 100MB입니다.

1. **[!UICONTROL 찾아보기]** (으)로 **tradeshow-contensent.csv** 컴퓨터에서 스프레드시트 파일을 클릭하고 **[!UICONTROL 다음]**.

   ![](assets/import-a-list-of-people-11.png)

   >[!NOTE]
   >
   >목록 가져오기 모드에서 **[!UICONTROL 새 직원 및 업데이트 건너뛰기]** 은(는) 기존 개인 레코드에 영향을 주지 않거나 활동을 기록하지 않음을 의미합니다. 마케팅 활동에 사용할 기존 직원의 사전 필터링된 빠른 정적 목록을 원하는 경우 이 모드를 사용하십시오. 이 모드를 선택하면 다음 작업이 수행됩니다.
   >
   > * 새 사용자 만들기 건너뛰기
   > * 개인 필드 업데이트 건너뛰기
   > * 활동 로깅 건너뛰기


1. 매핑 [!UICONTROL 목록 열] 필드를 해당 Marketo 필드로 이동하고 **[!UICONTROL 다음]**.

   ![](assets/import-a-list-of-people-12.png)

   >[!TIP]
   >
   >최상의 자동 매핑 결과를 얻으려면 열 헤더가 항상 필드와 정확히 일치해야 합니다(대/소문자 구분). 사용자 정의 필드를 사용 중인데 드롭다운에 표시되지 않는 경우 뒤로 돌아가서 [생성](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target="_blank"} 그래서 그들은 선택지가 될 수 있습니다.

   >[!NOTE]
   >
   >가져오지 않을 필드가 있으면 을(를) 선택합니다. **무시** (Marketo 필드 드롭다운 메뉴)

1. 선택 **내 박람회 프로그램** 대상: **[!UICONTROL 고객 확보 프로그램]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 가져오기]**.

   ![](assets/import-a-list-of-people-13.png)

1. 직원들이 가져올 때까지 기다린 다음 가져오기 진행률 팝업을 닫습니다.

   ![](assets/import-a-list-of-people-14.png)

1. 다시 시작 **내 박람회 프로그램**&#x200B;를 클릭하고 **[!UICONTROL 구성원]** 탭. 방금 가져온 모든 사람을 볼 수 있습니다.

   ![](assets/import-a-list-of-people-15.png)

>[!NOTE]
>
>프로그램 멤버십을 추적하여 프로그램의 성공을 분석할 수 있습니다. 자세히 알아보기 [**프로그램**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md){target="_blank"}.

## 임무 완료 {#mission-complete}

박람회 참석자가 이제 Marketo 프로그램의 구성원입니다!

<br> 

[◄ 미션 4: 이메일 자동 응답](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[미션 6: 물방울, 물방울, ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

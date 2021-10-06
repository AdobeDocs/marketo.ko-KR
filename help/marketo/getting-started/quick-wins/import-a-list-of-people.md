---
unique-page-id: 2359418
description: 사람 목록 가져오기 - Marketo 문서 - 제품 설명서
title: 사람 목록 가져오기
exl-id: a85ec787-7b22-4666-84fd-d7bf23d32cd4
source-git-commit: 1b37a750c5e609b9e43e942df752305d85153989
workflow-type: tm+mt
source-wordcount: '490'
ht-degree: 0%

---

# 사람 목록 가져오기 {#import-a-list-of-people}

## 임무: 트레이드쇼 참석자를 데이터베이스로 스프레드시트 목록 가져오기 {#mission-import-a-spreadsheet-list-of-trade-show-attendees-into-your-database}

>[!PREREQUISITES]
>
>[설정 및 개인 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)

이 자습서에서는 스프레드시트 파일에서 Marketo으로 사람을 가져오는 방법을 알아봅니다.

## 1단계: 스프레드시트 다운로드 및 편집 {#step-download-and-edit-a-spreadsheet}

1. 시작하려면 연습용 스프레드시트 파일([**tradeshow-attents.csv**](/help/marketo/getting-started/assets/tradeshow-attendees.csv))을 컴퓨터에 다운로드합니다.

   ![](assets/image2014-9-24-12-3a5-3a0.png)

   >[!NOTE]
   >
   >날짜를 가져올 때 다음 형식을 사용하십시오. **9/21/20** (월/일/년)

   >[!NOTE]
   >
   >가져오는 날짜/시간 필드는 모두 중부 시간으로 처리됩니다. 날짜/시간 필드가 다른 시간대에 있는 경우 Excel 공식을 사용하여 중부 표준시(미국/시카고)로 변환할 수 있습니다.

1. 이름, 성, 이메일 주소 및 직함을 추가한 다음 컴퓨터에 파일을 저장합니다.

   ![](assets/image2014-9-24-12-3a5-3a30.png)

>[!NOTE]
>
>CSV 파일에 실제 이메일 주소를 입력하여 다음 미션에서 전송할 육성 이메일을 받을 수 있습니다.

## 2단계: 프로그램 만들기 {#step-create-a-program}

1. **마케팅 활동** 영역으로 이동합니다.

   ![](assets/ma-2.png)

1. **학습** 폴더를 선택한 다음 **새로 만들기** 아래에서 **새 프로그램**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-12-3a21-3a13.png)

1. **** 프로그램 이름을 &quot;My Tradeshow Program&quot;으로 지정하고  **프로그램 유형**&#x200B;에 대해 &quot;Event&quot;를 선택합니다.

   ![](assets/image2014-9-24-12-3a21-3a25.png)

1. **채널**&#x200B;에 대해 **Tradeshow**&#x200B;을 선택하고 **만들기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-12-3a21-3a39.png)

>[!NOTE]
>
>이벤트 프로그램은 특정 날짜에 발생합니다. [**Events**](/help/marketo/product-docs/demand-generation/events/understanding-events/understanding-event-programs.md)&#x200B;에 대해 자세히 알아보십시오.

## 3단계: 스프레드시트를 Marketo에 가져오기 {#step-import-your-spreadsheet-into-marketo}

1. **My Tradeshow 프로그램**&#x200B;새로 만들기&#x200B;**를 클릭하고**&#x200B;새 로컬 자산&#x200B;**을 선택합니다.**

   ![](assets/seven-3.png)

1. **목록**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-12-3a22-3a56.png)

1. **** 목록 이름을 &quot;Tradeshow Contents&quot;로 지정하고  **만들기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-12-3a23-3a9.png)

1. **참석자 교환** 목록에서 **목록 작업**&#x200B;을 클릭하고 **목록 가져오기**&#x200B;를 선택합니다.

   ![](assets/ten-2.png)

   >[!CAUTION]
   >
   >고유한 CSV 파일을 사용하는 경우 UTF-8, UTF-16, Shift-JIS 또는 EUC-JP가 인코딩되어 있는지 확인하십시오.

   >[!NOTE]
   >
   >CSV 파일의 크기 제한은 100MB입니다.

1. **** 컴퓨터에서  **tradeshow-contents.** csvspreadsheet 파일을 찾아  **다음**&#x200B;을 클릭합니다.

   ![](assets/eleven-2.png)

   >[!NOTE]
   >
   >목록 가져오기 모드에서 **새 사용자 및 업데이트 건너뛰기**&#x200B;를 선택하면 기존 개인 레코드에 영향을 주지 않거나 활동을 기록하지 않습니다. 마케팅 활동에서 사용할 기존 사용자의 빠른 사전 필터링된 정적 목록을 원하는 경우 이 모드를 사용하십시오. 이 모드를 선택하면 다음 작업이 수행됩니다.
   >
   > * 새 사람 만들기 건너뛰기
   > * 개인 필드 업데이트 건너뛰기
   > * 활동 로깅 건너뛰기


1. 목록 열 필드를 해당 Marketo 필드에 매핑하고 **다음**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-12-3a24-3a49.png)

   >[!TIP]
   >
   >열 머리글은 최상의 자동 매핑 결과를 얻으려면 항상 필드와 정확히 일치해야 합니다(대/소문자 구분). 사용자 지정 필드를 사용하고 있는데 드롭다운에서 표시되지 않는 경우 뒤로 이동하고 [만들어 옵션이 될 수 있도록 만듭니다.](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

   >[!NOTE]
   >
   >가져오지 않으려는 필드가 있으면 Marketo 필드 드롭다운 메뉴에서 **무시** 를 선택합니다.

1. **획득 프로그램**&#x200B;에 대해 **My Tradeshow 프로그램**&#x200B;을 선택한 다음 **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-12-3a25-3a1.png)

1. 사용자가 가져올 때까지 기다렸다가 가져오기 진행률 팝업을 닫습니다.

   ![](assets/image2014-9-24-12-3a25-3a13.png)

1. **My Tradeshow 프로그램**&#x200B;으로 돌아가서 **구성원** 탭을 클릭합니다. 방금 가져온 사람들을 모두 보게 될 겁니다

   ![](assets/fifteen-1.png)

>[!NOTE]
>
>프로그램 멤버십을 추적하여 프로그램의 성공을 분석할 수 있습니다. [**프로그램**](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)&#x200B;에 대해 자세히 알아보십시오.

## 임무 완료 {#mission-complete}

현재 참석자가 Marketo 프로그램의 회원인 방식에 대한 기존의 설명!

<br> 

[◄ 미션 4: 이메일 자동 응답](/help/marketo/getting-started/quick-wins/email-auto-response.md)

[임무 6: 드립, 드립, 배양 ►](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

---
unique-page-id: 2359416
description: 이메일 자동 응답 - Marketo 문서 - 제품 설명서
title: 이메일 자동 응답
exl-id: c9c0a154-65ec-4845-97a0-a2100223cb13
feature: Getting Started
source-git-commit: ecd225af3ecfd7cb9159faf5a9d384d47ee6312c
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 2%

---

# 이메일 자동 응답 {#email-auto-response}

## 임무: 사용자가 양식을 작성할 때 감사 이메일 보내기 {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!PREREQUISITES]
>
>* [설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}

## 1단계: 이메일 만들기 {#step-create-an-email}

1. [!UICONTROL Marketing Activities] 영역으로 이동합니다.

   ![](assets/email-auto-response-1.png)

1. 왼쪽 메뉴에서 프로그램을 선택하고 **[!UICONTROL New]** 드롭다운을 클릭한 다음 **[!UICONTROL New Local Asset]**&#x200B;을(를) 선택합니다.

   ![](assets/email-auto-response-2.png)

1. **[!UICONTROL Email]**&#x200B;를 선택합니다.

   ![](assets/email-auto-response-3.png)

1. 전자 메일의 이름을 &quot;자동 응답 전자 메일&quot;로 지정하고 템플릿을 선택한 다음 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-4.png)

   이메일 편집기가 새 창이나 탭에서 열립니다. 팝업이 차단되면 자산 요약 페이지에서 **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭하여 전자 메일에 액세스합니다.

1. 제목 줄을 입력한 다음 이메일의 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/email-auto-response-5.png)

   _전자 메일 편집기 위에 서식 있는 텍스트 편집기가 열립니다._

1. 기존 이메일 콘텐츠를 강조 표시합니다.

   ![](assets/email-auto-response-6.png)

1. 전자 메일 콘텐츠를 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-7.png)

1. **[!UICONTROL Email Actions]** 드롭다운을 클릭하고 **[!UICONTROL Approve and Close]**&#x200B;을(를) 선택합니다.

   ![](assets/email-auto-response-8.png)

## 2단계: 스마트 캠페인 만들기 {#step-create-a-smart-campaign}

1. 프로그램을 선택하고 **[!UICONTROL New]** 드롭다운을 클릭한 다음 **[!UICONTROL New Smart Campaign]**&#x200B;을(를) 선택합니다.

   ![](assets/email-auto-response-9.png)

1. 스마트 캠페인 &quot;자동 응답 캠페인&quot;을 **이름**&#x200B;하고 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-10.png)

1. **[!UICONTROL Smart List]** 탭으로 이동합니다.

   ![](assets/email-auto-response-11.png)

   사용자가 [**랜딩 페이지에서 만든 양식을 양식**](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}&#x200B;으로 작성할 때마다 실행되도록 이 캠페인을 설정하는 중입니다.

1. **[!UICONTROL Fills Out Form]** 트리거를 찾아 캔버스로 드래그합니다.

   ![](assets/email-auto-response-12.png)

1. 드롭다운에서 **[!UICONTROL My Form]**&#x200B;을(를) 선택합니다. **[!UICONTROL Flow]** 탭을 클릭합니다.

   ![](assets/email-auto-response-13.png)

1. **[!UICONTROL Send Email]** 흐름 작업을 왼쪽 캔버스로 드래그합니다.

   ![](assets/email-auto-response-14.png)

1. **자동 응답 전자 메일**&#x200B;을 선택하세요. **[!UICONTROL Schedule]** 탭을 클릭합니다.

   ![](assets/email-auto-response-15.png)

1. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-16.png)

1. **[!UICONTROL every time]**&#x200B;을(를) 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-17.png)

1. **[!UICONTROL Activate]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-18.png)

1. 확인 화면에서 **[!UICONTROL Activate]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-19.png)

>[!NOTE]
>
>이 캠페인이 활성화되면 사용자가 지정된 양식을 작성할 때마다 실행됩니다. 캠페인은 비활성화될 때까지 계속 실행됩니다.

## 3단계: 양식 작성 {#step-fill-out-the-form}

1. **내 페이지**(양식이 있는 [랜딩 페이지에서 생성됨](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} 빠른 실행)을 선택하고 **[!UICONTROL Preview]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-20.png)

   _&quot;무료 체험판&quot; 랜딩 페이지가 새 탭에서 열립니다._

1. 이름, 성, 전자 메일 주소로 양식을 작성한 다음 **[!UICONTROL Submit]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-auto-response-21.png)

>[!NOTE]
>
>이메일을 받을 수 있도록 실제 이메일 주소를 사용해야 합니다.

## 임무 완료 {#mission-complete}

몇 분 안에 받은 편지함에 자동 응답 이메일이 표시됩니다.

[◄ 미션 3: 단순 점수](/help/marketo/getting-started/quick-wins/simple-scoring.md)

[미션 5: ► 사람 목록 가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)

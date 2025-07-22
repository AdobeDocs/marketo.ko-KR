---
unique-page-id: 14352540
description: 자체 보기 방지 - Marketo 문서 - 제품 설명서
title: 자기 뷰 방지
exl-id: c18715fc-4ca2-4a6b-8f63-a9406f30c0d8
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '261'
ht-degree: 0%

---

# 자기 뷰 방지 {#preventing-self-views}

## 개요 {#overview}

보기 추적에서 긍정 오류(false positive)를 얻으면 보고가 일치하지 않을 수 있습니다. 이는 MSC 사용자가 이메일 클라이언트에서 실수로 추적 픽셀을 호출하는 경우(자체 보기라고 함) 자주 발생합니다. 아래는 자기 관점을 크게 줄이고 심지어 없애는 데 대한 몇 가지 팁입니다.

## 웹([!DNL Outlook Web App] 및 Gmail) {#web-outlook-web-app-and-gmail}

[!DNL Sales Connect]은(는) Outlook Web App 및 Gmail에서 전자 메일을 열 때 보기가 추적되지 않도록 쿠키를 브라우저에 저장합니다. 여전히 자체 보기를 받고 있는 경우 다음을 수행하는 것이 좋습니다.

* 컴퓨터에 쿠키가 활성화되어 있는지 확인합니다.

* 새 컴퓨터나 모바일 장치를 사용하는 경우 웹 응용 프로그램에 로그인했는지 확인하십시오. 이렇게 하면 앞으로 귀하의 컴퓨터/장치를 인식할 수 있습니다.

## 데스크탑(Windows) {#desktop-windows}

전자 메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 보기를 추적합니다. 자동으로 다운로드되는 이미지를 사용하지 않도록 설정하여 [!DNL Outlook]의 자체 보기 횟수를 크게 줄일 수 있습니다. 다음은 방법 단계입니다.

1. [!DNL Outlook]의 메뉴 모음에서 **[!UICONTROL File]**&#x200B;을(를) 클릭합니다.

   ![](assets/win-1.png)

1. **[!UICONTROL Options]**&#x200B;을(를) 클릭합니다.

   ![](assets/win-2.png)

1. [!DNL Outlook] 옵션 대화 상자에서 **[!UICONTROL Trust Center]**&#x200B;을(를) 클릭합니다.

   ![](assets/win-3.png)

1. [!UICONTROL Microsoft Outlook Trust Center]에서 **[!UICONTROL Trust Center Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/win-4.png)

1. 왼쪽의 메뉴에서 [!UICONTROL Automatic Download]을(를) 클릭하고 **[!UICONTROL Don't download pictures automatically in HTML email or RSS items]** 확인란을 선택합니다.

   ![](assets/win-5.png)

1. **[!UICONTROL OK]** 대화 상자에서 [!UICONTROL Trust Center]을(를) 클릭합니다.

   ![](assets/win-6.png)

1. **[!UICONTROL OK]** 옵션 대화 상자에서 [!DNL Outlook]을(를) 클릭합니다.

   ![](assets/win-6.png)

## 데스크탑(Mac) {#desktop-mac}

전자 메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 보기를 추적합니다. 자동으로 다운로드되는 이미지를 사용하지 않도록 설정하여 [!DNL Outlook]의 자체 보기 횟수를 크게 줄일 수 있습니다. 다음은 방법 단계입니다.

1. [!DNL Outlook]에서 메뉴 모음의 **[!UICONTROL Outlook]**&#x200B;을(를) 클릭하고 **[!UICONTROL Preferences]**&#x200B;을(를) 선택합니다.

   ![](assets/mac-1.png)

1. [!UICONTROL Email]에서 **[!UICONTROL Reading]**&#x200B;을(를) 선택합니다.

   ![](assets/mac-2.png)

1. [!UICONTROL Security]에서 **[!UICONTROL Never]** 라디오 단추를 클릭합니다.

   ![](assets/mac-3.png)

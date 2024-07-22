---
unique-page-id: 14352540
description: 자체 보기 방지 - Marketo 문서 - 제품 설명서
title: 자기 뷰 방지
exl-id: c18715fc-4ca2-4a6b-8f63-a9406f30c0d8
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 0%

---

# 자기 뷰 방지 {#preventing-self-views}

## 개요 {#overview}

보기 추적에서 긍정 오류(false positive)를 얻으면 보고가 일치하지 않을 수 있습니다. 이는 MSC 사용자가 이메일 클라이언트에서 실수로 추적 픽셀을 호출하는 경우(자체 보기라고 함) 자주 발생합니다. 아래는 자기 관점을 크게 줄이고 심지어 없애는 데 대한 몇 가지 팁입니다.

## 웹(Outlook Web App 및 Gmail) {#web-outlook-web-app-and-gmail}

Sales Connect는 Outlook Web App 및 Gmail에서 이메일을 열 때 보기가 추적되지 않도록 쿠키를 브라우저에 저장합니다. 여전히 자체 보기를 받고 있는 경우 다음을 수행하는 것이 좋습니다.

* 컴퓨터에 쿠키가 활성화되어 있는지 확인합니다.

* 새 컴퓨터나 모바일 장치를 사용하는 경우 웹 응용 프로그램에 로그인했는지 확인하십시오. 이렇게 하면 앞으로 귀하의 컴퓨터/장치를 인식할 수 있습니다.

## 데스크탑(Windows) {#desktop-windows}

전자 메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 보기를 추적합니다. 자동으로 다운로드할 이미지를 비활성화하여 Outlook의 자체 보기 횟수를 크게 줄일 수 있습니다. 다음은 방법 단계입니다.

1. Outlook의 메뉴 표시줄에서 **파일**&#x200B;을 클릭합니다.

   ![](assets/win-1.png)

1. **옵션**&#x200B;을 클릭합니다.

   ![](assets/win-2.png)

1. Outlook 옵션 대화 상자에서 **트러스트 센터**&#x200B;를 클릭합니다.

   ![](assets/win-3.png)

1. Microsoft Outlook 트러스트 센터에서 **트러스트 센터 설정**&#x200B;을 클릭합니다.

   ![](assets/win-4.png)

1. 왼쪽의 메뉴에서 자동 다운로드를 클릭하고 **HTML 전자 메일 또는 RSS 항목에 그림을 자동으로 다운로드하지 않음** 확인란을 선택합니다.

   ![](assets/win-5.png)

1. [보안 센터] 대화 상자에서 **확인**&#x200B;을 클릭합니다.

   ![](assets/win-6.png)

1. Outlook 옵션 대화 상자에서 **확인**&#x200B;을 클릭합니다.

   ![](assets/win-6.png)

## 데스크탑(Mac) {#desktop-mac}

전자 메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 보기를 추적합니다. 자동으로 다운로드할 이미지를 비활성화하여 Outlook의 자체 보기 횟수를 크게 줄일 수 있습니다. 다음은 방법 단계입니다.

1. Outlook의 메뉴 표시줄에서 **Outlook**&#x200B;을 클릭하고 **기본 설정**&#x200B;을 선택합니다.

   ![](assets/mac-1.png)

1. [전자 메일]에서 **읽기**&#x200B;를 선택합니다.

   ![](assets/mac-2.png)

1. 보안에서 **절대** 라디오 단추를 클릭합니다.

   ![](assets/mac-3.png)

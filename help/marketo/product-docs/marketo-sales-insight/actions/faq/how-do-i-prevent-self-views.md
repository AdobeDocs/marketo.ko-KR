---
description: 자체 보기를 방지하는 방법 - Marketo 문서 - 제품 설명서
title: 자체 보기를 방지하려면 어떻게 합니까?
hide: true
hidefromtoc: true
source-git-commit: 3b7cc0c855221f6fd0fba6dca08ccbe361ca9758
workflow-type: tm+mt
source-wordcount: '314'
ht-degree: 0%

---

# 자체 보기를 방지하려면 어떻게 해야 합니까? {#how-do-i-prevent-self-views}

보기 추적에 긍정 오류가 있으면 보고가 일치하지 않을 수 있습니다. 이러한 일은 Marketo Sales 사용자가 실수로 이메일 클라이언트에서 추적 픽셀을 호출할 때 종종 발생합니다(자체 보기라고 함). 다음은 크게 줄이고 자체 보기를 제거하는 몇 가지 팁입니다.

## 웹(Outlook Web App 및 Gmail) {#web-outlook-web-app-and-gmail}

Marketo Sales는 Outlook Web App 및 Gmail에서 이메일을 열 때 보기가 추적되지 않도록 브라우저에 쿠키를 저장합니다. 여전히 자체 보기를 받는 경우, 다음을 수행하는 것이 좋습니다.

* 컴퓨터에서 쿠키를 활성화했는지 확인합니다.

* 새 컴퓨터 또는 모바일 장치를 사용하는 경우 웹 애플리케이션에 로그인했는지 확인하십시오. 이렇게 하면 사용자의 컴퓨터/장치가 앞으로 나아가고 있음을 알 수 있습니다.

## 데스크탑(Windows) {#desktop-windows}

보기는 이메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 추적됩니다. 이미지를 자동으로 다운로드하도록 비활성화하여 Outlook에서 자체 보기 수를 크게 줄일 수 있습니다. 아래는 방법 단계입니다.

1. Outlook에서 **파일** 메뉴 모음에서 를 클릭합니다.

   ![](assets/how-do-i-prevent-self-views-1.png)

1. 클릭 **옵션**.

   ![](assets/how-do-i-prevent-self-views-2.png)

1. Outlook 옵션 대화 상자에서 **Trust Center**.

   ![](assets/how-do-i-prevent-self-views-3.png)

1. Microsoft Outlook Trust Center에서 **트러스트 센터 설정**.

   ![](assets/how-do-i-prevent-self-views-4.png)

1. 왼쪽 메뉴에서 자동 다운로드 를 클릭하고 **HTML 전자 메일 또는 RSS 항목에 그림을 자동으로 다운로드하지 마십시오** 확인란을 선택합니다.

   ![](assets/how-do-i-prevent-self-views-5.png)

1. 클릭 **확인** 신뢰 센터 대화 상자에서 클릭합니다.

   ![](assets/how-do-i-prevent-self-views-6.png)

1. 클릭 **확인** [Outlook 옵션] 대화 상자에서 다음을 수행합니다.

   ![](assets/how-do-i-prevent-self-views-7.png)

## 데스크탑(Mac) {#desktop-mac}

보기는 이메일 클라이언트에서 보이지 않는 작은 이미지 픽셀을 다운로드하여 추적됩니다. 이미지를 자동으로 다운로드하도록 비활성화하여 Outlook에서 자체 보기 수를 크게 줄일 수 있습니다. 아래는 방법 단계입니다.

1. Outlook에서 **Outlook** 메뉴 모음에서 를 선택하고 **기본 설정**.

   ![](assets/how-do-i-prevent-self-views-8.png)

1. Email에서 을 선택합니다. **읽기**.

   ![](assets/how-do-i-prevent-self-views-9.png)

1. 보안(Security)에서 **절대 안 함** 라디오 단추입니다.

   ![](assets/how-do-i-prevent-self-views-10.png)
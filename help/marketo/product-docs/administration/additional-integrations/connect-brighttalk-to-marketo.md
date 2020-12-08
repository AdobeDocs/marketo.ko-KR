---
unique-page-id: 15695874
description: BrightTALK를 Marketing과 연결 - Marketing Docs - 제품 설명서
title: BrightTALK를 Marketing과 연결
translation-type: tm+mt
source-git-commit: 23428a6e0ba9b2108a8f2f7dd6a69929dd069834
workflow-type: tm+mt
source-wordcount: '341'
ht-degree: 0%

---


# BrightTALK를 Marketing과 연결 {#connect-brighttalk-to-marketo}

BrightTALK 채널을 마케팅 인스턴스에 연결하는 방법을 알아봅니다. 이렇게 하려면 두 사람 모두 관리자여야 합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## BrightTALK의 단계 {#steps-in-brighttalk}

1. business.brighttalk.com/demandcentral에 로그인하여 [지금](http://business.brighttalk.com/demandcentral/login) **연결을 클릭합니다**.
1. 고급 마케팅 커넥터에서 **연결을 클릭합니다**.
1. 다음과 같은 자격 증명 화면으로 표시됩니다.클라이언트 ID, 클라이언트 암호, ID 서비스 URL 및 Rest 서비스 URL. 이 정보를 얻으려면 Marketing에 로그인합니다.

## 마케팅 단계 {#steps-in-marketo}

>[!NOTE]
>
>이때 BrightTALK가 Marketing 인스턴스에서 보유할 권한을 제한하기 위해 API 전용 사용자 역할 및 API 사용자를 설정해야 합니다. 이러한 단계를 위한 아티클이 이미 있으므로 해당 단계에 연결해드리겠습니다.

1. API 전용 [사용자 역할을 만듭니다](http://docs.marketo.com/x/iwMk).
1. [4단계 동안 만든 BrightTALK API 역할을 사용하여 API 사용자를](http://docs.marketo.com/x/jwMk)만듭니다.
1. 관리 영역으로 돌아갑니다.

   ![](assets/one.png)

1. 통합에서 LaunchPoint를 **클릭합니다**.

   ![](assets/two.png)

1. 새로 **만들기** 드롭다운을 클릭하고 **새 서비스를 선택합니다**.

   ![](assets/three.png)

1. 선택한 표시 이름을 입력합니다. 서비스 드롭다운을 클릭하고 사용자 지정 **을** 선택합니다(BrightTALK를 **선택하지** 않음).

   ![](assets/four.png)

   >[!CAUTION]
   >
   >드롭다운에서 BrightTALK를 선택하지 않아야 합니다. 현재 제거 중인 필드이며 이 필드를 선택하면 Marketing/BrightTALK 통합에 중요한 문제가 발생할 수 있습니다.

1. 원하는 설명을 입력합니다. API 전용 사용자 드롭다운을 클릭하고 5단계 동안 만든 BrightTALK API 사용자를 선택합니다. 만들기를 **클릭합니다**.

   ![](assets/five.png)

1. 방금 **만든 사용자 지정 서비스에** 대한 세부 사항 보기를 클릭합니다.

   ![](assets/six.png)

1. 클라이언트 ID 및 **클라이언트 암호** 복사(및 저장) **를 수행합니다**. 닫기를 **클릭합니다**.

   ![](assets/eight-1.png)

1. 통합에서 **웹 서비스를 선택합니다**.

   ![](assets/nine-1.png)

1. Rest API에서 **끝점** 및 ID를 복사(및 저장) **합니다**.

   ![](assets/ten.png)

## BrightTALK의 단계 {#steps-in-brighttalk-1}

1. 3단계에서 BrightTALK 커넥터 설정 화면으로 돌아가서 12단계 및 14단계에서 저장한 자격 증명을 입력합니다.

   자격 증명이 인증되면 BrightTALK를 Marketing에 공식적으로 연결합니다. 다음 단계는 동기화할 [데이터 필드를 결정하는 것입니다](http://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync).


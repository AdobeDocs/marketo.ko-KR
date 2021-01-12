---
unique-page-id: 15695874
description: BrightTALK를 마케팅에 연결 - 마케팅 문서 - 제품 설명서
title: BrightTALK를 Marketing과 연결
translation-type: tm+mt
source-git-commit: 78961a3e163ce903facf955a9dda6909b5e85bad
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---


# BrightTALK를 Marketing에 연결 {#connect-brighttalk-to-marketo}

BrightTALK 채널을 마케팅 인스턴스와 연결하는 방법을 알아봅니다. 이렇게 하려면 두 사람 모두 관리자여야 합니다.

>[!NOTE]
>
>**관리자 권한 필요**

## BrightTALK {#steps-in-brighttalk}의 단계

1. [business.brighttalk.com/demandcentral](http://business.brighttalk.com/demandcentral/login)에 로그인하고 **지금 연결**&#x200B;을 클릭합니다.
1. 고급 마케팅 커넥터에서 **연결**&#x200B;을 클릭합니다.
1. 다음을 묻는 자격 증명 화면으로 표시됩니다.클라이언트 ID, 클라이언트 암호, ID 서비스 URL 및 Rest 서비스 URL. 이 정보를 얻으려면 Marketing에 로그인합니다.

## Marketing의 단계 {#steps-in-marketo}

>[!NOTE]
>
>이때 BrightTALK가 마케팅 인스턴스에서 보유할 권한을 제한하기 위해 API 전용 사용자 역할 및 API 사용자를 설정해야 합니다. 이러한 단계를 위한 아티클이 이미 있으므로 해당 단계에 연결하겠습니다.

1. [API 전용 사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md)을 만듭니다.
1. [4단계](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) 동안 만든 BrightTALK API 역할을 사용하여 API 사용자를 만듭니다.
1. 관리 영역으로 돌아갑니다.

   ![](assets/one.png)

1. 통합에서 **LaunchPoint**&#x200B;를 클릭합니다.

   ![](assets/two.png)

1. **새로 만들기** 드롭다운을 클릭하고 **새 서비스**&#x200B;를 선택합니다.

   ![](assets/three.png)

1. 선택한 표시 이름을 입력합니다. 서비스 드롭다운을 클릭하고 **사용자 지정**(BrightTALK 선택 안 함&#x200B;_하지 않음_&#x200B;을 선택합니다.)

   ![](assets/four.png)

   >[!CAUTION]
   >
   >드롭다운에서 BrightTALK를 선택하지 않아야 합니다. 이는 현재 제거하는 작업 중이며 이를 선택하면 Marketing to/BrightTALK 통합에 중요한 문제가 발생할 수 있습니다.

1. 원하는 설명을 입력합니다. API 전용 사용자 드롭다운을 클릭하고 5단계 동안 만든 BrightTALK API 사용자를 선택합니다. **만들기**&#x200B;를 클릭합니다.

   ![](assets/five.png)

1. 방금 만든 사용자 지정 서비스에 대해 **세부 사항 보기**&#x200B;를 클릭합니다.

   ![](assets/six.png)

1. **클라이언트 ID** 및 **클라이언트 암호**&#x200B;를 복사(및 저장)합니다. **닫기**&#x200B;를 클릭합니다.

   ![](assets/eight-1.png)

1. 통합에서 **웹 서비스**&#x200B;를 선택합니다.

   ![](assets/nine-1.png)

1. Rest API 아래에서 **끝점** 및 **ID**&#x200B;를 복사(및 저장)합니다.

   ![](assets/ten.png)

## BrightTALK {#additional-steps-in-brighttalk}의 추가 단계

1. 3단계에서 BrightTALK 커넥터 설정 화면으로 돌아가서 12단계 및 14단계에서 저장한 자격 증명을 입력합니다.

   자격 증명이 인증되면 BrightTALK를 공식적으로 Marketing에 연결합니다. 다음 단계는 [동기화할 데이터 필드를 결정하는 것입니다](http://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync).

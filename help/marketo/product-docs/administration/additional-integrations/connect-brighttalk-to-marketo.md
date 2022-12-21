---
unique-page-id: 15695874
description: BrightTALK를 Marketo에 연결 - Marketo 문서 - 제품 설명서
title: Marketo에 BrightTALK 연결
exl-id: 5c6a12ec-301b-4dec-975c-24ec759ebb37
source-git-commit: 5f509a7aa27692e54bf129b94c657aff0f645f2b
workflow-type: tm+mt
source-wordcount: '343'
ht-degree: 1%

---

# Marketo에 BrightTALK 연결 {#connect-brighttalk-to-marketo}

BrightTALK 채널을 Marketo 인스턴스에 연결하는 방법을 배웁니다. 이를 수행하려면 두 모두에 대한 관리자여야 합니다.

>[!NOTE]
>
>**관리 권한 필요**

## BrightTALK의 단계 {#steps-in-brighttalk}

1. 에 로그인합니다. [business.brighttalk.com/demandcentral](https://business.brighttalk.com/demandcentral/login){target=&quot;_blank&quot;} 를 클릭하고 **지금 연결**.
1. Advanced Marketo Connector에서 **Connect**.
1. 자격 증명 화면으로 와서 다음을 요청합니다. 클라이언트 ID, 클라이언트 암호, ID 서비스 URL 및 Rest 서비스 URL. 이 정보를 가져오려면 Marketo에 로그인하십시오.

## Marketo의 단계 {#steps-in-marketo}

>[!NOTE]
>
>이 시점에서 BrightTALK가 Marketo 인스턴스에 가질 권한을 제한하려면 API 전용 사용자 역할 및 API 사용자를 설정해야 합니다. 이러한 단계에 대한 문서가 이미 있으므로 해당 문서에 연결하겠습니다.

1. 만들기 [API 전용 사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md){target=&quot;_blank&quot;}.

1. [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target=&quot;_blank&quot;}, 4단계에서 만든 BrightTALK API 역할을 사용합니다.

1. 관리자 영역으로 돌아갑니다.

   ![](assets/connect-brighttalk-to-marketo-1.png)

1. 통합에서 **LaunchPoint**.

   ![](assets/connect-brighttalk-to-marketo-2.png)

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **새 서비스**.

   ![](assets/connect-brighttalk-to-marketo-3.png)

1. 원하는 표시 이름을 입력합니다. Service 드롭다운을 클릭하고 을 선택합니다. **사용자 지정** (do) _not_ BrightTALK)를 선택합니다.

   ![](assets/connect-brighttalk-to-marketo-4.png)

   >[!CAUTION]
   >
   >드롭다운에서 BrightTALK를 선택하지 않아야 합니다. 현재 제거하고 있는 필드이며 이 필드를 선택하면 Marketo/BrightTALK 통합에 중요한 문제가 발생할 수 있습니다.

1. 원하는 내용을 입력합니다. API 전용 사용자 드롭다운을 클릭하고 5단계에서 만든 BrightTALK API 사용자를 선택합니다. Click **Create**.

   ![](assets/connect-brighttalk-to-marketo-5.png)

1. 클릭 **세부 사항 보기** 방금 만든 사용자 지정 서비스에 대해 사용됩니다.

   ![](assets/connect-brighttalk-to-marketo-6.png)

1. 을(를) 복사하여 저장합니다 **클라이언트 ID** 및 **클라이언트 암호**. Click **Close**.

   ![](assets/connect-brighttalk-to-marketo-7.png)

1. 통합에서 을 선택합니다 **웹 서비스**.

   ![](assets/connect-brighttalk-to-marketo-8.png)

1. Rest API에서 를 복사(및 저장)합니다 **끝점** 및 **ID**.

   ![](assets/connect-brighttalk-to-marketo-9.png)

## BrightTALK의 추가 단계 {#additional-steps-in-brighttalk}

1. 3단계에서 BrightTALK 커넥터 설정 화면으로 돌아가서 12단계 및 14단계에서 저장한 자격 증명을 입력합니다.

   자격 증명이 인증되면 BrightTALK를 Marketo에 공식적으로 연결합니다. 다음 단계는 [동기화할 데이터 필드](https://support.brighttalk.com/hc/en-us/articles/115005131274-BrightTALK-Connector-for-Marketo-Choose-the-Fields-to-Sync){target=&quot;_blank&quot;}.

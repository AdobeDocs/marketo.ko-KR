---
unique-page-id: 2360297
description: IP를 기반으로 Marketo 로그인 제한 - Marketo 문서 - 제품 설명서
title: IP를 기반으로 Marketo 로그인 제한
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---

# IP를 기반으로 Marketo 로그인 제한 {#restrict-marketo-logins-based-on-ip}

사용자가 IP 주소를 기반으로 Marketo에 액세스하는 것을 제한하거나 활성화할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리 권한 필요**

>[!NOTE]
>
>이 문서의 정보는 login.marketo.com의 직접 로그인에만 적용됩니다. 현재 SSO(Single Sign-On) 로그인에 IP 제한을 적용할 수 없습니다.

1. 아래 **관리**&#x200B;를 클릭합니다. **로그인 설정**.

   ![](assets/image2014-9-16-12-3a57-3a56.png)

1. 클릭 **IP 제한 편집**.

   ![](assets/image2014-9-16-12-3a58-3a13.png)

1. 선택 **허용** 또는 **블록** 특정 주소를 입력한 다음 **저장**.

   >[!NOTE]
   >
   >**정의**
   >
   >* **허용된 IP 주소**: 허용되는 IP 주소를 추가하는 것은 포함됩니다. 지정된 모든 IP 주소가 포함되며 다른 모든 주소는 제외합니다.
   >* **IP 주소 차단**: 특정 IP가 Marketo에 액세스하지 못하도록 합니다.
   >* **IP 제한 사용 안 함**: 이를 선택하면 모든/모든 제한 규칙이 작동하지 않습니다. 테스트 목적으로 사용합니다.


   >[!NOTE]
   >
   >여러 제한 사항을 추가할 수 있지만 ALL 허용 또는 ALL 차단만 될 수 있습니다. 허용 및 차단을 혼합하여 사용할 수 없습니다.

   ![](assets/image2014-9-16-13-3a9-3a40.png)

   잘 됐군요, 당신의 마케팅 데이터는 지금 그 어느 때보다 더 안전합니다!

---
unique-page-id: 2360297
description: IP를 기반으로 Marketo 로그인 제한 - Marketo 문서 - 제품 설명서
title: IP를 기준으로 Marketo 로그인 제한
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 11%

---

# IP를 기준으로 Marketo 로그인 제한 {#restrict-marketo-logins-based-on-ip}

사용자가 IP 주소를 기반으로 Marketo에 액세스하지 못하도록 제한하거나 활성화할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!IMPORTANT]
>
>이 문서의 정보는 login.marketo.com에 직접 로그인하는 사용자를 위한 것으로 Adobe ID을 통해 인증하는 사용자에게는 적용되지 않습니다. 지금은 SSO(Single Sign-On) 로그인에 IP 제한을 적용할 수 없습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/restrict-marketo-logins-based-on-ip-1.png)

1. **[!UICONTROL Login Settings]**&#x200B;를 클릭합니다.

   ![](assets/restrict-marketo-logins-based-on-ip-2.png)

1. **[!UICONTROL Edit IP Restrictions]**&#x200B;를 클릭합니다.

   ![](assets/restrict-marketo-logins-based-on-ip-3.png)

1. 특정 주소를 **허용**&#x200B;할지 **차단**&#x200B;할지 선택하고 주소를 입력한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >**정의**
   >
   >* **[!UICONTROL Allowed IP addresses]**: 허용된 IP 주소를 추가하는 것은 필수입니다. 지정된 모든 IP 주소를 포함하며 그 외의 모든 주소는 제외됩니다.
   >* **[!UICONTROL Block IP addresses]**: 특정 IP가 Marketo에 액세스하지 못하도록 합니다.
   >* **[!UICONTROL Disable IP Restrictions]**: 이 옵션을 선택하면 모든 제한 규칙이 작동하지 않습니다. 테스트 목적으로 사용하십시오.

   >[!NOTE]
   >
   >여러 제한을 추가할 수 있지만 모두 허용되거나 모두 차단될 수 있습니다. 섞어서 허용과 차단을 일치시킬 수 없습니다.

   ![](assets/restrict-marketo-logins-based-on-ip-4.png)

   좋습니다. 이제 마케팅 데이터가 이전보다 안전해졌습니다.

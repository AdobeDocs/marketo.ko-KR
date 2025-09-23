---
unique-page-id: 10098433
description: IP 기반 API용 허용 목록에 추가하다 만들기 - Marketo 문서 - 제품 설명서
title: IP 기반 API 액세스에 대한 허용 목록 만들기
exl-id: 1a2f2216-07ee-4d37-b883-458ea39fc452
feature: Administration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 12%

---

# IP 기반 API 액세스에 대한 허용 목록 만들기 {#create-an-allowlist-for-ip-based-api-access}

경우에 따라 특정 IP 주소 또는 주소 범위에만 API 액세스 권한을 제공하려고 합니다. 이렇게 하려면 먼저 제한을 활성화한 다음 API 사용이 허용되는 IP 주소를 지정합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>이 기능은 Marketo Engage IP 기반 로그인 제한 사항( Admin Console의 IP 액세스 목록*으로 대체됨)과 독립적으로 작동하며 [Adobe IMS 마이그레이션](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) 후에도 계속 작동합니다.
>&#x200B;> 
>&#x200B;>&#42;IP 액세스 목록의 일반 가용성은 2025년 4분기에 예정되어 있습니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/create-an-allowlist-for-ip-based-api-access-1.png)

1. **[!UICONTROL Web Services]**&#x200B;를 클릭합니다.

   ![](assets/create-an-allowlist-for-ip-based-api-access-2.png)

1. **[!UICONTROL IP Restrictions]** 영역에서 **[!UICONTROL Edit],**&#x200B;을(를) 클릭하거나 왼쪽 상단의 **[!UICONTROL Edit IP Restrictions]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-an-allowlist-for-ip-based-api-access-3.png)

1. **[!UICONTROL Enable IP Restrictions]** 상자를 선택하고 허용 목록에 사용할 IP 주소를 입력하십시오.

   ![](assets/create-an-allowlist-for-ip-based-api-access-4.png)

   >[!NOTE]
   >
   >단일 IP 주소 또는 주소 범위를 입력하거나 와일드카드를 사용할 수 있습니다.

1. 추가 필드를 열어 추가 IP 주소를 입력하려면 **[!UICONTROL Add]**&#x200B;을(를) 클릭하십시오.

   ![](assets/create-an-allowlist-for-ip-based-api-access-5.png)

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/create-an-allowlist-for-ip-based-api-access-6.png)

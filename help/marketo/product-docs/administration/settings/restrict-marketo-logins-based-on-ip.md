---
unique-page-id: 2360297
description: IP를 기반으로 Marketo 로그인 제한 - Marketo 문서 - 제품 설명서
title: IP를 기준으로 Marketo 로그인 제한
exl-id: 5d9d0b88-b4bc-4e1b-b70c-2c2e7b4269f5
feature: Administration
source-git-commit: 3595cdc76a0f92da10dc5ddaac64c4cf83056e88
workflow-type: tm+mt
source-wordcount: '220'
ht-degree: 9%

---

# IP를 기준으로 Marketo 로그인 제한 {#restrict-marketo-logins-based-on-ip}

사용자가 IP 주소를 기반으로 Marketo에 액세스하지 못하도록 제한하거나 활성화할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!IMPORTANT]
>
>AAC(Adobe Admin Console)는 [IP 기반 액세스 제어](https://helpx.adobe.com/enterprise/using/ip-based-access.html){target="_blank"}를 지원합니다. 원활한 전환을 위해 이 기능이 활성화된 구독에서는 2026년 1분기까지 Adobe ID 사용자를 포함하여 기존 Marketo Engage IP 제한 사항이 활성화됩니다.
>
>* 언제든지 AAC IP 기반 액세스를 구성할 수 있습니다.
>* AAC 및 Marketo Engage 제한 사항은 모두 동시에 실행할 수 있습니다. 호환성을 위해 동일한 IP 허용 목록을 사용합니다.
>
>2026년 1분기 이후에는 Marketo Engage IP 제한 사항이 중단됩니다. IP 기반 액세스는 AAC를 통해서만 관리되며 로그인 제한을 적용하도록 구성해야 합니다. 최종 전환일은 나중에 발표될 예정입니다.

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

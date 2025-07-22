---
unique-page-id: 2360358
description: SSO로만 사용자 로그인 제한 - Marketo 문서 - 제품 설명서
title: SSO로만 사용자 로그인 제한
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
feature: Administration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 1%

---

# SSO로만 사용자 로그인 제한 {#restrict-user-login-to-sso-only}

[SSO를 사용](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)하고 있으며 사용자가 SSO 보안을 무시할 수 없도록 하려면 다음 지침을 따르십시오.

>[!IMPORTANT]
>
>이 문서는 [Adobe IMS 사용](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) Marketo 구독에는 적용되지 않습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. **[!UICONTROL Login Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. **[!UICONTROL Edit Security Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. **[!UICONTROL Advanced]** 설정을 확장하고 **[!UICONTROL Require SSO]**&#x200B;을(를) 확인한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>가장 좋은 방법은 사용자를 초대하고 초대를 수락하는 것입니다. _초대가 수락된 후_ 관리자는 초대를 &quot;[!UICONTROL Require SSO]&quot;(으)로 설정해야 합니다.

>[!TIP]
>
>**[!UICONTROL Require SSO]**&#x200B;을(를) 선택하는 경우 역할을 설정하는 동안 [ 옵션을 선택하여 ](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md)사용자 역할&#x200B;**[!UICONTROL Bypass Single Sign-On]**&#x200B;을(를) 이 제한에서 제외할 수 있습니다. 이렇게 하면 사용자가 정상적으로 로그인할 수 있습니다. 예를 들어 관리자는 로그인 화면을 통해 Marketo에 로그인해야 할 수 있습니다. SSO와 Universal ID가 모두 활성화되어 있으면 구독 간에 전환하려면 &quot;단일 사인온 우회&quot; 권한이 설정되어 있어야 합니다.

>[!CAUTION]
>
>새 사용자가 초대되면 초대 이메일을 받습니다. 그러나 **[!UICONTROL Require SSO]**&#x200B;을(를) 선택한 경우 **[!UICONTROL Bypass Single Sign-On]**(으)로 설정된 역할에 할당되지 않으면 해당 전자 메일을 받지 못합니다.

됐습니다. 이제 모든 사용자(Single Sign-On을 무시하는 권한이 있는 사용자 제외)가 SSO 로그인만 사용하도록 제한됩니다.

>[!MORELIKETHIS]
>
>* [포털에 SSO(Single Sign-On) 추가](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [범용 ID를 사용하는 두 개의 인스턴스에 Marketo 사용자 초대](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)

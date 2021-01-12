---
unique-page-id: 2360358
description: 사용자 로그인을 SSO로만 제한 - 마케팅 문서 - 제품 설명서
title: 사용자 로그인을 SSO로만 제한
translation-type: tm+mt
source-git-commit: 78961a3e163ce903facf955a9dda6909b5e85bad
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# 사용자 로그인을 SSO로만 제한 {#restrict-user-login-to-sso-only}

[SSO](add-single-sign-on-to-a-portal.md)을(를) 사용하고 있고 사용자가 SSO 보안을 우회할 수 없도록 하려면 다음 지침을 따르십시오.

>[!NOTE]
>
>**관리자 권한 필요**

1. **관리**&#x200B;로 이동하고 **로그인 설정**&#x200B;을 클릭합니다.

![](assets/image2014-9-24-14-3a44-3a40.png)

1. **보안 설정 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. 고급 설정을 확장하고 **SSO 필요**&#x200B;를 선택한 다음 **저장**&#x200B;을 클릭합니다.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!TIP]
>
>**SSO 필요**&#x200B;를 선택하는 경우 역할을 설정하는 동안 **단일 사인온 무시** 옵션을 선택하여 이 제한에서 [사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md)을 제외할 수 있습니다. 이렇게 하면 사용자가 정상적으로 로그인할 수 있습니다. 예를 들어 관리 사용자는 로그인 화면을 통해 Marketing To에 계속 로그인해야 할 수 있습니다.

>[!CAUTION]
>
>새 사용자가 초대되면 초대 이메일을 받습니다. 그러나 **SSO 필요**&#x200B;를 선택한 경우 **단일 사인온 무시**&#x200B;로 설정된 역할에 할당되지 않으면 이러한 이메일은 수신되지 않습니다.

바로 그거야! 이제 모든 사용자(단일 사인온을 무시할 권한이 있는 사용자 제외)는 SSO 로그인 전용으로 제한됩니다.

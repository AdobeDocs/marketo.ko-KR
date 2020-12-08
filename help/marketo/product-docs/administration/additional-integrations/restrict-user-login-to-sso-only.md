---
unique-page-id: 2360358
description: 사용자 로그인을 SSO로만 제한 - Marketing Docs - 제품 설명서
title: 사용자 로그인을 SSO로만 제한
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 0%

---


# 사용자 로그인을 SSO로만 제한 {#restrict-user-login-to-sso-only}

SSO [를](add-single-sign-on-to-a-portal.md) 사용하고 있고 사용자가 SSO 보안을 무시할 수 없도록 하려면 다음 지침을 따르십시오.

>[!NOTE]
>
>**관리자 권한 필요**

1. 관리자로 이동하고 로그인 설정을 클릭합니다.

![](assets/image2014-9-24-14-3a44-3a40.png)

1. 보안 설정 편집을 클릭합니다.

   ![](assets/image2014-9-24-14-3a44-3a53.png)

1. 고급 설정을 확장하고 SSO 필요를 선택한 다음 저장을 클릭합니다.

![](assets/image2014-9-24-14-3a45-3a6.png)

>[!TIP]
>
>SSO 필요 **를**&#x200B;선택하는 경우 역할을 [설정하는 동안 단일 사인온](../../../product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) 무시 **옵션을 선택하여** 사용자 역할을이 제한에서 제외할 수 있습니다. 그러면 사용자가 정상적으로 로그인할 수 있습니다. 예를 들어 관리 사용자는 로그인 화면을 통해 Marketing To에 계속 로그인해야 할 수 있습니다.

>[!CAUTION]
>
>새 사용자가 초대되면 초대 이메일을 받습니다. 그러나 [SSO **필요** ]를 선택한 경우 [단일 사인온 무시]로 설정된 역할에 **지정되어 있지 않으면 이러한 이메일은 수신되지 않습니다**.

바로 그거야! 이제 모든 사용자(단일 사인온을 무시할 수 있는 권한이 있는 사용자 제외)가 SSO 로그인 전용으로 제한됩니다.
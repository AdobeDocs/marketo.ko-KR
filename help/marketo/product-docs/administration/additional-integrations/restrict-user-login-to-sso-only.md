---
unique-page-id: 2360358
description: SSO로만 사용자 로그인 제한 - Marketo 문서 - 제품 설명서
title: 사용자 로그인을 SSO로만 제한
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
source-git-commit: 5f509a7aa27692e54bf129b94c657aff0f645f2b
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 0%

---

# 사용자 로그인을 SSO로만 제한 {#restrict-user-login-to-sso-only}

만약 [SSO 사용](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) 또한 사용자가 SSO 보안을 우회할 수 없도록 하려면 다음 지침을 따르십시오.

>[!IMPORTANT]
>
>이 문서는 다음 항목에 적용되지 않습니다 [Adobe IMS 지원](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) Marketo 구독.

>[!NOTE]
>
>**관리 권한 필요**

1. 로 이동합니다. **관리** 영역.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. 클릭 **로그인 설정**.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. 클릭 **보안 설정 편집**.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. 고급 설정을 확장하고 다음을 확인합니다. **SSO 필요**&#x200B;를 클릭하고 **저장**.

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>가장 좋은 방법은 사용자를 초대하고 초대를 수락하는 것입니다. _후_ 초대가 수락되면 관리자는 &quot;SSO 필요&quot;로 설정해야 합니다.

>[!TIP]
>
>선택하는 경우 **SSO 필요**&#x200B;를 제외할 수 있습니다 [사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) 이 제한 사항에서 **단일 사인온 무시** 옵션을 설정합니다. 이렇게 하면 사용자가 정상적으로 로그인할 수 있습니다. 예를 들어 관리자는 로그인 화면을 통해 Marketo에 계속 로그인해야 할 수 있습니다.

>[!CAUTION]
>
>새 사용자가 초대되면 초대 이메일을 받습니다. 그러나, **SSO 필요** 을(를) 선택하면 이(가) 설정된 역할에 할당되지 않은 경우 이러한 이메일을 받지 않습니다 **단일 사인온 무시**.

됐습니다. 이제 모든 사용자(단일 사인온을 무시할 권한이 있는 사용자 제외)는 SSO 로그인만 사용하도록 제한됩니다.

>[!MORELIKETHIS]
>
>* [포털에 단일 사인온 추가](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [범용 ID를 사용하여 Marketo 사용자를 두 인스턴스로 초대합니다.](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)


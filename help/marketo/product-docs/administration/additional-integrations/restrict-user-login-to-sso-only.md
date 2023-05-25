---
unique-page-id: 2360358
description: SSO로만 사용자 로그인 제한 - Marketo 문서 - 제품 설명서
title: SSO로만 사용자 로그인 제한
exl-id: 74915871-dcf5-478d-a5ae-b20c3d2de553
source-git-commit: 1f10e1fcdbd5cf91481f749236fd37050ade29f8
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---

# SSO로만 사용자 로그인 제한 {#restrict-user-login-to-sso-only}

만약.. [SSO 사용](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md) 사용자가 SSO 보안을 무시할 수 없도록 하려면 다음 지침을 따르십시오.

>[!IMPORTANT]
>
>이 조항은 다음 대상에는 적용되지 않습니다. [Adobe IMS 활성화](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md) Marketo 구독.

>[!NOTE]
>
>**관리자 권한 필요**

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/restrict-user-login-to-sso-only-1.png)

1. 클릭 **[!UICONTROL 로그인 설정]s**.

   ![](assets/restrict-user-login-to-sso-only-2.png)

1. 클릭 **[!UICONTROL 보안 설정 편집]**.

   ![](assets/restrict-user-login-to-sso-only-3.png)

1. 확장 **[!UICONTROL 고급]** 설정, 확인 **[!UICONTROL SSO 필요]**, 및 클릭 **[!UICONTROL 저장]**.

![](assets/restrict-user-login-to-sso-only-4.png)

>[!NOTE]
>
>가장 좋은 방법은 사용자를 초대하고 초대를 수락하는 것입니다. _다음 이후_ 초대가 수락되면 관리자는 초대를 다음으로 설정해야 합니다.[!UICONTROL SSO 필요].&quot;

>[!TIP]
>
>다음을 선택하는 경우 **[!UICONTROL SSO 필요]**, 다음을 제외할 수 있습니다. [사용자 역할](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md) 을(를) 확인하여 이 제한에서 **[!UICONTROL 단일 사인온 무시]** 옵션을 선택합니다. 이렇게 하면 사용자가 정상적으로 로그인할 수 있습니다. 예를 들어 관리자는 로그인 화면을 통해 Marketo에 로그인해야 할 수 있습니다.

>[!CAUTION]
>
>새 사용자가 초대되면 초대 이메일을 받습니다. 그러나 다음과 같은 경우에는 **[!UICONTROL SSO 필요]** 이(가) 선택되면 설정된 역할에 할당되지 않는 한 이러한 이메일을 수신하지 않습니다. **[!UICONTROL 단일 사인온 무시]**.

다 됐습니다! 이제 모든 사용자(Single Sign-On을 무시하는 권한이 있는 사용자 제외)가 SSO 로그인만 사용하도록 제한됩니다.

>[!MORELIKETHIS]
>
>* [포털에 SSO(Single Sign-On) 추가](/help/marketo/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal.md)
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [Marketo 사용자를 범용 ID를 사용하는 두 개의 인스턴스에 초대](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)


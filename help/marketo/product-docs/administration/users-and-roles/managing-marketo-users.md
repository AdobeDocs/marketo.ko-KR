---
unique-page-id: 2359906
description: Marketo 사용자 관리 - Marketo 문서 - 제품 설명서
title: Marketo 사용자 관리
exl-id: 40506d3c-a7cb-45fb-bc10-021bd0c70806
feature: Users and Roles
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 7%

---

# Marketo 사용자 관리 {#managing-marketo-users}

>[!IMPORTANT]
>
>이 문서는 Adobe Identity가 있는 _Marketo_&#x200B;을(를) [사용 안 함](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"}하는 사용자를 위한 것입니다. 그럴 경우 [이 문서](/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md){target="_blank"}의 단계를 따르세요.

## 사용자 만들기 {#create-users}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/managing-marketo-users-1.png)

1. **[!UICONTROL Users & Roles]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-2.png)

1. **[!UICONTROL Invite New User]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-3.png)

1. **[!UICONTROL Email]**, **[!UICONTROL First Name]** 및 **[!UICONTROL Last Name]**&#x200B;을(를) 입력하십시오.

   ![](assets/managing-marketo-users-4.png)

1. 필요한 경우 초대하는 이유를 입력하고 날짜 선택기를 사용하여 **[!UICONTROL Access Expires]** 필드에서 만료 날짜를 선택합니다.

   ![](assets/managing-marketo-users-5.png)

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-6.png)

   >[!TIP]
   >
   >만료 날짜는 짧은 시간 동안만 Marketo 액세스가 필요한 단기 외부 관련자 또는 컨설턴트에게 적합합니다.

   >[!NOTE]
   >
   >만료 날짜가 되면 사용자는 만료 알림을 받고 계정이 잠깁니다.

1. 선택한 **[!UICONTROL Role]**&#x200B;을(를) 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/managing-marketo-users-7.png)

1. 필요한 경우 초대 메시지를 편집합니다. **Send**&#x200B;을(를) 클릭합니다.

   ![](assets/managing-marketo-users-8.png)

   >[!NOTE]
   >
   >이메일/로그인은 고유해야 합니다. 샌드박스 인스턴스에서 이미 사용한 경우에는 프로덕션에서 다른 이메일/로그인을 사용해야 하며 그 반대의 경우도 마찬가지입니다.

   ![](assets/managing-marketo-users-9.png)

   >[!NOTE]
   >
   >초대는 새 사용자를 추가한 후 3일 후에 만료됩니다.

이제 새 사용자가 사용자 탭에 나열되며 계정 활성화 방법에 대한 지침이 포함된 이메일을 받게 됩니다.

## 사용자 삭제 {#delete-users}

>[!NOTE]
>
>삭제하려는 사용자가 Dynamic Chat 사용자이기도 한 경우 Marketo Engage에서 삭제하려면 먼저 Admin Console에서 [Dynamic Chat에서 제거](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#remove-a-chat-user){target="_blank"}해야 합니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/managing-marketo-users-10.png)

1. **[!UICONTROL Users & Roles]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-11.png)

1. 제거할 사용자를 선택하고 **[!UICONTROL Delete User]**&#x200B;을(를) 클릭합니다.

   ![](assets/managing-marketo-users-12.png)

1. **[!UICONTROL OK]**&#x200B;을(를) 클릭하여 확인합니다.

   ![](assets/managing-marketo-users-13.png)

## 사용자 암호 재설정 {#reset-user-passwords}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/managing-marketo-users-14.png)

1. **[!UICONTROL Users & Roles]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-15.png)

1. 사용자를 선택하고 **[!UICONTROL Reset Password]**&#x200B;을(를) 클릭합니다.

   ![](assets/managing-marketo-users-16.png)

1. 프롬프트를 닫으려면 **[!UICONTROL Close]**&#x200B;을(를) 클릭하십시오.

   ![](assets/managing-marketo-users-17.png)

사용자는 암호 재설정 지침이 포함된 이메일을 받게 됩니다.

>[!TIP]
>
>받은 편지함에 전자 메일이 표시되지 않으면 정크/스팸 폴더를 확인하도록 요청하세요.

## 권한 변경 및 사용자 정보 편집 {#change-permissions-and-edit-user-information}

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/managing-marketo-users-18.png)

1. **[!UICONTROL Users & Roles]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-19.png)

1. 사용자를 선택하고 **[!UICONTROL Edit User]**&#x200B;을(를) 클릭합니다.

   ![](assets/managing-marketo-users-20.png)

1. 사용자 정보를 편집하고 관련 역할을 변경할 수 있습니다. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/managing-marketo-users-21.png)

>[!CAUTION]
>
>Marketo의 유일한 관리자인 경우 자신의 관리 권한을 제거하지 마십시오.

>[!NOTE]
>
>새 사용자를 관리자로 초대하거나 관리자가 삭제되면 현재 모든 관리자가 이메일 알림을 받습니다.

멋진 작품이야! 이제 사용자를 만들고, 사용자를 삭제하고, 사용자의 암호를 재설정하고, 사용자를 편집하는 방법을 알 수 있습니다.

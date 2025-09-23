---
description: 이메일 확인 - Marketo 문서 - 제품 설명서
title: 이메일 인증
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
feature: Users and Roles
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 1%

---

# 이메일 인증 {#email-verification}

Adobe Marketo Engage 구독을 사용하려면 Marketo Engage 관리자를 포함하여 API가 아닌 모든 사용자가 이메일 주소를 확인해야 합니다.

## 이 기능이 도입된 이유 {#why-this-feature-was-introduced}

Marketo Engage은 Adobe ID로의 사용자 마이그레이션을 포함하여 고객을 Adobe Business Platform으로 마이그레이션할 것에 대비하여 이메일 확인 롤아웃을 계속 진행하고 있습니다. 이 기능은 기존 Marketo Engage 사용자 계정의 보안을 강화합니다. Marketo Engage 사용자가 적절한 Adobe ID과 연결되어 있는지 확인하려면 기존 Marketo Engage 사용자가 자신의 이메일 주소를 확인해야 합니다. Marketo Engage 사용자에게 Adobe ID으로 마이그레이션하려면 확인된 이메일 주소가 있어야 합니다. Marketo Engage 사용자가 이메일 주소를 확인하지 않는 경우, 사용자는 Adobe ID으로 마이그레이션할 수 없으며 구독에 대한 사용자 마이그레이션이 완료된 후 Marketo 구독에 대한 액세스 권한이 상실됩니다.

## 사용자 초대 {#user-invite}

관리자가 사용자를 초대하면 초대 링크를 클릭하면 해당 사용자가 자동으로 확인됩니다.

>[!IMPORTANT]
>
>위의 예외는 _SSO 전용 구독에서_ 관리자는 새 사용자 초대를 받지만 관리자가 아닌 사용자는 받지 않습니다. 관리자가 아닌 사용자는 여전히 전자 메일 확인 프로세스를 통해 레코드를 마이그레이션해야 합니다. 사용자는 &quot;내 프로필&quot; 아이콘을 클릭하고 **내 계정** > **계정 설정** > **확인 다시 보내기**&#x200B;로 이동하여 전자 메일 확인 링크를 보낼 수 있습니다.

![](assets/email-verification-1.png)

## 확인 전자 메일 {#verification-email}

구독에 대해 전자 메일 확인이 활성화되거나 관리자/사용자에 의해 트리거되는 경우 사용자는 아래 전자 메일을 받게 됩니다.

이메일 인증이 성공하려면 활성 사용자 세션이 필요합니다. 사용자는 먼저 IdP(ID 공급자) URL을 사용하여 Marketo 구독에 로그인해야 합니다. 세션이 설정되면 _그런 다음_&#x200B;이(가) 전자 메일의 **전자 메일 주소 확인** 링크를 클릭합니다.

![](assets/email-verification-2.png)

>[!TIP]
>
>확인되지 않은 사용자에게 확인 전자 메일을 다시 보내려면 해당 레코드를 선택하고 **[!UICONTROL Verify Email]** 단추를 클릭하면 됩니다.

## 이메일 주소 변경 {#changing-an-email-address}

사용자의 이메일 주소가 변경되면 확인되지 않습니다. 재확인을 허용하는 이메일이 발송됩니다. 사용자는 **[!UICONTROL Resend Verification]**&#x200B;을(를) 클릭하여 해당 이메일을 수동으로 다시 보낼 수 있습니다.

![](assets/email-verification-3.png)

![](assets/email-verification-4.png)

## 사용자 및 역할 {#users-and-roles}

**[!UICONTROL Admin]** > **[!UICONTROL Users & Roles]**&#x200B;에서 전자 메일 상태 열에 모든 사용자의 확인 상태가 표시됩니다.

![](assets/email-verification-5.png)

## 여러 사용자 로그인 ID {#multiple-user-login-ids}

하나의 이메일 주소에 하나의 사용자 계정만 연결할 수 있습니다. 단일 이메일 주소와 연결된 사용자 계정이 여러 개 있는 경우 Marketo Engage에서는 충돌을 해결해야 하며 이메일 주소와 연결된 모든 사용자 로그인과 세 가지 해결 옵션을 표시합니다.

* 현재 사용자 로그인 ID에 현재 이메일 사용
* 현재 사용자 로그인 ID에 대해 새 이메일 사용
* 다음 로그인까지 결정 지연

  ![](assets/email-verification-6.png)

>[!NOTE]
>
>사용자 계정을 단일 주소와 연결해야 하지만, 사용자 계정은 Universal ID를 통해 많은 구독에서 사용할 수 있습니다.

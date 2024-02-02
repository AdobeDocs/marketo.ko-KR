---
description: 이메일 확인 - Marketo 문서 - 제품 설명서
title: 전자 메일 확인
exl-id: 976e46a7-8c85-45ed-86c1-0c5cdb2d5c3e
feature: Users and Roles
source-git-commit: c5d5fd490fe2800dc7a34d02c73d728e115646a0
workflow-type: tm+mt
source-wordcount: '466'
ht-degree: 0%

---

# 전자 메일 확인 {#email-verification}

Adobe Marketo Engage 구독을 사용하려면 Marketo Engage 관리자를 포함하여 API가 아닌 모든 사용자가 이메일 주소를 확인해야 합니다.

## 이 기능이 도입된 이유 {#why-this-feature-was-introduced}

Marketo Engage은 Adobe ID로의 사용자 마이그레이션을 포함하여 고객을 Adobe 비즈니스 플랫폼으로 마이그레이션할 것에 대비하여 이메일 유효성 검사 롤아웃을 계속하고 있습니다. 이 기능은 기존 Marketo Engage 사용자 계정의 보안을 강화합니다. Marketo Engage 사용자가 적절한 Adobe ID과 연결되어 있는지 확인하려면 기존 Marketo Engage 사용자가 자신의 이메일 주소를 확인해야 합니다. Marketo Engage 사용자에게 Adobe ID으로 마이그레이션하려면 확인된 이메일 주소가 있어야 합니다. Marketo Engage 사용자가 이메일 주소를 확인하지 않는 경우, 사용자는 Adobe ID으로 마이그레이션할 수 없으며 구독에 대한 사용자 마이그레이션이 완료된 후 Marketo 구독에 대한 액세스 권한이 상실됩니다.

## 사용자 초대 {#user-invite}

관리자가 사용자를 초대하면 초대 링크를 클릭하면 해당 사용자가 자동으로 확인됩니다.

>[!IMPORTANT]
>
>상기 사항에 대한 예외는, _SSO 전용 구독에서_, 관리자는 새 사용자 초대를 받지만 관리자가 아닌 사용자는 받지 않습니다. 관리자가 아닌 사용자는 여전히 전자 메일 확인 프로세스를 통해 레코드를 마이그레이션해야 합니다. 로 이동하여 이메일 확인 링크를 보낼 수 있습니다. **관리자** > **내 계정** > **계정 설정** 및 클릭 **확인 다시 보내기**.

![](assets/email-verification-1.png)

## 확인 전자 메일 {#verification-email}

구독에 대해 전자 메일 확인이 활성화되거나 관리자/사용자에 의해 트리거되는 경우 사용자는 아래 전자 메일을 받게 됩니다.

이메일 인증이 성공하려면 활성 사용자 세션이 필요합니다. 사용자는 먼저 IdP(ID 공급자) URL을 사용하여 Marketo 구독에 로그인해야 합니다. 세션이 설정되면 다음 작업을 수행합니다 _그러면_ 클릭: **이메일 주소 확인** 이메일에 있는 링크입니다.

![](assets/email-verification-2.png)

>[!TIP]
>
>확인되지 않은 사용자에게 확인 이메일을 다시 보내려면 해당 기록을 선택하고 **[!UICONTROL 이메일 확인]** 단추를 클릭합니다.

## 이메일 주소 변경 {#changing-an-email-address}

사용자의 이메일 주소가 변경되면 확인되지 않습니다. 재확인을 허용하는 이메일이 발송됩니다. 사용자는 다음을 클릭하여 해당 이메일을 수동으로 다시 보낼 수 있습니다. **[!UICONTROL 확인 다시 보내기]**.

![](assets/email-verification-3.png)

![](assets/email-verification-4.png)

## 사용자 및 역할 {#users-and-roles}

위치 **[!UICONTROL 관리자]** > **[!UICONTROL 사용자 및 역할]**&#x200B;이메일 상태 열에는 모든 사용자의 확인 상태가 표시됩니다.

![](assets/email-verification-5.png)

## 여러 사용자 로그인 ID {#multiple-user-login-ids}

하나의 이메일 주소에 하나의 사용자 계정만 연결할 수 있습니다. 단일 이메일 주소와 연결된 사용자 계정이 여러 개 있는 경우 Marketo Engage은 충돌을 해결해야 하며 이메일 주소와 연결된 모든 사용자 로그인과 세 가지 해결 옵션을 표시합니다.

* 현재 사용자 로그인 ID에 현재 이메일 사용
* 현재 사용자 로그인 ID에 대해 새 이메일 사용
* 다음 로그인까지 결정 지연

  ![](assets/email-verification-6.png)

>[!NOTE]
>
>사용자 계정을 단일 주소와 연결해야 하지만, 사용자 계정은 Universal ID를 통해 많은 구독에서 사용할 수 있습니다.

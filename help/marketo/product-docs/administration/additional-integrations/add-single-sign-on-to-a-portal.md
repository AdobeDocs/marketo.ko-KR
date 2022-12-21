---
unique-page-id: 2360356
description: 포털에 단일 사인온 추가 - Marketo 문서 - 제품 설명서
title: 포털에 단일 사인온 추가
exl-id: 72f96239-7252-4cbc-bbe1-84ac7ae7f92e
source-git-commit: 813bab6169a121e90919f9a02505ccde5167cda4
workflow-type: tm+mt
source-wordcount: '540'
ht-degree: 0%

---

# 포털에 단일 사인온 추가 {#add-single-sign-on-to-a-portal}

사용자를 인증하는 디렉토리 서비스가 있는 경우 Marketo에 SSO(Single Sign-On)를 허용할 수 있습니다. SAML(Security Assertion Markup Language) 버전 2.0 이상을 사용하여 이 기능을 지원합니다.

Marketo은 SAML 서비스 공급자(SP)로 기능하며 사용자를 인증하기 위해 외부 ID 공급자(IdP)에 따라 다릅니다.

SSO가 활성화되면 IdP에서 사용자의 자격 증명을 확인할 수 있습니다. 사용자가 Marketo 소프트웨어를 사용하려는 경우 IdP는 Marketo에 SP로 작동하는 서명된 SAML 메시지를 전송합니다. 이 메시지는 사용자가 Marketo 소프트웨어를 사용할 수 있는 권한이 있음을 Marketo에 보증합니다.

>[!NOTE]
>
>**관리 권한 필요**

>[!NOTE]
>
>Microsoft Azure 사용자입니까? 해당 구성 요소 확인 [통합 자습서](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/){target=&quot;_blank&quot;}.

## 요청을 보내는 방법 {#how-to-send-the-request}

* SAML 응답인 SSO 요청을 보내십시오. `https://login.marketo.com/saml/assertion/<your-munchkin-id>`
* SP의 대상 URL로 사용됩니다. 사용 `http://saml.marketo.com/sp`
* SPNameQualifier 특성을 사용 중인 경우 [제목]에 대한 NameID 요소를 설정합니다 `http://saml.marketo.com/sp`
* 동일한 SSO 공급자에 여러 Marketo 구독을 페더레이션하는 경우 포맷으로 각 Marketo 하위 세트에 대해 고유한 SP url을 사용할 수 있습니다 `http://saml.marketo.com/sp/<munchkin_id>`

>[!NOTE]
>
>Marketo은 사용자가 먼저 Idp 로그인 페이지를 시작하고, 인증을 받은 다음 내 Marketo으로 이동하는 ID 공급자가 시작한(IdP가 시작이라고도 함)만 지원합니다.

## 추가 참고 사항 {#additional-notes}

* **동기화 시간** - 새 사용자의 경우 초기 SSO 요청이 처리되기 전에 약 10분 지연이 있습니다.
* **사용자 프로비저닝** - Marketo에서 사용자를 수동으로 프로비저닝합니다.
* **인증** - 사용자 권한은 Marketo 내에서 유지됩니다.
* **OAuth 지원** - Marketo은 현재 OAuth를 지원하지 않습니다.
* **자동 사용자 전파** - &quot;Just in Time Provisioning&quot;이라고도 하며, 사용자의 첫 번째 SAML 로그인이 사용자가 액세스하는 모든 웹 애플리케이션(예: Marketo)에서 사용자를 생성할 수 있고 수동 관리 작업이 필요하지 않은 경우입니다. 현재는 Marketo에서 지원하지 않습니다.
* **암호화** - Marketo은 현재 암호화를 지원하지 않습니다.

>[!NOTE]
>
>시작하기 전에 ID 공급자 인증서를 X.509 형식 및 .crt, .der 또는 .cer 확장으로 사용하십시오.

## SAML 설정 업데이트 {#update-saml-settings}

SSO는 기본적으로 비활성화되어 있습니다. 다음 단계에 따라 SAML을 활성화하고 구성합니다.

1. 로 이동합니다. **관리** 영역.

   ![](assets/add-single-sign-on-to-a-portal-1.png)

1. 클릭 **단일 사인온**.

   ![](assets/add-single-sign-on-to-a-portal-2.png)

   >[!NOTE]
   >
   >표시되지 않으면 **단일 사인온** 아래에 **관리**, 연락처 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target=&quot;_blank&quot;}.

1. 아래에 **SAML 설정** 섹션을 클릭합니다. **편집**.

   ![](assets/add-single-sign-on-to-a-portal-3.png)

1. 변경 **SAML 단일 사인온** to **활성화됨**.

   ![](assets/add-single-sign-on-to-a-portal-4.png)

1. 을(를) 입력합니다. **발급자 ID**, **엔티티 ID**&#x200B;에서 을(를) 선택합니다. **사용자 ID 위치**&#x200B;를 클릭한 다음 **찾아보기**.

   ![](assets/add-single-sign-on-to-a-portal-5.png)

1. 을(를) 선택합니다 **ID 공급자 인증서** 파일.

   ![](assets/add-single-sign-on-to-a-portal-6.png)

1. 클릭 **저장**.

   ![](assets/add-single-sign-on-to-a-portal-7.png)

## 리디렉션 페이지 설정 업데이트 {#update-redirect-page-settings}

1. 아래에 **페이지 리디렉션** 섹션을 클릭합니다. **편집**.

   ![](assets/add-single-sign-on-to-a-portal-8.png)

   >[!NOTE]
   >
   >SSO와 함께 범용 ID를 사용하는 고객은 ID 공급자의 로그인 URL을 **로그인 URL** 필드.

1. 을(를) 입력합니다. **로그아웃 URL**. 사용자가 Marketo에서 로그아웃할 때 이동하려는 URL입니다.

   ![](assets/add-single-sign-on-to-a-portal-9.png)

1. 을(를) 입력합니다. **오류 URL**. Marketo에 로그인하지 못할 경우 사용자에게 이동하려는 URL입니다. 클릭 **저장**.

   ![](assets/add-single-sign-on-to-a-portal-10.png)

   >[!NOTE]
   >
   >이 두 페이지를 모두 공개적으로 사용할 수 있어야 합니다.

>[!MORELIKETHIS]
>
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md){target=&quot;_blank&quot;}
>* [사용자 로그인을 SSO로만 제한](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md){target=&quot;_blank&quot;}
>* [범용 ID를 사용하여 Marketo 사용자를 두 인스턴스로 초대합니다.](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122){target=&quot;_blank&quot;}


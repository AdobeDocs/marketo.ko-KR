---
unique-page-id: 2360356
description: 포털에 단일 사인온 추가 - Marketo 문서 - 제품 설명서
title: 포털에 단일 사인온 추가
exl-id: 72f96239-7252-4cbc-bbe1-84ac7ae7f92e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '530'
ht-degree: 0%

---

# 포털 {#add-single-sign-on-to-a-portal}에 단일 사인온 추가

사용자를 인증하는 디렉토리 서비스가 있는 경우 Marketo에 SSO(Single Sign-On)를 허용할 수 있습니다. Adobe는 SAML(Security Assertion Markup Language) 버전 2.0 이상을 사용하여 이 기능을 지원합니다.

Marketo은 SAML 서비스 공급자(SP)로 기능하며 외부 ID 공급자(IdP)에 따라 사용자를 인증합니다.

SSO가 활성화되면 IdP는 사용자의 자격 증명을 확인할 수 있습니다. 사용자가 Marketo 소프트웨어를 사용하려는 경우 IdP는 SP 역할을 하는 Marketo에 서명된 SAML 메시지를 보냅니다. 이 메시지는 Marketo에 사용자가 Marketo 소프트웨어를 사용할 수 있는 권한을 부여했음을 보증합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>Microsoft Azure 사용자입니까? [통합 자습서](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/)를 확인합니다.

## 요청 {#how-to-send-the-request}을 보내는 방법

* SAML 응답인 SSO 요청을 `https://login.marketo.com/saml/assertion/<your-munchkin-id>`으로 전송합니다.
* SP의 대상 URL입니다. `https://saml.marketo.com/sp` 사용
* SPNameQualifier 특성을 사용 중인 경우 `https://saml.marketo.com/sp`에 대해 NameID 요소를 설정합니다.
* 동일한 SSO 공급자에 대해 여러 Marketo 구독을 페더레이션하는 경우, `https://saml.marketo.com/sp/<munchkin_id>` 형식의 각 Marketo 하위 항목에 대해 고유한 SP url을 사용할 수 있습니다.

>[!NOTE]
>
>Marketo은 사용자가 처음으로 Idp 로그인 페이지를 실행하고 인증을 받은 다음 내 Marketo으로 이동하는 ID 공급자 시작(IdP 시작이라고도 함)만 지원합니다.

## 추가 참고 사항 {#additional-notes}

* **동기화 시간**  - 새 사용자의 경우 초기 SSO 요청이 처리되기 전에 약 10분 지연이 있습니다.
* **사용자 프로비저닝**  - 사용자는 Marketo에서 수동으로 프로비저닝합니다.
* **인증**  - 사용자 권한은 Marketo 내에서 유지됩니다.
* **OAuth 지원**  - Marketo은 현재 OAuth를 지원하지 않습니다.
* **자동 사용자 전달**  - &quot;Just in Time Provisioning&quot;이라고도 하며, 이는 사용자의 첫 번째 SAML 로그인이 액세스 중인 웹 응용 프로그램(예: Marketo)에서 사용자를 생성할 수 있고 수동 관리 작업이 필요하지 않은 경우입니다. 지금은 Marketo에서 지원하지 않습니다.
* **암호화**  - Marketo은 현재 암호화를 지원하지 않습니다.

>[!NOTE]
>
>시작하기 전에 ID 공급자 인증서를 X.509 형식으로 .crt, .der 또는 .cer 확장명으로 만듭니다.

## SAML 설정 업데이트 {#update-saml-settings}

SSO는 기본적으로 비활성화되어 있습니다. SAML을 활성화하고 구성하려면 다음 단계를 따르십시오.

1. **관리**&#x200B;로 이동하고 **단일 사인온**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-14-3a36-3a50.png)

   >[!NOTE]
   >
   >**관리**&#x200B;에 **단일 사인온**&#x200B;이 표시되지 않으면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

1. **SAML 설정** 섹션에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-14-3a37-3a3.png)

1. **SAML 단일 사인온**&#x200B;을 **활성화됨**&#x200B;으로 변경합니다.

   ![](assets/image2014-9-24-14-3a37-3a17.png)

1. **발급자 ID**, **개체 ID**&#x200B;를 입력하고 **사용자 ID 위치**&#x200B;를 선택한 다음 **찾아보기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-14-3a37-3a32.png)

1. **ID 공급자 인증서** 파일을 선택합니다.

   ![](assets/image2014-9-24-14-3a38-3a8.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-14-3a38-3a22.png)

## 리디렉션 페이지 설정 업데이트 {#update-redirect-page-settings}

1. **리디렉션 페이지** 섹션에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >SSO와 함께 유니버설 ID를 사용하는 고객은 **로그인 URL** 필드에 ID 공급자의 로그인 URL을 입력해야 합니다.

1. **로그아웃 URL**&#x200B;을 입력합니다. Marketo에서 로그아웃할 때 사용자에게 안내할 URL입니다.

   ![](assets/eight.png)

1. **오류 URL**&#x200B;을 입력합니다. Marketo에 로그인하지 못할 경우에 사용자에게 안내할 URL입니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >이 두 페이지는 모두 공개적으로 사용할 수 있어야 합니다.

>[!MORELIKETHIS]
>
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md)
>* [사용자 로그인을 SSO로만 제한](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md)
>* [범용 ID로 2개의 인스턴스에 Marketo 사용자 초대](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122)


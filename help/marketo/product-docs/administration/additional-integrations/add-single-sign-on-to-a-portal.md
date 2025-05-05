---
unique-page-id: 2360356
description: 포털에 SSO(Single Sign-On) 추가 - Marketo 문서 - 제품 설명서
title: 포털에 SSO(Single Sign-On) 추가
exl-id: 72f96239-7252-4cbc-bbe1-84ac7ae7f92e
feature: Administration
source-git-commit: 573a40c7d2ee7329d82d209bfefc284497295239
workflow-type: tm+mt
source-wordcount: '606'
ht-degree: 0%

---

# 포털에 SSO(Single Sign-On) 추가 {#add-single-sign-on-to-a-portal}

사용자를 인증하는 디렉터리 서비스가 있는 경우 Marketo에 SSO(Single Sign-On)를 허용할 수 있습니다. [!DNL Security Assertion Markup Language] (SAML) 버전 2.0 이상을 사용하여 이 기능을 지원합니다.

Marketo은 SAML SP(서비스 공급자)로 작동하며 사용자를 인증하기 위해 외부 Id 제공업체(IdP)에 의존합니다.

SSO가 활성화되면 IdP는 사용자의 자격 증명을 확인할 수 있습니다. 사용자가 Marketo 소프트웨어를 사용하려는 경우 IdP가 서명된 SAML 메시지를 Marketo에 보내어 SP 역할을 합니다. 이 메시지는 사용자에게 Marketo 소프트웨어 사용 권한이 있음을 Marketo에 보증합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!IMPORTANT]
>
>Adobe ID에 온보딩된 구독에는 적용되지 않습니다. Adobe ID에 온보딩된 구독의 경우 단일 사인온이 Adobe Admin Console의 Adobe 조직 수준에서 설정됩니다. Adobe Admin Console은 현재 SP로 시작하는 경우에만 지원합니다. [자세히 알아보기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}.

>[!NOTE]
>
>[!DNL Microsoft Azure] 사용자이십니까? [통합 자습서](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/){target="_blank"}를 확인하십시오. 참고로, 그들의 자습서의 5c단계에 오타가 있습니다. 릴레이 상태를 `https://<munchkinid>.mktoweb.com`, **_not_** `https://<munchkinid>.marketo.com`(으)로 설정하십시오.

## 요청을 보내는 방법 {#how-to-send-the-request}

* SAML 응답인 SSO 요청을 `https://login.marketo.com/saml/assertion/<your-munchkin-id>`에게 보냅니다.
* SP 대상 URL로 사용됩니다. `http://saml.marketo.com/sp` 사용
* SPNameQualifier 특성을 사용하는 경우 Subject의 NameID 요소를 `http://saml.marketo.com/sp`(으)로 설정하십시오.
* 여러 Marketo 구독을 동일한 SSO 공급자에게 페더레이션하는 경우 `http://saml.marketo.com/sp/<munchkin_id>` 형식의 각 Marketo 하위 항목에 대해 고유한 SP URL을 사용할 수 있습니다

>[!NOTE]
>
>Marketo은 사용자가 먼저 IdP 로그인 페이지를 시작하고, 인증한 다음 내 Marketo으로 이동하는 ID 공급자가 시작한(IdP 시작이라고도 함)만 지원합니다. Marketo 구독이 Admin Console로 이동된 경우 Adobe Admin Console은 현재 서비스 공급업체에서 시작한 서비스(SP에서 시작한 서비스)만 지원합니다. SSO 환경이 변경될 수 있습니다.

## 추가 참고 사항 {#additional-notes}

* **동기화 시간** - 새 사용자의 경우 초기 SSO 요청이 처리되기까지 약 10분이 지연됩니다.
* **사용자 프로비전** - 사용자는 Marketo에서 수동으로 프로비전됩니다.
* **인증** - 사용자 권한은 Marketo 내에서 유지 관리됩니다.
* **OAuth 지원** - Marketo은 현재 OAuth를 지원하지 않습니다.
* **자동 사용자 전파** - &quot;Just in Time Provisioning&quot;이라고도 하며, 사용자의 첫 SAML 로그인이 액세스 중인 웹 응용 프로그램(예: Marketo)에서 사용자를 만들 수 있고 수동 관리 작업이 필요하지 않은 경우입니다. 현재 Marketo에서는 지원되지 않습니다.
* **암호화** - Marketo은 현재 암호화를 지원하지 않습니다.

>[!NOTE]
>
>시작하기 전에 X.509 형식과 .crt, .der 또는 .cer 확장명의 ID 공급자 인증서를 가지고 있어야 합니다.

## SAML 설정 업데이트 {#update-saml-settings}

SSO는 기본적으로 비활성화되어 있습니다. 다음 단계에 따라 SAML을 활성화하고 구성합니다.

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/add-single-sign-on-to-a-portal-1.png)

1. **[!UICONTROL Single Sign-On]**&#x200B;을 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-2.png)

   >[!NOTE]
   >
   >**[!UICONTROL 관리자]**&#x200B;의 **[!UICONTROL Single Sign-On]**&#x200B;이 표시되지 않으면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}에 문의하세요.

1. **[!UICONTROL SAML 설정]** 섹션에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-3.png)

1. **[!UICONTROL SAML Single Sign-On]**&#x200B;을(를) **[!UICONTROL 사용]**(으)로 변경합니다.

   ![](assets/add-single-sign-on-to-a-portal-4.png)

1. **[!UICONTROL 발급자 ID]**, **[!UICONTROL 엔티티 ID]**&#x200B;를 입력하고 **[!UICONTROL 사용자 ID 위치]**&#x200B;를 선택한 다음 **[!UICONTROL 찾아보기]**&#x200B;를 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-5.png)

1. **[!UICONTROL ID 공급자 인증서]** 파일을 선택하십시오.

   ![](assets/add-single-sign-on-to-a-portal-6.png)

1. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-7.png)

## 리디렉션 페이지 설정 업데이트 {#update-redirect-page-settings}

1. **[!UICONTROL 페이지 리디렉션]** 섹션 아래에서 **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-8.png)

   >[!NOTE]
   >
   >SSO와 함께 범용 ID를 사용하는 고객은 **[!UICONTROL 로그인 URL]** 필드에 ID 공급자의 로그인 URL을 입력해야 합니다.

1. **[!UICONTROL 로그아웃 URL]**&#x200B;을(를) 입력하십시오. Marketo에서 로그아웃할 때 사용자에게 표시할 URL입니다.

   ![](assets/add-single-sign-on-to-a-portal-9.png)

1. **[!UICONTROL 오류 URL]**&#x200B;을(를) 입력하십시오. Marketo 로그인에 실패할 경우 사용자에게 표시하려는 URL입니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/add-single-sign-on-to-a-portal-10.png)

   >[!NOTE]
   >
   >이 두 페이지는 모두 공개적으로 사용할 수 있어야 합니다.

>[!MORELIKETHIS]
>
>* [구독 로그인에 범용 ID 사용](/help/marketo/product-docs/administration/settings/using-a-universal-id-for-subscription-login.md){target="_blank"}
>* [SSO로만 사용자 로그인 제한](/help/marketo/product-docs/administration/additional-integrations/restrict-user-login-to-sso-only.md){target="_blank"}
>* [Marketo 사용자를 유니버설 ID를 가진 두 개의 인스턴스에 초대](https://nation.marketo.com/t5/Knowledgebase/Inviting-Marketo-Users-to-Two-Instances-with-Universal-ID-UID/ta-p/251122){target="_blank"}

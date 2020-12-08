---
unique-page-id: 2360356
description: 포털에 단일 사인온 추가 - Marketing To Docs - 제품 설명서
title: 포털에 단일 사인온 추가
translation-type: tm+mt
source-git-commit: c33b7ab59e612f37d3f64bb954579700dc574068
workflow-type: tm+mt
source-wordcount: '453'
ht-degree: 0%

---


# 포털에 단일 사인온 추가 {#add-single-sign-on-to-a-portal}

사용자를 인증하는 디렉토리 서비스가 있는 경우 Marketing To에 SSO(Single Sign-On)를 허용할 수 있습니다. SAML(Security Assertion Markup Language) 버전 2.0 이상을 사용하여 이 기능을 지원합니다.

Marketing to는 SP(SAML 서비스 공급자)로 작동하고 사용자를 인증하기 위해 외부 ID 공급자(IdP)에 따라 달라집니다.

SSO가 활성화되면 IdP는 사용자의 자격 증명을 확인할 수 있습니다. 사용자가 Marketing To 소프트웨어를 사용하려는 경우 IdP는 SP의 역할을 하는 서명된 SAML 메시지를 Marketing To에 보냅니다. 이 메시지는 사용자가 Marketing To 소프트웨어를 사용할 수 있도록 허가되었음을 Marketing에 보증합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>Microsoft Azure 사용자입니까? 통합 자습서를 [확인하십시오](https://azure.microsoft.com/en-us/documentation/articles/active-directory-saas-marketo-tutorial/).

## 요청 전송 방법 {#how-to-send-the-request}

* SAML 응답인 SSO 요청을 전송 `https://login.marketo.com/saml/assertion/<your-munchkin-id>`
* SP의 대상 URL입니다. http://saml.marketo.com/sp [사용](http://saml.marketo.com/sp)
* SPNameQualifier 특성을 사용하는 경우 http://saml.marketo.com/sp의 제목에 대한 NameID 요소를 [설정합니다](http://saml.marketo.com/sp)
* 동일한 SSO 공급자에 대해 여러 Marketing To 구독을 페더레이션하는 경우 각 Marketing Suite에 대해 고유한 SP url을 사용할 수 있습니다 `http://saml.marketo.com/sp/<munchkin_id>`

>[!NOTE]
>
>Marketing은 사용자가 처음으로 Idp 로그인 페이지를 실행하고 인증을 받은 다음 내 마켓터로 이동하는 ID 제공자가 시작한(IdP가 시작이라고도 함)만 지원합니다.

## 추가 참고 사항 {#additional-notes}

* **동기화 시간** - 새 사용자의 경우 초기 SSO 요청이 처리되기 전에 약 10분 지연이 있습니다.
* **사용자 프로비저닝** - 사용자는 Marketing Cloud에 의해 수동으로 프로비저닝됩니다.
* **인증** - 사용자 권한은 Marketing To 내에서 유지됩니다.
* **OAuth 지원** - Marketing to는 현재 OAuth를 지원하지 않습니다.

>[!NOTE]
>
>시작하기 전에 ID 공급자 인증서를 X.509 형식 및 .crt, .der 또는 .cer 확장명으로 보관하십시오.

## SAML 설정 업데이트 {#update-saml-settings}

기본적으로 SSO가 비활성화됩니다. 다음 단계에 따라 SAML을 활성화하고 구성합니다.

1. **Admin **으로 이동하고 **단일 사인온을 클릭합니다**.

   ![](assets/image2014-9-24-14-3a36-3a50.png)

   >[!NOTE]
   >
   >관리 아래에 **단일 사인온이** 표시되지 않는 경우 **에**&#x200B;문의하십시오 [`[email protected]`](http://mailto:support@marketo.com).

1. SAML **설정** 섹션에서 편집을 **클릭합니다**.

   ![](assets/image2014-9-24-14-3a37-3a3.png)

1. SAML **Single Sign-On** 을 사용하도록 **변경합니다**.

   ![](assets/image2014-9-24-14-3a37-3a17.png)

1. 발급자 **ID**, **엔티티 ID**&#x200B;를 입력하고 **사용자 ID 위치**&#x200B;를 선택한 다음 찾아보기를 ****&#x200B;클릭합니다.

   ![](assets/image2014-9-24-14-3a37-3a32.png)

1. ID **공급자 인증서** 파일을 선택합니다.

   ![](assets/image2014-9-24-14-3a38-3a8.png)

1. 저장을 **클릭합니다**.

   ![](assets/image2014-9-24-14-3a38-3a22.png)

## 리디렉션 페이지 설정 업데이트 {#update-redirect-page-settings}

1. 리디렉션 페이지 **섹션** 아래에서 **편집을 클릭합니다**.

   ![](assets/seven.png)

   >[!NOTE]
   >
   >SSO와 함께 유니버설 ID를 사용하는 고객은 **로그인 URL** 필드에 ID 공급자의 로그인 URL을 입력해야 합니다.

1. 로그아웃 **URL을 입력합니다**. 사용자가 Marketing To에서 로그아웃할 때 안내할 URL입니다.

   ![](assets/eight.png)

1. 오류 **URL을 입력합니다**. Marketing To에 로그인하지 못할 경우에 사용자에게 안내할 URL입니다. 저장을 **클릭합니다**.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >이 두 페이지는 공개적으로 사용 가능해야 합니다.


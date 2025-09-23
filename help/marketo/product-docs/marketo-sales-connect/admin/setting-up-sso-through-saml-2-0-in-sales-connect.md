---
unique-page-id: 14352405
description: ' [!DNL Sales Connect] - Marketo 문서 - 제품 설명서에서 SAML 2.0을 통해 SSO 설정'
title: ' [!DNL Sales Connect]에서 SAML 2.0을 통해 SSO 설정'
exl-id: aab80626-d6d1-4194-9733-09c90c0b49a6
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '252'
ht-degree: 0%

---

# [!DNL Sales Connect]에서 SAML 2.0을 통해 SSO 설정 {#setting-up-sso-through-saml-in-sales-connect}

SAML 2.0 사양을 통해 SSO를 지원합니다. 그러나 현재 어떤 공급자와도 직접 통합이 되어 있지 않습니다. 이 설정을 사용하려면 SSO 공급자로부터 일부 정보를 수집해야 합니다.

>[!NOTE]
>
>**Marketo Sales Connect** 사용자만 적용할 수 있습니다. Sales Connect가 없지만 자세히 알아보려면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

## 요구 사항 {#requirements}

* SSO 계정
* Marketo Sales Connect 구독
* SSO 계정의 Metadata.xml(문제 URL, 유효성 검사 끝점 및 공개 키)

## 설정 {#setup}

팀의 SSO 인스턴스에서 가져온 metadata.xml에는 발급자 URL, 유효성 검사를 위한 끝점 및 공개 키가 포함되어야 합니다.

또한 고유한 도메인이 되려면 귀사의 SSO 계정에 대한 SSO 위치가 필요합니다. 예를 들어 `toutapp.pingidentity.com` 또는 이와 유사한 고유한 하위 도메인이 필요합니다. 이 유형의 고유 식별자가 없으면 대시보드에서 SAML을 설정할 수 없습니다.

URL을 할당할 때 하나의 로그인 및 Okta가 항상 고유 식별자를 제공하는 것은 아닙니다. Okta 또는 One Login을 사용하는 경우 대시보드 버튼에서 하나의 로그인을 설정할 수 없음을 의미합니다. [웹 응용 프로그램](https://toutapp.com/login)의 SSO(Single Sign-On) 단추에서도 설정할 수 있습니다.

해당 정보가 준비되면 엔지니어링 팀과 협력하여 귀하의 구독을 위해 이를 설정합니다.

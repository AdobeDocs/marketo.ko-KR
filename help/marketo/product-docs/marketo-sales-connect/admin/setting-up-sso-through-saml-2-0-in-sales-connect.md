---
unique-page-id: 14352405
description: Sales Connect - Marketing Docs - 제품 문서에서 SAML 2.0을 통해 SSO 설정
title: Sales Connect에서 SAML 2.0을 통해 SSO 설정
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---


# Sales Connect에서 SAML 2.0을 통해 SSO 설정 {#setting-up-sso-through-saml-in-sales-connect}

SAML 2.0 사양을 통해 SSO를 지원합니다. 그러나 현재 어떤 공급자와의 직접 통합이 없습니다. 이 설정을 받으려면 SSO 공급자로부터 일부 정보를 수집해야 합니다.

>[!NOTE]
>
>**미리 알림**
>
>이는 Marketing **To Sales Connect 고객에게만** 적용됩니다. Sales Connect가 없지만 자세한 내용은 고객 성공 관리자에게 문의하십시오.

## 요구 사항 {#requirements}

* SSO 계정
* Marketing to Sales Connect 구독
* SSO 계정의 Metadata.xml(문제 URL, 유효성 검사 끝점 및 공개 키)

## 설정 {#setup}

팀의 SSO 인스턴스의 metadata.xml에는 발급자 URL, 유효성 검사 종단점 및 공개 키가 포함되어야 합니다.

회사의 SSO 계정이 고유한 도메인이 되려면 SSO 위치가 필요합니다. 예를 들어, Adobe는 &#39;toutapp.pingidentity.com&#39; 또는 이와 비슷한 것을 `require a unique subdomain` 좋아합니다. 이 유형의 고유 식별자가 없으면 대시보드에서 SAML을 설정할 수 없습니다.

URL을 할당할 때 하나의 로그인과 Okta가 항상 고유한 식별자를 제공하지는 않습니다. Okta 또는 One Login을 사용하는 경우 Adobe는 대시보드 단추에서 하나의 로그인을 설정할 수 없음을 의미합니다. 이제 [웹 애플리케이션의 단일 사인온 버튼을 통해 설정할 수 있습니다](http://toutapp.com/login).

해당 정보가 제공되면 엔지니어링 팀과 협력하여 구독을 위한 설정을 진행할 것입니다.

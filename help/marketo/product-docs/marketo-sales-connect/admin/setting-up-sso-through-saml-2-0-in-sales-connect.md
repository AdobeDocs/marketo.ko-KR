---
unique-page-id: 14352405
description: Sales Connect에서 SAML 2.0을 통해 SSO 설정 - Marketo 문서 - 제품 설명서
title: 판매 연결에서 SAML 2.0을 통해 SSO 설정
exl-id: aab80626-d6d1-4194-9733-09c90c0b49a6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '256'
ht-degree: 0%

---

# 판매 연결에서 SAML 2.0을 통해 SSO 설정 {#setting-up-sso-through-saml-in-sales-connect}

Adobe는 SAML 2.0 사양을 통해 SSO를 지원합니다. 그러나 현재는 어떤 공급자와의 직접 통합이 없습니다. 이 설정을 가져오려면 SSO 공급자로부터 정보를 수집해야 합니다.

>[!NOTE]
>
>다음에만 적용할 수 있습니다 **Marketo Sales Connect** 고객. Sales Connect가 없지만 자세한 내용을 알아보려면 고객 성공 관리자에게 문의하십시오.

## 요구 사항 {#requirements}

* SSO 계정
* Marketo Sales Connect 구독
* SSO 계정의 Metadata.xml(문제 URL, 유효성 검사 끝점 및 공개 키)

## 설정 {#setup}

팀의 SSO 인스턴스에서 가져온 metadata.xml에는 발급자 URL, 유효성 검사의 종단점 및 공개 키가 포함되어야 합니다.

또한 회사의 SSO 계정이 고유한 도메인이 되려면 SSO 위치가 필요합니다. 예를 들어 다음과 같은 고유한 하위 도메인이 필요합니다 `toutapp.pingidentity.com` 또는 과 비슷합니다. 이 유형의 고유 식별자가 없으면 대시보드에서 SAML을 설정할 수 없습니다.

URL을 할당할 때 하나의 로그인 및 Okta가 항상 고유 식별자를 제공하지는 않습니다. Okta 또는 One Login을 사용하는 경우 대시보드 단추에서 한 개의 로그인을 설정할 수 없음을 의미합니다. Adobe에서는 여전히 [웹 애플리케이션](https://toutapp.com/login).

그 정보가 있으면 저희 엔지니어링 팀과 협력하여 구독에 맞게 설정할 것입니다.

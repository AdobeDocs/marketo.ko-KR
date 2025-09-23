---
description: Salesforce - Marketo 문서 - 제품 설명서에 연결할 때 "요청을 인증할 수 없습니다"를 해결하려면 어떻게 합니까?
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다"를 해결하려면 어떻게 합니까
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
feature: Sales Insight Actions
source-git-commit: 65d607e279fb86b0816ccaec2f4bf3c69e309cb9
workflow-type: tm+mt
source-wordcount: '349'
ht-degree: 0%

---

# [!DNL Salesforce]에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;를 해결하려면 어떻게 합니까? {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Marketo Sales 인스턴스를 Salesforce에 연결하려고 하는데 &quot;요청을 인증할 수 없습니다.&quot; 오류가 표시되면 Salesforce 인스턴스가 구성된 방식과 관련된 것일 수 있습니다.

이 실패한 인증 페이지를 생성하는 데에는 두 가지 유형의 오류가 있습니다.

* 로그인 오류 제한된 도메인
* Oauth 앱 차단됨

URL을 확인하여 어떤 유형을 가져오는지 식별할 수 있습니다.

![](assets/how-do-i-fix-we-were-unable-to-authenticate-1.png)

![](assets/how-do-i-fix-we-were-unable-to-authenticate-2.png)

## 로그인 오류 해결 제한된 도메인 {#resolve-login-error-restricted-domain}

이 오류는 일반적으로 라우팅할 수 없는 사용자 정의 도메인이 있음을 나타냅니다. 이 오류를 해결하려면 먼저 연결하려는 Salesforce 인스턴스에 로그인하십시오. 그런 다음 단계를 수행하여 Salesforce에 연결합니다.

연결하려는 인스턴스가 Salesforce Sandbox 도메인이고 오류가 발생하는 경우 추가 단계를 수행하여 Salesforce Sandbox와 호환되도록 인스턴스를 업데이트해야 합니다. [자세히 알아보기](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/set-up-a-sales-insight-actions-sandbox.md){target="_blank"}

## Oauth 앱 차단 확인 {#resolve-oauth-app-blocked}

URL에 Oauth 앱 차단 오류 유형(또는 다른 유형)이 있는 오류 메시지 &quot;요청을 인증할 수 없습니다&quot;가 표시되면 Salesforce의 API에 대한 액세스가 제한될 수 있습니다. Salesforce 관리자에게 문의하여 아래 내용이 올바른지 확인하십시오.

### 사용자 권한에서 API 활성화 {#enable-api-in-user-permissions}

1. Salesforce 관리자가 Salesforce에 로그인하도록 합니다.
1. **설치**&#x200B;를 선택하십시오.
1. **사용자 관리**&#x200B;를 선택합니다.
1. **프로필**&#x200B;을 선택하세요.
1. ToutApp 사용자가 속한 프로필을 찾은 다음 **편집**&#x200B;을 클릭합니다.
1. **관리 권한**(으)로 스크롤하여 **API 사용**&#x200B;을(를) 확인합니다.

### Salesforce이 판매 Insight 작업의 연결을 차단하는지 확인 {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Salesforce 관리자가 Salesforce에 로그인하도록 합니다.
1. **설치**&#x200B;를 선택하십시오.
1. **앱 관리**&#x200B;를 선택합니다.
1. **연결된 앱 OAuth 사용**&#x200B;을 선택합니다.
1. Sales Insight Actions 옆에 &quot;Block&quot;이 표시되어 있는지 확인합니다. &quot;차단 해제&quot;가 표시되면 버튼을 클릭하여 Salesforce에 대한 Sales Insight 작업의 액세스 차단을 해제합니다.

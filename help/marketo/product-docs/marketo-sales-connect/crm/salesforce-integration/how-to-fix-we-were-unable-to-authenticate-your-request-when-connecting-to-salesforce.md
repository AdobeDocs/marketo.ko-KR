---
unique-page-id: 14352484
description: Salesforce - Marketo 문서 - 제품 설명서에 연결할 때 "요청을 인증할 수 없습니다."를 해결하는 방법
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다"를 해결하는 방법
exl-id: ddd49064-f584-4490-8d45-29cf61ed3ebe
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---

# Salesforce에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;를 해결하는 방법 {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Salesforce에 Sales Connect를 연결하려고 할 때 &quot;요청을 인증할 수 없습니다&quot;라는 오류 메시지가 표시되면 Salesforce의 API에 대한 액세스가 제한될 수 있습니다. Salesforce 관리자에게 문의하여 다음 항목이 올바른지 확인하십시오.

## 사용자 권한에서 API 활성화 {#enable-api-in-user-permissions}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. **설치**&#x200B;를 선택하십시오.
1. **사용자 관리**&#x200B;를 선택합니다.
1. **프로필**&#x200B;을 선택하세요.
1. ToutApp 사용자가 속한 프로필을 찾은 다음 **편집**&#x200B;을 클릭합니다.
1. **관리 권한**(으)로 스크롤하여 **API 사용**&#x200B;을(를) 확인합니다.

## Salesforce가 Sales Connect의 연결을 차단하는지 확인 {#check-if-salesforce-is-blocking-sales-connect-from-connecting}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. **설치**&#x200B;를 선택하십시오.
1. **앱 관리**&#x200B;를 선택합니다.
1. **연결된 앱 OAuth 사용**&#x200B;을 선택합니다.
1. Sales Connect 옆에 &quot;Block&quot;이 표시되어 있는지 확인합니다. &quot;차단 해제&quot;가 표시되면 버튼을 클릭하여 Salesforce에 대한 Sales Connect의 액세스 차단을 해제합니다.

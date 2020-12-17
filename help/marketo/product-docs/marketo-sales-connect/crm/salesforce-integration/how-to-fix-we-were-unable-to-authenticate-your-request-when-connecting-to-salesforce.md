---
unique-page-id: 14352484
description: Salesforce - Marketing To Docs - 제품 문서에 연결할 때 "요청을 인증할 수 없습니다"를 수정하는 방법
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다"를 수정하는 방법
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# Salesforce {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;를 수정하는 방법

Sales Connect를 Salesforce에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;라는 오류 메시지가 표시되면 Salesforce API에 대한 액세스가 제한될 수 있습니다. Salesforce 관리자에게 문의하여 다음 사항이 제대로 작동하는지 확인하십시오.

## 사용자 권한 {#enable-api-in-user-permissions}에서 API 활성화

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. **설정**&#x200B;을 선택합니다.
1. **사용자 관리**&#x200B;를 선택합니다.
1. **프로필**&#x200B;을 선택합니다.
1. ToutApp 사용자가 속한 프로필을 찾아 **편집**&#x200B;을 클릭합니다.
1. **관리 권한**&#x200B;으로 스크롤하고 **API 사용**&#x200B;이 선택되어 있는지 확인합니다.

## Salesforce가 {#check-if-salesforce-is-blocking-sales-connect-from-connecting} 연결을 차단하는지 확인

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. **설정**&#x200B;을 선택합니다.
1. **앱 관리**&#x200B;를 선택합니다.
1. **연결된 앱 OAuth 사용**&#x200B;을 선택합니다.
1. Sales Connect에 그 옆에 &quot;블록&quot;이 표시되는지 확인합니다. &quot;차단 해제&quot;가 표시되는 경우 단추를 클릭하여 Salesforce에 대한 Sales Connect의 액세스 차단 해제를 해제합니다.


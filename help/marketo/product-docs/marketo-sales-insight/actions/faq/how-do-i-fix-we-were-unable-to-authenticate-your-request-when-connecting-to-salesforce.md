---
description: Salesforce - Marketo 문서 - 제품 설명서에 연결할 때 "요청을 인증할 수 없습니다"를 수정하려면 어떻게 합니까?
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다"를 수정하려면 어떻게 합니까?
hide: true
hidefromtoc: true
source-git-commit: c398aff77e09f4a63db5d51af55178aa663ec98e
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---

# Salesforce에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;를 수정하려면 어떻게 합니까? {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Salesforce에 Sales Insight Actions를 연결하려고 할 때 &quot;요청을 인증할 수 없습니다.&quot;라는 오류 메시지가 표시되면 Salesforce API에 대한 액세스가 제한될 수 있습니다. Salesforce 관리자에게 문의하여 다음 항목이 있는지 확인하십시오.

## 사용자 권한에서 API 활성화 {#enable-api-in-user-permissions}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. 선택 **설정**.
1. 선택 **사용자 관리**.
1. 선택 **프로필**.
1. ToutApp 사용자가 속한 프로필을 찾아 을 클릭합니다. **편집**.
1. 아래로 스크롤하여 **관리 권한** 그리고 **API 활성화** 이(가) 선택되어 있습니다.

## Salesforce가 Sales Insight Actions의 연결을 차단하는지 확인합니다. {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. 선택 **설정**.
1. 선택 **앱 관리**.
1. 선택 **연결된 앱 OAuth 사용**.
1. Sales Insight Actions 옆에 &quot;블록&quot;이 표시되는지 확인합니다. &quot;차단 해제&quot;가 표시되면 버튼을 클릭하여 Salesforce에 대한 Sales Insight Actions의 액세스를 차단 해제합니다.

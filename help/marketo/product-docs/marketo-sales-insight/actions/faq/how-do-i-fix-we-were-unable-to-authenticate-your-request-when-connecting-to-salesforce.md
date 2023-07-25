---
description: Salesforce - Marketo 문서 - 제품 설명서에 연결할 때 "요청을 인증할 수 없습니다."를 해결하려면 어떻게 합니까?
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다."를 해결하려면 어떻게 합니까?
exl-id: ef876f0f-bd76-4ba5-bf48-885ee048ceae
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '193'
ht-degree: 0%

---

# Salesforce에 연결할 때 &quot;요청을 인증할 수 없습니다.&quot;를 해결하려면 어떻게 합니까? {#how-do-i-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

Sales Insight Actions 을 Salesforce에 연결하려고 할 때 &quot;요청을 인증할 수 없습니다.&quot;라는 오류 메시지가 표시되는 경우 Salesforce의 API에 대한 액세스가 제한될 수 있습니다. Salesforce 관리자에게 문의하여 다음 항목이 올바른지 확인하십시오.

## 사용자 권한에서 API 활성화 {#enable-api-in-user-permissions}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. 선택 **설정**.
1. 선택 **사용자 관리**.
1. 선택 **프로필**.
1. ToutApp 사용자가 속한 프로필을 찾아 **편집**.
1. 아래로 스크롤하여 **관리 권한** 그리고 확실히 **API 활성화됨** 이(가) 선택되었습니다.

## Salesforce가 Sales Insight 작업의 연결을 차단하는지 확인 {#check-if-salesforce-is-blocking-sales-insight-actions-from-connecting}

1. Salesforce 관리자가 SFDC에 로그인하도록 합니다.
1. 선택 **설정**.
1. 선택 **앱 관리**.
1. 선택 **연결된 앱 OAuth 사용**.
1. Sales Insight Actions 옆에 &quot;Block&quot;이 표시되어 있는지 확인합니다. &quot;차단 해제&quot;가 표시되면 버튼을 클릭하여 Salesforce에 대한 Sales Insight Actions의 액세스 차단을 해제합니다.

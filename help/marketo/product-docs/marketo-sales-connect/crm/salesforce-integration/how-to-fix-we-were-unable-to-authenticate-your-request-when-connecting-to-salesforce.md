---
unique-page-id: 14352484
description: Salesforce - Marketo 문서 - 제품 설명서에 연결할 때 "요청을 인증할 수 없습니다"를 해결하는 방법
title: Salesforce에 연결할 때 "요청을 인증할 수 없습니다"를 해결하는 방법
exl-id: ddd49064-f584-4490-8d45-29cf61ed3ebe
feature: Marketo Sales Connect
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 3%

---

# [!DNL Salesforce]에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;를 해결하는 방법 {#how-to-fix-we-were-unable-to-authenticate-your-request-when-connecting-to-salesforce}

[!DNL Sales Connect]을(를) [!DNL Salesforce]에 연결할 때 &quot;요청을 인증할 수 없습니다&quot;라는 오류 메시지가 표시되면 [!DNL Salesforce]의 API에 대한 액세스가 제한될 수 있습니다. [!DNL Salesforce] 관리자에게 다음 항목이 제대로 있는지 확인하십시오.

## 사용자 권한에서 API 활성화 {#enable-api-in-user-permissions}

1. [!DNL Salesforce] 관리자가 SFDC에 로그인하도록 합니다.
1. **[!UICONTROL Setup]**&#x200B;를 선택합니다.
1. **[!UICONTROL Manage Users]**&#x200B;를 선택합니다.
1. **[!UICONTROL Profiles]**&#x200B;를 선택합니다.
1. ToutApp 사용자가 속한 프로필을 찾은 다음 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Administrative Permissions]**(으)로 스크롤하고 **[!UICONTROL API Enabled]**&#x200B;이(가) 선택되어 있는지 확인하십시오.

## [!DNL Salesforce]이(가) [!DNL Sales Connect]의 연결을 차단하는지 확인 {#check-if-salesforce-is-blocking-sales-connect-from-connecting}

1. [!DNL Salesforce] 관리자가 SFDC에 로그인하도록 합니다.
1. **[!UICONTROL Setup]**&#x200B;를 선택합니다.
1. **[!UICONTROL Manage Apps]**&#x200B;를 선택합니다.
1. **[!UICONTROL Connected Apps OAuth Usage]**&#x200B;를 선택합니다.
1. [!DNL Sales Connect] 옆에 &quot;[!UICONTROL Block]&quot;이(가) 있는지 확인하십시오. &quot;[!UICONTROL Unblock]&quot;이(가) 표시되면 단추를 클릭하여 [!DNL Sales Connect]에 대한 [!DNL Salesforce]의 액세스를 차단 해제하십시오.

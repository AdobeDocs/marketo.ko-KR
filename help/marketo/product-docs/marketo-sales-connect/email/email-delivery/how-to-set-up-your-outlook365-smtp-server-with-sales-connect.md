---
unique-page-id: 14352600
description: Sales Connect를 사용하여 Outlook365 SMTP 서버를 설정하는 방법 - Marketing Docs - 제품 설명서
title: Sales Connect를 사용하여 Outlook365 SMTP 서버를 설정하는 방법
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '252'
ht-degree: 0%

---


# Sales Connect를 사용하여 Outlook365 SMTP 서버를 설정하는 방법 {#how-to-set-up-your-outlook-smtp-server-with-sales-connect}

>[!NOTE]
>
>조직에서 Outlook을 사용하고 Marketing To Sales Connect를 사용하여 이메일 배달 채널을 설정하려는 경우 이메일 연결 기능을 [사용하여 Exchange 서버에 연결하는 것이 좋습니다](http://docs.marketo.com/x/Z4AOAQ).

사용자 지정 [SMTP](http://docs.marketo.com/x/zYTS) 서버를 대체 배달 채널로 설정하려면 OutApp은 보안을 위해 일부 인증 양식을 활용해야 합니다. SMTP 구성 페이지에 모든 SMTP 서버를 설정할 수 [있습니다](http://toutapp.com/next#settings/email-servers/smtp/configure). Office365 SMTP 서버를 설정하려면 다음 구성을 권장합니다.\
**SMTP 서버**:smtp.office365.com\
**서버 포트**:포트 587 - 보안\
**인증 방법**:로그인(SSL/TLS)\
**사용자 이름 또는 로그인**:Office365 이메일 주소\
**암호**:Office365 이메일 암호\
**도메인**:회사 도메인

SMTP 서버를 설정하는 데 문제가 있는 경우 Exchange 관리자와 파트너 관계를 맺고 올바른 자격 증명을 사용하고 있는지 확인합니다.

>[!NOTE]
>
>Office365 SMTP를 통해 전송할 때 Microsoft는 하루에 받는 사람 `limit of 30 messages sent per minute`과 받는 사람 수를 10,000명으로 제한하고 있습니다. 또한 Office365 SMTP 서버를 통해 이메일을 보내려는 팀 `each member` 의 경우 Sales Connect 설정에서 해당 이메일 주소와 암호를 사용하여 이 설정을 설정해야 합니다. Microsoft의 Office365 계정 정책에 따라 이 구성에 `Make this deliverability channel to all my team members` 대한 설정 `" will not work` 에 대한 상자를 선택합니다.


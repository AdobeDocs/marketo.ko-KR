---
unique-page-id: 14352581
description: 제한 오류 - 마케팅 문서 - 제품 설명서
title: 제한 오류
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '163'
ht-degree: 0%

---


# 제한 오류 {#throttling-errors}

## 파일 제한 도달 {#file-limit-reached}

자신의 서버를 통해 전송하는 경우 동시에 보낼 수 있는 이메일 수에 제한이 있습니다. Sales Connect를 통해 보낼 때 많은 이메일을 보낼 수 있지만 동시에 모든 이메일을 보내려고 합니다. 따라서 서버가 분당 100개의 이메일을 전송하는 것을 알고 있는 경우 [웹 응용 프로그램](http://toutapp.com/login)을 통해 최대 100개의 이메일만 전송하면 됩니다. 그렇지 않으면 서버에서 제한된 이메일이 있으므로 이메일이 여기에 도착할 수 있습니다.

## 인증 오류 {#authentication-error}

이는 SMTP 서버에 대한 연결을 인증할 수 없음을 의미합니다. 대부분의 경우 최근에 암호가 변경되었으며 새로운 자격 증명을 인증해야 합니다.

이렇게 하려면 [SMTP 설정](http://docs.marketo.com/display/docs/assets/external-link-1.jspa) `where you should see the same error message. Update your credentials and hit **Authenticate and Save** to see a confirmation message.`으로 이동합니다.

실패한 배달로 이동하여 해당 이메일을 다시 전송합니다.

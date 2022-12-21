---
unique-page-id: 14352482
description: 회신 추적 작동 방식 - Marketo 문서 - 제품 설명서
title: 회신 추적 작동 방식
exl-id: 8d087014-99b7-47ba-9f08-95b13bc16438
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '180'
ht-degree: 0%

---

# 회신 추적 작동 방식 {#how-reply-tracking-works}

회신 추적은 보내는 모든 이메일에 있는 메시지 ID를 확인함으로써 수행됩니다. 모든 이메일에는 가장 좋은 회신 추적을 수행할 수 있는 고유한 메시지 ID가 포함되어 있습니다.

>[!PREREQUISITES]
>
>**전자 메일 서버와의 연결:** Sales Connect는 받은 편지함과 연결되어 있어야 새 회신이 언제 도착했는지 알 수 있습니다. Sales Connect 계정이 필요합니다 [Gmail에 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md). Outlook을 사용하는 경우 [exchange 서버](https://toutapp.com/next#settings/exchange_settings).

Sales Connect에서 잠재 고객의 전자 메일에 대한 응답을 추적할 수 없는 경우 회신 감지 또는 Salesforce에 회신하는 로그를 기준으로 캠페인을 중지할 수 없습니다.  이메일 주소가 회신할 수 있다는 것은 무엇입니까?

즉, flynn@flynnsarcade.com으로 이메일을 보내고 kevinf@flynnsarcade.com으로 응답하는 경우 응답을 추적할 수 있습니다. 또한 flynn@flynnsarcade.com 및 CC alan@encom.com으로 이메일을 보내고 Alan이 다시 편지를 보내는 경우 답장도 감지하여 캠페인을 종료합니다.

---
unique-page-id: 14352482
description: 회신 추적 작동 방식 - 마케팅 문서 - 제품 설명서
title: 회신 추적 작동 방식
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---


# 회신 추적 작동 방식 {#how-reply-tracking-works}

회신 추적은 보내는 모든 이메일에 있는 메시지 ID를 확인하여 수행됩니다. 모든 이메일에는 최고의 답글 추적을 할 수 있도록 해주는 고유한 메시지 ID가 포함되어 있습니다.

>[!PREREQUISITES]
>
>**이메일 서버와의 연결:** Sales Connect가 받은 편지함과 연결되어 있어야 새 회신이 언제 도착했는지 알 수 있습니다. Sales Connect 계정 [이 Gmail](http://docs.marketo.com/x/kYMOAQ)에 연결되어 있어야 합니다. Outlook을 사용하는 경우 [exchange 서버](http://toutapp.com/next#settings/exchange_settings)와 통합해야 합니다.

Sales Connect가 이메일에 대한 잠재 고객의 응답을 추적할 수 없는 경우 응답 감지 또는 Salesforce에 회신하는 로그 기록을 기반으로 캠페인을 중지할 수 없습니다.  어떤 이메일 주소가 회신할 수 있습니까?

즉, [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#783217162b16170f3830170d0b1d2b0c190a13561b1715)을(를) 이메일로 보내고 [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#c08aafae93aeafb78094a8a58ea9a7a8b4b397a1b4a3a8eea3afad)에 응답하면 응답을 추적할 수 있습니다. 또한 [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#450f2a2b162b2a32050d2a303620163124372e6b262a28) 및 CC [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#3e5f525f507e5b505d5153105d5153)로 이메일을 보내고 Alan이 다시 회신하는 경우 답글을 감지하고 캠페인을 종료합니다.

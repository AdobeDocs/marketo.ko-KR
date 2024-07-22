---
unique-page-id: 14352482
description: 답변 추적 작동 방식 - Marketo 문서 - 제품 설명서
title: 회신 추적 작동 방식
exl-id: 8d087014-99b7-47ba-9f08-95b13bc16438
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# 회신 추적 작동 방식 {#how-reply-tracking-works}

답글 추적은 보내는 모든 이메일에 포함된 메시지 ID를 확인하여 수행됩니다. 모든 이메일에는 최고의 답글 추적을 가질 수 있는 고유한 메시지 ID가 포함되어 있습니다.

>[!PREREQUISITES]
>
>**전자 메일 서버에 연결:** Sales Connect가 받은 편지함에 연결되어 있어야 새 회신이 언제 도착했는지 알 수 있습니다. Sales Connect 계정 [을(를) Gmail에 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)해야 합니다. Outlook을 사용하는 경우 [exchange server](https://toutapp.com/next#settings/exchange_settings)와 통합해야 합니다.

Sales Connect에서 잠재 고객의 이메일 회신을 추적할 수 없는 경우 회신 감지를 기반으로 캠페인을 중단하거나 Salesforce에 회신을 기록할 수 없습니다.  회신할 수 있는 이메일 주소는 무엇입니까?

즉, flynn@flynnsarcade.com으로 이메일을 보내고 kevinf@flynnsarcade.com으로 답장을 보내면 답장을 추적할 수 있습니다. 또한 flynn@flynnsarcade.com 및 CC alan@encom.com으로 이메일을 보내고 Alan이 회신을 보내면 회신도 감지하여 캠페인을 종료합니다.

---
unique-page-id: 14352407
description: 전달 채널 개요 - 마케팅 문서 - 제품 설명서
title: 전달 채널 개요
translation-type: tm+mt
source-git-commit: f3e3efc1cc480e9c6501b7e808f53c3a8bdc93d8
workflow-type: tm+mt
source-wordcount: '580'
ht-degree: 0%

---


# 배달 채널 개요 {#delivery-channel-overview}

Marketing To Sales Connect는 이메일을 전달할 수 있는 다양한 옵션을 제공합니다. 이 문서에서는 활용할 수 있는 전달 채널, 선택 방법 및 다른 채널을 선택할 시기를 검토합니다.

## 권장:이메일 연결을 통한 Gmail 또는 Exchange {#recommended-gmail-or-exchange-via-email-connection}

Sales Connect를 사용하면 이메일 연결 서비스를 통해 간소화된 설정과 향상된 제공 기능을 제공할 수 있습니다. 이메일 연결을 사용하면 각 사용자가 모든 Sales Connect 이메일에 대한 배달 채널로 사용할 [Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) 또는 [Exchange](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) 계정에 연결할 수 있습니다.

Gmail 또는 Exchange를 사용하면 다른 전달 채널 옵션에 비해 몇 가지 뚜렷한 이점을 얻을 수 있습니다.

* 이 채널은 택배로 이어질 수 있는 기존 명성을 자랑하는 검증된 전달 채널입니다.
* SPF 및 DKIM과 같은 인증 방법은 이미 IT 팀에서 구성하고 관리하므로 추가 설정이 없습니다.
* 지정된 이메일 네트워크 내에서 이메일을 보내는 경우(즉, Exchange를 통해 이메일을 받는 회사에 Exchange 사용자로 이메일을 보내는 경우) 더 많은 수신 능력을 높일 수 있습니다.

이러한 배달 채널에는 Microsoft 및 Google에 의해 적용되는 자체 전송 제한이 있습니다. 이러한 문제를 해결하기 위해 Adobe는 제한 메커니즘을 활용하여 사용자가 제한된 범위 내에서 작업을 계속할 수 있도록 지원합니다. [이메일 제한에 대한 자세한 내용을 보려면 ](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md) 여기를 클릭하십시오.

>[!NOTE]
>
>기본적으로 O365 플러그인은 항상 Exchange 배달 채널을 사용하며 Gmail 플러그인은 항상 Gmail 배달 채널을 사용하여 플러그인에서 이메일을 배달합니다.

**바운스 추적**:MSC는 보낸 사람의 받은 편지함으로 보내는 바운스 메시지를 감지하여 Exchange Online 또는 Gmail 사용자의 바운스를 감지할 수 있습니다. 이러한 바운스 알림은 사용자를 위한 템플릿 분석, 캠페인 분석 및 라이브 피드 알림에 롤업됩니다. Exchange On-Prem 고객은 바운스 추적을 지원하지 않습니다.

## SMTP {#custom-delivery-channel-via-smtp}을 통한 사용자 지정 배달 채널

Sales Connect는 영업 팀이 선호하는 배달 채널로 사용할 타사 SMTP 서버를 연결하는 추가 옵션을 제공합니다.

제3자 SMTP 공급자 활용은 이메일 볼륨이 제1의 우선 순위인 영업 팀에 가장 좋은 옵션입니다. Sendgrid 및 Sparkpost와 같은 SMTP 공급자는 대량 이메일 배달 요구에 맞게 최적화되며 대량의 이메일을 배포하려는 사용자의 요구 사항에 맞게 확장할 수 있습니다.

또한 제3자 SMTP 공급자는 고객의 팀 전달 요구 사항(예: 이메일 배달 보고서 및 전용 IP 주소)을 지원하는 다양한 기능을 제공하므로 판매 이메일 전달 채널을 자세히 제어하고 확인할 수 있는 옵션을 활용할 수 있습니다.

## MSC 서버(레거시) {#msc-servers-legacy}

MSC 서버는 일부 기존 ToutApp 고객에만 사용할 수 있습니다. 이러한 고객은 이메일 설정에서 사용할 수 있는 MSC 서버를 보게 됩니다. 이전 제품이 아닌 모든 고객은 MSC를 옵션으로 볼 수 없으며 Gmail 또는 Outlook 계정을 Sales Connect에 연결하여 배달 채널을 잠금 해제해야 합니다.

MSC 서버는 배달 가능성을 낮출 수 있는 DKIM 및 SPF 인증 방법을 지원하지 않습니다. 따라서 모든 고객은 Gmail 또는 Outlook에 연결하여 최상의 서비스를 제공하는 것이 좋습니다.

## 마케팅 서버 {#marketo-servers}

Marketing To 이메일 서버는 Sales Connect와 통합되지 않습니다. 마케팅 서버는 마케터의 요구 사항에 맞게 확장할 수 있도록 일괄 전달에 최적화되어 있습니다. 그러나 Gmail과 Exchange는 1:1 영업 커뮤니케이션의 성공률이 높으므로 이러한 서버를 판매 커뮤니케이션에 사용하는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [Gmail 사용자를 위한 이메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [사용자 지정 배달 채널 설정](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [이메일 연결 제한](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)


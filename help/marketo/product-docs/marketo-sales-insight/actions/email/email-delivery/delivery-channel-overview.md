---
description: 게재 채널 개요 - Marketo 문서 - 제품 설명서
title: 게재 채널 개요
hide: true
hidefromtoc: true
exl-id: 8dd6fe3e-86ae-4361-bc0a-6488dc1df9fa
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '668'
ht-degree: 0%

---

# 게재 채널 개요 {#delivery-channel-overview}

Marketo Sales는 이메일을 배달할 수 있는 다양한 옵션을 제공합니다. 이 문서에서는 활용할 수 있는 게재 채널, 이들을 선택하는 방법 및 서로를 선택할 시기를 검토합니다.

## 권장 사항: 이메일 연결을 통한 Gmail 또는 Exchange {#recommended-gmail-or-exchange-via-email-connection}

Marketo 영업에서는 이메일 연결 서비스를 통해 간소화된 설정과 향상된 게재 기능을 사용할 수 있습니다. 전자 메일 연결을 통해 각 사용자가 전자 메일 연결에 연결할 수 있습니다 [Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) 또는 [Exchange](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) 모든 Marketo 판매 이메일에 대해 선택할 수 있는 배달 채널로 사용할 Marketo Sales에 계정을 설정합니다.

Gmail 또는 Exchange를 사용하면 다른 게재 채널 옵션보다 몇 가지 뚜렷한 이점이 있습니다.

* 이 채널은 게재 능력을 높게 유지할 수 있는 정평이 있는 검증된 전달 채널입니다.
* SPF 및 DKIM과 같은 인증 방법은 이미 IT 팀이 구성 및 관리하므로 추가 설정이 없습니다.
* 주어진 이메일 네트워크 내에서 전자 메일을 보내는 것(즉, Exchange를 통해 전자 메일을 받는 회사에 Exchange 사용자로 전자 메일을 보내는 것)은 보다 많은 게재 능력을 높일 수 있습니다.

이러한 게재 채널에는 Microsoft 및 Google에 의해 적용되는 자체 전송 제한이 있습니다. 이러한 문제를 해결하기 위해 Adobe에서는 사용자가 이러한 제한 내에서 유지될 수 있도록 지원하는 조정 메커니즘을 활용합니다. 추가 정보 [여기서 이메일 제한](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md).

>[!NOTE]
>
>기본적으로 O365 플러그인은 항상 Exchange 게재 채널을 사용하며 Gmail 플러그인은 항상 Gmail 게재 채널을 사용하여 플러그인의 이메일을 배달합니다.

**바운스 추적**: Marketo Sales는 보낸 사람의 받은 편지함으로 전송되는 반송 메시지를 감지하여 Exchange Online 또는 Gmail 사용자의 반송 횟수를 감지할 수 있습니다. 이러한 바운스 알림은 사용자를 위한 템플릿 분석, 캠페인 분석 및 라이브 피드 알림으로 롤업됩니다. Exchange On-Prem 고객은 반송 추적을 지원하지 않습니다.

## SMTP를 통한 사용자 지정 배달 채널 {#custom-delivery-channel-via-smtp}

Marketo 판매에서는 영업 팀의 기본 제공 전달 채널로 사용할 타사 SMTP 서버를 연결하는 추가 옵션을 제공합니다.

타사 SMTP 공급자를 활용하는 것은 이메일 볼륨이 최우선 순위인 영업 팀에 가장 적합한 옵션입니다. Sendgrid 및 Sparkpost와 같은 SMTP 공급자는 대량 전자 메일 게재 요구 사항을 제공하도록 최적화되어 있으며 대량 전자 메일 배포를 원하는 고객의 요구 사항을 충족하도록 확장할 수 있습니다.

또한 타사 SMTP 공급자는 팀의 게재 요구 사항(예: 전자 메일 게재 보고서 및 전용 IP 주소)을 지원하는 데 도움이 되는 다양한 기능을 제공하므로 판매 전자 메일 게재 채널에 대한 보다 세부적인 제어 및 가시성을 원하는 사용자에게 적합합니다.

## Marketo 영업 서버(이전) {#marketo-sales-servers-legacy}

Marketo 영업 서버는 일부 기존 ToutApp 고객만 사용할 수 있습니다. 이러한 고객은 이메일 설정에서 사용할 수 있는 Marketo 판매 서버를 볼 수 있습니다. 기존 고객이 아닌 모든 고객은 Marketo Sales를 옵션으로 볼 수 없으며 Gmail 또는 Outlook 계정을 Marketo Sales에 연결하여 게재 채널을 잠금 해제해야 합니다.

Marketo 영업 서버는 DKIM 및 SPF 인증 방법을 지원하지 않으므로, 게재 가능성을 낮출 수 있습니다. 이러한 이유로 모든 고객은 최상의 게재 능력을 위해 Gmail 또는 Outlook에 연결하는 것이 좋습니다.

## MSC 서버(이전) {#msc-servers-legacy}

MSC 서버는 일부 기존 ToutApp 고객에게만 제공됩니다. 이러한 고객은 전자 메일 설정에서 사용할 수 있는 MSC 서버를 볼 수 있습니다. 기존 고객이 아닌 모든 고객은 MSC를 옵션으로 볼 수 없으며 Gmail 또는 Outlook 계정을 Sales Connect에 연결하여 배달 채널의 잠금을 해제해야 합니다.

MSC 서버는 DKIM 및 SPF 인증 방법을 지원하지 않으므로 게재 가능성을 낮출 수 있습니다. 이러한 이유로 모든 고객은 최상의 게재 능력을 위해 Gmail 또는 Outlook에 연결하는 것이 좋습니다.

## Marketo 서버 {#marketo-servers}

Marketo 이메일 서버는 Marketo Sales와 통합되지 않습니다. Marketo 서버는 마케터의 요구 사항에 맞게 확장할 수 있도록 벌크 전달에 최적화되어 있습니다. 그러나 Gmail 및 Exchange 는 1:1 영업 커뮤니케이션의 성공률이 높으므로 영업 커뮤니케이션에 이러한 서버를 사용하는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [Gmail 사용자를 위한 이메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [사용자 지정 게재 채널 설정](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [전자 메일 연결 조절](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)


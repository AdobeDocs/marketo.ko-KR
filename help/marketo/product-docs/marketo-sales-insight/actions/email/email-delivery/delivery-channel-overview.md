---
description: 게재 채널 개요 - Marketo 문서 - 제품 설명서
title: 게재 채널 개요
exl-id: 8dd6fe3e-86ae-4361-bc0a-6488dc1df9fa
feature: Sales Insight Actions
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '660'
ht-degree: 0%

---

# 게재 채널 개요 {#delivery-channel-overview}

Marketo Sales는 이메일을 게재할 수 있는 다양한 옵션을 제공합니다. 이 문서에서는 활용할 수 있는 게재 채널, 이를 선택하는 방법 및 서로 선택해야 하는 시기를 검토합니다.

## 권장: 이메일 연결을 통한 Gmail 또는 Exchange {#recommended-gmail-or-exchange-via-email-connection}

Marketo Sales에서는 이메일 연결 서비스를 통해 설정을 간소화하고 게재 능력을 향상시킬 수 있습니다. 이메일 연결을 통해 각 사용자는 Marketo Sales의 [Gmail](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md) 또는 [[!DNL Exchange]](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md) 계정에 연결하여 모든 Marketo Sales 이메일에 대해 선택한 게재 채널로 사용할 수 있습니다.

Gmail 또는 [!DNL Exchange]을 사용하면 다른 배달 채널 옵션에 비해 몇 가지 뚜렷한 이점이 있습니다.

* 이는 확고한 명성을 가진 입증된 게재 채널이며 게재 가능성을 높게 유지하는 데 도움이 됩니다.
* SPF 및 DKIM과 같은 인증 방법은 이미 IT 팀에서 구성 및 관리하고 있으므로 추가 설정이 없습니다.
* 지정된 전자 메일 네트워크 내에서 전자 메일을 보내는 것(즉, [!DNL Exchange]을(를) 통해 전자 메일을 받는 회사에 [!DNL Exchange] 사용자로 전자 메일을 보내는 것)은 게재 능력을 높이는 데 도움이 될 수 있습니다.

이러한 게재 채널에는 Microsoft 및 Google에 의해 적용되는 자체 전송 제한이 있습니다. 이를 해결하기 위해 사용자가 이러한 제한 내에서 유지될 수 있도록 조절 메커니즘을 활용합니다. [여기](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)에서 전자 메일 제한에 대해 자세히 알아보세요.

>[!NOTE]
>
>기본적으로 O365 플러그인은 항상 Exchange 게재 채널을 사용하고 Gmail 플러그인은 항상 Gmail 게재 채널을 사용하여 플러그인에서 이메일을 게재합니다.

**바운스 추적**: Marketo Sales는 보낸 사람의 받은 편지함으로 전송된 바운스 메시지를 감지하여 Exchange Online 또는 Gmail 사용자에 대한 바운스를 감지할 수 있습니다. 이러한 바운스 알림은 사용자를 위한 템플릿 분석, 캠페인 분석 및 라이브 피드 알림으로 롤업됩니다. 바운스 추적은 Exchange On-Prem 고객에 대해 지원되지 않습니다.

## SMTP를 통한 사용자 지정 배달 채널 {#custom-delivery-channel-via-smtp}

Marketo Sales에서는 영업 팀의 기본 배달 채널로 사용할 타사 SMTP 서버를 연결하는 추가 옵션을 제공합니다.

서드파티 SMTP 공급자를 활용하는 것은 이메일 볼륨이 가장 우선시되는 영업 팀에게 매우 적합한 옵션입니다. Sendgrid 및 Sparkpost와 같은 SMTP 공급자는 대량 이메일 전송 요구 사항을 지원하도록 최적화되었으며 대용량 이메일을 배포하려는 사용자의 요구 사항을 충족하도록 확장할 수 있습니다.

또한 서드파티 SMTP 공급자는 팀의 전달성 요구(예: 이메일 전달 보고서 및 전용 IP 주소)를 지원하는 데 도움이 되는 다양한 기능을 제공하므로 판매 이메일 전달 채널에 대한 보다 세분화된 제어 및 가시성을 원하는 사용자에게 매우 적합한 옵션입니다.

## Marketo Sales Server(기존) {#marketo-sales-servers-legacy}

Marketo Sales Server는 일부 기존 ToutApp 고객만 사용할 수 있습니다. 이러한 고객은 이메일 설정에서 사용할 수 있는 Marketo 판매 서버를 보게 됩니다. 레거시 이외의 모든 고객은 Marketo Sales를 옵션으로 볼 수 없으며 Gmail 또는 [!DNL Outlook] 계정을 Marketo Sales에 연결하여 게재 채널의 잠금을 해제해야 합니다.

Marketo Sales Server는 DKIM 및 SPF 인증 방법을 지원하지 않으므로 게재 가능성을 낮출 수 있습니다. 따라서 모든 고객은 최상의 전달 능력을 위해 Gmail 또는 [!DNL Outlook]에 연결하는 것이 좋습니다.

## MSC 서버(이전) {#msc-servers-legacy}

MSC 서버는 일부 이전 ToutApp 고객만 사용할 수 있습니다. 이러한 고객은 이메일 설정에서 사용할 수 있는 MSC 서버를 보게 됩니다. 레거시 이외의 모든 고객은 MSC를 옵션으로 보지 않으며 Gmail 또는 Outlook 계정을 Sales Connect에 연결하여 배달 채널을 잠금 해제해야 합니다.

MSC 서버는 DKIM 및 SPF 인증 방법을 지원하지 않으므로 전달률을 낮출 수 있습니다. 따라서 모든 고객은 최상의 전달 능력을 위해 Gmail 또는 [!DNL Outlook]에 연결하는 것이 좋습니다.

## Marketo 서버 {#marketo-servers}

Marketo 이메일 서버는 Marketo Sales와 통합되지 않습니다. Marketo 서버는 마케터의 요구에 따라 확장할 수 있도록 벌크 게재에 최적화되었습니다. 그러나 Gmail 및 [!DNL Exchange]은(는) 1:1 판매 커뮤니케이션에 대한 성공률이 더 높습니다. 따라서 이러한 서버를 판매 커뮤니케이션에 사용하는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [Gmail 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [사용자 [!DNL Outlook] 의 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)
>* [사용자 지정 게재 채널 설정](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/setting-up-a-custom-delivery-channel.md)
>* [전자 메일 연결 제한](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/email-connection-throttling.md)

---
unique-page-id: 12983291
description: 수신자 시간대 이해 - Marketo 문서 - 제품 설명서
title: 수신자 시간대 이해
exl-id: 8895241e-94c9-43a2-9158-11c1994df09b
source-git-commit: 46812deb41ed56328a4a64fbd36340d13c50dde4
workflow-type: tm+mt
source-wordcount: '391'
ht-degree: 0%

---

# 수신자 시간대 이해 {#understanding-recipient-time-zone}

전자 메일 및 참여 프로그램은 수신자의 시간대에 따라 전달되도록 구성할 수 있으므로 여러 프로그램을 만들 필요가 없습니다. 한 번 전송하고 Marketo은 올바른 로컬 시간까지 전자 메일을 자동으로 보관합니다.

>[!NOTE]
>
>받는 사람 시간대가 현재 작동합니다 **전용** 이메일 콘텐츠로 기본 참여 프로그램에는 작동하지 않습니다.

## 이메일 프로그램 {#email-programs}

다음의 두 가지 기본 시나리오가 있습니다. [이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md):

1. 다음 25시간 이내에 프로그램을 실행하도록 예약합니다.
1. 프로그램을 25시간 이상(즉, 다음 주)에 실행하도록 예약합니다.

모든 시간대를 수용하기 위해 수신자 시간대로 예약된 이메일 프로그램은 자정에 실행됩니다 **첫 번째/첫 번째** 세계의 시간대(UTC +14:00).

## 참여 프로그램 {#engagement-programs}

다음 경우에 [참여 프로그램 스트림 예약](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) 및 수신자 시간대가 활성화되면 프로그램 캐스팅이 UTC +14:00으로 자정에 실행됩니다. 전 세계 모든 시간대에 편성될 수 있으므로 향후 최소 25시간(24시간 + 캠페인을 시작하기 위한 시간)에 첫 방송을 예약해야 합니다. 현재 UTC +14:00에서 처리를 시작하면 이 배역에 대한 자격이 있는 모든 사람을 위해 예약된 날짜와 시간에 이메일을 보낼 수 있습니다.

## 표준 시간대 계산 {#calculating-time-zone}

Marketo은 개인의 도시, 주, 국가 또는 우편 번호를 기준으로 시간대를 계산합니다. 이 값에서 누군가의 시간대를 계산할 수 없다면, 유추된 도시, 유추된 상태, 유추된 국가 및 유추된 우편 번호 필드로 되돌아갑니다.

우리가 **전용** 국가 또는 **전용** 사용 가능한 상태:

* 시간대가 3개 이하인 국가의 경우에는 시간대를 선택합니다.
* 두 개의 시간대가 있는 상태의 경우 두 개의 시간대의 앞부분을 선택합니다.

이러한 필드 조합에서 사용자의 시간대를 확인할 수 없다면 다음을 수행합니다 **not** 표준 시간대를 할당하면 Marketo 구독 시간대를 기반으로 이메일이 전송됩니다. 따라서 프로그램이 오전 9시(PDT)로 예약된 경우, 시간대가 할당되지 않은 사용자는 9시 00분 PDT로 이메일을 받게 됩니다.

>[!NOTE]
>
>Marketo은 위의 입력 필드가 변경되면 개인 시간대를 자동으로 다시 계산합니다.

>[!MORELIKETHIS]
>
>* [수신자 시간대로 이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [이메일 프로그램 시작 시기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>
>* [받는 사람 시간대를 사용하여 참여 프로그램 예약](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)


---
unique-page-id: 12983291
description: 수신자 시간대 이해 - Marketo 문서 - 제품 설명서
title: 수신자 시간대 이해
exl-id: 8895241e-94c9-43a2-9158-11c1994df09b
feature: Email Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 3%

---

# 수신자 시간대 이해 {#understanding-recipient-time-zone}

수신자의 시간대에 따라 이메일 및 참여 프로그램을 전달하도록 구성할 수 있으므로 여러 프로그램을 만들 필요가 없습니다. 한 번만 보내면 Marketo에서 올바른 현지 시간까지 이메일을 자동으로 보관합니다.

>[!NOTE]
>
>[!UICONTROL Recipient Time Zone]은(는) 현재 전자 메일 콘텐츠로 **only**&#x200B;에서 작동합니다. 기본 참여 프로그램에는 작동하지 않습니다.

## 이메일 프로그램 {#email-programs}

[전자 메일 프로그램을 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)할 때 다음과 같은 두 가지 기본 시나리오가 있습니다.

1. 다음 25시간 내에 프로그램이 실행되도록 예약합니다.
1. 향후(즉, 다음 주) 25시간 이상 실행되도록 프로그램 예약.

모든 시간대를 수용하기 위해 [!UICONTROL Recipient Time Zone]&#x200B;(으)로 예약된 전자 메일 프로그램이 전 세계 **처음/가장 이른** 시간대의 자정에 실행됩니다(UTC +14:00).

## 참여 프로그램 {#engagement-programs}

[참여 프로그램 스트림을 예약](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)하고 [!UICONTROL Recipient Time Zone]이(가) 활성화되면 프로그램 캐스트가 자정(UTC +14:00)에 시작됩니다. 전 세계 모든 시간대에 캐스팅할 자격이 되므로 첫 번째 캐스팅을 25시간 이상 미래(24시간 + 캠페인을 시작하는 데 걸리는 시간)로 예약해야 합니다. 현재 UTC +14:00로 처리를 시작하면 이 캐스트에 대한 자격이 있는 모든 사용자에 대해 예약된 날짜와 시간에 이메일이 전송됩니다.

## 시간대 계산 중 {#calculating-time-zone}

Marketo은 개인의 도시, 주, 국가 또는 우편번호를 기반으로 시간대를 계산합니다. 이러한 값에서 누군가의 시간대를 계산할 수 없는 경우, 우리는 유추된 도시, 유추된 주, 유추된 국가 및 유추된 우편 번호 필드로 되돌아갑니다.

**only** 국가 또는 **only** 국가가 사용 가능한 경우:

* 시간대가 3개 이하인 국가의 경우 중간 시간대를 선택한다.
* 시간대가 두 개인 상태의 경우 두 개 중 이전 시간대를 선택합니다.

이러한 필드를 조합하여 다른 사람의 시간대를 확인할 수 없는 경우 **시간대를 할당하지** 않고 Marketo 구독 시간대를 기반으로 이메일이 전송됩니다. 따라서 프로그램이 9:00am PDT로 예약된 경우 시간대가 할당되지 않은 사람에게 9:00am PDT로 전자 메일이 전송됩니다.

>[!NOTE]
>
>Marketo은 위의 입력 필드 중 하나가 변경되면 개인의 시간대를 자동으로 다시 계산합니다.

>[!MORELIKETHIS]
>
>* [전자 메일 프로그램을 [!UICONTROL Recipient Time Zone]](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)(으)로 예약
>* [전자 메일 프로그램 시작 시작 시작](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>
>* [[!UICONTROL Recipient Time Zone]](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)과(와) 함께 참여 프로그램 예약

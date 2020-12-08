---
unique-page-id: 12983291
description: 수신자 시간대 이해 - 마케팅 문서 - 제품 설명서
title: 수신자 시간대 이해
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 0%

---


# 수신자 시간대 이해 {#understanding-recipient-time-zone}

이메일 및 참여 프로그램은 수신자의 시간대에 따라 전달되도록 구성할 수 있으므로 여러 프로그램을 제작할 필요가 없습니다. 한 번 전송하면 Marketing to에서 해당 지역의 시간으로 이메일을 자동으로 보관합니다.

>[!NOTE]
>
>받는 사람 시간대는 현재 **이메일 컨텐츠에서만** 작동합니다. 기본 참여 프로그램에서는 작동하지 않습니다.

## 이메일 프로그램 {#email-programs}

이메일 프로그램을 [예약할 때 다음과 같은 두 가지 주요 시나리오가 있습니다](schedule-email-programs-with-recipient-time-zone.md).

1. 다음 25시간 이내에 프로그램을 실행할 것을 예약합니다.
1. 향후 25시간 이상(예: 다음 주) 프로그램 실행을 예약합니다.

모든 시간대를 수용하기 위해 수신자 시간대와 함께 예약된 이메일 프로그램은 세계 **첫 번째/가장 이른** 시간대에서 자정에 시작됩니다(UTC +14:00).

## 참여 프로그램 {#engagement-programs}

참여 프로그램 스트림 [을](../../../../../product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) 예약하고 수신자 시간대가 활성 상태인 경우 프로그램 캐스팅은 UTC +14:00의 자정에 시작됩니다. 전 세계 모든 시간대에 편성할 수 있기 때문에 앞으로 최소 25시간(24시간 + 캠페인 시작 시간)에 첫 출연을 예약해야 합니다. 현재 UTC +14:00에서 처리를 시작하면 이 배역을 자격이 있는 모든 사용자에 대해 예약된 날짜와 시간에 이메일을 전달할 수 있습니다.

## 시간대 계산 {#calculating-time-zone}

Marketing은 사용자의 구/군/시, 주, 국가 또는 우편번호에 따라 시간대를 계산합니다. 이러한 값에서 사용자의 시간대를 계산할 수 없는 경우 유추된 도시, 유추된 상태, 유추된 국가 및 유추된 우편번호 필드로 돌아갑니다.

**만 **국가 또는 **국가만** 제공되는 경우:

* 시간대가 3개 이하인 국가의 경우 중간 시간대를 선택합니다.
* 2개의 시간대가 있는 주에서는 두 개의 시간대 중 가장 이른 시간대를 선택합니다.

이러한 필드 조합에서 다른 사람의 시간대를 아직 확인할 수 없는 경우, 시간대를 할당하지 **않고** , 귀하의 Marketing to 구독 시간대를 기반으로 이메일이 전달됩니다. 따라서 프로그램이 오전 9시(태평양 표준시)로 예정되어 있는 경우, 지정된 시간대가 없는 사람은 오전 9시(태평양 표준시)에 이메일을 받게 됩니다.

>[!NOTE]
>
>위의 입력 필드가 변경되면 Marketing Cloud에서 사용자의 시간대를 자동으로 다시 계산합니다.

>[!NOTE]
>
>**관련 문서**
>
>* [받는 사람 시간대에서 이메일 프로그램 예약](schedule-email-programs-with-recipient-time-zone.md)
>* [이메일 프로그램 시작](../../../../../product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)

   >
   >
* [받는 사람 시간대에서 참여 프로그램 예약](../../../../../product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)

>




---
unique-page-id: 12983291
description: 수신자 시간대 이해 - 마케팅 문서 - 제품 설명서
title: 수신자 시간대 이해
translation-type: tm+mt
source-git-commit: 8d45a28e1c2adad3e04645f7150f1757414092f0
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# 받는 사람 시간대 이해 {#understanding-recipient-time-zone}

이메일 및 참여 프로그램은 수신자의 시간대에 따라 전달되도록 구성할 수 있으므로 여러 프로그램을 제작할 필요가 없습니다. 한 번 이메일을 전송하면 Marketing Cloud에서 정확한 현지 시간까지 이메일을 자동으로 보관합니다.

>[!NOTE]
>
>받는 사람 시간대는 현재 전자 메일 내용으로 **만**&#x200B;합니다. 기본 참여 프로그램에서는 작동하지 않습니다.

## 이메일 프로그램 {#email-programs}

[이메일 프로그램 ](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)을 예약할 때 다음 두 가지 기본 시나리오가 있습니다.

1. 다음 25시간 이내에 프로그램을 실행하도록 예약합니다.
1. 향후 25시간 이상(예: 다음 주) 프로그램을 실행하도록 예약합니다.

모든 시간대를 수용하기 위해 수신자 시간대와 함께 예약된 이메일 프로그램은 **first/early** 시간대의 자정에 시작됩니다(UTC +14:00).

## 참여 프로그램 {#engagement-programs}

[참여 프로그램 스트림](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) 및 수신자 시간대가 활성 상태인 경우 프로그램 캐스팅은 UTC +14:00의 자정에 시작됩니다. 전 세계 모든 시간대에 편성할 수 있는 자격이 주어지기 때문에 앞으로 적어도 25시간(24시간 + 캠페인을 시작하는 데 필요한 시간)의 첫 방송을 예약할 필요가 있습니다. 현재 UTC +14:00에서 처리를 시작하면 이 배역을 자격이 있는 모든 사람에게 예약된 날짜와 시간에 이메일을 전달할 수 있습니다.

## 시간대 계산 중 {#calculating-time-zone}

Marketing은 사용자의 구/군/시, 주, 국가 또는 우편번호를 기준으로 시간대를 계산합니다. 이러한 값에서 사용자의 시간대를 계산할 수 없는 경우 유추된 도시, 유추된 상태, 유추된 국가 및 유추된 우편번호 필드로 돌아갑니다.

**국가 또는**&#x200B;만&#x200B;**상태를 사용할 수 있는 경우:**

* 시간대가 3개 이하인 국가의 경우 중간 시간대를 선택합니다.
* 2개의 시간대가 있는 주의 경우 2개의 시간대 중 가장 이른 시간대를 선택합니다.

이러한 필드 조합에서 다른 사람의 시간대를 여전히 확인할 수 없는 경우, **은(는) 시간대를 할당하지 않고**&#x200B;은(는) 사용자의 Marketing to 구독 시간대를 기반으로 이메일이 전달됩니다. 따라서 프로그램이 오전 9시(태평양 표준시)로 예정되어 있는 경우, 지정된 시간대가 없는 사람은 오전 9시(태평양 표준시)에 이메일을 받게 됩니다.

>[!NOTE]
>
>위의 입력 필드가 변경되면 Marketing Cloud는 사용자의 시간대를 자동으로 다시 계산합니다.

>[!MORELIKETHIS]
>
>* [받는 사람 시간대로 이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [이메일 프로그램의 즉각적인 시작](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)

   >
   >
* [받는 사람 시간대를 사용하여 참여 프로그램 예약](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)


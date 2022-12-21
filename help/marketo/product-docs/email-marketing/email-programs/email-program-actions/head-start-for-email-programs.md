---
unique-page-id: 10097202
description: 이메일 프로그램 시작 - Marketo 문서 - 제품 설명서
title: 이메일 프로그램 시작 시기
exl-id: f7c8b082-4d83-4e3b-8aa4-7b252e3dacd3
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 0%

---

# 이메일 프로그램 시작 시기 {#head-start-for-email-programs}

>[!PREREQUISITES]
>
>[이메일 프로그램 만들기](/help/marketo/product-docs/email-marketing/email-programs/creating-an-email-program/create-an-email-program.md)

이메일 프로그램의 날짜/시간을 선택하면 프로그램이 처리를 시작할 시기를 결정합니다. 선택한 시간에 이메일이 실행되도록 하려면 헤드 시작 이 프로그램을 미리 처리하여 해당 옵션을 제공합니다.

## 표준 헤드 시작 {#standard-head-start}

1. 클릭 **마케팅 활동**.

   ![](assets/one-1.png)

1. 이메일 프로그램을 찾아 선택합니다.

   ![](assets/selectemailprogram-4.jpg)

   >[!NOTE]
   >
   >Head Start는 A/B 테스트와 함께 사용할 수 없습니다.

1. 예약 타일에서 이메일을 예약한 다음 **헤드 시작** 상자.

   ![](assets/three-1.png)

   헤드 시작 을 선택하면 프로그램이 예약된 시간보다 약 12시간 전에 처리를 시작합니다. 처리가 시작되면 프로그램이 잠깁니다.

   >[!CAUTION]
   >
   >프로그램 잠금 후 구독을 취소한 대상의 모든 사용자는 여전히 이메일을 받게 됩니다. 가입 해지 알림을 조정하여 구독 취소를 처리하는 데 영업일 1~2일이 걸릴 수 있습니다.

1. 클릭 **프로그램 승인**.

   ![](assets/four-1.png)

   프로그램 승인 후 승인 타일에 표시되는 네 가지 다른 상태가 있습니다.

   * **실행 대기 중:** 프로그램이 승인되면.
   * **처리가 시작되어 실행 대기 중:** 처리 중입니다.
   * **처리가 완료되어 실행 대기 중:** 처리가 완료되었으며, 이제 예약된 시작 시간을 기다리는 이메일을 보냅니다.
   * **완료됨:** 프로그램이 완료되었습니다.

   >[!TIP]
   >
   >프로그램이 잠금 후 이메일이 전송되기 전에 취소하시겠습니까? 문제 없어! 간단히 **프로그램 중단** ( 승인 타일의 오른쪽 아래에 있습니다.)

   >[!NOTE]
   >
   >예약된 실행 시간보다 12시간 미만의 이메일 프로그램을 승인하지 않고 변경하려는 경우 승인 날짜보다 최소 12시간 빠른 새 날짜/시간을 선택해야 합니다.

## 수신자 시간대로 시작 {#head-start-with-recipient-time-zone}

기존의 헤드 시작 기능을 사용하려면 프로그램을 최소 12시간 전에 예약해야 합니다. 수신자 시간대에는 어떤 의미가 있습니까? 수신자 시간대가 활성화되면 가장 이른 시간대의 자정(UTC +14:00)에 이메일 프로그램을 실행하기 시작합니다. 따라서 **둘 다** Head Start 및 Recipient Time Zone, 프로그램을 예약해야 함 **가장 이른 시간대의 최소 12시간(UTC +14:00)**)

즉, 미국/LA에 있고 헤드 시작 및 수신자 시간대 모두를 사용하려면 프로그램을 예약해야 합니다 **34시간** 미리 요 이 번호로 어떻게 왔나요?

![](assets/image2017-12-5-13-3a11-3a46.png)

[추가 정보](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md) 수신자 시간대를 사용하여 이메일 프로그램을 예약하는 방법에 대한 정보입니다.

>[!MORELIKETHIS]
>
>* [이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.md)
>* [수신자 시간대로 이메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [수신자 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)


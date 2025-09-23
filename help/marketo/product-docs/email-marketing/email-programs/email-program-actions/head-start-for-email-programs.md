---
unique-page-id: 10097202
description: 이메일 프로그램 - Marketo 문서 - 제품 설명서 헤드 시작
title: 이메일 프로그램 시작
exl-id: f7c8b082-4d83-4e3b-8aa4-7b252e3dacd3
feature: Email Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 3%

---

# 이메일 프로그램 시작 {#head-start-for-email-programs}

>[!PREREQUISITES]
>
>[전자 메일 프로그램 만들기](/help/marketo/product-docs/email-marketing/email-programs/creating-an-email-program/create-an-email-program.md)

이메일 프로그램의 날짜/시간을 선택하면 프로그램 처리를 시작할 시기가 결정됩니다. 이메일을 선택한 시간에 시작하려는 경우 헤드 스타트 에서는 프로그램을 미리 처리하여 해당 옵션을 제공합니다.

## 표준 헤드 시작 {#standard-head-start}

1. **[!UICONTROL Marketing Activities]**&#x200B;를 클릭합니다.

   ![](assets/one-1.png)

1. 이메일 프로그램을 찾아 선택합니다.

   ![](assets/selectemailprogram-4.jpg)

   >[!NOTE]
   >
   >헤드 시작은 A/B 테스트와 함께 사용할 수 없습니다.

1. [!UICONTROL Schedule] 타일에서 전자 메일을 예약한 다음 **[!UICONTROL Head Start]** 상자를 선택합니다.

   ![](assets/three-1.png)

   [!UICONTROL Head Start]을(를) 선택하면 프로그램이 예약된 시간보다 약 12시간 전에 처리를 시작합니다. 처리가 시작되면 프로그램이 잠깁니다.

   >[!CAUTION]
   >
   >프로그램 잠금 후 구독을 취소하는 대상자의 모든 사용자는 여전히 이메일을 받게 됩니다. 구독 취소를 처리하는 데 영업일 기준 1~2일이 소요될 수 있음을 반영하도록 구독 취소 알림을 조정하는 것이 좋습니다.

1. **[!UICONTROL Approve Program]**&#x200B;를 클릭합니다.

   ![](assets/four-1.png)

   프로그램 승인 후 승인 타일에 표시되는 네 가지 상태가 있습니다.

   * 프로그램 승인 후 **[!UICONTROL Waiting to run]:**.
   * **[!UICONTROL Processing started, waiting to run]:** 처리가 진행 중입니다.
   * **[!UICONTROL Processing finished, waiting to run]:** 처리가 완료되었습니다. 이제 예약된 시작 시간을 기다리는 중입니다.
   * **[!UICONTROL Finished]:** 프로그램이 완료되었습니다.

   >[!TIP]
   >
   >프로그램이 잠긴 후 이메일을 보내기 전에 취소하시겠습니까? 문제 없습니다! 승인 타일의 오른쪽 아래에서 **[!UICONTROL Abort Program]**&#x200B;을(를) 클릭하면 됩니다.

   >[!NOTE]
   >
   >예약된 실행 시간으로부터 12시간 이내에 이메일 프로그램의 승인을 취소했지만 마음이 바뀌는 경우 승인보다 최소 12시간 앞선 새 날짜/시간을 선택해야 합니다.

## 수신자 시간대로 시작 {#head-start-with-recipient-time-zone}

기존의 헤드 스타트 기능을 사용하려면 최소 12시간 전에 프로그램을 예약해야 합니다. 수신자 시간대는 무엇을 의미합니까? 수신자 시간대가 활성화된 경우 가장 이른 시간대(UTC +14:00)의 자정에 이메일 프로그램을 시작합니다. 따라서 **시작 및 받는 사람 시간대**&#x200B;를 모두 사용하려면 가장 이른 시간대(UTC +14 **)보다 최소 12시간 앞서:00**&#x200B;프로그램을 예약해야 합니다.

즉, 미국/로스앤젤레스에 있고 헤드 시작 및 수신자 시간대를 모두 활성화하려는 경우 **34시간** 프로그램을 미리 예약해야 합니다. 어떻게 우리가 이 번호를 알게 됐죠?

![](assets/image2017-12-5-13-3a11-3a46.png)

받는 사람 시간대로 전자 메일 프로그램을 예약하는 방법에 대해 [자세히 알아보기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md).

>[!MORELIKETHIS]
>
>* [전자 메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.md)
>* [받는 사람 시간대로 전자 메일 프로그램 예약](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [받는 사람 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)

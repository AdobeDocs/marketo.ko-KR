---
unique-page-id: 12982903
description: 수신자 시간대로 이메일 프로그램 예약 - Marketo 문서 - 제품 설명서
title: 수신자 시간대로 이메일 프로그램 예약
exl-id: d0c3f3c1-9f21-4081-818d-7c5cb1766915
feature: Email Programs
source-git-commit: 21bcdc10fe1f3517612efe0f8e2adaf2f4411a70
workflow-type: tm+mt
source-wordcount: '794'
ht-degree: 0%

---

# 수신자 시간대로 이메일 프로그램 예약 {#schedule-email-programs-with-recipient-time-zone}

수신자 시간대가 활성화된 동안 이메일 프로그램을 예약할 때 두 가지 가능한 시나리오가 있습니다.

1. 다음 25시간 이내에 **다음** 내에서 실행되도록 프로그램을 예약하는 중
1. 향후(즉, 다음 주) 25시간 이상 동안 **더**&#x200B;을(를) 실행하도록 프로그램을 예약하는 중

## 시나리오 1: 25시간 이내 {#scenario-within-hours}

수신자 시간대가 활성화된 이메일 프로그램을 승인하고 25시간 이내에 예약된 배달 시간을 준다고 가정해 보겠습니다. 스마트 목록에 예약된 시간이 이미 경과한 시간대에 거주하는 사용자가 있을 수 있습니다.

이 시나리오에서는 자격 있는 사람의 하위 집합으로 수행할 작업을 결정할 수 있습니다. 전자 메일 프로그램의 **[!UICONTROL Recipient Time Zone]** 타일에서 **[!UICONTROL Schedule]** 옆에 있는 톱니바퀴 아이콘을 클릭합니다.

![](assets/image2017-12-5-10-3a46-3a42.png)

이렇게 하면 두 가지 옵션이 제공됩니다.

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**정의**
>
>* **[!UICONTROL Deliver the following day in recipient’s time zone]**: 전자 메일이 화요일 9:00am에 나가도록 예약되어 있는 경우 예약된 시간이 이미 지난 시간대에 거주하는 자격이 있는 사람은 *수요일* 9:00am에 전자 메일을 받게 됩니다.
>
>* **[!UICONTROL Deliver using the program's default set time]**: 전자 메일이 화요일 9:00am에 나가도록 예약되어 있는 경우 예약된 시간이 이미 지난 시간대에 거주하는 자격이 있는 사람이 *구독 시간대 설정에 따라*&#x200B;전자 메일을 받게 됩니다. 따라서 [구독 시간대 설정](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md)이 PDT America/Los Angeles로 설정된 경우 이러한 수신자는 화요일 9:00am PDT에 이메일을 계속 수신하게 됩니다(자체 시간대에 있는 모든 시간).

>[!NOTE]
>
>Marketo에서 수신자의 시간대를 계산하는 방법에 대해 [자세히 알아보기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md#calculating-time-zone).

이 시나리오를 좀 더 자세히 살펴보겠습니다. 샌프란시스코에 있는 경우 :00am9 **전송을 위해 7:00am**&#x200B;에 전자 메일을 예약합니다. 스마트 목록에는 다음 지역의 사람들이 있습니다.

* 샌프란시스코
* 텍사스
* 뉴욕
* 이탈리아

![](assets/image2017-12-6-10-3a52-3a41.png)

9:00am이(가) 이미 뉴욕과 이탈리아에서 통과했으므로 이 두 시간대의 적격 사용자는 **시간대 설정**&#x200B;을(를) 기반으로 이메일을 수신하게 됩니다.

* **[!UICONTROL Deliver the following day in recipient’s time zone]:** 수요일 9:00am(각 시간대: **또는**)

* **[!UICONTROL Deliver using the program's default set time]**: 화요일 9:00am PDT(뉴욕 - 12:00pm EDT 및 이탈리아 - 6:00pm CET).

프로그램을 승인하면 15분 내에 시작됩니다.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>프로그램에서 15분 후에 전자 메일 보내기 *프로세스*&#x200B;를 시작하지만 해당 시간에는 전자 메일이 *배달*&#x200B;되지 않습니다. 받는 사람은 선택한 **[!UICONTROL Time Zone Settings]**&#x200B;을(를) 기반으로 이메일을 계속 받습니다.

## 시나리오 2: 25시간 이상 {#scenario-more-than-hours}

이 두 번째 시나리오에서는 **[!UICONTROL Recipient Time Zone]**&#x200B;이(가) 활성화된 이메일 프로그램을 승인하며 향후 25시간 이상 예약된 배달 시간을 승인합니다. 이 경우 프로그램은 세계의 **가장 이른** 시간대(UTC + 14:00)에 예약된 시간에 실행됩니다. 전 세계 모든 시간대에 스마트 목록을 사용할 수 있는 사람이 있을 수 있으므로 가장 빠른 시간대에 시작하면 각 시간대의 모든 수신자에게 예약된 날짜/시간에 이메일을 전송할 수 있습니다.

**헤드 시작**

이제 [[!UICONTROL Head Start]](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)이(가) **[!UICONTROL Recipient Time Zone]**&#x200B;과(와) 함께 작동하는 방식에 대해 설명하겠습니다. 기존의 헤드 스타트 기능을 사용하려면 최소 12시간 전에 프로그램을 예약해야 합니다. 수신자 시간대는 어떤 의미입니까? 수신자 시간대가 활성화되면 가장 이른 시간대(UTC +14:00)의 예약된 시간에 이메일 프로그램 실행을 시작합니다. 따라서 **시작 및 받는 사람 시간대**&#x200B;를 모두 사용하려면 전자 메일 프로그램을 UTC +14 **.:00에서 예약된 시간보다 최소 12시간 전에**&#x200B;예약해야 합니다.

즉, 미국/로스앤젤레스에 있고 헤드 시작 및 수신자 시간대를 모두 활성화하려는 경우 **34시간** 프로그램을 미리 예약해야 합니다. 어떻게 우리가 이 번호를 알게 됐죠?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

즉, 수신자 시간대로 예약된 이메일 프로그램은 모든 시간대를 수용하기 위해 가장 이른 시간대(즉, 첫 번째 자정에 도달하는 시간대)의 예약된 시간에 실행을 시작해야 합니다. 이메일 프로그램을 예약하면...

* **배달 시간이 *25시간 이내*인 경우**&#x200B;에 프로그램이 15분 이내에 시작됩니다. 예약된 시간을 이미 경과한 수신자는 선택한 시간대 설정을 기반으로 이메일을 수신하게 됩니다.
* **배달 시간이 *앞으로 25시간 이상*인 경우** 가장 빠른 표준 시간대(UTC +14:00)의 예약된 시간에 프로그램이 실행됩니다.
* **시작 시점**&#x200B;에서 가장 빠른 표준 시간대(UTC +14:00)의 예약된 시간보다 12시간 전에 프로그램이 처리를 시작합니다.

>[!CAUTION]
>
>이메일 전송을 시작한 시간과 실제로 이메일을 배달한 시간 사이에 구독을 취소하는 사람은 이메일을 계속 수신합니다. 구독 취소를 처리하는 데 영업일 기준 1~2일이 소요될 수 있음을 반영하도록 구독 취소 알림을 조정하는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [받는 사람 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [전자 메일 프로그램 시작 시작 시작](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [받는 사람 시간대로 예약된 전자 메일 프로그램 배달 중단](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)

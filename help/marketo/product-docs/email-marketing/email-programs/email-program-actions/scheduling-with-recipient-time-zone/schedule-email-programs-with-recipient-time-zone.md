---
unique-page-id: 12982903
description: 수신자 시간대로 이메일 프로그램 예약 - Marketo 문서 - 제품 설명서
title: 수신자 시간대로 이메일 프로그램 예약
exl-id: d0c3f3c1-9f21-4081-818d-7c5cb1766915
feature: Email Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---

# 수신자 시간대로 이메일 프로그램 예약 {#schedule-email-programs-with-recipient-time-zone}

수신자 시간대가 활성화된 동안 이메일 프로그램을 예약할 때 두 가지 가능한 시나리오가 있습니다.

1. 프로그램 실행 예약 **다음 범위 내** 다음 25시간
1. 프로그램 실행 예약 **기타** 25시간 이상 미래(즉, 다음 주)

## 시나리오 1: 25시간 이내 {#scenario-within-hours}

수신자 시간대가 활성화된 이메일 프로그램을 승인하고 25시간 이내에 예약된 배달 시간을 준다고 가정해 보겠습니다. 스마트 목록에 예약된 시간이 이미 경과한 시간대에 거주하는 사용자가 있을 수 있습니다.

이 시나리오에서는 자격 있는 사람의 하위 집합으로 수행할 작업을 결정할 수 있습니다. 옆에 있는 톱니바퀴 아이콘을 클릭합니다 **수신자 시간대** 다음에서 **예약** 이메일 프로그램 타일.

![](assets/image2017-12-5-10-3a46-3a42.png)

이렇게 하면 두 가지 옵션이 제공됩니다.

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**정의**
>
>* **수신자의 시간대에 다음 날 게재**: 이메일이 화요일 오전 9시에 발송되도록 예약된 경우, 예약된 시간이 이미 경과한 시간대에 거주하는 자격이 있는 사람은에 이메일을 수신하게 됩니다. *수요일* 오전 9시에
>
>* **프로그램의 기본 설정 시간을 사용하여 게재**: 이메일이 화요일 오전 9시에 발송되도록 예약된 경우, 예약된 시간이 이미 경과한 시간대에 거주하는 자격이 있는 사람이 이메일을 수신합니다 _구독 시간대 설정에 따라_. 그렇다면 [구독 시간대 설정](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md) 는 PDT 아메리카/로스앤젤레스로 설정되어 있으며, 이러한 수신자는 화요일 오전 9시(PDT)에도 여전히 이메일을 수신하게 됩니다(자체 시간대에 속하는 모든 시간).

>[!NOTE]
>
>[자세히 알아보기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md#calculating-time-zone) Marketo에서 수신자의 시간대를 계산하는 방법에 대해 설명합니다.

이 시나리오를 좀 더 자세히 살펴보겠습니다. 샌프란시스코에 있다고 가정하고 오전 7시에 이메일 예약 **오전 9:00** 전송. 스마트 목록에는 다음 지역의 사람들이 있습니다.

* 샌프란시스코
* 텍사스
* 뉴욕
* 이탈리아

![](assets/image2017-12-6-10-3a52-3a41.png)

뉴욕과 이탈리아에서는 오전 9시가 이미 지났습니다. 따라서 이 두 시간대의 자격이 있는 사용자는 다음을 기반으로 이메일을 수신하게 됩니다. **시간대 설정**:

* **수신자의 시간대에 다음 날을 게재합니다.** 수요일 오전 9시에 각각의 시간대에서 **또는**

* **프로그램의 기본 설정 시간을 사용하여 게재**: 화요일 오전 9시(태평양 표준시)(뉴욕 - 오후 12시(태평양 표준시) 및 이탈리아 - 오후 6시(태평양 표준시)

프로그램을 승인하면 15분 내에 시작됩니다.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>프로그램이 _프로세스_ 15분 안에 이메일을 보낼 경우 이메일은 _게재됨_ 그 때. 수신자는 여전히 다음을 기반으로 이메일을 수신하게 됩니다. **시간대 설정** 네가 선택해

## 시나리오 2: 25시간 이상 {#scenario-more-than-hours}

이 두 번째 시나리오에서는 **수신자 시간대** 활성화되었으며 향후 25시간 이상의 예약된 배달 시간. 이 경우 프로그램은 의 예약된 시간에 실행됩니다. **가장 빠르** 세계의 시간대(UTC + 14:00). 전 세계 모든 시간대에 스마트 목록을 사용할 수 있는 사람이 있을 수 있으므로 가장 빠른 시간대에 시작하면 각 시간대의 모든 수신자에게 예약된 날짜/시간에 이메일을 전송할 수 있습니다.

**헤드 스타트**

이제, 방법에 대해 이야기해 보겠습니다 [헤드 스타트](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) 와 함께 작업 **수신자 시간대**. 기존의 헤드 스타트 기능을 사용하려면 최소 12시간 전에 프로그램을 예약해야 합니다. 수신자 시간대는 어떤 의미입니까? 수신자 시간대가 활성화되면 가장 이른 시간대의 예약된 시간에 이메일 프로그램을 시작합니다(UTC +14:00). 따라서 활성화하려면 **모두** 시작 및 수신자 시간대, 이메일 프로그램을 예약해야 함 **UTC +14:00으로 예약된 시간보다 최소 12시간 빠릅니다.**

즉, 미국/로스앤젤레스에 있는 사용자가 헤드 스타트 및 수신자 시간대를 모두 활성화하려면 프로그램을 예약해야 합니다 **34시간** 미리. 어떻게 우리가 이 번호를 알게 됐죠?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

즉, 수신자 시간대로 예약된 이메일 프로그램은 모든 시간대를 수용하기 위해 가장 이른 시간대(즉, 첫 번째 자정에 도달하는 시간대)의 예약된 시간에 실행을 시작해야 합니다. 이메일 프로그램을 예약하면...

* **게재 시간 포함 _다음 범위 내_ 25시간**, 프로그램 실행이 15분 내에 시작됩니다. 예약된 시간을 이미 경과한 수신자는 선택한 시간대 설정을 기반으로 이메일을 수신하게 됩니다.
* **게재 시간 포함 _보다 큼_ 향후 25시간**, 프로그램이 가장 이른 시간대의 예약된 시간에 실행됩니다(UTC +14:00).
* **헤드 시작 포함**, 프로그램은 가장 빠른 시간대에 예약된 시간보다 12시간 전에 처리를 시작합니다(UTC +14:00).

>[!CAUTION]
>
>이메일 전송을 시작한 시간과 실제로 이메일을 배달한 시간 사이에 구독을 취소하는 사람은 이메일을 계속 수신합니다. 구독 취소를 처리하는 데 영업일 기준 1~2일이 소요될 수 있음을 반영하도록 구독 취소 알림을 조정하는 것이 좋습니다.

>[!MORELIKETHIS]
>
>* [수신자 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [이메일 프로그램 헤드 시작](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [수신자 시간대로 예약된 이메일 프로그램 배달 중단](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)

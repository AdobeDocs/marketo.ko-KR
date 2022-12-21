---
unique-page-id: 12982903
description: 수신자 시간대로 이메일 프로그램 예약 - Marketo 문서 - 제품 설명서
title: 수신자 시간대로 이메일 프로그램 예약
exl-id: d0c3f3c1-9f21-4081-818d-7c5cb1766915
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---

# 수신자 시간대로 이메일 프로그램 예약 {#schedule-email-programs-with-recipient-time-zone}

수신자 시간대가 활성화된 동안 이메일 프로그램을 예약할 때 두 가지 가능한 시나리오가 있습니다.

1. 실행할 프로그램을 예약합니다. **within** 다음 25시간
1. 실행할 프로그램을 예약합니다. **자세히** 향후 25시간 이내(즉, 다음 주)

## 시나리오 1: 25시간 이내 {#scenario-within-hours}

수신자 시간대가 활성화된 이메일 프로그램과 다음 25시간 내에 예약된 배달 시간을 승인한다고 가정해 보겠습니다. 예약된 시간이 이미 경과한 시간대에 있는 스마트 목록에 있는 사람이 있을 수 있습니다.

이 시나리오에서는 이 자격 있는 사람의 하위 집합으로 수행할 작업을 결정할 수 있습니다. 옆에 있는 톱니바퀴 아이콘을 클릭합니다 **받는 사람 시간대** 에서 **예약** 이메일 프로그램 타일.

![](assets/image2017-12-5-10-3a46-3a42.png)

다음 두 가지 옵션을 제공합니다.

![](assets/image2017-12-5-10-3a31-3a28.png)

>[!NOTE]
>
>**정의**
>
>* **수신자의 시간대에 다음 날 게재**: 이메일이 화요일 오전 9시에 발송되도록 예약되어 있는 경우 예약된 시간이 이미 경과한 시간대에 거주하는 자격이 있는 사용자는 이메일을 받게 됩니다 *수요일* 오전 9시에
>
>* **프로그램의 기본 설정 시간을 사용하여 게재**: 이메일이 화요일 오전 9시에 발송되도록 예약되어 있는 경우 예약된 시간이 이미 경과한 시간대에 거주하는 자격이 있는 사용자는 이메일을 받게 됩니다 _구독 시간대 설정에 따라_. 만약 [구독 시간대 설정](/help/marketo/product-docs/administration/settings/select-your-language-locale-and-time-zone.md) 가 PDT 미국/LOS Angeles로 설정되면 이러한 수신자는 여전히 화요일 오전 9시(즉, 고유한 시간대에 있을 수 있는 시간)에 이메일을 받게 됩니다.


>[!NOTE]
>
>[추가 정보](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md#calculating-time-zone) Marketo이 수신자의 시간대를 계산하는 방법에 대해 설명합니다.

이 시나리오를 자세히 살펴보겠습니다. 지금 샌프란시스코라고 하세요. 오전 7시에 이메일을 예약하고 **오전 9:00** 전송. 스마트 목록에는 다음 지역 사람들이 있습니다.

* 샌프란시스코
* 텍사스
* 뉴욕
* 이탈리아

![](assets/image2017-12-6-10-3a52-3a41.png)

오전 9시가 이미 뉴욕과 이탈리아에서 통과되었으므로 이 두 시간대에 있는 자격이 있는 사용자는 **시간대 설정**:

* **수신자의 시간대에 다음 날을 게재합니다.** 수요일 오전 9시에 각 시간대에 **또는**

* **프로그램의 기본 설정 시간을 사용하여 게재**: 화요일 오전 9시(PDT) (뉴욕 - 오후 12시 0분 EDT 및 이탈리아 - 오후 6시 00분 CET).

프로그램을 승인하면 15분 이내에 실행이 시작됩니다.

![](assets/screen-shot-2017-12-09-at-3.34.14-pm.png)

>[!NOTE]
>
>프로그램이 _프로세스_ 이메일은 15분 안에 보낼 수 있습니다 _배달됨_ 그때. 수신자는 여전히 **시간대 설정** 선택하시면 됩니다

## 시나리오 2: 25시간 이상 {#scenario-more-than-hours}

이 두 번째 시나리오에서는 **받는 사람 시간대** 활성화되고 25시간 이상의 예약된 배달 시간입니다. 이 경우 프로그램은 **가장** 세계의 시간대(UTC + 14:00). 전 세계 모든 시간대에 스마트 목록에 대한 자격이 있는 사람이 있을 수 있으므로 가장 이른 시간대를 시작으로 해당 시간대에 있는 모든 수신자에게 예약된 날짜/시간에 이메일을 전달할 수 있습니다.

**헤드 시작**

이제, 어떻게 [헤드 시작](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md) 작업 **받는 사람 시간대**. 기존의 헤드 시작 기능을 사용하려면 프로그램을 최소 12시간 전에 예약해야 합니다. 그러면 그것이 수신자 시간대를 의미하는 것은 무엇입니까? 수신자 시간대가 활성화되면 가장 이른 시간대의 예약된 시간에 이메일 프로그램 실행을 시작합니다(UTC +14:00). 따라서 **둘 다** 헤드 시작 및 수신자 시간대, 이메일 프로그램을 예약해야 함 **UTC +14:00에서 예약된 시간보다 최소 12시간 앞당깁니다.**

즉, 미국/LA에 있고 헤드 시작 및 수신자 시간대 모두를 사용하려면 프로그램을 예약해야 합니다 **34시간** 미리 요 이 번호로 어떻게 왔나요?

![](assets/image2017-12-5-13-3a11-3a38.png)

<br> 

즉, 수신자 시간대와 함께 예약된 이메일 프로그램은 모든 시간대를 수용하기 위해 가장 이른 시간대의 예약된 시간에(즉, 자정 전에 도달하는 경우) 실행을 시작해야 합니다. 이메일 프로그램을 예약하면...

* **배달 시간으로 _within_ 25시간**&#x200B;로 설정되면 15분 이내에 프로그램이 실행됩니다. 예약된 시간을 이미 경과한 수신자는 선택한 시간대 설정에 따라 이메일을 수신하게 됩니다.
* **배달 시간으로 _보다 큼_ 향후 25시간**&#x200B;를 입력하면 프로그램은 가장 이른 시간대의 예약된 시간에 실행됩니다(UTC +14:00).
* **헤드 시작 사용**&#x200B;를 지정하는 경우, 프로그램은 가장 이른 시간대의 예약된 시간보다 12시간 전에 처리를 시작합니다(UTC +14:00).

>[!CAUTION]
>
>이메일 전송을 시작한 시간과 실제로 배달된 시간 사이에 가입을 해지한 모든 사용자는 여전히 이메일을 받게 됩니다. 가입 해지 알림을 조정하여 구독 취소를 처리하는 데 영업일 1~2일이 걸릴 수 있습니다.

>[!MORELIKETHIS]
>
>* [수신자 시간대 이해](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
>* [이메일 프로그램 시작 시기](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>* [수신자 시간대로 예약된 이메일 프로그램의 배달 중단](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/abort-delivery-of-email-programs-scheduled-with-recipient-time-zone.md)


---
description: 이메일 연결 제한 - Marketo 문서 - 제품 설명서
title: 전자 메일 연결 조절
exl-id: 02450a1e-5b30-4057-b204-19fab1a7d6c9
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '435'
ht-degree: 0%

---

# 전자 메일 연결 조절 {#email-connection-throttling}

Exchange 또는 Gmail 이메일 공급자를 통해 전송할 Sales Connect 계정을 통합하면 간소화된 설정이 제공되며 1:1 영업 커뮤니케이션에 대한 이메일 게재 기능이 최적화됩니다. 그러나 시스템 상태 및 계정을 안전하게 유지하기 위해 Gmail 및 Exchange는 이메일 전송 제한을 적용합니다. 이러한 제한은 공급자 재량에 따라 늘리거나 줄일 수 있습니다.

## 이메일 연결 조절(베타) {#email-connection-throttling-beta}

>[!AVAILABILITY]
>
>이 기능은 현재 베타 릴리스에 있습니다. 이 베타에 참여하려면 고객 성공 관리자에게 문의하십시오.

이메일 연결 조절 기능을 사용하면 Sales Connect 관리자가 Gmail 또는 Exchange를 게재 채널로 사용할 때 전자 메일의 전송 속도를 구성할 수 있으므로 전자 메일이 게재 채널 공급자에게 전달되는 비율이 강제 제한을 초과하지 않도록 할 수 있습니다.

제한이 일관되게 초과되면 게재 채널 공급자에서 의심스러운 동작으로 보여져 이메일이 실패하거나 계정을 비활성화하는 경우가 있을 수 있습니다.

**메모/특징**

* 사용자가 Gmail 또는 Exchange에 접속하면 자동으로 활성화됩니다
* 필요에 맞게 권장 사항의 설정을 늘리거나 줄이려면 사용자 지정할 수 있습니다
* Gmail 또는 Exchange를 통해 전송된 이메일만 제한하며 사용자 지정 게재 채널에 대해서는 조절되지 않습니다
* 전자 메일 연결 조절 기능은 각 사용자가 전자 메일 공급자와 자체 연결이 있을 때 각 개별 사용자의 전자 메일을 별도로 큐에 추가합니다

**전자 메일 연결 조절 설정 구성**

1. 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/email-connection-throttling-1.png)

1. 관리자 설정에서 을 클릭합니다. **일반**.

   ![](assets/email-connection-throttling-2.png)

1. 오른쪽 전자 메일 연결 조절 카드에서 **전자 메일 조절 사용** 슬라이더.

   ![](assets/email-connection-throttling-3.png)

1. 오른쪽의 이메일 연결 조절 카드에 전자 메일 채널 공급자에게 보낼 이메일의 원하는 배치 크기를 입력합니다.

   ![](assets/email-connection-throttling-4.png)

1. 각 일괄 처리가 전송되기 전에 대기할 시간을 설정합니다. 이 예제에서는 45초마다 25개의 이메일을 선택합니다.

   ![](assets/email-connection-throttling-5.png)

1. 클릭 **저장**.

   ![](assets/email-connection-throttling-6.png)

변경 사항이 저장되면 모든 사용자는 전송을 위해 연결된 Gmail 또는 Exchange 계정에 일괄적으로 전자 메일이 전송됩니다.

## 전자 메일 공급자 제한 {#email-provider-limits}

**Outlook 365**

비즈니스/엔터프라이즈

* 하루에 10,000개
* 분당 30
* 이메일당 500명의 수신자

추가 정보 [여기에서 찾을 수 있습니다.](https://docs.microsoft.com/en-us/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits?redirectedfrom=MSDN#RecipientLimits).

**Gmail**

* 평가판 및 플래그가 지정된 계정의 경우 2000명
* 초당 2개의 이메일(API 제한)
* 메시지당 2,000명의 수신자(외부 수신자의 경우 최대 500명)

추가 정보 [여기에서 찾을 수 있습니다.](https://support.google.com/a/answer/166852?hl=en).

**Microsoft Exchange Server(2010년, 2013년)**

제한은 조직이 서버를 호스팅함에 따라 조직의 IT 부서에 의해 설정됩니다. 자세한 내용은 네트워크 또는 시스템 관리자에게 문의하십시오.

>[!MORELIKETHIS]
>
>* [게재 채널 개요](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/delivery-channel-overview.md)
>* [Gmail 사용자를 위한 이메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Outlook 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)


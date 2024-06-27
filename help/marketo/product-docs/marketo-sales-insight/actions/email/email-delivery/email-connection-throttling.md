---
description: 이메일 연결 제한 - Marketo 문서 - 제품 설명서
title: 이메일 연결 제한
exl-id: 02450a1e-5b30-4057-b204-19fab1a7d6c9
feature: Sales Insight Actions
source-git-commit: 19f60f58ae4de26536b304eb8ae9677ecc221993
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 0%

---

# 이메일 연결 제한 {#email-connection-throttling}

Exchange 또는 Gmail 이메일 공급자를 통해 전송하기 위해 Sales Connect 계정을 통합하면 간소화된 설정이 제공되며 1:1 판매 커뮤니케이션을 위한 이메일 전달성을 최적화합니다. 그러나 시스템의 상태와 계정의 안전을 유지하기 위해 Gmail 및 Exchange는 이메일 전송 제한을 적용합니다. 이러한 한계는 제공자의 재량에 따라 증감될 여지가 있다.

## 이메일 연결 제한(Beta) {#email-connection-throttling-beta}

이메일 연결 제한을 사용하면 Sales Connect 관리자는 Gmail 또는 Exchange를 게재 채널로 사용할 때 이메일 전송 속도를 구성할 수 있으므로 전송 채널 공급자에게 이메일이 전달되는 속도가 강제 제한을 초과하지 않습니다.

제한을 지속적으로 초과하면 게재 채널 공급자의 의심스러운 동작으로 보여져 이메일이 실패하고 계정이 비활성화되는 경우가 있습니다.

**메모/하이라이트**

* 사용자가 Gmail 또는 Exchange에 연결하면 자동으로 활성화됨
* 필요에 맞게 추천에서 설정을 늘리거나 줄이려면 사용자 지정할 수 있습니다
* Gmail 또는 Exchange를 통해 전송된 이메일만 제한하며 사용자 지정 게재 채널에는 제한하지 않습니다.
* 이메일 연결 조절은 각 사용자가 이메일 공급자와 자체 연결을 가지고 있으므로 각 개별 사용자의 이메일을 별도로 큐에 추가합니다

**전자 메일 연결 제한 설정 구성**

1. 톱니바퀴 아이콘을 클릭하고 **설정**.

   ![](assets/email-connection-throttling-1.png)

1. Admin Settings에서 **일반**.

   ![](assets/email-connection-throttling-2.png)

1. 오른쪽의 전자 메일 연결 제한 카드에서 **이메일 제한 사용** 슬라이더.

   ![](assets/email-connection-throttling-3.png)

1. 오른쪽의 전자 메일 연결 제한 카드에 전자 메일 채널 공급자에게 보낼 전자 메일의 원하는 배치 크기를 입력합니다.

   ![](assets/email-connection-throttling-4.png)

1. 각 일괄 처리가 전송되기 전에 대기할 시간을 설정합니다. 이 예제에서는 45초마다 25개의 이메일을 선택합니다.

   ![](assets/email-connection-throttling-5.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/email-connection-throttling-6.png)

변경 사항이 저장되면 모든 사용자는 연결된 Gmail 또는 Exchange 계정에 이메일을 일괄적으로 보내 배달할 수 있습니다.

## 이메일 공급자 제한 {#email-provider-limits}

**Outlook 365**

비즈니스/엔터프라이즈

* 하루 10,000
* 분당 30
* 이메일당 500명의 수신자

추가 정보 [은(는) 여기에서 찾을 수 있음](https://docs.microsoft.com/en-us/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits?redirectedfrom=MSDN#RecipientLimits).

**Gmail**

* 일일 2000개(평가판 및 플래그가 지정된 계정의 경우 500개)
* 초당 이메일 2개(API 제한)
* 메시지당 수신자 2,000명(외부 수신자의 경우 최대 500명)

추가 정보 [은(는) 여기에서 찾을 수 있음](https://support.google.com/a/answer/166852?hl=en).

**Microsoft Exchange Server(2010, 2013)**

서버가 조직에 의해 호스팅되므로 조직의 IT 부서에서 한도를 설정합니다. 추가 정보는 해당되는 경우 네트워크 또는 시스템 관리자에게 문의하십시오.

>[!MORELIKETHIS]
>
>* [게재 채널 개요](/help/marketo/product-docs/marketo-sales-connect/email/email-delivery/delivery-channel-overview.md)
>* [Gmail 사용자를 위한 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/gmail/email-connection-for-gmail-users.md)
>* [Outlook 사용자용 전자 메일 연결](/help/marketo/product-docs/marketo-sales-connect/email-plugins/msc-for-outlook/email-connection-for-outlook-users.md)

---
unique-page-id: 4720710
description: 이메일 전달성을 위한 SPF 및 DKIM 설정 - Marketo 문서 - 제품 설명서
title: 이메일 전달성을 위한 SPF 및 DKIM 설정
exl-id: a0f88e94-3348-4f48-bbd2-963e2af93dc0
feature: Deliverability
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '421'
ht-degree: 4%

---

# 이메일 전달성을 위한 SPF 및 DKIM 설정 {#set-up-spf-and-dkim-for-your-email-deliverability}

전자 메일 게재 속도를 향상시키는 한 가지 빠른 방법은 **SPF**(보낸 사람 정책 프레임워크) 및 **DKIM**(Domain Keys Identified Mail)을 DNS 설정에 통합하는 것입니다. DNS 항목 외에도 Marketo에서 귀하를 대신하여 이메일을 보내도록 승인했음을 수신자에게 알려 줍니다. 이 변경 사항이 없으면 이메일이 도메인에서 주소가 지정되었지만 Marketo 도메인이 있는 IP 주소에서 전송되었기 때문에 이메일이 스팸으로 표시될 가능성이 더 높습니다.

>[!CAUTION]
>
>네트워크 관리자가 DNS 레코드에서 이 변경 작업을 수행해야 합니다.

## SPF 설정 {#set-up-spf}

**도메인에 SPF 레코드가 없는 경우**

네트워크 관리자에게 DNS 항목에 다음 줄을 추가하도록 요청하십시오. [domain]을(를) 웹 사이트의 주 도메인으로 바꾸십시오(예: 회사 전자 메일 서버의 IP 주소가 &quot;company.com&quot;) 및 [corpIP]입니다(예: &quot;255.255.255.255&quot;). Marketo을 통해 여러 도메인에서 이메일을 보내는 경우 각 도메인(한 줄)에 추가해야 합니다.

`[domain] IN TXT v=spf1 mx ip4:[corpIP] include:mktomail.com ~all`

**도메인에 SPF 레코드가 있는 경우**

DNS 항목에 이미 SPF 레코드가 있는 경우 다음을 추가합니다.

include:mktomail.com

## DKIM 설정 {#set-up-dkim}

**DKIM이란? DKIM을 설정하는 이유는 무엇입니까?**

DKIM은 이메일 수신자가 이메일 메시지를 보낸 사람이 보냈는지 확인하는 데 사용하는 인증 프로토콜입니다. DKIM은 종종 수신자가 메시지가 위조가 아니라고 확신할 수 있으므로 받은 편지함으로 이메일을 배달하는 기능을 향상시킵니다.

**DKIM은 어떻게 작동합니까?**

DNS 레코드에서 공개 키를 설정하고 관리 섹션(A)에서 전송 도메인을 활성화하면 보내는 메시지에 대해 사용자 지정 DKIM 서명을 켭니다. 이 서명에는 보내는 각 전자 메일(B)과 함께 암호화된 디지털 서명이 포함됩니다. 수신자는 전송 도메인의 DNS(C)에서 &quot;공개 키&quot;를 조회하여 디지털 서명을 해독할 수 있습니다. 이메일의 키가 DNS 레코드의 키와 일치하는 경우 수신 메일 서버는 사용자를 대신하여 보낸 이메일 Marketo을 수락할 가능성이 높습니다.

![](assets/image2015-1-12-13-3a56-3a55.png)

**DKIM을 어떻게 설정합니까?**

[사용자 지정 DKIM 서명 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md){target="_blank"}을 참조하세요.

>[!MORELIKETHIS]
>
>* SPF 및 작동 방식에 대해 자세히 알아보기`: http://www.open-spf.org/Introduction/`
>* SPF가 올바르게 설정되었습니까?: `https://www.kitterman.com/spf/validate.html`
>* 올바른 구문을 사용했습니까?: `http://www.open-spf.org/SPF_Record_Syntax/`

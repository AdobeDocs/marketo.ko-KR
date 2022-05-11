---
unique-page-id: 4720710
description: 이메일 게재 기능을 위한 SPF 및 DKIM 설정 - Marketo 문서 - 제품 설명서
title: 전자 메일 게재 기능에 대해 SPF 및 DKIM을 설정합니다
exl-id: a0f88e94-3348-4f48-bbd2-963e2af93dc0
source-git-commit: de32becbfe74c2a88c53de8af8be4ee022782114
workflow-type: tm+mt
source-wordcount: '443'
ht-degree: 0%

---

# 전자 메일 게재 기능에 대해 SPF 및 DKIM을 설정합니다 {#set-up-spf-and-dkim-for-your-email-deliverability}

이메일 전송률을 향상시키는 한 가지 빠른 방법은 다음을 통합하는 것입니다 **SPF** (보낸 사람 정책 프레임워크) 및 **DKIM** (식별된 메일) 을 DNS 설정으로 가져옵니다. DNS 항목 외에도 사용자를 대신하여 Marketo에서 전자 메일을 보내도록 인증했음을 수신자에게 알리고 있습니다. 이 변경 사항이 없으면 이메일이 도메인에서 주소가 지정되었지만 Marketo 도메인이 있는 IP 주소에서 보낸 이후로 스팸으로 표시될 가능성이 높습니다.

>[!CAUTION]
>
>DNS 레코드를 변경하려면 네트워크 관리자가 필요합니다.

## SPF 설정 {#set-up-spf}

**도메인에 SPF 레코드가 없는 경우**

네트워크 관리자에게 DNS 항목에 다음 줄을 추가하라고 요청합니다. 바꾸기 [도메인] 웹 사이트의 주 도메인(예: &quot;company.com&quot;) 및 [corpIP] (예: 회사 이메일 서버의 IP 주소 사용) &quot;255.255.255.255&quot;). 여러 도메인에서 Marketo을 통해 이메일을 보내는 경우 각 도메인에 (한 줄에) 추가해야 합니다.

`[domain] IN TXT v=spf1 mx ip4:[corpIP] include:mktomail.com ~all`

**도메인에 SPF 레코드가 있는 경우**

DNS 항목에 이미 SPF 레코드가 있는 경우 다음을 추가합니다.

include:mktomail.com

## DKIM 설정 {#set-up-dkim}

**DKIM이란 무엇입니까? DKIM을 설정해야 하는 이유는 무엇입니까?**

DKIM은 전자 메일 수신자가 전자 메일 메시지를 보낸 사람이 전자 메일 메시지를 보냈는지 여부를 확인하기 위해 사용하는 인증 프로토콜입니다. DKIM은 메시지가 위조되지 않는다고 수신자가 확신할 수 있으므로 종종 받은 편지함으로 전자 메일의 게재 능력을 향상시킵니다.

**DKIM은 어떻게 작동합니까?**

DNS 레코드에 공개 키를 설정하고 관리 섹션(A)에서 전송 도메인을 활성화하면, 보내는 메시지에 대한 사용자 지정 DKIM 서명을 켜며, 이 서명에는 보내는 각 이메일에 암호화된 디지털 서명이 포함됩니다(B). 수신자는 전송 도메인의 DNS(C)에서 &quot;공개 키&quot;를 조회하여 디지털 서명을 해독할 수 있습니다. 이메일의 키가 DNS 레코드의 키와 일치하는 경우 수신 메일 서버가 사용자를 대신하여 보낸 이메일 Marketo을 수락할 가능성이 높습니다.

![](assets/image2015-1-12-13-3a56-3a55.png)

**DKIM을 설정하려면 어떻게 해야 합니까?**

자세한 내용은 [사용자 지정 DKIM 서명 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md).

>[!MORELIKETHIS]
>
>* [SPF 및 SPF 작동 방식에 대해 자세히 알아보기](http://www.open-spf.org/Introduction/)
>* [Marketo의 이메일 게재 기능 도구](https://www.marketo.com/software/email-marketing/email-deliverability/)
>* [내 SPF가 올바르게 설정되어 있습니까?](https://www.kitterman.com/spf/validate.html)
>* [올바른 구문을 사용했습니까?](http://www.open-spf.org/SPF_Record_Syntax/)


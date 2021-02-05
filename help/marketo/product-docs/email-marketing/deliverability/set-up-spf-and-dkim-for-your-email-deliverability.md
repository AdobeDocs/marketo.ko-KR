---
unique-page-id: 4720710
description: 이메일 전달 - Marketing To Docs - 제품 설명서에 대해 SPF 및 DKIM 설정
title: 이메일 전달을 위해 SPF 및 DKIM 설정
translation-type: tm+mt
source-git-commit: 074701d1a5f75fe592ac7f44cce6fb3571e94710
workflow-type: tm+mt
source-wordcount: '443'
ht-degree: 0%

---


# 이메일 배달 가능 {#set-up-spf-and-dkim-for-your-email-deliverability}에 대해 SPF 및 DKIM을 설정합니다.

이메일 배달 비율을 개선하는 한 가지 빠른 방법은 **SPF**(보낸 사람 정책 프레임워크) 및 **DKIM**(도메인 키 식별된 메일)을 DNS 설정에 통합하는 것입니다. DNS 항목을 추가하면 수신자에게 Marketing Cloud가 대신 이메일을 보내도록 인증했음을 알리는 것입니다. 이러한 변경 사항이 없으면 이메일이 도메인에서 보내졌지만 Marketing To 도메인이 있는 IP 주소에서 보낸 이후로 스팸으로 표시될 가능성이 높습니다.

>[!CAUTION]
>
>DNS 레코드를 변경하려면 네트워크 관리자가 필요합니다.

## SPF {#set-up-spf} 설정

**도메인에 SPF 레코드가 없는 경우**

DNS 항목에 다음 줄을 추가하도록 네트워크 관리자에게 요청합니다. [도메인]을 웹 사이트의 주 도메인으로 바꿉니다(예: 회사 이메일 서버의 IP 주소를 사용하는 [corpIP]( 예: &quot;company.com&quot;) 및 corpIP). &quot;255.255.255.255&quot;). Marketing To를 통해 여러 도메인의 이메일을 전송하는 경우 각 도메인(한 줄에)에 추가해야 합니다.

`[domain] IN TXT v=spf1 mx ip4:[corpIP] include:mktomail.com ~all`

**도메인에 SPF 레코드가 있는 경우**

DNS 항목에 이미 SPF 레코드가 있으면 SPF 레코드에 다음을 추가합니다.

include:mktomail.com

## DKIM {#set-up-dkim} 설정

**DKIM 소개 DKIM을 설정하는 이유는 무엇입니까?**

DKIM은 이메일 수신자가 이메일 메시지를 전송했다고 말하는 사람이 이메일 메시지를 전송했는지 여부를 결정하기 위해 사용하는 인증 프로토콜입니다. DKIM은 수신자가 메시지가 위조되지 않는다고 확신할 수 있기 때문에 종종 받은 편지함으로 이메일의 배달 능력을 향상시킵니다.

**DKIM은 어떻게 작동합니까?**

DNS 레코드에 공개 키를 설정하고 관리 섹션(A)에서 전송 도메인을 활성화한 후, 본사는 (B) 귀하에게 발송하는 각 이메일에 암호화된 디지털 서명을 포함하는 발신 메시지에 대한 사용자 지정 DKIM 서명을 활성화합니다. 수신자는 전송 도메인의 DNS(C)에서 &quot;공개 키&quot;를 조회하여 디지털 서명을 해독할 수 있습니다. 이메일의 키가 DNS 레코드의 키와 일치하는 경우 받는 메일 서버가 사용자를 대신하여 보낸 이메일 마케팅을 수락할 가능성이 더 높습니다.

![](assets/image2015-1-12-13-3a56-3a55.png)

**DKIM을 설정하려면 어떻게 해야 합니까?**

[사용자 지정 DKIM 서명 설정](/help/marketo/product-docs/email-marketing/deliverability/set-up-a-custom-dkim-signature.md)을 참조하십시오.

>[!MORELIKETHIS]
>
>* [SPF에 대한 자세한 내용 및 작동 방법](https://www.open-spf.org/Introduction/)
>* [Marketing To의 이메일 전달 기능 도구](https://www.marketo.com/software/email-marketing/email-deliverability/)
>* [SPF가 올바르게 설정되어 있습니까?](https://www.kitterman.com/spf/validate.html)
>* [올바른 구문을 사용했습니까?](https://www.open-spf.org/SPF_Record_Syntax/)


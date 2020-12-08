---
unique-page-id: 4720710
description: 이메일 전달 기능에 대한 SPF 및 DKIM 설정 - Marketing Docs - 제품 설명서
title: 이메일 전달 기능에 대해 SPF 및 DKIM 설정
translation-type: tm+mt
source-git-commit: 07ae1b3f3ee3e9d7f35373eea039d336bd786f97
workflow-type: tm+mt
source-wordcount: '456'
ht-degree: 0%

---


# 이메일 전달 기능에 대해 SPF 및 DKIM 설정 {#set-up-spf-and-dkim-for-your-email-deliverability}

이메일 배달 비율을 개선하는 빠른 방법 중 하나는 **SPF** (Sender Policy Framework) 및 **DKIM** (Domain Keys Identified Mail)을 DNS 설정에 통합하는 것입니다. DNS 항목을 추가하면 수신자에게 대신 Marketing Cloud에서 이메일을 보내도록 인증했다고 알립니다. 이러한 변경 사항이 없으면 이메일이 도메인에서 보내졌으나 Marketing To 도메인이 있는 IP 주소에서 보낸 것이므로 스팸으로 표시될 가능성이 높아집니다.

>[!CAUTION]
>
>네트워크 관리자가 DNS 레코드를 변경해야 합니다.

## SPF 설정 {#set-up-spf}

**도메인에 SPF 레코드가 없는 경우**

DNS 항목에 다음 줄을 추가하도록 네트워크 관리자에게 요청합니다. 도메인 [] 을 웹 사이트의 주 도메인으로 바꿉니다(예: 회사 이메일 서버의 IP 주소를 사용하는 &quot;company.com&quot;) 및 [corpIP] (예: &quot;255.255.255.255&quot;). Marketing to를 통해 여러 도메인에서 이메일을 전송하는 경우 이를 각 도메인(한 줄)에 추가해야 합니다.
[domain] IN TXT v=spf1 mx ip4:[corpIP] include:mktomail.com ~all\
도메인에 SPF 레코드가 있는 경우

DNS 항목에 이미 SPF 레코드가 있는 경우 DNS 항목에 다음을 추가합니다.

include:mktomail.com

## DKIM 설정 {#set-up-dkim}

### DKIM 소개 DKIM을 설정하려는 이유는 무엇입니까? {#what-is-dkim-why-do-i-want-to-set-up-dkim}

DKIM은 이메일 수신자가 이메일 메시지를 보냈는지 여부를 결정하기 위해 사용하는 인증 프로토콜입니다. DKIM은 수신자가 메시지가 위조되지 않는다고 확신할 수 있기 때문에 종종 받은 편지함에 대한 이메일의 배달 능력을 향상시킨다.

DKIM은 어떻게 작동합니까?

DNS 레코드에 공개 키를 설정하고 관리 섹션(A)에서 전송 도메인을 활성화한 후, 본사는 전송한 각 이메일에 암호화된 디지털 서명을 포함하는 발신 메시지에 대한 사용자 지정 DKIM 서명을 활성화합니다(B). 수신자는 전송 도메인의 DNS(C)에서 &quot;공개 키&quot;를 조회하여 디지털 서명을 해독할 수 있습니다. 이메일의 키가 DNS 레코드의 키와 일치하는 경우 수신 메일 서버는 귀하를 대신하여 보낸 이메일 마케팅을 수락할 가능성이 높습니다.

![](assets/image2015-1-12-13-3a56-3a55.png)

DKIM을 어떻게 설정합니까?

사용자 [지정 DKIM 서명 설정을 참조하십시오](set-up-a-custom-dkim-signature.md).

>[!NOTE]
>
>**관련 문서**
>
>* [SPF와 SPF의 작동 방식에 대한 자세한 내용](http://www.open-spf.org/Introduction/)
>* [Marketing&#39;s Email Delivery Tools](https://www.marketo.com/software/email-marketing/email-deliverability/)
>* [SPF가 제대로 설정되어 있습니까?](http://www.kitterman.com/spf/validate.html)
>* [올바른 구문을 사용했습니까?](http://www.open-spf.org/SPF_Record_Syntax/)

>




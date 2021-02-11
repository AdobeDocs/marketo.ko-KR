---
unique-page-id: 14746594
description: SMTP 서버 설정 - 마케팅 문서 - 제품 설명서
title: SMTP 서버 설정
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '655'
ht-degree: 0%

---


# SMTP 서버 설정 {#setting-up-an-smtp-server}

## 개요 {#overview}

**SMTP 서버란 무엇입니까?**

****&#x200B;단순  ****&#x200B;메일  ****&#x200B;전송  ****&#x200B;프로토콜. 이 서버는 아웃바운드 메일을 보내는 데 책임이 있는 서버입니다. 이메일 클라이언트에서 이메일을 보내면 동일한 서비스를 사용하여 이메일을 보냅니다.

**Sales Connect를 사용하여 SMTP 서버를 설정하는 이유는 무엇입니까?**

회사 도메인의 명성을 활용할 수 있고 택할 수 있으며 다른 사람의 충성도에 의존할 필요가 없습니다. 기본 MSC 서버는 공유 평판에서 보내는 것을 의미하는 공유 IP 풀의 일부입니다. Adobe에서는 팀이 Sales Connect를 통해 고유한 전달 채널을 설정하는 것이 좋습니다.

**Sales Connect는 SMTP 서버와 어떻게 전송됩니까?**

[다음 단계를 따릅니다](http://docs.marketo.com/x/ZgPh).

![](assets/1.png)

`<pre><em>SMTP Server Setup Page in Sales Connect</em><br> </pre>` **이메일 클라이언트에 설정해야 합니까?**

전달 채널은 그렇지 않습니다. Adobe Add-in을 설치하면 Sales Connect는 이메일 전송을 위해 설정한 것과 동일한 전달 채널을 사용합니다.

## SMTP 자격 증명 가져오기 {#getting-the-smtp-credentials}

**SMTP 자격 증명을 받으려면 어떻게 합니까?**

IT 팀에 문의하여 회사에서 이메일을 보내는 데 사용하는 배달 채널과 SMTP 자격 증명에 대한 액세스 방법을 확인하십시오. 서버 구성 방식에 따라 SMTP 서버 이름 또는 서버 포트에 대한 사용자 지정 값이 있을 수 있습니다. 전용 IT 팀이 없는 경우 이메일 공급업체에 문의하십시오.

**회사에서 Office365를 사용하는 경우 어떻게 해야 합니까?**

전문가

* 간편한 설정
* Office365 계정을 가진 모든 사용자는 이 SMTP 서버에 액세스할 수 있습니다

반대

* 제한 발생 가능
* 각 사용자는 이 설정을 직접 설정해야 합니다.
* 사용자의 O365 암호를 변경하면 연결이 끊어집니다.

Office365 또는 Exchange Online을 사용하는 경우 표준 자격 증명 집합을 사용하여 SMTP 서버에 연결할 수 있습니다. 일회성 이메일 전송에는 잘 작동하지만 Office 365는 대량 이메일 배달 서비스가 아닙니다. 벌크 이메일을 보낼 때 Office 365는 이메일을 스로틀 수 있으므로 배달이 실패할 수 있습니다. 이 문서에 대한 자세한 내용은 [SMTP 클라이언트 제출](http://support.office.com/en-us/article/how-to-set-up-a-multifunction-device-or-application-to-send-email-using-office-365-69f58e99-c550-4274-ad18-c805d654b4c4)을 설정하는 방법에 대한 Microsoft 문서를 참조하십시오.

&quot;장치가 여러 Office 365 사서함에 대한 로그인 자격 증명을 저장할 수 없는 한 하나의 전자 메일 주소에서만 보낼 수 있습니다. Office 365에서는 분당 메시지 30개, 하루 받는 사람 수 1만 개로 제한됩니다.

배달 채널로 Office 365를 사용하려는 경우 이 자격 증명을 입력해야 합니다. Office365에서는 사용자의 전자 메일 및 암호를 사용하여 연결할 수 있으므로 팀 전체에서 동일한 자격 증명을 사용할 수 없습니다.

Microsoft 및 일괄 전송

[Office365에서 벌크 전송에 대해 여기를 ](https://technet.microsoft.com/en-us/library/exchange-online-limits.aspx#RecipientLimits) 클릭하십시오.

합당한 대량 광고 이메일(예: 고객 뉴스레터)을 보내야 하는 Exchange Online 고객은 이러한 서비스를 전문으로 하는 제3자 제공업체를 이용해야 합니다.&quot;

**우리 회사가 지메일을 사용한다면 어떻게 하지?**

팀이 Sales Connect에서 Gmail을 배달 채널로 사용하려면 SMTP 자격 증명을 가져올 필요가 없습니다. Sales Connect를 사용하면 OAuth 통합을 통해 Gmail 전달 채널에 액세스할 수 있습니다. 사용자는 Sales Connect 계정을 Gmail과 통합하여 이를 활성화할 수 있습니다.

![](assets/2.png)

**동일한 SMTP 자격 증명을 팀 전체와 공유할 수 있습니까?**

사용 중인 전달 채널에 따라 다릅니다. 예를 들어 Sparkpost와 같은 서비스는 자격 증명을 도메인 기반으로 할 수 있도록 허용하므로 특정 도메인으로 전송된 사람은 해당 서버를 통해 전송하도록 인증됩니다. 이 경우 예. 팀과 자격 증명을 공유할 수 있습니다.

Office 365에 연결하는 경우 자격 증명은 전자 메일 주소를 기반으로 합니다. 즉, 연결을 설정한 이메일 주소만 해당 배달 채널을 통해 이메일을 전송하도록 인증되므로 자격 증명은 **공유되지 않아야 합니다.**

![](assets/3.png)

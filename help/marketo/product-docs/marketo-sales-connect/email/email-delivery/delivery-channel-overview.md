---
unique-page-id: 14352407
description: 전달 채널 개요 - 마케팅 문서 - 제품 설명서
title: 전달 채널 개요
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 0%

---


# 전달 채널 개요 {#delivery-channel-overview}

활용할 수 있는 세 개의 서로 다른 채널, 이를 선택하는 방법, 다른 채널을 선택하는 방법, 이러한 채널을 둘러싼 미묘한 차이를 구분해 보겠습니다.

>[!NOTE]
>
>이 정보는 [웹 응용](http://toutapp.com/login)프로그램에서 이메일을 보내는 경우에만 관련이 있습니다. Gmail 또는 Outlook에서 Sales Connect를 사용하는 경우 해당 이메일 서버를 통해 이메일이 전달됩니다.

## MSC 이메일 서버(기본값) {#msc-email-servers-default}

기본적으로 이 방법은 이메일 배달에 대해 선택됩니다. MSC 이메일 서버는 Gmail 또는 Outlook을 사용하지 않는 사용자에게 좋은 옵션입니다. 또한 본사는 서버가 서버이기 때문에 바운스 또는 실패한 게재와 관련된 오류 메시지를 가져와서 대화 탭의 &quot;실패한 배달&quot; 섹션에서 귀하에게 표시할 수 있습니다.

MSC 서버를 사용할 때의 또 다른 이점은 [이메일 ID를](https://help.toutapp.com/hc/en-us/articles/215371427)사용할 경우 사용자가 만든 ID의 이메일 주소를 수신자에게 볼 수 있다는 것입니다.

MSC 서버를 사용하는 경우 받는 사람에게 &quot;using utapp.com&quot; 태그가 표시될 수 있습니다. 이 이메일은 Sales Connect를 사용하여 보낸 이메일을 알려주는 이메일 클라이언트입니다.

자세한 내용은 이 Gmail [도움말 문서를 참조하십시오](https://support.google.com/mail/answer/1311182?hl=en).

>[!NOTE]
>
>MSC 서버에는 사용 가능한 [DMARC 레코드가](https://dmarc.org/) 없습니다. 자체 서버에서 허용 목록에 추가할 수 없습니다.

## Gmail 서버 {#gmail-server}

회사의 이메일 공급자가 Gmail인 경우 기존 계정을 활용하여 Sales Connect 이메일을 보낼 수 있습니다. &quot;tutapp.com을 통해&quot; 정보를 사용하지 않으려는 경우, 회사 도메인 및 수신 기능에 의존하려는 경우 이 옵션이 적합합니다. Gmail 서버를 사용하면 웹 응용 프로그램에서 보내는 모든 내용이 Gmail 보낸 폴더에 자동으로 추가됩니다.

Adobe는 Sales Connect 이메일을 전달할 단일 Gmail 계정(하나의 이메일 주소)과 제대로 연결할 수 있습니다. 즉, 여러 개의 이메일 ID를 사용하는 경우 세부 사항을 볼 때 Adobe가 연결된 계정의 주소만 나타납니다.

웹 응용 프로그램에서 ID는 만든 대로 표시됩니다(위). 그러나 Gmail 서버를 통해 보내면 연결된 계정의 주소가 표시됩니다.

>[!NOTE]
>
>Sales Connect는 Gmail 서버를 직접 관리하지 않으므로 웹 응용 프로그램에 바운스된 이메일 이벤트를 기록하지 않습니다.

## 사용자 지정 SMTP 서버  {#custom-smtp-server}

서버 비용을 지불하시겠습니까? Microsoft Exchange 환경을 사용하십니까? 이 옵션은 사용자가 선택할 수 있습니다. 설정 [에](http://docs.marketo.com/x/zYTS) 대한 지침을 확인하십시오. Gmail Server와 마찬가지로 Sales Connect는 서버를 직접 관리하지 않으므로 웹 응용 프로그램에 바운스된 이메일 이벤트를 기록하지 않습니다.


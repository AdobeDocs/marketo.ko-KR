---
description: Websocket 연결 설정 불가 알림을 받은 Marketo Engage 사용자에 대한 알림 세부 정보
title: 알림 - Websocket 연결
hide: true
hidefromtoc: true
exl-id: 00c754f8-3850-4209-803d-5cdb108dc6dc
source-git-commit: 15427eacd2fc42a02f6a4c59d9102bacba02e57b
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 30%

---

# 알림: 웹소켓 연결 {#notification-websocket-connection}

이 문서는 Marketo 인스턴스에서 다음 알림을 받은 Marketo Engage 사용자를 위한 것입니다. `"We were unable to establish a websocket connection to <some-server.adobe.net>. We are ending support of the servers you are currently connected to. Please work with your IT Team to allowlist required Marketo Engage and Adobe domains and ports to prevent access disruptions."`

사용자 또는 사용자 조직에서 제한적 방화벽 또는 프록시 서버 설정을 사용하는 경우, 사용자 또는 네트워크 관리자는 Adobe Marketo Engage가 예상대로 작동하도록 특정 도메인 및 IP 주소 범위를 허용 목록에 추가해야 할 수 있습니다.

Marketo 지원이 아래 프로토콜 구현을 지원하도록 설정되지 않았습니다. 지원이 필요한 경우 이 문서를 IT 팀과 공유하십시오. 허용 목록에 추가하다를 사용하여 웹 액세스를 제한하는 경우 모든 Marketo 리소스 및 웹 소켓을 허용하도록 다음 도메인(별표 포함)을 추가하도록 요청합니다.

* `*.marketo.com`
* `*.marketodesigner.com`
* `*.mktoweb.com`
* `*.experience.adobe.com`
* `*.adobe.net`

---
description: 이메일 추적 개요 - Marketo 문서 - 제품 설명서
title: 이메일 추적 개요
hide: true
hidefromtoc: true
exl-id: 89437d22-d739-45ea-8a2e-046a7de80379
source-git-commit: fda1bf51d4016a61c41be9acba4771db1797a552
workflow-type: tm+mt
source-wordcount: '510'
ht-degree: 0%

---

# 이메일 추적 개요 {#email-tracking-overview}

## 회신 추적 작동 방식 {#how-reply-tracking-works}

회신 추적은 보내는 모든 이메일에 있는 메시지 ID를 확인함으로써 수행됩니다. 모든 이메일에는 가장 좋은 회신 추적을 수행할 수 있는 고유한 메시지 ID가 포함되어 있습니다.

>[!PREREQUISITES]
>
>전자 메일 서버와의 연결: Sales Connect는 받은 편지함과 연결되어 있어야 새 회신이 언제 도착했는지 알 수 있습니다. Gmail에 Sales Connect 계정을 연결해야 합니다. Outlook을 사용하는 경우 Exchange 서버와 통합해야 합니다.

Sales Connect에서 잠재 고객의 전자 메일에 대한 응답을 추적할 수 없는 경우 회신 감지 또는 Salesforce에 회신하는 로그를 기준으로 캠페인을 중지할 수 없습니다. 이메일 주소가 회신할 수 있다는 것은 무엇입니까?

즉, flynn@flynnsarcade.com으로 이메일을 보내고 kevinf@flynnsarcade.com으로 응답하는 경우 응답을 추적할 수 있습니다. 또한 flynn@flynnsarcade.com 및 CC alan@encom.com으로 이메일을 보내고 Alan이 다시 편지를 보내는 경우 답장도 감지하여 캠페인을 종료합니다.

## 전자 메일 첨부 파일을 추적하는 방법 {#how-to-track-your-email-attachments}

Sales Connect는 첨부 파일(.doc, .ppt, .pdf)에 대한 추적 기능을 제공하여 첨부 파일이 열리거나 다운로드되는 시점을 확인하고 수신자가 어떤 페이지를 보고 있는지 확인할 수 있습니다. 추적 가능한 첨부 파일 기능을 두 사이트에서 사용할 수 있습니다 [웹 애플리케이션](https://toutapp.com/login) 및 Gmail(또는 Google 앱)을 사용하여 제품에서 사용할 수 있습니다.

>[!NOTE]
>
>첨부 파일 추적은 팀 플랜(g3startup plan부터 시작)에만 사용할 수 있습니다.

**첫 번째 추적 가능한 첨부 파일을 보내는 방법**

1. 이메일을 작성하거나 템플릿을 편집한 다음 **컨텐츠** 버튼을 클릭합니다.

1. 첨부 파일을 업로드하고 발송합니다. PDF, Word 문서 및 Powerpoint 프레젠테이션을 지원합니다.

1. 선택 **전자 메일에 추가**.

1. 클릭 **보내기** 라이브 피드를 실행합니다. 수신자가 첨부 파일을 열고 페이지를 확인할 수 있습니다.

>[!TIP]
>
>첨부 파일을 추적하지 않으려면 파일 첨부 를 클릭하면 이 첨부 파일이 추적되지 않습니다.

## 보기 추적 작동 방식 {#how-view-tracking-works}

보내는 전자 메일 내에 보이지 않는 이미지를 배치하여 전자 메일 열기 횟수를 추적합니다.

누군가 전자 메일에 응답하지만 Sales Connect에서 해당 전자 메일을 보지 않았다고 말하는 경우, 수신자가 전자 메일 클라이언트 내에서 이미지를 활성화하지 않았을 가능성이 있습니다(즉, 이메일의 &quot;이미지를 다운로드하려면 여기를 클릭&quot; 메시지 클릭).

이메일에서 상태를 더 잘 추적하기 위한 몇 가지 팁입니다.

* 이메일에 이미지(로고 등)를 포함하면 수신자는 이미지를 통해 메시지를 볼 수 있습니다.
* 링크를 이메일에 동작 호출로 포함합니다.

## 표시된 대로 표시되지 않은 테스트 이메일 {#test-email-not-showed-as-viewed}

메시지를 다른 이메일 주소로 보내더라도 Adobe는 라이브 피드에서 자신에게 보낸 이메일을 보는 데 로그인하지 않습니다. Adobe의 추적은 장치 기반입니다. Sales Connect에 로그인한 컴퓨터를 사용하는 한 해당 활동을 필터링합니다.

이유는? Sales Connect는 스마트하며, 활성 사용자는 보낸 이메일을 볼 때마다 라이브 피드 활동에서 자신의 정보가 급증하면 Adobe를 용서하지 않습니다.

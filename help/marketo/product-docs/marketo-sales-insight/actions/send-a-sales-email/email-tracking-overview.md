---
description: 이메일 추적 개요 - Marketo 문서 - 제품 설명서
title: 이메일 추적 개요
exl-id: 89437d22-d739-45ea-8a2e-046a7de80379
feature: Sales Insight Actions
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '507'
ht-degree: 0%

---

# 이메일 추적 개요 {#email-tracking-overview}

## 회신 추적 작동 방식 {#how-reply-tracking-works}

답글 추적은 보내는 모든 이메일에 포함된 메시지 ID를 확인하여 수행됩니다. 모든 이메일에는 최고의 답글 추적을 가질 수 있는 고유한 메시지 ID가 포함되어 있습니다.

>[!PREREQUISITES]
>
>이메일 서버와의 연결: Sales Connect는 받은 편지함에 연결되어야 새 회신이 언제 도착했는지 알 수 있습니다. Sales Connect 계정이 Gmail에 연결되어 있어야 합니다. Outlook을 사용하는 경우 exchange 서버와 통합해야 합니다.

Sales Connect에서 잠재 고객의 이메일 회신을 추적할 수 없는 경우 회신 감지를 기반으로 캠페인을 중단하거나 Salesforce에 회신을 기록할 수 없습니다. 회신할 수 있는 이메일 주소는 무엇입니까?

즉, flynn@flynnsarcade.com으로 이메일을 보내고 kevinf@flynnsarcade.com으로 답장을 보내면 답장을 추적할 수 있습니다. 또한 flynn@flynnsarcade.com 및 CC alan@encom.com으로 이메일을 보내고 Alan이 회신을 보내면 회신도 감지하여 캠페인을 종료합니다.

## 이메일 첨부 파일을 추적하는 방법 {#how-to-track-your-email-attachments}

Sales Connect는 첨부 파일(.doc, .ppt, .pdf)에 대한 추적을 제공하여 언제 열렸는지 그리고 수신자가 어떤 페이지를 통해 보고 있는지 확인할 수 있습니다. [웹 응용 프로그램](https://toutapp.com/login)과 Gmail(또는 Google 앱) 모두에서 추적 가능한 첨부 파일 기능을 사용할 수 있습니다.

>[!NOTE]
>
>첨부 파일 추적은 팀 계획(g3startup 계획부터)에만 사용할 수 있습니다.

**추적할 수 있는 첫 번째 첨부 파일을 보내는 방법**

1. 전자 메일을 작성하거나 템플릿을 편집한 다음 **콘텐츠** 단추를 클릭합니다.

1. 첨부 파일을 업로드하고 전송합니다. PDF, Word 문서 및 Powerpoint 프레젠테이션을 지원합니다.

1. **전자 메일에 추가**&#x200B;를 선택합니다.

1. **보내기**&#x200B;를 클릭하고 Live Feed를 실행합니다. 수신자가 첨부 파일을 열고 페이지를 클릭하면 수신자가 표시됩니다.

>[!TIP]
>
>첨부 파일을 추적하지 않으려면 파일 첨부 를 클릭하면 이 첨부 파일이 추적되지 않습니다.

## 보기 추적 작동 방식 {#how-view-tracking-works}

보내는 이메일 내에 보이지 않는 이미지를 배치하여 이메일 열림을 추적합니다.

누군가가 이메일에 응답하지만 Sales Connect가 보이지 않았다고 답하는 경우 수신자가 이메일 클라이언트 내에서 이미지를 활성화하지 않았을 가능성이 높습니다(즉, 이메일의 &quot;이미지를 다운로드하려면 여기를 클릭하십시오&quot; 메시지 클릭).

이메일에서 더 나은 추적 통계를 얻기 위한 몇 가지 팁:

* 이메일에 이미지(로고 등)를 포함시키면 수신자는 이미지를 통해 메시지를 볼 수 있습니다.
* 이메일에 콜 투 액션으로 링크를 포함합니다.

## 테스트 이메일이 조회함으로 표시되지 않음 {#test-email-not-showed-as-viewed}

다른 이메일 주소로 메시지를 보낸 경우에도 Live Feed에 자신에게 보낸 이메일을 보는 것으로 기록되지 않습니다. 추적은 장치를 기반으로 합니다. Sales Connect에 로그인한 컴퓨터를 사용하는 한 해당 활동을 필터링합니다.

그 이유? Sales Connect는 스마트하므로 활성 사용자가 보낸 이메일을 볼 때마다 라이브 피드 활동에 자신의 정보가 표시되는 경우 절대 용서하지 않습니다.

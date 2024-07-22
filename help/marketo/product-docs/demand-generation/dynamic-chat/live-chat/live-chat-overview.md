---
description: 라이브 채팅 개요 - Marketo 문서 - 제품 설명서
title: 라이브 채팅 개요
feature: Dynamic Chat
exl-id: 44e8b249-b534-4cec-a612-daa184acd266
source-git-commit: 14ccfe39059b9c900a5e5e00b082146bb500d79d
workflow-type: tm+mt
source-wordcount: '665'
ht-degree: 0%

---

# 라이브 채팅 개요 {#live-chat-overview}

라이브 채팅을 사용하면 웹 사이트 방문자가 판매 에이전트와 실시간 채팅 대화를 나눌 수 있습니다.

>[!NOTE]
>
>Dynamic Chat 선택 패키지에 있는 사용자의 경우, 라이브 채팅은 100회 참여 수명 제한이 있는 체험판 기능입니다. 이 한도에 도달하면 라이브 에이전트와의 채팅을 요청하는 방문자는 연결되지 않고 대신 글로벌 대체 메시지를 받게 됩니다. 한도를 높이려면 Adobe 계정 담당자에게 문의하여 패키지 업그레이드 옵션에 대해 논의하십시오.

## 라이브 채팅 에이전트 추가 {#add-live-chat-agents}

라이브 채팅을 시작하려면 라이브 채팅 에이전트를 [Adobe Admin Console의 사용자](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#add-a-chat-user){target="_blank"}로 추가하고 [라이브 채팅 권한](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md){target="_blank"}을 부여해야 합니다. 이 작업이 완료되면 새 대화 상자 또는 기존 대화 상자에 [실시간 채팅 카드](#using-the-live-chat-card)를 추가할 수 있습니다.

방문자가 대화 상자를 통해 에이전트와 채팅을 요청하면 에이전트에는 여러 [알림 옵션](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md#live-chat-notifications){target="_blank"}이 있습니다. 알림을 클릭하면 방문자와 대화를 시작할 수 있는 [에이전트 받은 편지함](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"}(으)로 이동합니다.

>[!NOTE]
>
>라이브 에이전트 아바타는 에이전트의 Adobe 계정 프로필에서 프로필 사진을 사용합니다. 이미지를 업데이트하려면 [다음 단계](https://helpx.adobe.com/manage-account/using/edit-adobe-account-personal-profile.html){target="_blank"}를 따르십시오.

## 라이브 채팅 카드 사용 {#using-the-live-chat-card}

방문자가 실시간 에이전트와 채팅하도록 하려면 [Designer 스트리밍](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/stream-designer.md){target="_blank"}에서 실시간 채팅 카드를 사용하십시오.

![](assets/live-chat-overview-1.png)

>[!IMPORTANT]
>
>라이브 채팅 카드는 항상 분기의 마지막 카드여야 합니다. 카드를 지점 내 임의의 지점에 배치하면 갑자기 에이전트와 연결해 방문자를 놀라게 할 수 있다.

### 우수 사례 {#best-practices}

* 라이브 채팅 카드 앞에 있는 질문 카드를 사용하여 방문자에게 연결 여부를 물어봅니다.
* 방문자가 연결에 동의한 후 정보 캡처 카드를 사용하여 이름/성, 이메일 주소, 직책 등과 같은 일부 정보를 수집합니다. (최소 이름 및 이메일 주소를 요청하는 것이 좋습니다.)

## 라이브 채팅 카드 옵션 {#live-chat-card-options}

스트림에서 라이브 채팅 카드를 클릭하면 방문자가 라우팅되는 방법을 선택할 수 있습니다. 라운드 로빈, 에이전트, 사용자 정의 규칙 또는 팀 중에서 선택합니다.

![](assets/live-chat-overview-2.png)

<table> 
 <tbody> 
  <tr> 
   <td><b>라운드 로빈</b></td>
   <td>채팅은 에이전트에 순차적으로 할당됩니다.</td>
  </tr> 
  <tr> 
   <td><b>에이전트</b></td>
   <td>채팅을 받을 특정 에이전트를 선택합니다.</td>
  </tr>
    <tr> 
   <td><b>사용자 지정 규칙</b></td>
   <td>방문자를 라우팅할 위치를 고려할 때 모든 사용자 지정 규칙이 순환됩니다. 방문자가 사용자 지정 규칙에 적합하지 않으면 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-management.md#live-chat-fallback" target="_blank">라이브 채팅 대체 메시지</a>를 받습니다.</td>
  </tr> 
  <tr> 
   <td><b>팀</b></td>
   <td>채팅을 받을 특정 팀을 선택하십시오. 이 옵션을 선택하면 해당 팀 내에 라운드 로빈이 할당됩니다.</td>
  </tr>
 </tbody> 
</table>

## 라이브 채팅 알림 {#live-chat-notifications}

>[!IMPORTANT]
>
>라이브 채팅에 대한 브라우저 알림을 받으려면 모든 라이브 채팅 에이전트가 메시지가 표시되면 Dynamic Chat에 대한 브라우저 알림을 활성화해야 합니다.

### 알림 활성화 {#enabling-notifications}

라이브 채팅 에이전트가 로그인하면 화면 상단에 &quot;라이브 채팅 알림을 받으려면 브라우저 알림을 활성화하십시오.&quot;라는 배너가 표시됩니다. **사용**&#x200B;을 클릭합니다.

![](assets/live-chat-overview-4.png)

그러면 실시간 채팅 에이전트가 알림을 표시하도록 브라우저에서 메시지를 표시합니다. **허용**&#x200B;을 클릭합니다.

![](assets/live-chat-overview-5.png)

에이전트가 브라우저에서 허용한 후에도 브라우저 알림을 받지 않는 경우 OS 알림 설정에서 브라우저에 대한 알림을 활성화해야 할 수 있습니다.

Mac의 [단계](https://support.apple.com/guide/mac-help/change-notifications-settings-mh40583/mac){target="_blank"}

[Windows용 단계](https://support.microsoft.com/en-us/windows/change-notification-settings-in-windows-8942c744-6198-fe56-4639-34320cf9444e){target="_blank"}

### 실시간 채팅이 에이전트에게 라우팅되는 경우 {#when-a-live-chat-is-routed-to-an-agent}

실시간 채팅이 에이전트에게 라우팅되면 화면 맨 위에 수락하라는 파란색 배너가 표시됩니다.

![](assets/live-chat-overview-3.png)

>[!TIP]
>
>또한 Dynamic Chat 알림을 설정할 수 있는 옵션도 있습니다. 이 옵션은 브라우저에 로그인하지 않은 경우 알림을 제공합니다.
>
>* [Google Chrome](https://support.google.com/chrome/answer/3220216?hl=en&amp;co=GENIE.Platform%3DDesktop){target="_blank"}에서 브라우저 알림 사용
>* [Mozilla Firefox](https://support.mozilla.org/en-US/kb/push-notifications-firefox){target="_blank"}에서 브라우저 알림 사용

### 참고할 사항 {#things-to-note}

* 상담원은 &quot;채팅 수락&quot; 메시지가 시간 초과되기 전에 45초 동안 응답할 수 있습니다. 이후 방문자는 [대체 메시지](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/agent-management.md#live-chat-fallback){target="_blank"}를 받게 됩니다. 라우팅 옵션이 **Team**(으)로 설정된 Dynamic Chat Prime 구독자의 경우 대체 메시지가 나타나기 전에 에이전트를 하나 더 시도합니다.
* 현재 에이전트당 라이브 채팅 수는 10개로 제한됩니다.

>[!MORELIKETHIS]
>
>[에이전트 받은 편지함](/help/marketo/product-docs/demand-generation/dynamic-chat/live-chat/agent-inbox.md){target="_blank"}

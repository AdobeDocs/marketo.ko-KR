---
description: 콜백 함수 - Marketo 문서 - 제품 설명서
title: 콜백 함수
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 30deeb59cd70b42af38cd1e047833394f9341a5c
workflow-type: tm+mt
source-wordcount: '623'
ht-degree: 3%

---

# 콜백 함수 {#callback-functions}

Dynamic Chat 위젯 콜백 함수를 사용하여 대화 이벤트를 서드파티 플랫폼으로 보낼 수 있습니다.

## 시작하기 {#getting-started}

이 이벤트는 Dynamic Chat 위젯을 사용할 준비가 되었음을 나타내며 Dynamic Chat과 관련된 모든 스크립트가 웹 페이지에 로드될 때 실행됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    // code here will execute when chatbot scripts are loaded in a webpage 
});
```

## 대화 이벤트 {#conversation-events}

이러한 이벤트는 특정 방문자의 특정 페이지를 대상으로 하는 대화와 관련이 있습니다.

### 대화가 트리거됨

웹 사이트 방문자를 대상으로 하는 대화(예: 대화)가 해결되고 챗봇이 표시됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 

    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
// code here will execute when chatbot is loaded for a visitor 
   });
});
```

### 대화 참여 {#conversation-engaged}

방문자가 챗봇과 참여(예: 첫 번째 응답 제공)했습니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_ENGAGED, (event) => { 
 // code here will execute when visitor engages with chatbot 
    });
});
```

### 대화 완료됨 {#conversation-completed}

방문자가 대화의 끝에 도달했습니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_COMPLETED, (event) => { 
 // code here will execute when conversation is completed 
    });
});
```

### 대화 종료됨

방문자가 종료되기 전에 대화를 닫았습니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_CLOSED, (event) => { 
 // code here will execute when conversation is closed 
    });
});
```

이벤트의 &#39;event&#39; 인수가 대화와 관련된 메타데이터가 있는 개체입니다. event.data별로 메타데이터에 액세스할 수 있습니다.

다음은 액세스할 수 있는 몇 가지 주요 메타데이터 값입니다.

<table>
<thead>
  <tr>
    <th style="width:75%">메타데이터</th>
    <th style="width:25%">속성</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화 이름</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>대화 ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>대화 유형(대화/대화 흐름)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI 유형(팝업/챗봇/인라인)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>세션 ID</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## 방문자 입력 이벤트

이러한 이벤트는 대화에 참여하는 방문자가 연락처 정보(예: 전화 번호 또는 이메일 주소)를 제공할 때 트리거됩니다. 다음은 이 범주에 속하는 이벤트입니다.

### 전화번호 {#phone-number}

이 이벤트는 대화 중에 방문자가 전화 번호를 제공할 때 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_INPUT_PHONE, (event) => { 
  // code here will execute when a visitor provides their phone number 
    }); 
}); 
```

### 이메일 ID {#email-id}

이 이벤트는 대화 중에 방문자가 이메일 주소를 제공할 때 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_INPUT_EMAIL, (event) => { 
 // code here will execute when a visitor provides their email address 
    }); 
});
```

이벤트의 &#39;event&#39; 인수가 대화와 관련된 메타데이터가 있는 개체입니다. event.data별로 메타데이터에 액세스할 수 있습니다.

다음은 액세스할 수 있는 몇 가지 주요 메타데이터 값입니다.

<table>
<thead>
  <tr>
    <th style="width:75%">메타데이터</th>
    <th style="width:25%">속성</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화 이름</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>대화 ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>대화 유형(대화/대화 흐름)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI 유형(팝업/챗봇/인라인)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>세션 ID</td>
    <td>payload.sid</td>
  </tr>
</tbody>
</table>

## 모임 예약 이벤트 {#meeting-booking-events}

이러한 이벤트는 방문자가 비즈니스 담당자와 회의를 예약할 때 트리거됩니다.

다음은 이 범주에 속하는 이벤트입니다.

### 예약된 회의 {#meeting-booked}

이 이벤트는 방문자가 에이전트의 캘린더에서 모임을 예약할 때 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_MEETING_BOOKED, (event) => { 
 // code here will execute when a meeting is booked 
    }); 
});
```

이벤트의 &#39;event&#39; 인수가 대화와 관련된 메타데이터가 있는 개체입니다. event.data별로 메타데이터에 액세스할 수 있습니다.

다음은 액세스할 수 있는 몇 가지 주요 메타데이터 값입니다.

<table>
<thead>
  <tr>
    <th style="width:75%">메타데이터</th>
    <th style="width:25%">속성</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화 이름</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>대화 ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>대화 유형(대화/대화 흐름)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI 유형(팝업/챗봇/인라인)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>세션 ID</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>에이전트 이름</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>에이전트 ID</td>
    <td>payload.agentID</td>
  </tr>
  <tr>
    <td>모임 정보</td>
    <td>payload.meetingInfo</td>
  </tr>
</tbody>
</table>

## 라이브 채팅 이벤트 {#live-chat-events}

이러한 이벤트는 방문자가 챗봇과 참여하는 동안 라이브 에이전트와 연결할 때 트리거됩니다.

다음은 이 범주에 속하는 이벤트입니다.

### 라이브 채팅 요청됨 {#live-chat-requested}

이 이벤트는 방문자가 라이브 에이전트와 채팅하도록 옵션을 선택하고 사용 가능한 에이전트를 해결하는 경우 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUESTED, (event) => { 
 // code here will execute when a visitor requests for live chat 
    }); 
});
```

### 라이브 채팅 시작됨 {#live-chat-initiated}

이 이벤트는 방문자가 라이브 에이전트와 채팅하도록 옵션을 선택하고 에이전트가 채팅을 수락하면 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_INITIATED, (event) => { 
 // code here will execute after a live agent accepted the chat 
    }); 
});
```

### 라이브 채팅 종료됨 {#live-chat-ended}

이 이벤트는 방문자와 라이브 에이전트 간의 대화가 종료될 때 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_ENDED, (event) => { 
 // code here will execute when a live chat is ended 
    }); 
});
```

### 라이브 채팅 시간 초과 {#live-chat-timeout}

이 이벤트는 방문자가 응답을 중지하거나 삭제되어 라이브 채팅 대화 시간이 초과되면 트리거됩니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_LIVE_CHAT_REQUEST_TIMEOUT, (event) => { 
 // code here will execute when a visitor abandoned live chat 
    }); 
});
```

이벤트의 &#39;event&#39; 인수가 대화와 관련된 메타데이터가 있는 개체입니다. event.data별로 메타데이터에 액세스할 수 있습니다.

다음은 액세스할 수 있는 몇 가지 주요 메타데이터 값입니다.

<table>
<thead>
  <tr>
    <th style="width:75%">메타데이터</th>
    <th style="width:25%">속성</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화 이름</td>
    <td>payload.name</td>
  </tr>
  <tr>
    <td>대화 ID</td>
    <td>payload.id</td>
  </tr>
  <tr>
    <td>대화 유형(대화/대화 흐름)</td>
    <td>payload.type</td>
  </tr>
  <tr>
    <td>UI 유형(팝업/챗봇/인라인)</td>
    <td>payload.uiType</td>
  </tr>
  <tr>
    <td>세션 ID</td>
    <td>payload.sid</td>
  </tr>
  <tr>
    <td>에이전트 이름</td>
    <td>payload.agentName</td>
  </tr>
  <tr>
    <td>에이전트 ID</td>
    <td>payload.agentID</td>
  </tr>
</tbody>
</table>

이러한 이벤트를 Adobe Analytics 또는 Google Analytics과 같은 서드파티 플랫폼으로 보내려면 이러한 Dynamic Chat 이벤트 내에 해당 추적 호출을 추가해야 합니다. 아래 예와 같은 모습일 것입니다.

```javascript
window.addEventListener('adobedx.conversations.ready', () => { 
    addListener(Enum.Events.CONVERSATION_TRIGGERED, (event) => { 
 // Enter Adobe Analytics or Google Analytics function here 
    ga('send', 'event', { 
      eventCategory: Dynamic Chat Conversations', 
      eventAction: 'Conversation Triggered', 
      eventLabel: event.data.payload.id, 
    }); 
    }); 
});
```

---
description: Dynamic Chat 릴리스 노트 - Marketo 문서 - 제품 설명서
title: Dynamic Chat 릴리스 노트
hide: true
hidefromtoc: true
feature: Release Information, Dynamic Chat
exl-id: 0447dc47-b9c5-42e1-8f66-73bf67c7871d
source-git-commit: e2fcd5587df8776a07b092cd03f081a88480353e
workflow-type: tm+mt
source-wordcount: '1193'
ht-degree: 0%

---

# Dynamic Chat 릴리스 노트 {#dynamic-chat-release}

Adobe Dynamic Chat 릴리스는 기능 배포에 대한 보다 확장 가능한 접근 방식을 고려하는 연속 제공 모델에서 작동합니다. 한 달에 릴리스가 여러 개인 경우가 있으므로 정기적으로 최신 정보를 확인하십시오.

Marketo Engage을 위한 표준 릴리스 노트 페이지 [은(는) 여기에서 찾을 수 있음](/help/marketo/release-notes/current.md){target="_blank"}.

## 2024년 4월 릴리스 {#april-release}

**릴리스 날짜: 2024년 4월 16일**

### 이제 선택 패키지의 사용자가 대화형 흐름을 사용할 수 있습니다. {#conversational-flows-select-package}

작년에 대화형 플로우를 릴리스했을 때 Dynamic Chat 선택 패키지의 사용자는 100개의 라이프타임 참여 평가판으로만 기능을 활용할 수 있었습니다. 이제 Select 패키지의 모든 사용자가 대화형 흐름을 완전히 사용할 수 있습니다.

대화 흐름 참여는 Select 패키지에서 사용자의 참여 대화 월별 제한인 250개에 포함됩니다.

### 콜백 함수 {#callback-functions}

콜백 함수를 사용하면 방문자가 Dynamic Chat 대화를 나눌 때 Adobe Analytics 또는 Google Analytics과 같은 외부 시스템에서 Dynamic Chat 분석 이벤트를 수집할 수 있습니다. 이벤트를 수신할 API에 콜백을 등록하여 Dynamic Chat 분석 이벤트를 활성화합니다. 이를 통해 웹 트래픽과 같은 다른 주요 데이터와 연관되므로 Dynamic Chat 참여를 보다 전체적으로 파악할 수 있습니다.

### 조건부 분기에 라이브 에이전트 가용성 조건 추가됨 {#live-agent-availability-conditional-branching}

이제 기본 및 사용자 지정 Marketo Engage 필드 외에도 조건부 분기를 사용하여 에이전트 가용성에 따라 분기를 만들 수 있습니다. 이 기능은 사용 가능한 라이브 에이전트가 있을 때 방문자에게 라이브 에이전트와 대화할 수 있는 옵션만 제공하려는 경우에 유용합니다.

![](assets/dynamic-chat-release-1.png)

### 조건부 분기에 스마트 목록 조건이 추가됨 {#smart-list-condition}

조건부 분기에서 새 Marketo Engage 스마트 목록 조건을 추가하면 Dynamic Chat에서 대상 분기 조건을 정의하는 대신 Marketo Engage에서 이미 만든 기존 대상을 기반으로 분기를 만들 수 있습니다.

![](assets/dynamic-chat-release-2.png)

### 대화형 흐름에 대한 조건부 분기 {#conditional-branching-for-conversational-flows}

올해 초 대화 상자에 대한 조건부 분기를 출시했으며, 이제 대화 흐름에서도 조건부 분기를 활용할 수 있습니다! 조건부 분기를 사용하면 다양한 조건을 기반으로 플로우에서 분기를 만들 수 있습니다.

### 대화 흐름에 대한 라이브 채팅 {#live-chat-for-conversational-flows}

2023년에 대화 상자에 대한 라이브 채팅 기능이 릴리스되었으며 이제 대화 흐름에 라이브 채팅 참여를 추가할 수 있습니다. 이제 Marketo Engage 양식과 함께 대화형 흐름을 사용하는 경우, 양식 제출 직후 자격을 갖춘 방문자가 라이브 에이전트와 채팅하도록 허용할 수 있습니다.

### 에이전트 받은 편지함의 최근 Marketo Engage 활동 {#recent-marketo-engage-activities-in-agent-inbox}

최근 Marketo Engage 활동을 에이전트 받은 편지함의 최근 활동 섹션에 추가했으므로 사이트 방문자가 에이전트와의 채팅을 요청할 때 에이전트는 방문자가 최근에 다음 Marketo Engage 활동을 했는지(최근 25개 활동) 여부를 빠르게 확인할 수 있습니다.

* 이메일 열림
* 방문한 웹 페이지
* 작성된 양식
* “즐거운 순간”이 있었음

![](assets/dynamic-chat-release-3.png)

### 에이전트 관리의 캘린더 연결 상태 {#calendar-connection-status-in-agent-management}

이제 관리자는 회의 예약 권한이 있는 에이전트가 Dynamic Chat에서 캘린더를 연결했는지 쉽게 확인할 수 있습니다. 이렇게 하면 전체 영업팀이 연결되어 있고 Dynamic Chat의 회의 요청을 수락할 준비가 되었는지 확인할 수 있습니다.

![](assets/dynamic-chat-release-4.png)

### 에이전트 달력 구성의 최소 알림 설정 {#minimum-notice-setting-in-agent-calendar-configuration}

사용자가 웹 방문자가 10분 정도의 고급 알림으로 캘린더에서 모임을 예약한다고 보고했으므로 에이전트 캘린더 구성에 최소 알림 설정을 도입하고 기본 리드 타임을 24시간으로 설정했습니다.

![](assets/dynamic-chat-release-5.png)

### 사용자 동작 추가/제거 업데이트됨 {#add-remove-user-behavior-updated}

일부 사용자가 Dynamic Chat에서 에이전트를 추가 및 제거하는 데 문제가 있다고 표시했기 때문에 이러한 문제를 해결하기 위해 몇 가지 사항을 변경했습니다.

사용자가 라이브 채팅 또는 모임 예약 권한이 있는 Admin Console에 추가되면 에이전트 관리 목록에 즉시 표시되고 대화 상자, 대화 흐름, 라우팅 규칙 및 팀에 추가할 수 있습니다.

모임 예약 또는 라이브 채팅 권한이 있는 사용자가 Admin Console에서 제거되면 Dynamic Chat에서 즉시 제거되고, 더 이상 라이브 채팅 또는 모임 라우팅에 사용할 수 없으며, 더 이상 라이선스 제한에 포함되지 않습니다.

### 향상된 대화 수준 보고서 성능 {#improved-conversation-level-report-performance}

이제 개별 대화 상자 및 대화 흐름 수준 보고서의 성능이 향상되고 정확해졌습니다. 이전에는 대화 상자 보고서를 로드하는 데 몇 초 정도 소요될 수 있었고 데이터가 때때로 글로벌 성능 보고서와 일치하지 않았습니다. 이제 개별 대화 상자 보고서가 순식간에 로드되고 데이터가 항상 글로벌 보고 데이터와 정렬됩니다.

![](assets/dynamic-chat-release-6.png)

### 권한 업데이트 {#permission-updates}

보다 직관적인 권한 관리를 위해 Adobe Admin Console의 권한 구조 및 이름 지정을 정리했습니다.

* 이제 &#39;대화 관리&#39; 범주를 &#39;대화&#39;라고 합니다.
* 이제 &#39;모임&#39; 범주를 &#39;활동&#39;이라고 합니다.
* 이제 &#39;에이전트 설정&#39; 범주를 &#39;에이전트&#39;라고 합니다.
* 이제 &#39;관리자 설정&#39; 범주를 &#39;구성&#39;이라고 합니다.
* &#39;라이브 채팅&#39; 범주가 제거되었으며 모든 라이브 채팅 권한이 에이전트 범주로 이동되었습니다.

![](assets/dynamic-chat-release-7.png)

### 에이전트 받은 편지함에서 하이퍼링크 지원 {#support-for-hyperlinks-in-agent-inbox}

이제 라이브 채팅 에이전트가 채팅에서 방문자와 URL을 공유할 때 이러한 URL이 하이퍼링크되므로 방문자가 URL을 복사하여 브라우저에 붙여넣을 필요 없이 해당 URL을 클릭하여 페이지로 이동할 수 있습니다.

### 에이전트 받은 편지함에서 업데이트된 키 동작 입력 {#enter-key-behavior-updated-in-agent-inbox}

에이전트 받은 편지함에서 반환 키 동작이 전환되었으므로 Return 또는 Enter 키를 누르면 메시지가 전송되고 Shift+Enter를 누르면 줄 바꿈이 만들어집니다.

![](assets/dynamic-chat-release-8.png)

### 라운드 로빈 페이지 제거됨 {#round-robin-page-removed}

걱정 마! 라운드 로빈 라우팅은 여전히 완벽하게 작동하며 항상 작동하는 방식으로 작동합니다. 라운드 로빈 라우팅 큐에서 종종 부정확한 에이전트 목록과 순서를 보여주는 페이지를 제거했습니다.

2022년 Dynamic Chat 출시 당시에는 라이브 채팅에 대한 지원이 없었고, 모임 예약만 지원되었으며, 라운드 로빈 라우팅 페이지는 모임 예약만을 염두에 두고 설계되었습니다. 작년에 라이브 채팅이 도입되면서, 라운드 로빈 페이지는 모임 예약 및 라이브 채팅 권한이 모두 있는 에이전트 간의 라운드 로빈 라우팅의 보다 복잡한 특성을 정확하게 반영하지 않아 더 이상 사용되지 않게 되었습니다. 이를 해결하기 위해 몇 가지 다른 옵션을 살펴보았지만, 궁극적으로 혼동을 최소화하기 위해 모두 제거하는 것이 최선의 선택이라고 결정했습니다.

![](assets/dynamic-chat-release-9.png)

## 2024년 2월 릴리스 {#february-release}

**릴리스 날짜: 2024년 2월 22일**

### 대화 페이지 {#conversations-page}

새로운 대화 페이지에서는 알려진 리드와 익명 리드 모두에서 인스턴스에 대해 발생한 모든 대화(자동화된 라이브)의 대본을 볼 수 있는 원스톱 샵을 제공하여 고객이 대화, 대화 흐름 및 라이브 에이전트에 어떻게 참여하는지를 보다 잘 파악할 수 있습니다.

![](assets/dynamic-chat-release-10.png)

### 글로벌 대시보드의 날짜 범위가 90일에서 24개월로 늘어남 {#date-range-in-global-dashboard}

당신이 물어보고 배달을 했어요. 이제 모든 분석 대시보드에서 최대 2년 동안의 Dynamic Chat 참여 데이터를 볼 수 있습니다.

### 대화 상자의 조건부 분기 {#conditional-branching-in-dialogues}

조건부 분기를 사용하면 다양한 조건을 기반으로 대화 상자 흐름에서 분기를 만들 수 있습니다. 이제 Marketo Engage의 리드 및 회사 속성에 따라 동일한 대화 상자의 다른 사용자에게 다른 컨텐츠를 제공할 수 있습니다.

## 2024년 1월 릴리스 {#january-release}

**릴리스 날짜: 2024년 1월 24일**

### 에이전트 관리의 동시 라이브 채팅 제한 설정 {#Concurrent-live-chat-limit-setting}

기본적으로 인스턴스의 각 라이브 채팅 에이전트는 한 번에 최대 5개의 라이브 채팅 세션에 참여할 수 있습니다. 에이전트 관리에 이 제한을 1에서 10으로 조정할 수 있는 새로운 설정이 도입되었습니다.

![](assets/dynamic-chat-release-11.png)
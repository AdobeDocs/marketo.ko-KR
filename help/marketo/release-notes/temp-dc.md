---
description: Dynamic Chat 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: Dynamic Chat 릴리스 정보
feature: Release Information, Dynamic Chat
hide: true
hidefromtoc: true
exl-id: 12130dee-2dbf-4e71-b542-30d4732b1067
source-git-commit: cc8de935451fe5d6dc9c8dad19962391d8ed3535
workflow-type: tm+mt
source-wordcount: '495'
ht-degree: 2%

---

# 임시 Dynamic Chat 릴리스 노트 {#dynamic-chat-release}

## 2024년 9월/10월 릴리스 {#august-release}

### 향상된 라이브 채팅 분석 {#enhanced-live-chat-analytics}

다음을 포함하여 Analytics 대시보드에 대한 몇 가지 개선 사항이 이루어졌습니다.

* 요청된 총 라이브 채팅 수: &quot;에이전트와의 채팅&quot;을 요청한 방문자 수

* 연결된 총 라이브 채팅: 연결된 방문자 수와 &quot;에이전트와의 채팅&quot;을 요청한 총 방문자 수

* 누락된 총 라이브 채팅 요청 수: 무인 방문자와 &quot;에이전트와의 채팅&quot;에 대해 요청한 총 방문자 수

* 평균 채팅 길이(분): 방문자와 에이전트 간의 &quot;평균 채팅 길이&quot;를 분석합니다.

* 평균 에이전트 응답 시간(초): 에이전트가 라이브 채팅 Q&amp;A에 응답하는 데 걸린 &quot;평균 시간&quot;을 분석합니다.

* 일별 대시보드: 라이브 채팅 요청이 정상적으로 연결됨, 라이브 채팅 요청이 누락됨, 최근 라이브 채팅 활동을 정렬 및 필터링함

스크린샷

### 대화 점수 {#conversation-scoring}

채팅 상호 작용의 품질을 기반으로 리드를 수치화하고 해당 지표를 Marketo Engage 스마트 캠페인의 트리거/필터로 사용합니다. 다음 활동에서 새 특성 _대화 점수_&#x200B;를 사용하십시오.

* 대화 참여
* 대화 흐름에 참여
* 에이전트와 참여

**참고할 사항:**

* 점수 값은 0, 1, 2, 3부터 시작됩니다(기본값은 null).

* 대화가 완료 또는 삭제되면 활동에서 채점 값을 저장하고 편집할 수 없다는 게시물을 표시합니다   ????? (이 문장은 무엇을 의미합니까)

* 점수 설정:

   * 에이전트 받은 편지함에서 - 라이브 채팅 중에 에이전트는 대화 활동에 저장된 대화에 대한 점수를 업데이트하거나 설정할 수 있습니다

   * 스트림 디자이너 - 목표 카드에서 사용자는 대화에 대한 점수를 업데이트하거나 설정할 수 있습니다

스크린샷

스크린샷

스크린샷

### 새로운 잠재 고객 생성 논리 {#new-lead-creation-logic}

잠재 고객이 전자 메일 `abc@test.com`을(를) 사용하여 양식을 작성하고 xyz로 쿠키가 작성되면 나중에 전자 메일 `def@test.com`을(를) 사용하여 동일한 양식을 작성하고 새 잠재 고객이 생성되지만 쿠키 xyz가 새 잠재 고객과 연결되고 잠재 고객 `abc@test.com`에서 제거됩니다.

그 이후부터 `abc@test.com`은(는) 쿠키가 없는 잠재 고객이 됩니다. 익명 잠재 ??

따라서 쿠키 abc를 사용하는 방문자가 페이지에 도달하여 전자 메일 ID를 `abc@test.com`(으)로 제공하는 경우:

표

### 최적화된 대화 흐름 로드 시간 {#optimized-conversation-flow-load-time}

사용자 경험을 개선하기 위해 이제 대화 흐름이 로드되는 동안 빈 공간 대신 쉬머 로더가 표시됩니다. 대화 또는 대화???

**이전**

GIF

**이후**

GIF

### 글꼴 상속 옵션 {#option-to-inherit-font}

이제 Dynamic Chat에서 브랜드 글꼴을 관리하는 대신 챗봇이 호스팅 중인 웹 페이지에서 글꼴을 직접 상속할 수 있습니다. 이 옵션을 활성화하면 챗봇이 페이지의 `<body>` 태그에 정의된 글꼴을 사용합니다.

스크린샷

### Demandbase와 Dynamic Chat 통합 {#demandbase-integration-with-dynamic-chat}

Demandbase 사용자는 자신의 Demandbase 라이선스를 가져와 통합을 활성화할 수 있습니다. 대화 상자 타겟팅, 조건부 브랜딩 및 사용자 지정 라우팅에는 Demandbase 사용자 특성을 사용합니다.

잠재 고객에 대한 이러한 속성 값의 해결은 실시간으로 수행되며 해당 잠재 고객 프로필에 저장됩니다.

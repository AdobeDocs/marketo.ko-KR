---
description: 에이전트 관리 - Marketo 문서 - 제품 설명서
title: 에이전트 관리
feature: Dynamic Chat
exl-id: 151d8cf2-a5b7-43c4-8418-cc22252108b2
source-git-commit: 42e2a23c1c451c61fd62237fd1305924b51437b2
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 1%

---

# 에이전트 관리 {#agent-management}

에이전트 관리에서 Dynamic Chat 인스턴스의 에이전트 목록을 보고, 팀을 관리하고, 대체 규칙을 설정합니다.

![](assets/agent-management-1.png)

## 상담원 {#agents}

이 탭에는 Dynamic Chat 인스턴스의 모든 에이전트가 나열되며 여기에는 이름, 이메일 주소, 라이브 채팅 상태 등의 정보가 포함됩니다.

![](assets/agent-management-2.png){width="800" zoomable="yes"}

>[!NOTE]
>
>_방금_&#x200B;에 추가한 에이전트가 표시되지 않습니까? Adobe Admin Console에서 추가한 후 여기에 표시되는 데 최대 2시간이 걸릴 수 있습니다.

## 팀 {#teams}

관리자는 에이전트 팀을 만들어 특정 영업 에이전트 그룹으로 쉽게 라우팅할 수 있습니다.

>[!AVAILABILITY]
>
>Teams에 액세스하려면 Dynamic Chat Prime 구독이 필요합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

![](assets/agent-management-3.png)

### 팀 만들기 {#create-a-team}

1. **+ 팀 만들기**&#x200B;를 클릭합니다.

   ![](assets/agent-management-4.png)

1. 팀에 이름을 지정하십시오.

   ![](assets/agent-management-5.png)

1. **에이전트 추가** 드롭다운을 클릭하고 원하는 에이전트를 선택합니다.

   ![](assets/agent-management-6.png)

1. **만들기**&#x200B;를 클릭합니다.

   ![](assets/agent-management-7.png)

## 대체 규칙 {#fallback-rules}

### 모임 대체 항목 {#meeting-fallback}

회의 예약을 사용할 수 없을 때 방문자가 볼 수 있도록 표준(시스템) 메시지를 선택하거나 사용자 지정 메시지를 작성하십시오.

![](assets/agent-management-8.png)

### 라이브 채팅 대체 {#live-chat-fallback}

표준(시스템) 메시지를 선택하거나 방문자가 Live Chat을 사용할 수 없을 때 볼 수 있도록 사용자 지정 메시지를 작성하십시오.

![](assets/agent-management-9.png)

>[!NOTE]
>
>* _모임 예약 옵션 포함_ 확인란을 선택하면 실시간 채팅을 사용할 수 있는 에이전트가 없을 때 채팅 방문자에게 모임을 예약할 수 있는 옵션이 제공됩니다.
>
>* **실시간 채팅 카드로서 사용자 지정 규칙/팀의 경우**: 에이전트를 확인하는 동안 해당 에이전트를 사용할 수 없거나 연결할 수 없는 경우 &quot;사용 가능한 에이전트&quot;(스트림에 배치된 라우팅 논리/규칙에 상관없이 해당 시점에 사용 가능한 모든 에이전트)를 사용하도록 시도하기 위해 라운드 로빈으로 돌아갑니다.

>[!TIP]
>
>사용자 지정 메시지를 만들 때 글꼴 스타일을 지정하고 링크를 사용하거나 이모지를 삽입할 수 있습니다. `:)`

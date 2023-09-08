---
description: Dynamic Chat 개요 - Marketo 문서 - 제품 설명서
title: Dynamic Chat 개요
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: b4ba55769034e8fb8a7878f52e21bd08e073fa8c
workflow-type: tm+mt
source-wordcount: '876'
ht-degree: 2%

---

# Dynamic Chat 개요 {#dynamic-chat-overview}

Dynamic Chat을 사용하면 사용하기 쉬운 인터페이스를 활용하여 웹 사이트를 방문하는 사용자와 계정을 모두 타겟팅할 수 있습니다. 이름, 연락처 정보 및 자유 텍스트와 같은 관련 콘텐츠를 수집합니다. 사이트 방문자는 영업 팀과의 회의를 예약할 수도 있습니다. Dynamic Chat 활동 및 참여 데이터를 사용하여 Marketo 프로그램에 멤버를 추가하고 크로스 채널 활동을 트리거할 수 있습니다.

>[!NOTE]
>
>Dynamic Chat은 점진적으로 롤아웃되는 과정에 있으며 현재 가용성이 제한되어 있습니다. 이 페이지는 사용 가능한 GA(일반 가용성) 세부 사항으로 업데이트됩니다.

>[!TIP]
>
>방문 [이 페이지](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dynamic-chat-overview.html) Dynamic Chat 자습서 비디오를 보십시오.

## 통합 {#integrations}

Dynamic Chat의 주요 구성 요소는 Marketo 구독과 기본적으로 상호 작용하는 기능입니다. 이 통합의 전체 기능을 활용하려면 먼저 데이터 동기화를 시작해야 합니다. Marketo 데이터베이스의 크기에 따라 초기 데이터의 경우 최대 24시간이 걸릴 수 있습니다. [1회 동기화](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/connect-dynamic-chat-to-marketo.md) 완료를 위해.

다음 항목이 동기화됩니다.

* 개인 필드 데이터
* 회사 필드 데이터
* 활동 데이터

## 대화 상자 {#dialogues}

대화 상자는 단일 채팅 참여를 나타냅니다. 웹 사이트 방문자에게 매력적인 채팅 대화 상자를 만드는 데 필요한 모든 기능이 포함된 컨테이너라고 생각해 보십시오. 각 대화 상자에서 대화 상자를 표시할 페이지, 표시할 대상, 대화 상자 자체의 내용 및 흐름을 지정할 수 있습니다. 또한 지표를 찾아 대화 상자의 성능을 확인할 수 있습니다. [대화 상자에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/dialogue-overview.md){target="_blank"}.

## 구성 {#configuration}

구성 탭에서 다양한 대화 상자의 모양과 느낌을 사용자 지정합니다. 글꼴, 색상, 응답 시간 등을 변경합니다! [구성에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/configuration.md){target="_blank"}.

## 캘린더 {#calendar}

챗봇에서 약속 예약에 사용할 Outlook 또는 Gmail 일정을 연결합니다. [캘린더에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/calendar.md){target="_blank"}

## 회의 {#meetings}

여기에서 다양한 대화 상자를 통해 웹 사이트 방문자가 예약한 모든 약속을 볼 수 있습니다. [모임에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/meetings.md){target="_blank"}

## 라우팅 {#routing}

여기에서 달력에 연결된 모든 에이전트 목록과 웹 사이트 방문자에게 제공될 순서 및 사용자 지정 라우팅 규칙을 만들 수 있습니다. [라우팅에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/appointment-scheduling/routing.md){target="_blank"}

## 라이브 채팅 {#live-chat}

라이브 채팅을 통해 자격을 갖춘 웹 방문자에게 영업 담당자와 연결할 수 있도록 하십시오. 문서에 연결

## FAQ {#faq}

**회사 웹 사이트의 어디에나 Dynamic Chat을 설치할 수 있습니까, 아니면 Marketo 랜딩 페이지에서만 작동합니까?**

Dynamic Chat JavaScript 코드 조각은 Marketo 랜딩 페이지뿐만 아니라 모든 웹 사이트에 설치할 수 있습니다.

**보고를 위해 데이터가 저장되는 기간은 얼마입니까?**

90일(전체 제한 목록 참조) [아래](#limits-in-dynamic-chat)).

**Dynamic Chat에서 라이브 채팅을 허용합니까?**

아니요, 미리 결정된 응답만 활용합니다.

**Dynamic Chat은 영어 외에 다른 언어를 지원합니까?**

예. Dynamic Chat은 프랑스어, 독일어, 일본어, 스페인어, 이탈리아어, 포르투갈어(브라질), 한국어, 중국어 간체 및 중국어 번체를 지원합니다. 다음에서 자세히 알아보기 [아래 섹션](#changing-the-language).

**AI/NLP 기능을 지원합니까?**

당사는 AI/NLP 기능을 지원하지 않습니다.

**익명의 사용자를 타깃팅하려면 어떻게 해야 합니까?**

대화 상자에서 _개인 이메일이 비어 있음_ 특성.

## 언어 변경 {#changing-the-language}

Dynamic Chat 언어를 변경하려면 다음 단계를 따르십시오.

>[!IMPORTANT]
>
>프로필 수준에서 언어를 변경하면 의 언어가 변경됩니다. _모두_ Experience Cloud 응용 프로그램입니다. Dynamic Chat이 아닙니다.

1. Experience Cloud 계정에서 설정 아이콘을 클릭하고 **환경 설정**.

   ![](assets/dynamic-chat-overview-1.png)

1. 전자 메일 주소 아래의 현재 언어를 클릭합니다.

   ![](assets/dynamic-chat-overview-2.png)

1. 새 언어(두 번째 언어는 선택 사항)를 선택하고 **저장**.

   ![](assets/dynamic-chat-overview-3.png)

   >[!NOTE]
   >
   >Dynamic Chat 선택할 수 있는 언어는 수십 개이지만 영어, 프랑스어, 독일어, 일본어, 스페인어, 이탈리아어, 포르투갈어(브라질), 한국어, 중국어 간체 및 중국어 번체만 지원합니다.

언어를 업데이트할 때 개인적으로 채운 단어(예: 스트림 응답)를 제외한 앱 자체의 모든 내용이 변경됩니다.

## Dynamic Chat 제한 {#limits-in-dynamic-chat}

<table>
  <th>매개 변수</th>
  <th>설명</th>
  <th>제한</th>
 <tr>
  <td>총 대화 상자</td>
  <td>대화 상자 수(게시됨 및 초안)</td>
  <td>500</td>
 </tr>
 <tr>
  <td>총 캘린더</td>
  <td>연결된 캘린더 수</td>
  <td>25</td>
 </tr>
 <tr>
  <td>총 사용자(관리자 및 마케팅 사용자)</td>
  <td>Dynamic Chat 인스턴스당 허용된 결합된 사용자 수</td>
  <td>50</td>
 </tr>
 <tr>
  <td>게시된 대화 상자</td>
  <td>저장된 게시된 대화 상자 수</td>
  <td>100</td>
 </tr>
 <tr>
  <td>대화 상자당 타겟 URL</td>
  <td>단일 대화 상자에 추가할 수 있는 Target URL 수</td>
  <td>20</td>
 </tr>
 <tr>
  <td>대화 상자당 속성</td>
  <td>단일 대화 상자의 대상 기준에 추가할 수 있는 속성 수입니다</td>
  <td>100</td>
 </tr>
 <tr>
  <td>그룹</td>
  <td>단일 대화 상자에 추가할 수 있는 그룹 수</td>
  <td>10</td>
 </tr>
 <tr>
  <td>그룹당 속성</td>
  <td>그룹에 추가할 수 있는 속성 수</td>
  <td>10</td>
 </tr>
 <tr>
  <td>카드</td>
  <td>대화 상자 당 캔버스에 추가할 수 있는 카드 수</td>
  <td>500</td>
 </tr>
 <tr>
  <td>익명 잠재 고객 데이터 유지 기간</td>
  <td>참여 없이 익명 잠재 고객의 정보가 유지되는 기간</td>
  <td>90일</td>
 </tr>
 <tr>
  <td>목표 활동 유지 기간</td>
  <td>목표 활동 데이터가 유지되는 시간</td>
  <td>24개월</td>
 </tr>
 <tr>
  <td>문서 활동 보존 기간</td>
  <td>문서 활동 데이터가 유지되는 시간</td>
  <td>24개월</td>
 </tr>
 <tr>
  <td>대화 상자 활동 유지 기간을 사용하여 상호 작용</td>
  <td>대화 상자 활동 데이터와 상호 작용한 시간이 유지됩니다.</td>
  <td>90일</td>
 </tr>
 <tr>
  <td>모임 예약 활동 유지 기간</td>
  <td>모임 예약 활동이 Dynamic Chat에 저장되는 시간</td>
  <td>24개월</td>
 </tr>
 <tr>
  <td>대화 참여</td>
  <td>월별 웹 방문자가 참여할 수 있는 채팅 대화 수</td>
  <td>250</td>
 </tr>
 <tr>
  <td>대화 트리거됨</td>
  <td>월별 웹 방문자에게 표시할 수 있는 채팅 대화 수</td>
  <td>25,000</td>
 </tr>
</table>

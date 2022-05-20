---
description: 동적 채팅 개요 - Marketo 문서 - 제품 설명서
title: 동적 채팅 개요
exl-id: 73ab651e-bb11-459d-aa6a-39d9e208d512
source-git-commit: ff34ef099f2af949602aa3220eb44e4494a6a7a9
workflow-type: tm+mt
source-wordcount: '896'
ht-degree: 1%

---

# 동적 채팅 개요 {#dynamic-chat-overview}

Dynamic Chat를 사용하면 사용하기 쉬운 인터페이스를 활용하여 웹 사이트를 방문하는 사용자와 계정을 모두 타겟팅할 수 있습니다. 이름, 연락처 정보 및 무료 텍스트와 같은 관련 컨텐츠를 수집합니다. 사이트 방문자는 영업 팀과 회의를 예약할 수도 있습니다. 동적 채팅 활동 및 참여 데이터를 사용하여 Marketo 프로그램에 구성원을 추가하고 크로스채널 활동을 트리거할 수 있습니다.

>[!NOTE]
>
>Dynamic Chat는 서서히 롤아웃되는 중입니다. 현재 제한된 가용성을 유지하고 있습니다. 이 페이지는 사용 가능한 GA(General Availability) 세부 정보로 업데이트됩니다.

>[!TIP]
>
>방문 [이 페이지](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dynamic-chat-overview.html) 다이내믹 채팅의 자습서 비디오를 보려면 다음을 수행하십시오.

## 통합 {#integrations}

Dynamic Chat의 주요 구성 요소는 Marketo 구독과 기본적으로 연결할 수 있는 기능입니다. 이 통합의 전체 기능을 활용하려면 먼저 데이터 동기화를 시작해야 합니다. Marketo 데이터베이스의 크기에 따라 초기 데이터 처리에 최대 24시간이 걸릴 수 있습니다. [1회 동기화](/help/marketo/product-docs/demand-generation/dynamic-chat/connect-dynamic-chat-to-marketo.md) 을 클릭하여 완료합니다.

다음 항목이 동기화됩니다.

* 개인 필드 데이터
* 회사 필드 데이터
* 활동 데이터

## 대화 상자 {#dialogues}

대화 상자는 단일 채팅 참여를 나타냅니다. 웹 사이트 방문자에게 매력적인 채팅 대화 상자를 제공하는 데 필요한 모든 것이 포함된 컨테이너라고 생각하십시오. 각 대화 상자에서 대화 상자를 표시할 페이지, 표시할 페이지 및 대화 상자 자체의 콘텐츠와 흐름을 지정할 수 있습니다. 또한 지표를 찾아 대화 상자가 얼마나 잘 작동하는지 확인할 수 있습니다. [대화 상자에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/dialogue-overview.md){target=&quot;_blank&quot;}.

## 구성 {#configuration}

구성 탭에서 다양한 대화 상자의 모양과 느낌을 사용자 지정합니다. 글꼴, 색상, 응답 시간 등을 변경합니다. [구성에 대해 자세히 알아보기](/help/marketo/product-docs/demand-generation/dynamic-chat/configuration.md).

## 달력 {#calendar}

달력 탭에서 (Outlook 또는 Gmail) 일정을 차트보트의 약속 예약에 사용할 일정을 연결합니다. 사용자의 일정이 Dynamic Chat에 연결되면 해당 사용자가 큐에 추가되고 웹 사이트 방문자가 약속을 예약할 수 있도록 해당 일정을 사용할 수 있습니다.

방문자가 사용자의 일정에서 약속을 예약할 때 방문자에게 보내는 초대의 본문을 사용자 지정할 수도 있습니다.

## 회의 {#meetings}

다양한 대화 상자를 통해 웹 사이트 방문자가 예약한 모든 약속을 볼 수 있습니다. 여기에서 약속을 예약한 사람의 전자 메일 주소, 약속을 예약한 대리인, 약속 발생 예정 시간, 회의가 발생했는지 여부를 확인할 수 있습니다.

## 라우팅 {#routing}

이 위치에서 달력을 연결한 모든 에이전트 목록과 웹 사이트 방문자에게 표시할 순서를 볼 수 있습니다. 회의는 윤곽 스타일로 진행되는데, 만약 5명의 에이전트들과 3명의 에이전트가 마지막 회의를 했다면, 4명의 요원이 다음 1명을 얻고, 5명의 요원이 그 다음에 1명으로 돌아옵니다.

## FAQ {#faq}

**Dynamic Chat를 회사 웹 사이트의 어디에나 설치할 수 있습니까, 아니면 Marketo 랜딩 페이지에서만 작동합니까?**

Dynamic Chat JavaScript 코드 조각은 Marketo 랜딩 페이지뿐만 아니라 모든 웹 사이트에 설치할 수 있습니다.

**보고용으로 데이터가 얼마나 오래 저장됩니까?**

90일(전체 제한 목록 참조) [아래](#limits-in-dynamic-chat)).

**Dynamic Chat에서 실시간 채팅을 허용합니까?**

아니요, 사전 결정된 응답만 사용합니다.

**Dynamic Chat는 영어 이외의 다른 언어를 지원합니까?**

예. 동적 채트는 다음 언어를 지원합니다. 프랑스어, 독일어, 일본어, 스페인어, 이탈리아어, 포르투갈어(브라질), 한국어, 중국어(간체) 및 중국어(번체). 자세한 내용은 [아래 섹션](#changing-the-language).

**AI/NLP 기능을 지원합니까?**

AI/NLP 기능은 지원하지 않습니다.

**익명의 사람들을 어떻게 타겟팅해야 하나요?**

대화 상자에서 다음을 사용해야 합니다 _개인 전자 메일이 비어 있음_ 속성을 사용합니다.

## 언어 변경 {#changing-the-language}

다음 단계에 따라 다이내믹 채팅 언어를 변경합니다.

1. Experience Cloud 계정에서 설정 아이콘을 클릭하고 을 선택합니다 **기본 설정**.

   ![](assets/dynamic-chat-overview-1.png)

1. 이메일 주소 아래에서 현재 언어를 클릭합니다.

   ![](assets/dynamic-chat-overview-2.png)

1. 새 언어(두 번째 언어는 선택 사항)를 선택하고 **저장**.

   ![](assets/dynamic-chat-overview-3.png)

   >[!IMPORTANT]
   >
   >선택할 수 있는 언어가 수십 개 있지만 Dynamic Chat에서는 다음과 같은 기능만 지원합니다. 영어, 프랑스어, 독일어, 일본어, 스페인어, 이탈리아어, 브라질 포르투갈어, 한국어, 중국어 간체 및 중국어 번체.

언어를 업데이트하면 개인적으로 채운 단어(예: 스트림 응답)를 제외하고 앱 자체의 모든 내용이 변경됩니다.

## 동적 채팅의 제한 사항 {#limits-in-dynamic-chat}

<table>
  <th>매개 변수</th>
  <th>설명</th>
  <th>제한</th>
 <tr>
  <td>총 대화 상자 수</td>
  <td>총 대화 상자 수(게시됨 및 초안)</td>
  <td>500년</td>
 </tr>
 <tr>
  <td>게시된 대화 상자</td>
  <td>저장된 게시된 대화 상자 수</td>
  <td>100년</td>
 </tr>
 <tr>
  <td>대화 상자당 Target URL</td>
  <td>단일 대화 상자에 추가할 수 있는 Target URL 수</td>
  <td>20년</td>
 </tr>
 <tr>
  <td>대화 상자당 속성</td>
  <td>단일 대화 상자의 대상 기준에 추가할 수 있는 속성 수입니다</td>
  <td>100년</td>
 </tr>
 <tr>
  <td>그룹</td>
  <td>단일 대화 상자에 추가할 수 있는 그룹 수</td>
  <td>10</td>
 </tr>
 <tr>
  <td>그룹당 속성 수</td>
  <td>그룹에 추가할 수 있는 속성 수</td>
  <td>10</td>
 </tr>
 <tr>
  <td>카드</td>
  <td>대화 상자당 캔버스에 추가할 수 있는 카드 수</td>
  <td>500년</td>
 </tr>
 <tr>
  <td>익명 리드 데이터 보존 기간</td>
  <td>참여 없이 익명 리드의 정보를 유지하는 기간</td>
  <td>90일</td>
 </tr>
 <tr>
  <td>목표 활동 유지 기간</td>
  <td>목표 활동 데이터가 보존되는 시간</td>
  <td>24개월</td>
 </tr>
 <tr>
  <td>문서 활동 보존 기간</td>
  <td>문서 활동 데이터가 보존되는 시간입니다</td>
  <td>24개월</td>
 </tr>
 <tr>
  <td>대화 상자 활동 유지 기간과 상호 작용</td>
  <td>대화 상자 활동 데이터와 상호 작용한 시간이 유지됩니다</td>
  <td>90일</td>
 </tr>
 <tr>
  <td>모임 예약 활동 보존 기간</td>
  <td>모임 예약 활동이 Dynamic Chat에 저장되는 시간입니다</td>
  <td>24개월</td>
 </tr>
</table>

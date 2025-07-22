---
description: '[!DNL Dynamic Chat]개 활동 - Marketo 문서 - 제품 설명서'
title: '[!DNL Dynamic Chat]개 활동'
exl-id: ef3bb1a3-6758-4798-92eb-fef28a5ff9c7
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 0%

---

# [!DNL Dynamic Chat]개 활동 {#dynamic-chat-activities}

[!DNL Dynamic Chat]은(는) 스마트 목록에서 사용할 수 있는 몇 가지 필터 및 트리거를 제공합니다.

![](assets/dynamic-chat-activities-1.png)

## 정의 {#definitions}

<table>
<thead>
<tbody>
  <tr>
    <td style="width:25%"><b>트리거됨</b></td>
    <td>트리거 이벤트는 방문자가 대화 상자 또는 대화 흐름에 대한 타겟팅 기준을 충족하고 대화 상자를 표시할 때 발생합니다.
    <br>방문자당, 세션당 하나의 트리거 이벤트.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>대화 흐름/대화 참여</b></td>
    <td>대화나 대화 흐름(다중 선택 옵션 클릭, 정보 제출, 회의 예약, 문서 열기 등)에서 웹 방문자가 처음으로 프롬프트를 클릭할 때 참여가 발생합니다. 방문자가 대화 상자 또는 대화 흐름을 열었지만 프롬프트를 클릭하지 않으면 참여가 <b>기록되지 않음</b>. 
    <br>방문자당, 세션당 하나의 참여 이벤트.</td>
  </tr>
   <tr>
    <td style="width:25%"><b>에이전트와 참여</b></td>
    <td>방문자가 라이브 채팅 에이전트에 성공적으로 연결되었을 때 발생합니다.
    <br>한 명이 방문자당, 세션당 에이전트 이벤트에 참여했습니다.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>문서와 상호 작용</b></td>
    <td>방문자가 문서 카드의 문서를 클릭할 때 발생합니다.
    <br>방문자당, 세션당 여러 문서 상호 작용이 있을 수 있습니다.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>목표에 도달함</b></td>
    <td>방문자가 목표에 도달하면 발생합니다. <br>방문자당 세션당 여러 개의 목표 도달 이벤트가 있을 수 있습니다.</td>
  </tr>
  <tr>
    <td style="width:25%"><b>예약된 회의</b></td>
    <td>방문자가 Dynamic Chat 에이전트와의 회의를 예약할 때 발생합니다.
    <br>방문자당, 세션당 여러 개의 모임 예약 이벤트가 있을 수 있습니다.</td>
  </tr>
</tbody>
</table>

## 참고할 사항 {#things-to-note}

* 조건은 [!DNL Dynamic Chat] 흐름 단계에서 지원됩니다.
* [!DNL Dynamic Chat] 활동을 [[!DNL Marketo Sales Insight]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/dynamic-chat-integration.md){target="_blank"}에 동기화할 수 있습니다.
* 개인 레코드의 활동 로그에서 개별 [!DNL Dynamic Chat] 활동을 볼 수 있습니다.

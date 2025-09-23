---
description: 릴리스 노트 - 2024년 3월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2024년 3월
feature: Release Information
exl-id: d8bc7f88-a77b-4b49-aed5-aceab9e639f0
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '350'
ht-degree: 28%

---

# 릴리스 노트: 2024년 3월 {#release-notes-mar-24}

아래에는 2024년 3월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2024년 3월 8일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>고급 대화 흐름 논리</strong>: 대화 흐름 후속 작업에 대한 단일 선택 항목에 평가를 위한 추가 필드를 추가합니다.</td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Marketo Engage 양식에 대한 대화 플로우 설정</a></td>
  </tr>
   <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
   </tr>
    <tr>
   <td><strong>대화형 흐름 논리 순서 바꾸기</strong>: 이제 Marketo Engage Forms에서 삭제하고 다시 추가하는 대신 대화형 흐름 선택 항목을 다시 정렬할 수 있습니다.</td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Marketo Engage 양식에 대한 대화 플로우 설정</a></td>
   </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
    <tr>
   <td><strong>API 활동 메타데이터</strong>:
   이제 사용자 에이전트, 플랫폼 및 장치와 같은 메타데이터가 웹 및 이메일 활동에 포함되어 Marketo REST API를 통해 이러한 활동에 대한 일관된 통찰력을 제공하는 데 도움이 됩니다.</td>
   <td>출시됨</td>
   <td>해당 사항 없음</td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **프로그램 구성원 API 가져오기**: [프로그램 구성원 가져오기](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Program-Members/operation/getProgramMembersUsingGET){target="_blank"} 끝점의 동작을 수정하기 위해 최근에 변경되었습니다. 이전에는 `updatedAt` 필터 유형을 사용하여 날짜 범위를 지정할 때 해당 범위 내에서 업데이트된 프로그램 멤버십 레코드가 응답에 포함되지 않았을 수 있었습니다. 또한 지정된 날짜 범위 외에 업데이트된 프로그램 멤버십 레코드가 응답에 잘못 포함될 가능성이 있었습니다. 두 문제가 모두 해결되었습니다.

* **계정 Insight 브라우저 플러그인 사용 중단**: Adobe이 2024년 4월 8일에 Chrome 웹 스토어에서 Target 계정 관리 [계정 Insight 브라우저 플러그인](/help/marketo/product-docs/target-account-management/setup-tam/account-insight-plug-in-overview.md){target="_blank"}을 제거합니다. 기존 사용자: Marketo Engage 인스턴스를 Adobe ID 및 Admin Console으로 마이그레이션할 때까지 플러그인을 계속 사용할 수 있습니다. 이 변경 사항은 **Marketo Engage 또는 Sales Insight에서 작동하는 Chrome 및 Outlook 전자 메일 플러그인 내의 다른 TAM 기능/데이터에는 영향을 주지 않습니다**. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/marketo-engage-account-insights-browser-plug-in-end-of-life/ba-p/344834){target="_blank"}

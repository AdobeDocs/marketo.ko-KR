---
description: 릴리스 노트 - 2024년 3월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2024년 3월
feature: Release Information
exl-id: d8bc7f88-a77b-4b49-aed5-aceab9e639f0
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '351'
ht-degree: 0%

---

# 릴리스 노트: 2024년 3월 {#release-notes-mar-24}

아래에는 2024년 3월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![별](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하고 다음부터 릴리스됩니다. **2024년 3월 8일**: 이후 몇 주 동안 나머지 기능에 대한 단계별 롤아웃 포함. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에 있는 상태를 확인하십시오.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">기능</th> 
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr> 
   <td><strong>고급 대화 흐름 논리</strong>: 대화 흐름 후속 작업을 위해 단일 선택 사항에 평가를 위한 추가 필드를 추가합니다.</td> 
   <td>배송됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Forms Marketo Engage에 대한 대화 흐름 설정</a></td>
  </tr>
   <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
   </tr>
    <tr> 
   <td><strong>대화형 흐름 논리 재정렬</strong>: 이제 Forms Marketo Engage에서 을 삭제하고 다시 추가하는 대신 대화 흐름 선택 사항을 재정렬할 수 있습니다.</td> 
   <td>배송됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Forms Marketo Engage에 대한 대화 흐름 설정</a></td>
   </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>API 활동 메타데이터</strong>: 사용자 에이전트, 플랫폼 및 장치와 같은 메타데이터가 이제 웹 및 이메일 활동에 포함되어 Marketo REST API를 통해 이러한 활동에 대한 일관된 통찰력을 제공하는 데 도움이 됩니다.</td> 
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## 공지 {#announcements}

* **프로그램 구성원 API 수정 가져오기**: 최근에 의 동작을 수정하기 위해 변경되었습니다. [프로그램 구성원 가져오기](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Program-Members/operation/getProgramMembersUsingGET){target="_blank"} 엔드포인트. 이전에는 `updatedAt` 필터 유형 을 사용하여 날짜 범위를 지정할 수 있습니다. 해당 범위 내에서 업데이트된 프로그램 멤버십 레코드가 응답에 포함되지 않을 수 있습니다. 또한 지정된 날짜 범위 외에 업데이트된 프로그램 멤버십 레코드가 응답에 잘못 포함될 가능성이 있었습니다. 두 문제가 모두 해결되었습니다.

* **계정 통찰력 브라우저 플러그인 사용 중단**: Adobe이 Target 계정 관리를 제거하는 중입니다. [계정 통찰력 브라우저 플러그인](/help/marketo/product-docs/target-account-management/setup-tam/account-insight-plug-in-overview.md){target="_blank"} 2024년 4월 8일 Chrome 웹 스토어에서. 기존 사용자: Marketo Engage 인스턴스를 Adobe ID 및 Admin Console으로 마이그레이션할 때까지 플러그인을 계속 사용할 수 있습니다. 이 변경 사항 **영향을 주지 않음** Sales Insight에서 작동하는 Marketo Engage 또는 Chrome 및 Outlook 이메일 플러그인 내의 기타 TAM 기능/데이터. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/marketo-engage-account-insights-browser-plug-in-end-of-life/ba-p/344834){target="_blank"}.

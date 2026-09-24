---
description: 릴리스 노트 - 2026년 7월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2026년 7월
feature: Release Information
source-git-commit: a1b00f94acf0fe9cd354a48bf40f17c3ad9b8ae6
workflow-type: tm+mt
source-wordcount: '578'
ht-degree: 13%
---
# 릴리스 노트: 2026년 8월 {#release-notes-aug-26}

아래에는 2026년 8월 릴리스에 포함된 모든 기능이 있습니다. 기능 사용 가능 여부는 Adobe Marketo Engage 에디션에서 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2026년 8월 14일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주에 걸쳐 나머지 기능이 단계적으로 롤아웃됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인하십시오.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>Marketo Engage의 새로운 UI</strong>: Marketo Engage 인터페이스에서 보다 깔끔하고 현대적인 환경을 위해 업데이트된 메뉴, 아이콘 및 레이아웃을 포함하여 새로운 디자인을 구현했습니다. 이는 시각적 업데이트일 뿐이며 기존 기능이나 워크플로는 영향을 받지 않습니다.
</td>
   <td>8월 및 9월 동안의 단계적 롤아웃</td>
   <td><i>해당 사항 없음</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>Marketo Engage MCP 서버</strong>: Marketo Engage MCP 서버는 AI 어시스턴트와 Marketo Engage 간의 가교 역할을 합니다. 양식, 프로그램, 스마트 캠페인, 사람/리드, 이메일, 코드 조각, 목록 및 폴더에 100개 이상의 작업을 노출합니다.</td>
   <td>현재 일반적으로 사용 가능</td>
   <td><a href="https://experienceleague.adobe.com/docs/marketo-developer/marketo/mcp-server.html" target="_blank">Marketo 서버</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>보관 중인 캠페인 비활성화</strong>: 이제 폴더를 보관하면 해당 폴더 트리의 모든 캠페인이 비활성화되고 예약해제되어 보관된 스마트 캠페인이 예기치 않게 실행되지 않습니다.
</td>
   <td>릴리스됨</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-folders#disable-campaigns-archive" target="_blank">보관 중인 캠페인 비활성화</a></td>
  </tr>
    <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 콘텐츠 상황별 메뉴 생성</strong>: 이제 상황별 메뉴(검은색 막대)에서 이메일 Designer의 "콘텐츠 생성" 기능에 액세스할 수 있습니다. 예를 들어 텍스트 콘텐츠를 선택하면 상황별 메뉴에 콘텐츠 생성 아이콘이 표시되어 빠른 작업을 수행할 수 있습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **이제 Marketo AI가 Marketo Engage의 공동 작업자입니다**: Marketo Engage의 공동 작업자는 시간이 많이 걸리는 마케팅 기능을 자동화하기 위해 고안된 에이전트 기술을 제공합니다. 모든 사용자가 사용할 수 있는 새 이름, 동일한 기능. [자세히 알아보기](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/coworker-for-marketo/overview){target="_blank"}

* **REST API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 더 이상 사용되지 않으며 2026년 8월 31일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **REST API 캠페인 실행 ID**: 특정 상황에서 활동의 캠페인 실행 ID 값이 두 쌍의 따옴표(예: `"campaignRunId": ""102938""`) 사이에 잘못된 형식으로 반환되는 경우가 있었습니다.<br/>8월 릴리스부터 이 값은 항상 올바른 숫자 형식(`"campaignRunId": 102938`)으로 반환됩니다

* **잠재 고객 가져오기 활동 및 잠재 고객 변경 가져오기에 대한 정적 목록 크기 제한**: 2026년 9월 30일부터 대상 목록에 10,000개 이상의 잠재 고객이 포함된 경우 `listId` 매개 변수를 포함하는 잠재 고객 가져오기 활동 또는 잠재 고객 변경 가져오기 엔드포인트에 대한 호출이 1003 오류 코드(대상 정적 목록에 레코드가 너무 많음을 나타냄)로 실패합니다. 자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.

* **REST API 병합 리드 제한**: 2026년 7월 31일부터 병합 리드 API 호출의 leadIds 매개 변수에 25개 이상의 ID를 포함하는 호출로 인해 1080 오류 코드가 발생하고 호출이 건너뜁니다. 25개 이상의 레코드를 하나로 병합해야 하는 작업은 이러한 호출의 성공을 보장하기 위해 여러 작업으로 분할해야 합니다.

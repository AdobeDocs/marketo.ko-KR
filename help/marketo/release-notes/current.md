---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
TQID: https://experienceleague.adobe.com/QJFy7PeGXlvS3jcJGcZJROlc8c1UvphO-TOOwPUQeX8
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: b0bb9048-d951-48d8-8232-45cf248a7e27id: b13bd2ad-8e65-49e5-9691-2a0d31067b35id: d1d0a9cd-295d-4976-8c39-ddae266f240eid: f71e690b-4480-4b67-9ef5-88f42f9cdfdbid: f82558ea-6af5-44eb-a424-5b3389abb0a3
subfeature_v2: id: c942e9f6-ed06-481a-abdd-1195363d1452
topic_v2: id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: 2b3c872bfdef4b5cd8e80f754609dd0059c164b2
workflow-type: tm+mt
source-wordcount: 434
ht-degree: 21%

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
   <td>8월 한 달 동안의 단계적 롤아웃</td>
   <td><i>해당 사항 없음</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - Script Builder</strong>: Script Builder는 개인화 스크립트를 더 빨리 만들 수 있도록 도와주는 AI 기반 도우미입니다.
</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>보관 중인 캠페인 비활성화</strong>: 이제 폴더를 보관하면 해당 폴더 트리의 모든 캠페인이 비활성화되고 예약해제되어 보관된 스마트 캠페인이 예기치 않게 실행되지 않습니다.
</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **Rest API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 더 이상 사용되지 않으며 2026년 8월 31일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **REST API 캠페인 실행 ID**: 특정 상황에서 활동의 캠페인 실행 ID 값이 두 쌍의 따옴표(예: `"campaignRunId": ""102938""`) 사이에 잘못된 형식으로 반환되는 경우가 있었습니다.<br/>8월 릴리스부터 이 값은 항상 올바른 숫자 형식(`"campaignRunId": 102938`)으로 반환됩니다

* **리드 가져오기 활동 및 리드 변경 가져오기에 대한 정적 목록 크기 제한**: 2026년 9월 30일부터 대상 목록에 레코드가 너무 많음을 나타내는 1003 오류 코드와 함께 10,000개 이상의 리드가 포함된 경우 `listId` 매개 변수를 포함하는 리드 가져오기 활동 또는 리드 변경 가져오기 엔드포인트에 대한 호출이 실패합니다.

자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.

* **REST API 병합 리드 제한**: 2026년 7월 31일부터 병합 리드 API 호출의 leadIds 매개 변수에 25개 이상의 ID를 포함하는 호출로 인해 1080 오류 코드가 발생하고 호출이 건너뜁니다. 25개 이상의 레코드를 하나로 병합해야 하는 작업은 이러한 호출의 성공을 보장하기 위해 여러 작업으로 분할해야 합니다.

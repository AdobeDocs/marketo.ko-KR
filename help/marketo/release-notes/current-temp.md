---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
hide: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
TQID: https://experienceleague.adobe.com/RZsCx9HAyJuDLO46WfshT30be-rMMDZjnygvU32NGfk
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
source-git-commit: df650f93bedc7202ad82f8f725616cd25e4a99ef
workflow-type: tm+mt
source-wordcount: '521'
ht-degree: 18%
---
# 릴리스 노트: 2026년 9월 {#release-notes-sep-26}

아래에는 2026년 9월 릴리스에 포함된 모든 기능이 있습니다. 기능 사용 가능 여부는 Adobe Marketo Engage 에디션에서 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2026년 9월 25일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주 동안 나머지 기능은 단계적으로 롤아웃됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인하십시오.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>Marketo Engage의 새로운 UI</strong>: Marketo Engage 인터페이스에서 보다 깔끔하고 현대적인 환경을 위해 업데이트된 메뉴, 아이콘 및 레이아웃을 포함하여 새로운 디자인을 구현했습니다. 이는 시각적 업데이트일 뿐이며 기존 기능이나 워크플로는 영향을 받지 않습니다. <i>클래식 UI를 선택하는 기능은 2027년 1월 릴리스</i>를 통해 사용할 수 있습니다.
</td>
   <td>9월 말까지 일반 공급</td>
   <td><i>해당 사항 없음</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>가져올 때 파티션 선택</strong>: 이제 작업 영역과 파티션이 활성화된 환경에서 개인 레코드를 가져올 때 로컬 작업 영역의 파티션 목록에서 선택할 수 있습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>CRM 동기화에 대한 즉각적인 경고</strong>: CRM 알림을 구독한 사용자는 기본 CRM 동기화의 사용 상태가 변경되면 즉시 알림을 받게 되므로 관리자가 CRM 동기화 상태를 더 잘 볼 수 있습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
   <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>셀프 서비스 흐름 단계 - 콜백 시간 초과 증가</strong>: 셀프 서비스 흐름 단계에 대한 콜백 시간 초과 기간이 1시간에서 4시간으로 증가하고 있습니다. 별도의 작업이 필요하지 않습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **사용자 지정 활동 특성에 대한 API 이름 제한**: 이제 API 또는 UI를 통해 만든 사용자 지정 활동 특성에 대한 API 이름에는 영숫자와 밑줄만 포함될 수 있으며 영숫자로 시작해야 합니다.

* **잠재 고객 가져오기 활동 및 잠재 고객 변경 가져오기에 대한 정적 목록 크기 제한**: 2026년 9월 30일부터 대상 목록에 10,000개 이상의 잠재 고객이 포함된 경우 `listId` 매개 변수를 포함하는 잠재 고객 가져오기 활동 또는 잠재 고객 변경 가져오기 엔드포인트에 대한 호출이 1003 오류 코드(대상 정적 목록에 레코드가 너무 많음을 나타냄)로 실패합니다. 자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.

* **REST API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 2026년 8월 31일부터 더 이상 사용되지 않습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **REST API 캠페인 실행 ID**: 특정 상황에서 활동의 캠페인 실행 ID 값이 두 쌍의 따옴표(예: `"campaignRunId": ""102938""`) 사이에서 잘못된 형식으로 반환되는 경우가 있었습니다.<br/>8월 릴리스부터는 이 값이 항상 올바른 숫자 형식(`"campaignRunId": 102938`)으로 반환됩니다.

* **웹에서 Grab 이미지 사용 중단**: 최신 보안 및 개인 정보 보호 모범 사례를 준수하기 위해 [웹에서 Grab 이미지 사용 중단](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/images-and-files/grab-the-images-from-a-web-page){target="_blank"} 기능은 10월 릴리스부터 더 이상 사용되지 않습니다.

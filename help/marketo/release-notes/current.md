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
source-git-commit: 48aeac444cca4abfc4393eb53dc091b8e73a5b63
workflow-type: tm+mt
source-wordcount: 421
ht-degree: 28%

---

# 릴리스 노트: 2026년 5월 {#release-notes-may-26}

아래에는 2026년 5월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2026년 5월 22일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주에 걸쳐 나머지 기능의 단계적인 롤아웃이 시작됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>전자 메일 Designer - 전자 메일 조각에 대한 조건부 콘텐츠</strong>: <i>이전 전자 메일 편집기와 동일</i>. 이제 조각에 조건부 콘텐츠가 지원됩니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>선택 목록 관리</strong>: 이제 Marketo Engage의 필드에 사용할 수 있는 값을 지정할 수 있습니다.
   </td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **소셜 기능 사용 중단 필드**: 2025년 Marketo Engage에서는 다음 소셜 기능을 사용하지 않습니다.

   * 투표
   * 소셜 버튼
   * 추천 시 제공 경품
   * 동영상 공유
   * 경품 추첨

올해 초 Marketo에 남겨져 있던 관련 분야가 삭제됐다. 곧이어 특정 소셜 관련 리드 필드를 참조하는 API 요청에서 &quot;필드를 찾을 수 없음&quot; 오류가 반환되어 중단이 발생했습니다. 영향을 받은 필드를 다시 사용할 수 있게 된 후 서비스가 복원되었으므로 더 이상의 중단을 방지하기 위해 Marketo은 소셜 기능 사용 중단에서 소셜 필드를 영구적으로 분리했습니다(따라서 Marketo 계정에서 사용할 수 있게 됨). 사용자는 Marketo 소셜 관련 필드를 참조하는 API 쿼리 및 통합을 검토하고 이러한 필드가 지속적인 비즈니스 프로세스에 여전히 필요한지 확인하는 것이 좋습니다.

* **Rest API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 더 이상 사용되지 않으며 2026년 7월 31일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원은 2026년 7월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

* **잠재 고객 가져오기 활동 및 잠재 고객 변경 사항 가져오기에 대한 정적 목록 크기 제한**: 2026년 9월 30일부터 `listId` 매개 변수를 포함하는 잠재 고객 가져오기 활동 및 잠재 고객 변경 사항 가져오기 엔드포인트에 대한 호출은 대상 정적 목록에 10,000개 이상의 잠재 고객이 포함된 경우 1003 오류 코드를 반환합니다. 자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.

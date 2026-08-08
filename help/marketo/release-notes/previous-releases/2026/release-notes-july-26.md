---
description: 릴리스 노트 - 2026년 7월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2026년 7월
feature: Release Information
source-git-commit: 354c6285ff143a28b3057fa7d3b0ca528c3e51b6
workflow-type: tm+mt
source-wordcount: '480'
ht-degree: 20%

---

# 릴리스 노트: 2026년 7월 {#release-notes-july-26}

아래에는 2026년 7월 릴리스에 포함된 모든 기능이 있습니다. 기능 사용 가능 여부는 Adobe Marketo Engage 에디션에서 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2026년 7월 10일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주에 걸쳐 나머지 기능의 단계적인 롤아웃이 시작됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인하십시오.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>Marketo AI 스킬 - 제품 지식</strong>: 제품 지식을 통해 플랫폼을 떠나지 않고 Marketo 전문 지식을 온디맨드로 이용할 수 있습니다. 일반 언어로 질문하면 Marketo AI가 공식 Adobe 설명서를 통해 답변을 제공합니다.
</td>
   <td>Beta 열기</td>
   <td><a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/marketo-ai/skills/product-knowledge" target="_blank">제품 지식</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>Marketo AI 스킬 - 리드 조사</strong>: 특정 사용자/리드가 마일스톤(예: MQL, 프로그램 자격 또는 캠페인)에 도달하지 않은 이유를 확인하고 발생한 사항에 대한 간단한 설명을 얻을 수 있습니다.
</td>
   <td>Beta 열기</td>
   <td><a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/marketo-ai/skills/investigate-leads" target="_blank">리드 조사</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 콘텐츠 상황별 메뉴 생성</strong>: 이제 상황별 메뉴(검은색 막대)에서 이메일 Designer의 "콘텐츠 생성" 기능에 액세스할 수 있습니다. 예를 들어 텍스트 콘텐츠를 선택하면 상황별 메뉴에 콘텐츠 생성 아이콘이 표시되어 해당 메뉴에서 빠른 작업을 수행할 수 있습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **Rest API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 더 이상 사용되지 않으며 2026년 8월 31일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.
* **REST API 병합 리드 제한**: 2026년 7월 31일부터 병합 리드 API 호출의 leadIds 매개 변수에 25개 이상의 ID를 포함하는 호출은 1080 오류 코드를 생성하며, 호출이 건너뜁니다. 25개 이상의 레코드를 하나로 병합해야 하는 작업은 이러한 호출의 성공을 보장하기 위해 여러 작업으로 분할해야 합니다.
* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원은 2026년 7월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.
* **잠재 고객 가져오기 활동 및 잠재 고객 변경 사항 가져오기에 대한 정적 목록 크기 제한**: 2026년 9월 30일부터 `listId` 매개 변수를 포함하는 잠재 고객 가져오기 활동 및 잠재 고객 변경 사항 가져오기 엔드포인트에 대한 호출은 대상 정적 목록에 10,000개 이상의 잠재 고객이 포함된 경우 1003 오류 코드를 반환합니다. 자세한 내용은 [마이그레이션 안내서](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"}를 참조하십시오.

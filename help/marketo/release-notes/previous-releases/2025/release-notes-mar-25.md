---
description: 릴리스 노트 - 2025년 3월 - Marketo 문서 - 제품 설명서
title: 릴리스 노트 - 2025년 3월
feature: Release Information
source-git-commit: 38ec4726dece1695a15104fdb7fa7592b298d4a9
workflow-type: tm+mt
source-wordcount: '475'
ht-degree: 3%

---

# 릴리스 노트: 2025년 3월 {#release-notes-mar-25}

아래에는 2025년 3월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

Adobe Dynamic Chat [에 대한 릴리스 정보는 여기에서 찾을 수 있습니다](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>별(![별](assets/yellow-star.png))로 표시되는 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하며 **2025년 3월 28일**&#x200B;에 릴리스되기 시작합니다. 이후 몇 주에 걸쳐 나머지 기능이 단계적으로 롤아웃됩니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에 있는 상태를 확인하십시오.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">기능</th> 
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
    <tr> 
   <td><strong>모든 프로그램에서 사용할 수 있는 이메일 Designer</strong>: 이제 참여, 기본 및 이벤트 프로그램에서 새로운 이메일 Designer 이메일에 액세스할 수 있습니다(대화형 웨비나 프로그램만 제외). 이전에는 이메일 프로그램에서만 사용할 수 있었습니다. 이 업데이트를 통해 복제도 사용할 수 있게 됩니다.</td>
   <td>배송됨</td>
   <td>해당 사항 없음</td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong>대화형 웨비나의 GenAI 기능</strong>: 이제 챕터를 생성하고 온디맨드 웨비나에 대한 요약을 작성할 수 있습니다. 데이터의 HTML 파일을 편집하고 내보냅니다.</td>
   <td>배송됨</td>
   <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/gen-ai">GenAI의 특징</a></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  <tr> 
   <td><strong>글로벌 및 Workspace 내 토큰</strong>: 생산성을 높이고 Marketo Engage 작업 영역 및 전체 인스턴스에서 brand 및 마케팅 자료를 제어할 수 있도록 작업 영역과 글로벌 수준에서 내 토큰을 구성합니다.</td> 
   <td>배송됨</td>
   <td>해당 사항 없음</td>
  </tr>
  </tbody> 
</table>
<br/>

## 공지 {#announcements}

* **소셜 기능 사용 중단**: 2024년 7월 31일 수요일에 Marketo Engage은 제품 내에서 다음 소셜 기능의 사용 중단을 시작했습니다.

   * 투표
   * 소셜 단추
   * 추천 시 제공 경품
   * 동영상 공유
   * 경품 추첨

그 이후로는 사용자가 Marketo Engage에서 이러한 소셜 기능을 생성, 복제 또는 포함할 수 없습니다. 기존 소셜 자산은 2025년 1월 31일까지 계속 작동합니다. 2025년 2월 1일 사회적 자산은 기능이 중단되었다. 랜딩 페이지에 임베드된 모든 소셜 기능은 제거해야 합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

* **Rest API &#39;access_token&#39; 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개 변수는 더 이상 사용되지 않으며 2025년 6월 30일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 &#39;인증&#39; 헤더 [을(를) 사용하여 여기에 설명된 대로 REST API 호출을 인증해야 합니다](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원은 2025년 10월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}(으)로 마이그레이션해야 합니다.

* **새로운 Analytics 기능 - 공개 Beta**: [고급 BI Analytics](/help/marketo/product-docs/reporting/advanced-bi-analytics/overview.md){target="_blank"}(이전 Revenue Explorer 및 고급 Report Builder)은 4월 중순부터 모든 현재 Revenue Cycle Explorer 사용자에게 롤아웃되기 시작합니다. 이 새로운 도구는 Marketo Engage 데이터에 대한 유연한 보고 및 시각화 인터페이스를 제공하여 진행 상황, 성능 등에 대한 세부 정보를 제공합니다. 더욱 풍부한 상호 작용 및 시각화, 빠른 성능, 보다 원활하고 직관적인 사용자 경험을 제공합니다.

이 기능에 액세스하려면 고급 BI Analytics 추가 기능을 구입해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

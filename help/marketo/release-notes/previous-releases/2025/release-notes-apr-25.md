---
description: 릴리스 노트 - 2025년 4월 - Marketo 설명서 - 제품 설명서
title: 릴리스 정보 - 2025년 4월
feature: Release Information
exl-id: 94010780-41aa-4212-a1d4-1b78806bd728
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 42%

---

# 릴리스 노트: 2025년 4월 {#release-notes-apr-25}

아래에는 2025년 4월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2025년 4월 25일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>SSL(Secure Socket Layer) 셀프 서비스</strong>: SSL 암호화를 사용하면 Marketo Engage 인스턴스의 랜딩 페이지를 안전하게 만들 수 있습니다. 이 기능을 활성화하려면 Adobe 지원 팀의 지원이 필요합니다. 이제 Marketo 사용자가 직접 활성화할 수 있으므로 귀중한 시간을 절약할 수 있습니다.</td>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-ssl-to-your-landing-pages.md">랜딩 페이지에 SSL 추가</a></td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **새로운 Analytics 기능 - 공개 Beta**: [고급 BI Analytics](/help/marketo/product-docs/reporting/advanced-bi-analytics/overview.md){target="_blank"}(이전 Revenue Explorer 및 고급 Report Builder)은 4월 중순부터 모든 현재 Revenue Cycle Explorer 사용자에게 롤아웃되기 시작합니다. 이 새로운 도구는 Marketo Engage 데이터에 대한 유연한 보고 및 시각화 인터페이스를 제공하여 진행 상황, 성능 등에 대한 세부 정보를 제공합니다. 더욱 풍부한 상호 작용 및 시각화, 빠른 성능, 보다 원활하고 직관적인 사용자 경험을 제공합니다.

이 기능에 액세스하려면 고급 BI Analytics 추가 기능을 구입해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2026년 3월 31일 수요일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2026년 3월 31일 수요일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

* **소셜 기능 사용 중단**: 2024년 7월 31일 수요일에 Marketo Engage은 제품 내에서 다음 소셜 기능의 사용 중단을 시작했습니다.

   * 투표
   * 소셜 버튼
   * 추천 시 제공 경품
   * 동영상 공유
   * 경품 추첨

그 이후로는 사용자가 Marketo Engage에서 이러한 소셜 기능을 생성, 복제 또는 포함할 수 없습니다. 기존 소셜 자산은 2025년 1월 31일까지 계속 작동합니다. 2025년 2월 1일 사회적 자산은 기능이 중단되었다. 랜딩 페이지에 임베드된 모든 소셜 기능은 제거해야 합니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

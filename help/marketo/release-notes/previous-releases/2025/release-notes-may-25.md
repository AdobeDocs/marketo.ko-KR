---
description: 릴리스 노트 - 2025년 5월 - Marketo 문서 - 제품 설명서
title: 릴리스 정보 - 2025년 5월
feature: Release Information
exl-id: 99cd1d54-0a80-40fa-9d0c-1cb437be90f0
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '435'
ht-degree: 39%

---

# 릴리스 노트: 2025년 5월 {#release-notes-may-25}

아래에는 2025년 5월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2025년 5월 23일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>이메일 Designer Assets에 대한 역할 기반 액세스 제어</strong>: 역할 기반 액세스 제어(RBAC) 시스템의 새로운 개선 사항은 새로운 이메일 Designer에서 제공하는 에셋에 대해 보다 세분화된 권한과 개선된 사용자 관리를 제공합니다.</td>
   <td>릴리스됨</td>
   <td><a href="https://nation.marketo.com/t5/latest-product-innovations/product-updates-granular-permissions-to-new-email-designer/ba-p/357057">새 이메일 Designer(블로그 게시물)에 대한 세분화된 권한</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>전자 메일 Designer에서 만든 전자 메일 복제</strong>: 이제 새 전자 메일 Designer을 사용하여 만든 기존 전자 메일을 복제할 수 있습니다.</td>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>모든 특성에 대한 트리거 토큰</strong>: Smart Campaign 필드에 있는 모든 활동 특성의 데이터를 사용할 수 있도록 지원하는 확장된 트리거 토큰 목록입니다.</td>
   <td>릴리스됨</td>
   <td>해당 사항 없음</td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **Facebook 오프라인 전환 통합 업데이트**: 2025년 5월 29일에 Marketo Engage의 [Facebook 오프라인 전환](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions){target="_blank"} 통합이 새 Meta [전환 API](https://developers.facebook.com/docs/marketing-api/conversions-api){target="_blank"}(으)로 마이그레이션됩니다. 이는 Meta이 Graph API 버전 관리에 따라 [오프라인 전환 API](https://developers.facebook.com/docs/marketing-api/offline-conversions/){target="_blank"}를 더 이상 사용하지 않기 때문입니다. 자세한 내용은 Meta의 전환 API를 통해 [오프라인 이벤트 보내기](https://developers.facebook.com/docs/marketing-api/conversions-api/offline-events/){target="_blank"}(오프라인 CAPI)에 대한 안내서를 참조하십시오.

* **새로운 Analytics 기능 - 공개 Beta**: [고급 BI Analytics](/help/marketo/product-docs/reporting/advanced-bi-analytics/overview.md){target="_blank"}(이전 명칭: Revenue Explorer 및 고급 Report Builder)가 4월 중순부터 모든 현재 Revenue Cycle Explorer 사용자에게 롤아웃되기 시작했습니다. 이 새로운 도구는 Marketo Engage 데이터에 대한 유연한 보고 및 시각화 인터페이스를 제공하여 진행 상황, 성능 등에 대한 세부 정보를 제공합니다. 더욱 풍부한 상호 작용 및 시각화, 빠른 성능, 보다 원활하고 직관적인 사용자 경험을 제공합니다.

이 기능에 액세스하려면 고급 BI Analytics 추가 기능을 구입해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2026년 3월 31일 수요일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2026년 3월 31일 수요일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

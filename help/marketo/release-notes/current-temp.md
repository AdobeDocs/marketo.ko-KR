---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
hide: true
hidefromtoc: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
source-git-commit: f806c0984cf221bd88fdf50013a8f1d2911b5d86
workflow-type: tm+mt
source-wordcount: '455'
ht-degree: 61%

---

# 릴리스 노트: 2026년 1월 {#release-notes-jan-26}

아래에는 2026년 1월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2026년 1월 30일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>기능 제목</strong>: 기능 설명.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 제공 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>기능 제목</strong>: 기능 설명.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 제공 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>기능 제목</strong>: 기능 설명.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## Adobe Connect 기능 {#adobe-connect-features}

Marketo Engage [대화형 웨비나](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/interactive-webinars-overview){target="_blank"} 기능은 Adobe Connect에서 제공하며 이벤트 데이터를 통해 개인 관리 및 캠페인을 강화하고 개인 품질을 향상시킵니다. 다음은 대화형 웨비나 사용자에게 직접 영향을 주는 몇 가지 최신 Adobe Connect 릴리스입니다.

* **설문 조사 Pod**: Adobe Connect 12.11에서는 호스트가 라이브 세션 내에서 직접 구조화된 피드백 양식을 디자인하고 제공할 수 있는 새로운 설문 조사 Pod를 도입했습니다.

* **리소스 Pod**: 새로운 리소스 Pod는 이전 파일 및 웹 링크 Pod를 대체하며, 라이브 세션 중에 리소스를 공유할 수 있는 통합된 단일 방법을 제공합니다.

* **향상된 Room 인터페이스 환경**: Adobe Connect 12.11에서는 Adobe의 최신 Spectrum 2 디자인 프레임워크를 기반으로 하여 Creative Cloud 및 Experience Cloud과 같은 다른 Adobe 제품에서 사용되는 시각적 언어에 맞게 새로 고침되고 현대적인 Room 인터페이스를 도입했습니다.

자세한 내용은 [Adobe Connect 12.11 릴리스 정보](https://helpx.adobe.com/kr/adobe-connect/release-note/adobe-connect-12-11-release-notes.html){target="_blank"}를 검토하세요.

## 공지 {#announcements}

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2026년 3월 31일 수요일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2026년 3월 31일 수요일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

* **Marketo Engage Identity 서비스 종료**:

   * _IP 기반 Marketo 로그인 제한_&#x200B;을 위한 [IP 제한 지원 중단](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"}은 2025년 7월 30일에 종료되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 새로운 위치 기반 액세스 제어 기능이 곧 출시됩니다.

   * _Single Sign-On (SSO) 지원 중단_: [Marketo Identity SSO](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"}에 대한 지원은 2025년 7월 30일에 중단되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 Single Sign-On은 별도로 구성해야 합니다. 설정 단계는 [ID 및 Single Sign-On 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}을 참조합니다.

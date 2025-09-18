---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
hide: true
hidefromtoc: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
source-git-commit: 29c1b59c9d2598626f546554a8bdc1b26b9e1590
workflow-type: tm+mt
source-wordcount: '494'
ht-degree: 100%

---

# 릴리스 정보: 2025년 9월 {#release-notes-sep-25}

아래에서 2025년 9월 릴리스에 포함된 모든 기능을 확인할 수 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2025년 9월 19일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>온디맨드 웨비나 활동 유지</strong>: 대화형 웨비나 사용자는 이제 온디맨드 웨비나 대시보드 데이터를 30일 넘게 사용할 수 있습니다(기존에는 웨비나 날짜로부터 최대 30일까지만 가능).</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **새로운 이메일 디자이너에서 Velocity Scripting으로 다시 전환**: Adobe Marketo Engage는 지난 6월 새로운 이메일 디자이너를 위한 _조건부 콘텐츠_ 기능을 출시했습니다. 이 기능은 Velocity Scripting에서 대신 Handlebar Scripting을 사용해 다이내믹 콘텐츠에 더 큰 유연성을 제공하기 위한 것입니다. 하지만 이로 인해 일부 토큰이 잘못 해석되는 현상이 발견되었으며 이 기능을 일시적으로 비활성화하기로 결정했습니다. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Marketo Engage Identity 지원 중단**: 2025년 8월에 Adobe는 Marketo Engage Identity(`login.marketo.com`을 통한 로그인)에 대한 지원을 단계적으로 중단하기 시작했습니다. Marketo Engage에 대한 액세스가 중단되는 것을 방지하려면 늦어도 2025년 9월 30일까지 [Adobe Identity](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"}로 전환해야 합니다.

   * [IP 기반 Marketo 로그인 제한](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"}을 위한 _IP 제한 지원 중단_&#x200B;은 2025년 7월 30일에 종료되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 새로운 위치 기반 액세스 제어 기능이 곧 출시됩니다.

   * _Single Sign-On (SSO) 지원 중단_: [Marketo Identity SSO](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"}에 대한 지원은 2025년 7월 30일에 중단되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 Single Sign-On은 별도로 구성해야 합니다. 설정 단계는 [ID 및 Single Sign-On 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}을 참조합니다.

* **_친구에게 전달_ 기능** 사용 중단: 2025년 9월 29일부터 Marketo Engage 2.0 이메일(레거시 이메일 편집기)의 _친구에게 전달_ 기능이 모든 구독에서 완전히 사용 중단됩니다. 이는 이미 토큰을 사용하여 전송되었거나 전송될 예정인 이메일의 &#39;친구에게 전달&#39; 토큰과 &#39;친구에게 전달&#39; 링크에 영향을 미치게 됩니다. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2025년 10월 31일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명된 대로](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"} &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2025년 10월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

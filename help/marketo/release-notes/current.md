---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 7234082102356fc05c760f359ef19ca8cff375b5
workflow-type: tm+mt
source-wordcount: '704'
ht-degree: 92%

---

# 릴리스 정보: 2025년 9월 {#release-notes-sep-25}

아래에서 2025년 9월 릴리스에 포함된 모든 기능을 확인할 수 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2025년 9월 19일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

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
   <td><i>곧 제공 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 디자이너 - 콘텐츠 공동 작업 워크플로</strong>: 이제 이메일 자산 내에서 다른 Marketo 사용자에 대해 댓글을 달고 공동 작업을 수행할 수 있습니다. 팀원 태그 지정(적절한 자산 권한이 있는 Marketo 사용자)에 태그를 지정하면 이메일 또는 펄스 알림을 받습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 제공 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 디자이너 - AI 어시스턴트 권한</strong>: Marketo 관리자는 특정 사용자에게 GenAI 기능에 대한 액세스 권한을 제공할 수 있습니다.</td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/ai-assistant.md#set-up-permissions">권한 설정</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 디자이너 - 다크 모드</strong>: 이제 지원 이메일 클라이언트와 앱이 텍스트, 버튼 및 기타 UI 요소에 대해 더 어두운 배경과 밝은 색상의 이메일을 표시할 수 있는 다크 모드를 사용할 수 있습니다.</td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-designer/dark-mode.md">다크 모드</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 디자이너 - 리디렉션 수정 사항</strong>: 일부 사용자들은 새로운 디자이너를 사용하여 생성된 이메일의 URL을 리디렉션하는 문제가 발생하고 있었습니다 (예: URL을 직접 붙여넣거나 이메일 자산을 북마크하는 것이 항상 효과가 있었던 것은 아닙니다). 이 문제는 해결되었습니다. 또한 <b>이메일 템플릿</b> &gt; <b>세부 정보</b> &gt; <b>사용자</b>에서 이메일 자산으로 연결되는 링크가 해당 이메일 자산으로 리디렉션됩니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **REST API 이중 슬래시 사용 중단**: 2025년 9월 16일, Adobe은 보안 및 확장성을 추가하여 최신 기술을 활용하는 REST API URL용 최신 호스팅 인프라로 전환했습니다. 구독이 URL에서 이중 슬래시(//)가 있는 API를 사용하고 있는 경우 다음 단계에 대해 [이 국가 게시물](https://nation.marketo.com/t5/product-blogs/rest-api-double-slash-deprecation/ba-p/358616){target="_blank"}을 읽어 보십시오.

* **새로운 이메일 디자이너에서 Velocity Scripting으로 다시 전환**: Adobe Marketo Engage는 지난 6월 새로운 이메일 디자이너를 위한 _조건부 콘텐츠_ 기능을 출시했습니다. 이 기능은 Velocity Scripting에서 대신 Handlebar Scripting을 사용해 다이내믹 콘텐츠에 더 큰 유연성을 제공하기 위한 것입니다. 하지만 이로 인해 일부 토큰이 잘못 해석되는 현상이 발견되었으며 이 기능을 일시적으로 비활성화하기로 결정했습니다. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/update-on-email-scripting-in-the-new-email-designer/ba-p/358179){target="_blank"}

* **Marketo Engage Identity 지원 중단**: 2025년 8월에 Adobe는 Marketo Engage Identity(`login.marketo.com`을 통한 로그인)에 대한 지원을 단계적으로 중단하기 시작했습니다. Marketo Engage에 대한 액세스가 중단되는 것을 방지하려면 늦어도 2025년 9월 30일까지 [Adobe Identity](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"}로 전환해야 합니다.

   * _IP 기반 Marketo 로그인 제한_&#x200B;을 위한 [IP 제한 지원 중단](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"}은 2025년 7월 30일에 종료되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 새로운 위치 기반 액세스 제어 기능이 곧 출시됩니다.

   * _Single Sign-On (SSO) 지원 중단_: [Marketo Identity SSO](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"}에 대한 지원은 2025년 7월 30일에 중단되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 Single Sign-On은 별도로 구성해야 합니다. 설정 단계는 [ID 및 Single Sign-On 설정](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}을 참조합니다.

* **_친구에게 전달_ 기능** 사용 중단: 2025년 9월 29일부터 Marketo Engage 2.0 이메일(레거시 이메일 편집기)의 _친구에게 전달_ 기능이 모든 구독에서 완전히 사용 중단됩니다. 이는 이미 토큰을 사용하여 전송되었거나 전송될 예정인 이메일의 &#39;친구에게 전달&#39; 토큰과 &#39;친구에게 전달&#39; 링크에 영향을 미치게 됩니다. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2026년 1월 31일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2026년 1월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

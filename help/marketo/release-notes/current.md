---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: c4fe9a5048c8c0a750d186edde1557cd082e73e4
workflow-type: tm+mt
source-wordcount: '575'
ht-degree: 45%

---

# 릴리스 노트: 2025년 8월 {#release-notes-aug-25}

아래에는 2025년 8월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성은 Adobe Marketo Engage 에디션을 확인합니다.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2025년 8월 22일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 보고</strong>: 이제 이메일 성능 및 이메일 링크 성능 보고서에 새 이메일 Designer을 사용하여 만든 이메일의 데이터가 표시됩니다.</td>
   <td><i>곧 제공 예정</i></td>
   <td><i>곧 제공 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 이메일 미리 보기 최적화</strong>: 일부 사용자가 이메일/이메일 템플릿/조각 세부 정보 페이지에서 이메일을 미리 보는 동안 로드 시간이 느려졌습니다. 이 경험은 최대 60% 더 빠른 로드 시간에 최적화되었습니다.</td>
   <td><i>곧 제공 예정</i></td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 템플릿 수정 사항</strong>: 일부 기본 템플릿에 렌더링 문제가 있습니다(예: 특정 브라우저/다크 모드에서 올바르게 렌더링되지 않음, 이미지 정렬 오류, CTA 단추 위치 오류 등). 이 모든 사항은 이 릴리스에서 해결되었습니다.</td>
   <td><i>곧 제공 예정</i></td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>전자 메일 Designer - 콘텐츠 잠금 수정</strong>: 이전에는 전자 메일 템플릿이 콘텐츠 잠금으로 만들어지고 이 템플릿을 사용하여 전자 메일을 만드는 경우 전자 메일을 다시 설정하거나 "디자인 변경"을 선택하더라도 콘텐츠 잠금이 유지됩니다. 이 문제는 이 릴리스에서 해결되었습니다.</td>
   <td><i>곧 제공 예정</i></td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 자동 완성 제거</strong>: 토큰 개인화 편집기의 자동 완성 옵션이 잘못된 개체를 가리키므로 제거되었습니다. 현재로서는 재시행 계획이 없습니다.</td>
   <td>출시됨</td>
   <td>해당 사항 없음</td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **Marketo Engage ID 수명 종료**: 2025년 8월, Adobe은 Marketo Engage ID 지원을 단계적으로 중단하기 시작했습니다(`login.marketo.com`을(를) 통해 로그인). Marketo Engage에 대한 액세스가 중단되는 것을 방지하려면 늦어도 2025년 9월 30일까지 [Adobe Identity](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview){target="_blank"}로 전환해야 합니다.

   * _IP 제한 사용 중단_: [IP를 기반으로 Marketo 로그인 제한](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/settings/restrict-marketo-logins-based-on-ip){target="_blank"}에 대한 지원이 2025년 7월 30일에 종료되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console에서 Adobe ID에 대한 새로운 위치 기반 액세스 제어 기능이 곧 제공될 예정입니다.

   * _SSO(Single Sign-On) 사용 중단_: [Marketo Identity SSO](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/additional-integrations/add-single-sign-on-to-a-portal){target="_blank"}에 대한 지원이 2025년 7월 30일에 종료되었습니다. 이 기능은 Adobe Identity로의 전환이 완료될 때까지 계속 작동합니다. Adobe Admin Console의 Adobe Identity에 대한 Single Sign-On은 별도로 구성해야 합니다. 설정 단계는 [ID 및 Single Sign-On 설정](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"}을 참조합니다.

* **친구에게 보내기&#x200B;_기능 사용 중단_: 2025년 9월 29일에 Marketo Engage 2.0 전자 메일(기존 전자 메일 편집기)의**&#x200B;친구에게 보내기&#x200B;_기능이 모든 구독에서 완전히 사용되지 않습니다._ 이는 토큰을 사용하여 이미 전송되었거나 전송될 이메일의 &#39;친구에게 전달&#39; 토큰 및 &#39;친구에게 전달&#39; 링크에 영향을 줍니다. [자세히 알아보기](https://nation.marketo.com/t5/product-blogs/deprecation-of-forward-to-a-friend/ba-p/358045#M2889){target="_blank"}

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2025년 10월 31일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명된 대로](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"} &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2025년 10월 31일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

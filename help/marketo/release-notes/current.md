---
description: 최신 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 70939d387dcfe6064e179e4e7e91b16c6baa7b8b
workflow-type: tm+mt
source-wordcount: '462'
ht-degree: 38%

---

# 릴리스 노트: 2026년 3월 {#release-notes-mar-26}

아래에는 2026년 3월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2026년 3월 27일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 브랜드 관리(베타)</strong>: 조직/브랜드별 카피라이팅 지침을 기반으로 이메일 콘텐츠를 생성합니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 브랜드 품질 검사기</strong>: 일반 콘텐츠 품질을 평가하여 브랜드 지침과 관계없이 가독성, 콘텐츠 응집성 및 효과성에 문제가 있을 수 있음을 식별합니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>전자 메일 Designer - Outlook 렌더링 수정 사항</strong>: 이 업데이트는 특히 MS Outlook의 렌더링 문제를 수정합니다. "전문가 모드"를 사용하면 HTML/CSS를 약간 편집하거나 이메일에 스크립트 태그를 추가할 수 있습니다(시각적 요소를 그대로 유지하기 위해 이메일의 HTML에 다른 변경 작업을 수행하지 않는 것이 좋습니다).
   </td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>이메일 Designer - 빠른 작업</strong>: <i>이전 이메일 편집기와 동일</i>. 이제 모든 이메일 Designer 에셋(이메일, 이메일 템플릿, 조각)에 대해 빠른 작업을 사용할 수 있습니다. 지원되는 빠른 작업에는 복제, 삭제, 이동, 초안 생성/편집 등이 있습니다.
   </td>
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
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  <tr>
   <td><strong>푸시 알림</strong>: 이제 푸시 알림 메시지에 구성된 리디렉션 URL이 Marketo Engage 토큰을 지원합니다(<i>앱 URL 시작</i>에만 적용 가능).
   </td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  </tbody>
</table>
<br/>

## 공지 {#announcements}

* **SEO 기능 사용 중단**: 2026년 3월 31일 화요일에 Marketo Engage은 SEO(검색 엔진 최적화 기능)를 사용하지 않습니다. SEO를 적극적으로 활용하지 않는다면 아무것도 하지 않아도 된다. 최근 SEO를 사용한 경우 데이터를 내보낼 수 있습니다. [자세히 알아보기](https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/seo-feature-deprecation-248617){target="_blank"}

* **REST API 병합 리드 제한**: 2026년 3월 31일부터 병합 리드 API 호출의 leadIds 매개 변수에 25개 이상의 ID를 포함하는 호출은 1080 오류 코드를 생성하며, 호출이 건너뜁니다. 25개 이상의 레코드를 하나로 병합해야 하는 작업은 이러한 호출의 성공을 보장하기 위해 여러 작업으로 분할해야 합니다.

* **REST API &#39;access_token&#39; 매개변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 `access_token` 쿼리 매개변수는 사용 중단될 예정이며 2026년 7월 31일 토요일 이후에는 사용할 수 없습니다. 모든 신규 및 기존 통합은 [여기에 설명](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication){target="_blank"}된 대로 &#39;Authorization&#39; 헤더를 사용하여 REST API 호출을 인증해야 합니다.

* **SOAP API 사용 중단**: Marketo SOAP API에 대한 지원이 2026년 7월 31일 토요일에 종료됩니다. SOAP API 기능을 사용하는 서비스는 [REST API](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}로 마이그레이션해야 합니다.

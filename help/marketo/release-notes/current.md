---
description: 현재 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 10a77a09f5ca9ce57e7a357fe1b6736b7bdb95e3
workflow-type: tm+mt
source-wordcount: '465'
ht-degree: 1%

---

# 릴리스 노트: 2024년 7월 {#release-notes-july-24}

아래에는 2024년 6월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 노트 [은(는) 여기에서 찾을 수 있음](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![별](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하고 다음부터 릴리스됩니다. **2024년 7월 26일**: 이후 몇 주 동안 나머지 기능에 대한 단계별 롤아웃 포함. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에 있는 상태를 확인하십시오.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">기능</th> 
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
     <tr> 
   <td><strong>대화형 웨비나에 대한 참여 대시보드</strong>: 웨비나 동안 전체 웨비나 성과 보기와 각 참석자에 대한 포괄적인 참여 보기를 가져와 Marketo Engage 오케스트레이션 도구를 통해 어느 리드가 타겟으로 연결되는지 결정할 수 있습니다.</td> 
    <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr> 
   <td><strong>대화형 웨비나를 위한 룸 관리</strong>: 생성된 개별 룸에 액세스하고(필요한 경우 수정) 콘텐츠 및 녹화에 액세스합니다(필요한 경우 지우어 저장 공간 최적화).</td> 
    <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr> 
   <td><strong>대화형 웨비나에 대한 웨비나 사용자 지정</strong>: 웨비나 전략이 브랜드 전략에 보다 쉽게 부합할 수 있도록 공통 룸 인터페이스, 중간 화면(예: 참석자 시작 화면 배경) 및 사용자 정의 비디오 배경을 사용하여 조직에서 승인한 균일한 브랜드 경험을 제공합니다.</td> 
    <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
  </tr>
     <tr> 
   <td><strong>Marketo REST API 변경</strong>: 다음에 대한 작은 변경 사항을 소개합니다. <a href="https://developers.marketo.com/rest-api/user-management/">사용자 관리 API</a>. 두 가지 모두 <a href="https://developers.marketo.com/rest-api/user-management/#browse_users">사용자 찾아보기</a> 및 <a href="https://developers.marketo.com/rest-api/user-management/#delete_user">사용자 삭제</a> 엔드포인트가 이제 지원 <a href="/help/marketo/product-docs/target-account-management/setup-tam/target-account-management-overview.md">타겟 계정 관리</a> 사용자.</td> 
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## 공지 {#announcements}

* **새 개발자 설명서 사이트**: Marketo Engage 사용자 경험을 향상시키기 위한 지속적인 노력의 일환으로 2024년 7월에 모든 개발자 설명서를 Adobe Experience League 및 Adobe Developer 웹 사이트로 마이그레이션할 예정입니다. [자세히 알아보기](https://nation.marketo.com/t5/employee-blogs/new-developer-documentation-website/ba-p/351055){target="_blank"}

* **쿼리 매개 변수 사용 중지의 액세스 토큰**: Marketo Engage REST API 호출의 쿼리 매개 변수에서 액세스 토큰을 사용하여 인증을 지원하는 기능은 향후 릴리스(특정 날짜 TBD)에서 제거됩니다. 기존 통합은 인증 헤더 사용으로 마이그레이션해야 함 [여기에 설명됨](https://developers.marketo.com/rest-api/authentication/){target="_blank"}. 새 개발에서는 Marketo Engage 인증을 위한 인증 헤더만 사용해야 합니다.

* **LinkedIn 재인증 필요**: LinkedIn이 Marketo Engage LinkedIn 통합에 사용되는 마케팅 API를 업그레이드하고 있습니다. 이러한 변경 사항을 적용하려면 의 모든 LinkedIn LaunchPoint 서비스에 대한 재인증이 필요합니다. **관리자** > **시작 지점** 서비스 중단을 방지하기 위해 2024년 7월 26일부터 12월 15일 사이에 메뉴에서 사용할 수 있습니다. 이 작업을 수행하는 방법에 대한 지침을 찾을 수 있습니다 [리드 젠인 Forms의 경우](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md){target="_blank"} 및 [일치하는 대상자를 위한 여기](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md){target="_blank"}. Lead Gen Form 서비스에는 &quot;LinkedIn Lead Gen&quot; 유형이 있으며 Matched Audience 서비스에는 &quot;LinkedIn Matched Audiences&quot; 유형이 있습니다. 자세한 내용은 다음을 참조하십시오. [마이그레이션 FAQ](https://nation.marketo.com/t5/employee-blogs/linkedin-re-authentication-required/ba-p/347794){target="_blank"}.

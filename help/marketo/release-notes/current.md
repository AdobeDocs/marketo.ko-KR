---
description: 현재 릴리스 정보 - Marketo 설명서 - 제품 설명서
title: 최신 릴리스 정보
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
source-git-commit: 9f442b64f2e6d012207f79d06298583655db86b7
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 3%

---

# 릴리스 노트: 2024년 4월 {#release-notes-apr-24}

아래에는 2024년 4월 릴리스에 포함된 모든 기능이 있습니다. Adobe Marketo Engage 버전에서 사용 가능한 기능이 있는지 확인하십시오.

>[!AVAILABILITY]
>
>별표로 표시되는 기능(![별](assets/yellow-star.png))는 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 해당하고 다음부터 릴리스됩니다. **2024년 4월 26일**: 이후 몇 주 동안 나머지 기능에 대한 단계별 롤아웃 포함. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에 있는 상태를 확인하십시오.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">기능</th> 
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
     <tr> 
   <td><strong>대화형 웨비나 개선 사항</strong>: 이제 호스트 및 발표자에게 웨비나 제목을 추가하고, 회의실 이름을 바꾸고, 이벤트 게재 후 참여 데이터를 수동으로 동기화할 수 있는 기능을 제공할 수 있습니다.</td> 
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>감사 추적 개선 사항</strong>: 이제 감사 추적에서 필드 관리에서 변경한 사항, 사용자 및 역할에 변경한 사항, 목록 및 스마트 목록에서 내보낸 사람 수에 대한 새로운 유형의 작업을 캡처할 수 있습니다.</td> 
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr> 
   <td> </td> 
   <td> </td>
   <td> </td>
  </tr>
    <tr> 
   <td><strong>새 사용자 및 역할 권한</strong>: 새로운 권한을 사용할 수 있으므로 사용자는 Marketo Engage에 보다 세밀하게 액세스할 수 있습니다. 새 경험 및 예측 대상과 같이 이전에 제어되지 않은 관리자의 부분을 제어하고, 자산 감사 추적 및 관리자 감사 추적에 대한 액세스 권한을 별도로 부여하기 위해 권한을 분할하고, 자산 및 폴더에 대한 새로운 만들기 및 이동 권한을 활용하여 읽기 전용 사용자가 변경하지 못하도록 합니다.</td> 
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
 </tbody> 
</table>
<br/>

## 공지 {#announcements}

* **활동 API 업데이트**: 4월 26일부터 를 사용하여 활동을 검색할 때 반환되는 웹 기반 및 이메일 기반 활동에 몇 가지 새로운 속성을 추가합니다. [MARKETO REST API](https://developers.marketo.com/rest-api/lead-database/activities/){target="_blank"}. The activities listed below will now include Browser, Platform, Device, and User Agent attributes. Call the [Get Activity Types](https://developers.marketo.com/rest-api/endpoint-reference/lead-database-endpoint-reference/#!/Activities/getAllActivityTypesUsingGET){target="_blank"} 각 활동에 대한 속성 세부 사항을 검토할 종단점입니다.

**웹 기반 활동**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">활동</th> 
   <th style="width:70%">새로 추가된 속성</th>
   </tr>
  <tr> 
   <td>웹 페이지 방문</td> 
   <td>브라우저, 플랫폼, 장치</td>
  </tr>
   <tr> 
   <td>양식 작성</td> 
   <td>브라우저, 플랫폼, 장치</td>
  </tr>
  <tr> 
   <td>링크 클릭</td> 
   <td>브라우저, 플랫폼, 장치</td>
  </tr>
 </tbody> 
</table>

**이메일 기반 활동**

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:30%">활동</th> 
   <th style="width:70%">새로 추가된 속성</th>
  </tr>
   <tr> 
   <td>이메일 보내기</td> 
   <td>브라우저, 플랫폼, 장치, 사용자 에이전트</td>
  </tr>
   </tr>
  <tr> 
   <td>이메일 전달됨</td> 
   <td>브라우저, 플랫폼, 장치, 사용자 에이전트</td>
  </tr>
   <tr> 
   <td>반송된 이메일</td> 
   <td>브라우저, 플랫폼, 장치, 사용자 에이전트</td>
  </tr>
  <tr> 
   <td>이메일 구독 취소</td> 
   <td>브라우저, 플랫폼, 장치</td>
  </tr>
  <tr> 
   <td>이메일 열기</td> 
   <td>브라우저</td>
  </tr>
   <tr> 
   <td>이메일 클릭</td> 
   <td>브라우저</td>
  </tr>
  <tr> 
   <td>가볍게 반송된 이메일</td> 
   <td>브라우저, 플랫폼, 장치, 사용자 에이전트</td>
  </tr>
 </tbody> 
</table>

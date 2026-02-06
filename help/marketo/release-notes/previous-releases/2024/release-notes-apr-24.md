---
description: 릴리스 노트 - 2024년 4월 - Marketo 설명서 - 제품 설명서
title: 릴리스 정보 - 2024년 4월
feature: Release Information
exl-id: d87474f8-fc47-407b-bc97-e343b56c1f8f
source-git-commit: 8e72b24e18ae108ec74e6d4fa6b04f10130439a4
workflow-type: tm+mt
source-wordcount: '447'
ht-degree: 26%

---

# 릴리스 노트: 2024년 4월 {#release-notes-apr-24}

아래에는 2024년 4월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2024년 4월 26일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
     <tr>
   <td><strong>대화형 웨비나 개선 사항</strong>: 이제 이벤트 게재 후 호스트 및 발표자에게 웨비나 제목을 추가하고, 회의실 이름을 바꾸고, 참여 데이터를 수동으로 동기화할 수 있는 기능을 제공할 수 있습니다.</td>
   <td>릴리스됨</td>
   <td><li><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/create-an-interactive-webinar.md">대화형 웨비나 만들기</a></li>
   <li><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/event-workflows.md#manual-sync">수동 동기화</a></li></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
    <tr>
   <td><strong>감사 추적 개선 사항</strong>:
   이제 필드 관리에서 변경한 사항, 사용자 및 역할에 대한 변경 사항, 목록 및 스마트 목록에서 내보낸 사람 수에 대한 새로운 유형의 작업을 감사 추적에서 캡처할 수 있습니다.</td>
   <td><i>곧 출시 예정</i></td>
   <td><i>곧 출시 예정</i></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
    <tr>
   <td><strong>새 사용자 및 역할 권한</strong>: 새 권한을 사용할 수 있으므로 사용자가 Marketo Engage에 보다 세밀하게 액세스할 수 있습니다. 새 경험 및 예측 대상과 같이 이전에 제어되지 않은 관리자의 부분을 제어하고, 자산 감사 추적 및 관리자 감사 추적에 대한 액세스 권한을 별도로 부여하기 위해 권한을 분할하고, 자산 및 폴더에 대한 새로운 만들기 및 이동 권한을 활용하여 읽기 전용 사용자가 변경하지 못하도록 합니다.
   <p>새 권한은 4월 26일부터 Marketo Engage 인스턴스에 표시되지만 현재로서는 수동적이며 이번 분기 말에 액세스할 수 있습니다.
   <li>Adobe Experience Manager 액세스</li>
   <li>Adobe 조직 매핑 액세스</li>
   <li>관리자 감사 추적 액세스</li>
   <li>자산 감사 추적 액세스</li>
   <li>새 경험 액세스</li>
   <li>예측 대상 액세스</li>
   <li>보고서 만들기</li>
   <li>목록 만들기</li>
   <li>캠페인 활동 내보내기</li>
   </td>
   <td>릴리스됨</td>
   <td><a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md">역할 권한 설명</a></td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **활동 API 업데이트**: 4월 26일에 [Marketo REST API](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities){target="_blank"}를 사용하여 활동을 검색할 때 반환되는 웹 기반 및 전자 메일 기반 활동에 몇 가지 새로운 특성을 추가하고 있습니다. 아래 나열된 활동에는 이제 브라우저, 플랫폼, 장치 및 사용자 에이전트 속성이 포함됩니다. 각 활동에 대한 특성 세부 정보를 검토하려면 [활동 유형 가져오기](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities/operation/getAllActivityTypesUsingGET){target="_blank"} 끝점을 호출하십시오.

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

**전자 메일 기반 활동**

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
   <td>이메일 열람</td>
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

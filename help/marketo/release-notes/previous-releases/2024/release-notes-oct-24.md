---
description: 릴리스 노트 - 2024년 10월 - Marketo 설명서 - 제품 설명서
title: 릴리스 노트 - 2024년 10월
feature: Release Information
exl-id: 2e28ae7f-51de-4510-b3e8-79a989f0daf5
source-git-commit: 29c1b59c9d2598626f546554a8bdc1b26b9e1590
workflow-type: tm+mt
source-wordcount: '548'
ht-degree: 20%

---

# 릴리스 노트: 2024년 10월 {#release-notes-oct-24}

아래에는 2024년 10월 릴리스에 포함된 모든 기능이 있습니다. 기능 가용성에 대해 Adobe Marketo Engage 에디션을 확인하십시오.

Adobe Dynamic Chat에 대한 릴리스 정보는 [여기에서 확인](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}할 수 있습니다.

>[!AVAILABILITY]
>
>별표(![별표](assets/yellow-star.png))로 표시된 기능은 유료 추가 기능입니다. 자세한 내용은 Marketo Engage 담당자에게 문의하십시오.

## 표준 릴리스 주기 기능 {#standard-release-cycle-features}

다음 기능은 표준 릴리스 주기에 포함되며, **2024년 10월 4일 토요일**&#x200B;부터 출시되기 시작하고 나머지 기능은 이후 몇 주에 걸쳐 단계적으로 출시될 예정입니다. 릴리스 기능 및 날짜는 변경될 수 있습니다. 각 기능 옆에서 상태를 확인합니다.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">기능</th>
   <th style="width:10%">상태</th>
   <th style="width:25%">설명서</th>
  </tr>
    <tr>
   <td><strong>대화형 웨비나에 대한 토큰화</strong>: 이제 웨비나 세부 정보를 수동으로 추가하지 않고도 토큰을 사용하여 이메일 및 랜딩 페이지에서 대화형 웨비나를 홍보할 수 있습니다.</td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/promoting-an-interactive-webinar.md#interactive-webinars-tokens" target="_blank">대화형 웨비나 홍보</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  </tr>
   <tr>
   <td><strong>스마트 목록 "영향을 미치도록 설정" 수</strong>: 스마트 캠페인의 자격 규칙을 편집할 때 영향을 받는 사람 수를 확인합니다.</td>
   <td>출시됨</td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
  </tr>
   <tr>
   <td><strong>탐색 레일의 내 계정 단추</strong>: Adobe Identity Management System으로 마이그레이션한 사용자의 경우 왼쪽 탐색 레일에 새 "내 계정" 단추를 사용하면 시간대를 구성하고 구독 세부 정보에 액세스할 수 있습니다.</td>
   <td>출시됨</td>
   <td>해당 사항 없음</td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
   <tr>
   <td><strong>전자 메일 성능 보고서 개선 사항</strong>: 전자 메일 보고 지표 및 활동 추적에 여러 가지 개선 사항이 적용되어 추가적인 통찰력을 제공하고 정확도를 개선했습니다.
   <ul>
   <li>이메일 성능 지표에서 삭제 및 병합된 사람 필터링</li>
   <li>3일 동안 응답 활동을 기다린 후 전자 메일이 이제 <i>중단됨</i>(으)로 분류됨</li>
   <li>이메일 열람수는 각 스마트 캠페인에 대해 별도로 고유 열람수로 계산됩니다</li>
   </td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md" target="_blank">이메일 성과 보고서</a></td>
  </tr>
  <tr>
   <td> </td>
   <td> </td>
   <td> </td>
  </tr>
   <tr>
   <td><strong>Salesforce 동기화 백로그 지표</strong>: 최적의 동기화 환경을 위해 CRM 업데이트를 계획 및 예약하기 위해 동기화 처리량 및 백로그 트렌드를 모니터링합니다.
   </td>
   <td>출시됨</td>
   <td><a href="/help/marketo/product-docs/crm-sync/salesforce-sync/salesforce-sync-backlog-metrics.md" target="_blank">Salesforce 동기화 백로그 지표</a></td>
  </tr>
 </tbody>
</table>
<br/>

## 공지 {#announcements}

* **대량 추출 API 업데이트**: 내보낸 파일에 사용자 지정 열 헤더 이름을 지정할 수 있는 columnHeaderNames 옵션과 관련된 대량 추출 API의 문제를 해결했습니다. 이전에는 ASCII가 아닌 문자가 포함된 열 헤더 이름이 손상될 수 있었습니다.

* **Rest API access_token 매개 변수 사용 중단**: Marketo REST API 호출을 인증하는 데 사용되는 &#39;access_token&#39; 쿼리 매개 변수는 더 이상 사용되지 않으며 2026년 1월 31일 이후에 사용할 수 없습니다. 모든 신규 및 기존 통합은 여기에 설명된 대로 [인증 헤더를 사용하여 REST API 호출을 인증해야 합니다](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/rest/authentication#using-an-access-token).

* **QR 코드 사용 중단**: 2024년 10월 4일에 푸시 알림 및 인앱 메시지 에셋에 사용되는 QR 코드 기능이 더 이상 사용되지 않습니다. 여기에는 새 테스트 장치에 QR 코드를 사용하는 것은 물론 QR 코드로 새 에셋을 만드는 것이 포함됩니다. 사용량이 적은 기능의 사용 중단을 통해 해당 리소스를 Marketo Engage의 전반적인 유지 관리에 다시 할당할 수 있습니다.

* **Munchkin 변경 사항**

   * **새 버전**: 2024년 9월 17일부터 [Munchkin](/help/marketo/product-docs/administration/setup-administration/munchkin.md){target="_blank"} v.164가 **관리자** > **보물 상자**&#x200B;에서 &quot;Munchkin Beta&quot; 설정을 사용하도록 설정된 Marketo Engage 인스턴스로 롤아웃됩니다. 10월 29일에 다른 모든 인스턴스로의 롤아웃을 시작할 예정입니다. 이 버전은 Munchkin 쿠키 생성을 업데이트합니다. 기능에는 변경 사항이 없습니다.

   * **URL에서 문자 제거**: Munchkin JS에서 만든 &#39;웹 페이지 방문 횟수&#39; 및 &#39;링크 클릭 수&#39; 활동에서 이제 모든 URL 필드에서 URL로 인코딩되지 않은 컨트롤 문자가 제거됩니다. 이 변경 사항은 이러한 유형의 문자를 지원하지 않고 Marketo Engage 내에서 사용할 수 없는 시스템에 전파하는 것과 관련된 오류를 방지하기 위해 설계되었습니다.

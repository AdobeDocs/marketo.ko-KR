---
description: 상속된 인스턴스 관리 검사 목록 - Marketo 문서 - 제품 설명서
title: 상속된 인스턴스 관리 검사 목록
feature: Getting Started
exl-id: 088f3ce9-bf3d-4323-9cde-c39fec06c20e
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '1858'
ht-degree: 1%

---

# 상속된 인스턴스: 관리 섹션 확인 목록 {#inherited-instance-admin-section-checklist}

아래 체크리스트(각 문서의 하단에 연결된 후속 체크리스트)는 Adobe Professional Services에서 Marketo 챔피언의 입력을 통해 통합하여 빠르게 시작할 수 있도록 구성되었습니다. [확인 목록을 다운로드](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-inherited-instance-admin-checklist.xlsx)하고 진행 상황을 추적할 수도 있습니다.

>[!TIP]
>
>새로운 Marketo Engage 사용자이고 여러 용어에 익숙하지 않은 경우 [Marketo Engage 용어집](/help/marketo/getting-started/things-to-know/marketo-engage-glossary.md){target="_blank"}을 확인하세요.

## Identity Management Adobe {#adobe-identity-management}

>[!NOTE]
>
>[IMS(Adobe Identity Management System)](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"}에 온보딩된 Marketo Engage 구독에만 적용됩니다. 구독이 아직 Adobe IMS에 온보딩되지 않았다면 Marketo Engage > 관리 > 사용자 및 역할에서 [기존 사용자 역할 및 권한 경험](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}을 계속 진행하십시오.

<table> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th> 
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>구독 및 Marketo Engage 제품 관리자</td> 
   <td><li>Marketo Engage 구독이 <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md" target="_blank">Adobe IMS</a>(으)로 마이그레이션되었습니까? 
<br/>     그렇다면 'Adobe Admin Console 시스템 관리자'로부터 'Adobe Admin Console 제품 관리자' 역할이 부여되었습니까? 조직의 콘솔 관리자 권한이 있는 사용자를 모를 경우 <a href="https://helpx.adobe.com/kr/contact.html" target="_blank">고객 지원 Adobe</a>에 문의하세요.</li>
<li>'Marketo Engage 제품 관리자' 초대를 수락했습니까? Adobe Admin Console에서 역할이 할당되면 이메일이 전송됩니다.
<br/>     없는 경우 받은 편지함에서 <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md#initial-setup" target="_blank">환영 이메일</a>을 찾아 초대를 수락하여 Adobe ID을 활성화하십시오.</li></td>
  </tr>
  <tr> 
   <td>제품 프로필</td> 
   <td><li>모든 적절한 사용자가 Adobe Admin Console에서 Marketo Engage의 제품 프로필에 할당됩니까?
<br/>     그렇지 않은 경우 Adobe Admin Console의 Marketo Engage 제품 프로필에서 <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md" target="_blank">사용자를 추가 및/또는 제거</a>해야 합니다. 제품 프로필에 추가된 경우 Marketo Engage &gt; 관리자 &gt; 사용자 및 역할에서 사용자 역할을 할당할 수 없습니다.</li>
<p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 원치 않는 사용자가 여러 제품 프로필에 추가되면 모든 제품 프로필에서 사용자를 제거해야 합니다. 그렇지 않으면, 여전히 Marketo Engage에 액세스할 수 있습니다.</td>
  </tr>
  <tr> 
   <td>사용자 관리 API</td> 
   <td><li>구독에서 Marketo User Management API를 사용합니까?
<br/>     이 경우 <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html" target="_blank">Adobe IMS API</a>를 사용하여 사용자를 앞으로 초대, 업데이트 및 삭제해야 합니다.</li>
<p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: '역할 관리'는 Marketo Engage에 남아 있으며 Marketo 사용자 관리 API는 여전히 역할 관리에 사용할 수 있습니다.</td>
  </tr>
 </tbody> 
</table>

## 사용자 및 역할 {#users-and-roles}

<table> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>사용자</td> 
   <td><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 구독이 이미 Adobe IMS에 등록되어 있는 경우 Adobe Admin Console에서 다음 사용자 관리 검토를 계속 진행하십시오. 그렇지 않으면 [관리] &gt; [사용자 및 역할] &gt; [Marketo Engage의 사용자]로 이동합니다.
   <p>
   <li><a href="/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md" target="_blank">사용자가 몇 명입니까</a>?</li>
<li><a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md#remove-a-user" target="_blank">제거</a>해야 하는 사용자가 있습니까?</li>
<li>회사에 사용자 삭제에 대한 정책이 있습니까?</li> 
<li><a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">관리자 권한</a>을 가진 사용자는 몇 명입니까?</li>
<li>그러한 사용자 중 <a href="/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md" target="_blank">다른 역할로 변경하시겠습니까?</a></li> 
<li>이 인스턴스의 <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md" target="_blank">API 사용자</a>는 누구입니까?</li></td>
  </tr>
  <tr> 
   <td>역할</td> 
   <td><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: Adobe ID와 함께 Marketo을 사용하든 사용하지 않든, 관리 &gt; 사용자 및 역할 &gt; 역할 아래의 Marketo Engage에서 역할 권한 검토를 계속 진행하십시오.
   <p><li>역할이 몇 개 있습니까?</li>  
<li>각 역할에 있는 <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">권한/액세스</a>는 무엇입니까? 조정해야 합니까?</li>
<li>역할당 사용자가 몇 명입니까?</li>
<li>사용자가 <a href="/help/marketo/product-docs/administration/audit-trail/user-login-history.md" target="_blank">로그인</a>하는 빈도는 얼마나 됩니까?</li>
<li>각 API 사용자의 <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md" target="_blank">고유한 사용자 역할</a>이 있습니까? 그렇지 않은 경우 이 기능을 구현하여 문제를 더 쉽게 해결할 수 있습니다.</li> 
<li>사용자 역할 및 권한이 규정 준수(예: <a href="https://gdpr-info.eu/" target="_blank">GDPR</a>)를 위해 회사 데이터 개인정보 처리방침과 일치합니까? 회사 데이터 <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md" target="_blank">개인정보 처리방침</a>을(를) 통해 사용자가 Marketo Engage 사용자 데이터를 다운로드하고 공유할 수 있습니까? 허가 업무가 필요합니까?</li></td>
  </tr>
  <tr> 
   <td>사용자 지원</td> 
   <td><li>지원 포털에서 적절한 <a href="/help/marketo/getting-started/initial-setup/setup-steps.md#set-up-your-authorized-support-contacts" target="_blank">승인된 연락처</a>를 설정했습니까?</li></td>
  </tr>
  <tr> 
   <td>내부 설명서</td> 
   <td><li>조직에서 사용자와 역할이 명확하게 정의됩니까?</li>
<li>새 사용자/관리자를 추가하는 프로세스는 무엇입니까?</li></td>
  </tr>
  <tr> 
   <td>샌드박스(해당되는 경우)</td> 
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">샌드박스 인스턴스</a>가 있습니까?
   <br/>     그렇다면 샌드박스에 대한 위의 카테고리를 검토하십시오.</li>
<li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md" target="_blank">프로그램 가져오기</a>가 샌드박스에 연결되어 있습니까?</li></td>
  </tr>
 </tbody> 
</table>

## 감사 추적 {#audit-trail}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>감사 추적</td> 
   <td><li>인스턴스에서 <a href="/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md" target="_blank">작업 중인 사용자</a></li></td>
  </tr>
 </tbody> 
</table>

## 작업 공간 및 파티션 {#workspaces-and-partitions}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>작업 공간 및 파티션</td> 
   <td><li>보유한 <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.md" target="_blank">작업 공간 및/또는 파티션</a>은(는) 몇 개입니까?</li>
<li>각 Workspace 및 파티션의 기본 목적은 무엇입니까?</li>
<li><a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-a-workspace.md" target="_blank">작업 공간</a> 또는 <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-an-existing-person-partition.md" target="_blank">파티션</a>을 감사/변경해야 합니까?</li>
<li>작업 영역과 파티션 간의 관계는 무엇입니까?</li>
<li>각 Workspace에 대해 <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.md" target="_blank">액세스 권한이 있는</a>명의 사용자 수</li></td>
  </tr>
  <tr> 
   <td>내부 설명서</td> 
   <td><li>작업 공간 및 분할 영역은 어떻게 정의됩니까?</li>
<li>인스턴스에 작업 영역을 추가하거나 Workspace에 사용자를 추가하는 프로세스는 무엇입니까?</li></td>
  </tr>
 </tbody> 
</table>

## 스마트 캠페인 {#smart-campaigns}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>스마트 캠페인</td> 
   <td><li><a href="/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md" target="_blank">스마트 캠페인 크기에 대한 제한이 있습니까</a>? 
   <br/>     그렇지 않으면 한 개를 추가하는 것이 좋습니다. 워크플로우에서 전체 데이터베이스를 처리하거나 과도한 통신을 방지하기 위해 Smart Campaign 제한을 데이터베이스의 25%로 제한하는 것이 좋습니다. 이렇게 하면 브랜드를 보호할 뿐만 아니라 인스턴스의 성능을 보호할 수 있습니다.</li></td>
  </tr>
 </tbody> 
</table>

## 커뮤니케이션 제한 {#communication-limits}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>커뮤니케이션 제한</td> 
   <td><li><a href="/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md" target="_blank">통신 제한</a>이 적용되어 있습니까? 귀사의 비즈니스에 통신 제한이 필요할 수 있는 정책이 있습니까?</li>
<p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: <b>non</b>-<a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md" target="_blank">operational</a> 이메일을 차단하여 하루에 1번, 7일에 3번으로 커뮤니케이션을 제한하는 것이 좋습니다.</td>
  </tr>
 </tbody> 
</table>

## 태그 {#tags}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>태그</td> 
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags.md" target="_blank">태그가 몇 개입니까</a>? 몇 개의 태그가 사용 중입니까? 추가해야 합니까?</li>
<li>프로그램 내에 태그가 필요합니까?</li></td>
  </tr>
  <tr> 
   <td>채널</td> 
   <td><li><a href="/help/marketo/product-docs/administration/tags/create-a-program-channel.md" target="_blank">채널 수</a>가 몇 개나 있습니까? 몇 대가 사용 중입니까?</li>
<li>모든 <a href="/help/marketo/product-docs/administration/tags/hide-unhide-a-program-channel.md" target="_blank">채널 프로그램 상태가 적절합니까</a>? 프로그램 내에서 진행 상황을 표시합니까?</li>
<li>특정 프로그램 유형과 관련된 채널?</li>
<li>각 채널에 대해 성공으로 간주되는 상태는 무엇입니까? 이것이 마케팅 목표와 일치합니까?</li>
<li>운영 채널이 적절하게 사용되고 있습니까?</li>
<li>고급 Report Builder(Revenue Cycle Explorer/RCE)의 경우 채널 분석 비헤이비어가 기간 비용을 통합하는 프로그램 관행에 맞게 설정되었습니까?</li></td>
  </tr>
  <tr> 
   <td>마케팅 달력(해당되는 경우)</td> 
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.md" target="_blank">일정 항목 유형</a>이 몇 개입니까? 그들 모두 여전히 관련이 있습니까?</li></td>
  </tr>
 </tbody> 
</table>

## 데이터베이스 관리 {#database-management}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>필드 관리</td> 
   <td><li>몇 개의 필드가 있습니까? 
   <br/>     필드, 사용자 정의 필드 및 API 이름 목록을 검토하려면 <a href="/help/marketo/product-docs/administration/field-management/export-a-list-of-all-marketo-api-field-names.md" target="_blank">필드 이름 내보내기</a>를 클릭하십시오.</li>
<li><a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">사용자 지정 필드</a>의 수는 얼마입니까?</li>
<li>얼마나 많은 필드가 사용되고 있습니까? 
<br/>     필드 작업 드롭다운에서 <a href="/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md" target="_blank">Export Used By</a>을(를) 선택하여 필드의 관련 에셋을 검토합니다.</li>
<li>Marketo Engage과 CRM 간에 동기화되는 필드는 몇 개입니까?</li>
<li>CRM 필드가 적절한 오브젝트에 동기화됩니까?</li>
<li>개인 세부 정보에 대한 <a href="/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md" target="_blank">사용자 지정 보기 집합</a>이 있습니까? 있어야 하나?</li>
<li>소스를 기반으로 필드에 대한 이름 지정 규칙이 있습니까? 
<br/>     그렇지 않으면 이를 구현하는 것이 좋습니다.</li>
<li><a href="/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md" target="_blank">차단됨</a> 필드가 있습니까? 
<br/>     그렇다면 그 이유가 무엇인지 반드시 이해하십시오.</li></td>
  </tr>
  <tr> 
   <td>사용자 지정 활동</td> 
   <td><li><a href="/help/marketo/product-docs/administration/marketo-custom-activities/understanding-custom-activities.md" target="_blank">사용자 지정 활동</a>이 있습니까?
<br/>     그렇다면 이러한 활동을 클릭하여 Marketo 양식, 이메일 또는 랜딩 페이지와 관련이 없는 활동을 이해합니다.</li></td>
  </tr>
  <tr> 
   <td>사용자 지정 개체</td> 
   <td><li><a href="/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md" target="_blank">사용자 지정 개체</a>는 몇 개입니까? CRM에 동기화되는 방법은 무엇입니까?</li>
<li>프로그램 및 목록 쿼리에서 이러한 사용자 지정 개체를 어떻게 활용합니까?</li></td>
  </tr>
 </tbody> 
</table>

## 이메일 {#email}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>이메일 기본 설정</td> 
   <td><li>관리자 &gt; 이메일에서, 모든 기본 설정이 최신 상태입니까(예: <a href="/help/marketo/product-docs/administration/email-setup/change-the-default-from-email-and-from-label.md" target="_blank">"from" email/label</a>, <a href="/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md" target="_blank">브랜딩 도메인</a>, <a href="/help/marketo/product-docs/administration/email-setup/edit-the-unsubscribe-message.md" target="_blank">구독 취소 메시지</a> 등)?</li></td>
  </tr>
 </tbody> 
</table>

## 통합 {#integrations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>CRM</td> 
   <td><li>어떤 CRM과 동기화하시겠습니까? Salesforce? MS Dynamics? 베바?</li>
<li><a href="https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758" target="_blank">사용자 지정 동기화</a>를 사용하고 있습니까?</li>
<li>[Salesforce만 해당] 인스턴스에 사용자 지정 동기화 필터가 구현되었습니까? 
<p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: Marketo 지원 센터에 문의하여 사용자 지정 동기화 필터를 식별하거나 사용자 지정 동기화 규칙을 구현하도록 요청하십시오.</li></td>
  </tr>
  <tr> 
   <td>랜딩 페이지</td> 
   <td><li><a href="/help/marketo/product-docs/administration/settings/edit-landing-page-settings.md" target="_blank">도메인으로 설정된 </a>은(는) 무엇입니까?</li>
   <li>홈페이지가 무엇으로 설정되어 있습니까?</li>
<li><a href="/help/marketo/product-docs/administration/settings/set-a-fallback-page.md" target="_blank">대체 집합을 </a>(으)로 설정하는 방법은 무엇입니까?</li>
<li>양식 미리 채우기가 활성화되었습니까?</li>
<li><a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/enable-personalized-urls-for-your-account.md" target="_blank">개인화된 URL</a>이 활성화되었습니까?</li>
<li><a href="/help/marketo/product-docs/demand-generation/landing-pages/landing-page-actions/redirect-a-marketo-landing-page-to-another-page.md" target="_blank">리디렉션</a>에 대한 규칙이 설정되어 있습니까?</li>
<li>도메인 별칭을 사용할 수 있습니까? 도메인 별칭을 어떻게 활용하고 있는지 추적하고 있습니까?</li>
<li><a href="https://nation.marketo.com/t5/knowledgebase/setting-up-secured-domains-for-marketo-landing-pages-first-time/ta-p/250370" target="_blank">랜딩 페이지용 보안 도메인</a>이 활성화되어 있습니까? 
<br/>     랜딩 페이지 에셋에 "http" URL이 포함되어 있는지 확인합니다.</li></td>
  </tr>
  <tr> 
   <td>먼치킨</td> 
   <td><li>웹 사이트에서 <a href="/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md" target="_blank">Munchkin 추적 코드</a>를 사용하고 있습니까(Marketo Engage 랜딩 페이지 아님)?</li>
<li><a href="/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md" target="_blank">추적 안 함</a> 브라우저 요청이 활성화되었습니까?</li>
<li><a href="https://experienceleague.adobe.com/docs/marketo-developer/marketo/javascriptapi/lead-tracking.html" target="_blank">Munchkin API</a>이(가) 구성되어 있습니까? 
<p><img src="assets/tip-icon.png" alt="팁 아이콘">팁: 웹 사이트에서 munchkin 코드가 있는 위치에 대한 설명서가 없으면 <a href="/help/marketo/product-docs/reporting/basic-reporting/report-types/web-page-activity-report.md" target="_blank">웹 페이지 활동 보고서</a>를 만들어 모든 URL을 볼 수 있습니다.</li></td>
  </tr>
  <tr> 
   <td>웹 서비스</td> 
   <td><li><a href="/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md" target="_blank">IP 제한</a>이 활성화되어 있습니까? 그래야 하나?</li>
<li>인스턴스에서 API를 호출하는 사용자/앱은 무엇입니까?</li>
<li>API 제한에 도달하고 있습니까, 거의 도달하고 있습니까?
<br/>     그런 경우에는 API를 늘리거나 인스턴스를 감사하여 해당 API 호출을 줄여 보십시오.</li></td>
  </tr>
  <tr> 
   <td>Adobe Dynamic Chat(해당되는 경우)</td> 
<td>아래 단계를 따라 <a href="https://adminconsole.adobe.com/" target="_blank">Adobe Admin Console</a>에 액세스해야 합니다. 아직 Adobe ID을 설정하지 않은 경우 <a href="https://helpx.adobe.com/kr/manage-account/using/create-update-adobe-id.html" target="_blank">여기에서 설정하는 방법을 알아보세요</a>.
<br/>
<li><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.md" target="_blank">Dynamic Chat 제품 관리자</a> 초대를 수락했습니까? Marketo Engage 인스턴스에서 Dynamic Chat이 활성화되고 시스템 관리자로 지정되면 이메일이 전송됩니다.
<br/>     없는 경우 받은 편지함에서 환영 이메일을 찾고 초대를 수락하여 Adobe ID을 설정합니다.</li>   
<li>Adobe Admin Console의 Dynamic Chat 제품 프로필에 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users.md#add-a-chat-user" target="_blank">원하는 사용자</a>를 추가했습니까?
<li>자격 있는 사용자에게 Adobe ID에 추가된 Dynamic Chat 제품 프로필이 있는지 확인하십시오. 제품 프로필에 추가된 경우 Marketo Engage &gt; 관리자 &gt; 사용자 및 역할에서 '액세스 Dynamic Chat' 역할을 할당할 수 없습니다.</li>
<li>제품 프로필 탭에서 기본 프로필 권한이 조직의 필요에 맞게 조정됩니까?<br/> 
그렇지 않은 경우 특정 프로필에 대한 권한을 편집합니다. </li>
<li>구독이 두 개 이상인 경우 사용자가 올바른 구독에 추가되고 있습니까?</li>
<br>
사용자 및 역할 설정 감사를 마치면 Dynamic Chat에 로그인하여 감사를 계속합니다.  
<li>Dynamic Chat에 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-marketo-engage.md" target="_blank">Marketo Engage 인스턴스를 연결</a>했습니까?</li>
<li>사전 정의된 권한이 있는 5개의 기본 프로필을 조직에 적용할 수 있습니까?<br/> 
     그렇지 않으면 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md#edit-existing-permissions" target="_blank">Dynamic Chat에서 편집할 수 있습니다</a>. 사용자 지정 사용 권한 집합을 사용하여 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions.md#create-a-profile" target="_blank">사용자 지정 프로필을 만들기</a>할 수도 있습니다.</li>
<li>사용자에게 Dynamic Chat에 대한 액세스 권한을 제공하려면 관리 &gt; 사용자 및 역할 &gt; 역할에서 적용 가능한 Marketo Engage 역할에 대해 "Dynamic Chat 액세스"를 선택했습니까?
<br/><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: '관리자' 및 '마케팅 사용자' 역할에는 Dynamic Chat 액세스 권한이 있어야 합니다.</li>
</td>
  </tr>
  <td>Marketo Sales Insight(해당되는 경우)</td> 
   <td><li><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI 패키지가 설치되었습니까</a>?</li>
<li><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">최신 버전의 Sales Insight로 업그레이드</a>했습니까?</li>
<li>Sales Insight 구성을 완료했습니까? <br/>     Enterprise/Unlimited 사용자 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md" target="_blank">여기를 클릭</a>, Professional 사용자 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md" target="_blank">여기를 클릭</a>.</li>
<li>구매한 시트 수에 따라 <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">사용자에게 액세스 권한을 부여</a>받았습니까?</li>
<li><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md" target="_blank">별과 불꽃</a>을(를) 사용자 지정했습니까?</li></td>
  </tr>
  <tr> 
   <td>론치 포인트(해당되는 경우)</td> 
   <td><li>구성한 서비스(예: <a href="/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md" target="_blank">BrightTALK</a>, <a href="/help/marketo/product-docs/administration/additional-integrations/connect-brighttalk-to-marketo.md" target="_blank">확대/축소</a> 등) 유통기한이 임박했나요?</li>
<li><a href="https://nation.marketo.com/t5/knowledgebase/viewing-your-number-of-api-calls-to-marketo/ta-p/254256" target="_blank">통합에서 사용하는 API 호출의 수</a>입니다.</li>
<li>사용 사례에 적합한 통합이 있습니까?</li></td>
  </tr>
  <tr> 
   <td>Webhooks(해당되는 경우)</td> 
   <td><li><a href="/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md" target="_blank">어떤 연결</a>을 설정했습니까?</li>
<li>더 이상 사용되지 않습니까?</li></td>
  </tr>
  <tr> 
   <td>모바일 앱 (해당되는 경우)</td> 
   <td><li>보유 중인 <a href="/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md" target="_blank">모바일 앱</a>은 무엇입니까?</li>
<li><a href="/help/marketo/product-docs/mobile-marketing/push-notifications/adding-a-new-test-device.md" target="_blank">테스트 장치</a>를 추가했습니까?</li></td>
  </tr>
 </tbody> 
</table>

## 보물상자 {#treasure-chest}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>보물상자</td> 
   <td><li><a href="/help/marketo/product-docs/administration/settings/enable-or-disable-treasure-chest-features.md" target="_blank">보물 상자</a>에서 켜진 항목</li>
<li>켜거나 꺼야 하는 기능이 있습니까?</li></td>
  </tr>
  <tr> 
   <td>캠페인 검사자</td> 
   <td><li><a href="/help/marketo/product-docs/administration/settings/campaign-inspector.md" target="_blank">Campaign Inspector</a>가 켜져 있습니까?
<br/>활성화되지 않은 경우 켜서 활성 캠페인, CRM과 동기화 또는 레코드 삭제 등을 쉽게 식별하십시오.</li></td>
  </tr>
 </tbody> 
</table>

## 경고 및 업데이트 {#alerts-and-updates}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">영역</th>
   <th>리뷰 포커스</th>
  </tr> 
  <tr> 
   <td>Marketo Engage 상태 업데이트</td> 
   <td><li>인스턴스가 <a href="https://nation.marketo.com/t5/knowledgebase/how-to-subscribe-to-status-page-notifications/ta-p/296749" target="_blank">Marketo Engage 상태 업데이트</a>를 구독하고 있습니까?</li></td>
  </tr>
  <tr> 
   <td>경고</td> 
   <td><li>Marketo Engage에서 내부 팀으로 보내는 <a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md" target="_blank">활성 경고</a>가 있습니까?</li>
<li>그렇다면 해당 경고가 적절하게 작동하고 있습니까?</li></td>
  </tr>
  <tr> 
   <td>알림</td> 
   <td><li>적절한 관리자 <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md" target="_blank">알림</a>을 구독하고 있습니까?</li></td>
  </tr>
 </tbody> 
</table>

---
description: 새 Marketo Engage 인스턴스에 대한 관리 섹션을 설정합니다.
title: 새 인스턴스 모범 사례 - 관리 섹션 검사 목록
feature: Getting Started
exl-id: 4fa90a32-7e97-404c-90b1-90d05c2561d0
source-git-commit: df8087dbaf2b621d0d877eba1c16f160ee9bf460
workflow-type: tm+mt
source-wordcount: '634'
ht-degree: 1%

---

# 새 인스턴스 모범 사례: 관리 섹션 검사 목록 {#new-instance-best-practices-admin-section-checklist}

새 Marketo Engage 인스턴스를 탐색하는 새 관리자는 아래 체크리스트를 적용하여 구현 프로세스를 안내합니다. 이 모든 안내서와 마찬가지로 [확인 목록 다운로드](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) 진행 상황을 추적할 수 있습니다.

## 역할 {#roles}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>역할</td>
    <td><li>미리 작성된 역할을 검토하고 각 역할에 어떤 권한/액세스 권한이 있는지 확인하십시오.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">새 역할 만들기</a> 또는 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">역할 편집</a> 조직의 요구 사항을 기반으로 합니다.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user" target="_blank">적절한 역할에 사용자 할당</a>. '역할'에서 역할을 부여하려면 먼저 Adobe Admin Console의 구독에 사용자를 추가해야 합니다. 의 사용자 섹션을 참조하십시오. <a href="/help/marketo/getting-started/initial-setup/user-setup.md">초기 설정 체크리스트</a>.</li>
    <li>사용자에 대한 역할을 할당한 후 역할당 사용자 수를 검토하십시오.</li>
    <li>간단한 문제 해결을 위해 각 API 사용자에 대해 고유한 역할을 구현합니다.</li></td>
  </tr>
  <tr>
    <td>샌드박스(해당되는 경우)</td>
    <td><li>다음에 대한 위의 범주를 검토하십시오. <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">샌드박스</a>.</li></td>
  </tr>
</tbody>
</table>

## 작업 공간 및 파티션 {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>작업 공간 및 파티션(해당되는 경우)</td>
    <td><li>의 수 결정<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> 작업 공간</a> 및/또는 조직에 필요한 파티션 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">각 작업 영역에 액세스할 수 있는 사용자 수.</a></li>
    <li>각 작업 공간 및 파티션의 주요 목적을 정의합니다.</li>
    <li>작업 영역과 파티션 간의 관계를 정의합니다.</li></td>
  </tr>
</tbody>
</table>

## 스마트 캠페인 설정 {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>스마트 캠페인 설정</td>
    <td><li>추가 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">스마트 캠페인 크기 제한</a>전체 데이터베이스에 실수로 이메일을 보내는 것을 방지합니다.</li></td>
  </tr>
</tbody>
</table>

## 커뮤니케이션 제한 {#communication-limits}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>커뮤니케이션 제한</td>
    <td><li>구현 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank">커뮤니케이션 제한</a>.</li>
    <li>비즈니스에 통신 제한에 대한 정책이 필요한지 확인합니다.</li></td>
  </tr>
</tbody>
</table>

## 태그 {#tags}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>채널</td>
    <td><li>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank">채널</a>.</li></td>
  </tr>
  <tr>
    <td>태그</td>
    <td><li>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank">태그</a>.</li></td>
  </tr>
  <tr>
    <td>캘린더<br> 
    (해당되는 경우)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank">마케팅 달력 시트 문제 해결</a> 액세스 권한이 필요한 사용자에게</li>
    <li>다음을 설정합니다. <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank">캘린더</a>.</li></td>
  </tr>
</tbody>
</table>

## 데이터베이스 관리 {#database-management}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>필드 관리</td>
    <td><li>에 대한 명명 규칙 구현 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank">사용자 정의 필드</a> (예: "MKTO"로 시작하는 경우).</li>
    <li>동기화하는 필드를 선택합니다. 더 많은 필드를 동기화하면 동기화 주기가 더 느려집니다.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank">필드 업데이트 차단</a> (예: 원본 리드 소스, 원본 리드 소스 세부 사항, 첫 번째 터치 UTM 필드 등)에 한 번 기록하려는 경우.</li></td>
  </tr>
  <tr>
    <td>사용자 지정 활동</td>
    <td><li>정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank">사용자 지정 활동</a> 이는 귀하의 비즈니스에 따라 다릅니다.</li></td>
  </tr>
  <tr>
    <td>사용자 지정 개체</td>
    <td><li>몇 개 검토 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank">사용자 지정 개체</a> 넌 필요해.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank">해당 사용자 지정 개체 동기화</a> CRM에 연결합니다.</li></td>
  </tr>
</tbody>
</table>

## 통합 {#integrations}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM </td>
    <td><li>CRM에 액세스하는 데 필요한 권한을 식별합니다.</li>
    <li>문제 해결을 위해 CRM 관리자를 식별합니다.</li></td>
  </tr>
  <tr>
    <td>웹 서비스</td>
    <td><li>다음을 수행할 수 있는 사용자/앱 결정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html" target="_blank">API 호출</a> 을 참조하십시오.</li>
    <li>API 호출을 수행할 모든 앱을 검토하고 API 호출의 증가 또는 감소가 필요한지 결정합니다.</li></td>
  </tr>
  <tr>
    <td>시작 지점</td>
    <td><li>설정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html" target="_blank">시작 지점</a> 비즈니스를 위한 서비스. 각 LaunchPoint는 문제 해결을 지원하기 위해 고유한 API 사용자와 연결되어야 합니다.</li></td>
  </tr>
  <tr>
    <td>대화형 웨비나(해당되는 경우)</td>
    <td><li>대화형 웨비나, Marketo Engage 기본 제공 웨비나 기능을 만들려면 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management" target="_blank">'사용자' 섹션에 사용자 추가</a> ( 대화형 웨비나 탭).</li>
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 대화형 웨비나는 프로덕션 인스턴스에만 프로비저닝됩니다.</td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat(해당되는 경우)</td>
    <td><li>사용자 할당 대상 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role" target="_blank">'액세스 Dynamic Chat' 역할</a> Marketo Engage &gt; 관리자 &gt; 사용자 및 역할에서 다음을 수행합니다.</li></td>
  </tr>
  <tr>
    <td>Sales Insight(해당되는 경우)</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account" target="_blank">Sales Insight 작업 설정</a> Sales Insight &gt; Actions Config에서 확인할 수 있습니다.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank">시트 발행</a> 적절한 사용자에게.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank">API 구성</a>.</li>
    <li>사용자 지정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank">잠재 고객 스코어</a>.</li></td>
  </tr>
  <tr>
    <td>Sales Connect(해당되는 경우)</td>
    <td><li>적절한 Marketo Engage 관리자를 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance" target="_blank">Sales Connect 인스턴스</a>.</li>
    <li>다음을 완료합니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins" target="_blank">추가 Sales Connect 관리자 설정</a> Sales Connect 및 Salesforce에서 확인할 수 있습니다.</li></td>
  </tr>
  <tr>
    <td>Webhooks(해당되는 경우)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html" target="_blank">필요한 웹후크 만들기</a> 비즈니스.</li>
    </td>
  </tr>
</tbody>
</table>

## 보물상자 {#treasure-chest}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>보물상자 </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html" target="_blank">보물 상자 활성화</a> 테스트 도구 모음을 표시합니다.</li>
    <li>켜거나 끌 기능을 결정합니다.</li></td>
  </tr>
  <tr>
    <td>캠페인 검사자 </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html" target="_blank">Campaign Inspector 켜기</a> 모든 스마트 캠페인을 한 곳에서 볼 수 있습니다.</li></td>
  </tr>
</tbody>
</table>

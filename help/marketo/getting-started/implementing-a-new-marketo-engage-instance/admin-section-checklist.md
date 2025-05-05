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

새 Marketo Engage 인스턴스를 탐색하는 새 관리자는 아래 체크리스트를 적용하여 구현 프로세스를 안내합니다. 이러한 모든 안내서와 마찬가지로 [확인 목록을 다운로드](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx)하고 진행 상황을 추적할 수도 있습니다.

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
    <li>조직의 필요에 따라 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html?lang=ko#create-a-new-role" target="_blank">새 역할을 만들거나</a> <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html?lang=ko#edit-a-role" target="_blank">역할을 편집</a>합니다.</li>
    <li><a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user" target="_blank">사용자를 적절한 역할에 할당</a>. '역할'에서 역할을 부여하려면 먼저 Adobe Admin Console의 구독에 사용자를 추가해야 합니다. <a href="/help/marketo/getting-started/initial-setup/user-setup.md">초기 설정 검사 목록</a>의 사용자 섹션을 참조하십시오.</li>
    <li>사용자에 대한 역할을 할당한 후 역할당 사용자 수를 검토하십시오.</li>
    <li>간단한 문제 해결을 위해 각 API 사용자에 대해 고유한 역할을 구현합니다.</li></td>
  </tr>
  <tr>
    <td>샌드박스(해당되는 경우)</td>
    <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">샌드박스</a>에 대한 위의 범주를 검토하십시오.</li></td>
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
    <td><li>조직에 필요한 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html?lang=ko" target="_blank">개의 작업 영역</a> 및/또는 파티션의 수와 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html?lang=ko" target="_blank">각 작업 영역에 액세스할 수 있는 사용자의 수를 결정합니다.</a></li>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html?lang=ko" target="_blank">스마트 캠페인 크기에 대한 제한</a>을 추가하여 전체 데이터베이스에 실수로 이메일을 보내는 것을 방지합니다.</li></td>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html?lang=ko" target="_blank">통신 제한</a>을 구현합니다.</li>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html?lang=ko" target="_blank">채널</a>을 사용하는 방법을 정의합니다.</li></td>
  </tr>
  <tr>
    <td>태그</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html?lang=ko" target="_blank">태그</a>를 사용하는 방법을 정의합니다.</li></td>
  </tr>
  <tr>
    <td>캘린더<br> 
    (해당되는 경우)</td>
    <td><li>액세스 권한이 필요한 사용자에게 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html?lang=ko" target="_blank">마케팅 일정 시트 문제</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html?lang=ko" target="_blank">일정</a>을 설정합니다.</li></td>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html?lang=ko" target="_blank">사용자 지정 필드</a>에 대한 명명 규칙을 구현합니다(예: "MKTO"로 시작).</li>
    <li>동기화하는 필드를 선택합니다. 더 많은 필드를 동기화하면 동기화 주기가 더 느려집니다.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html?lang=ko" target="_blank">필드에 대한 업데이트 차단</a> 한 번에 기록하려는 필드(예: 원본 리드 소스, 원본 리드 소스 세부 정보, 첫 번째 터치 UTM 필드 등).</li></td>
  </tr>
  <tr>
    <td>사용자 지정 활동</td>
    <td><li>비즈니스와 관련된 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html?lang=ko" target="_blank">사용자 지정 활동</a>을(를) 정의합니다.</li></td>
  </tr>
  <tr>
    <td>사용자 지정 개체</td>
    <td><li>필요한 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html?lang=ko" target="_blank">사용자 지정 개체 수</a>를 검토하십시오.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html?lang=ko" target="_blank">이러한 사용자 지정 개체를 CRM에 동기화</a>합니다.</li></td>
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
    <td><li>인스턴스에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html?lang=ko" target="_blank">API 호출</a>을 수행할 수 있는 사용자/앱을 결정합니다.</li>
    <li>API 호출을 수행할 모든 앱을 검토하고 API 호출의 증가 또는 감소가 필요한지 결정합니다.</li></td>
  </tr>
  <tr>
    <td>시작 지점</td>
    <td><li>비즈니스용 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html?lang=ko" target="_blank">LaunchPoint</a> 서비스를 설정합니다. 각 LaunchPoint는 문제 해결을 지원하기 위해 고유한 API 사용자와 연결되어야 합니다.</li></td>
  </tr>
  <tr>
    <td>대화형 웨비나(해당되는 경우)</td>
    <td><li>대화형 웨비나를 만들려면 Marketo Engage 기본 제공 웨비나 기능이 대화형 웨비나 탭에서 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management" target="_blank">사용자를 '사용자' 섹션에 추가</a>합니다.</li>
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 대화형 웨비나는 프로덕션 인스턴스에만 프로비저닝됩니다.</td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat(해당되는 경우)</td>
    <td><li>Marketo Engage &gt; 관리 &gt; 사용자 및 역할에서 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role" target="_blank">의 'Dynamic Chat 역할 액세스</a>에 사용자를 할당하십시오.</li></td>
  </tr>
  <tr>
    <td>Sales Insight(해당되는 경우)</td>
    <td><li>Sales Insight &gt; Actions Config에서 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account" target="_blank">Sales Insight 작업을 설정합니다</a>.</li>
    <li>적절한 사용자에게 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html?lang=ko#invite-individual-users-to-msi-actions" target="_blank">시트를 발급합니다</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html?lang=ko" target="_blank">API 구성</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html?lang=ko" target="_blank">리드 점수</a>를 사용자 지정합니다.</li></td>
  </tr>
  <tr>
    <td>Sales Connect(해당되는 경우)</td>
    <td><li>적절한 Marketo Engage 관리자를 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance" target="_blank">Sales Connect 인스턴스</a>에 초대합니다.</li>
    <li>Sales Connect 및 Salesforce에서 <a href="https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins" target="_blank">추가 Sales Connect 관리자 설정</a>을 완료합니다.</li></td>
  </tr>
  <tr>
    <td>Webhooks(해당되는 경우)</td>
    <td><li>비즈니스에 필요한 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html?lang=ko" target="_blank">웹후크를 만듭니다</a>.</li>
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
    <td><li>파일럿 기능을 실험하려면 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html?lang=ko" target="_blank">보물 상자를 사용</a>하세요.</li>
    <li>켜거나 끌 기능을 결정합니다.</li></td>
  </tr>
  <tr>
    <td>캠페인 검사자 </td>
    <td><li>모든 스마트 캠페인을 한 곳에서 보려면 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html?lang=ko" target="_blank">캠페인 검사기를 켜세요</a>.</li></td>
  </tr>
</tbody>
</table>

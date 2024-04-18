---
description: 새 영역 - Marketo 문서 - 제품 설명서
title: 새 영역
hide: true
hidefromtoc: true
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: 14ccfe39059b9c900a5e5e00b082146bb500d79d
workflow-type: tm+mt
source-wordcount: '1113'
ht-degree: 1%

---

# 새 영역: 관리자 체크리스트 {#new-area-admin-checklist}

소개 텍스트입니다.

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
    <td><li>미리 작성된 역할을 검토하고 각 역할에 어떤 권한/액세스 권한이 있는지 확인하십시오.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">새 역할 만들기</a> 또는 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">역할 편집</a> 조직의 요구 사항과 사용자 로그인 빈도를 기반으로 합니다.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html%22%20/l%20%22assign-roles-to-a-user" target="_blank">적절한 역할에 사용자 할당</a>. 역할에서 역할을 부여하려면 먼저 Adobe Admin Console의 구독에 사용자를 추가해야 합니다. '초기 설정' 체크리스트 [LINK]의 '사용자' 섹션을 참조하십시오. <br>사용자에 대한 역할을 할당한 후 역할당 사용자 수를 검토하십시오.<br>간단한 문제 해결을 위해 각 API 사용자에 대해 고유한 역할을 구현합니다.</td>
  </tr>
  <tr>
    <td>사용자 가이드</td>
    <td>조직의 사용자 및 역할을 정의합니다.<br>새 사용자/관리자를 추가하기 위한 프로세스를 정의합니다.</td>
  </tr>
  <tr>
    <td>샌드박스(해당되는 경우)</td>
    <td>샌드박스가 있는 경우 위의 범주를 검토하십시오.</td>
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
    <td>의 수 결정<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> 작업 공간</a> 및/또는 조직에 필요한 파티션 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">각 작업 영역에 액세스할 수 있는 사용자 수.</a><br>각 작업 공간 및 파티션의 주요 목적을 정의합니다.<br>작업 영역과 파티션 간의 관계를 정의합니다.</td>
  </tr>
  <tr>
    <td>사용자 가이드</td>
    <td>작업 영역의 정의 방법과 데이터베이스 파티션(예: 모든 사용자와 비즈니스 섹터를 볼 수 있는 글로벌 작업 영역)과 관련된 작업을 문서화합니다. <br>새 레코드를 적절한 파티션으로 가져옵니다.<br>CRM에서 사용자를 적절한 파티션에 배치하는 값을 정의합니다.</td>
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
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>스마트 캠페인 설정</td>
    <td>추가 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">스마트 캠페인 크기 제한</a>전체 데이터베이스에 실수로 이메일을 보내는 것을 방지합니다.</td>
  </tr>
  <tr>
    <td>사용자 가이드</td>
    <td>작업 영역의 정의 방법과 데이터베이스 파티션(예: 모든 사용자와 비즈니스 섹터를 볼 수 있는 글로벌 작업 영역)과 관련된 작업을 문서화합니다.  <br>새 레코드를 적절한 파티션으로 가져옵니다.<br>CRM에서 사용자를 적절한 파티션에 배치하는 값을 정의합니다.</td>
  </tr>
</tbody>
</table>

## 이메일 설정 {#email-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>이메일 기본값</td>
    <td>브랜딩 도메인에서 도메인을 선택하고 이메일 CNAME을 추가합니다. [EmailTrackingCNAME] 형식이어야 합니다.[CompanyDomain].com.  <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console" target="_blank">Marketo 지원 문의</a> ssl 인증서 제공으로 보안을 유지합니다. 이 프로세스를 완료하는 데 영업일 기준으로 최대 3일이 소요될 수 있습니다.</td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html" target="_blank">SPF 및 DKIM 설정</a> 이메일 전달성.</td>
  </tr>
  <tr>
  </tr>
  <tr>
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
    <td>위치 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank" rel="noopener noreferrer">커뮤니케이션 제한</a>.<br>비즈니스에 통신 제한에 대한 정책이 필요한지 확인 </td>
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
    <td>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank" rel="noopener noreferrer">채널</a>.</td>
  </tr>
  <tr>
    <td>태그</td>
    <td>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank" rel="noopener noreferrer">태그</a>.</td>
  </tr>
  <tr>
    <td>달력(해당되는 경우)</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank" rel="noopener noreferrer">마케팅 달력 시트 문제 해결</a> 액세스 권한이 필요한 사용자에게 <br>설정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank" rel="noopener noreferrer">달력.</a></td>
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
    <td>에 대한 명명 규칙 구현 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank" rel="noopener noreferrer">사용자 정의 필드.</a> 예를 들어, "MKTO"로 시작합니다.<br>동기화하는 필드를 선택합니다. 더 많은 필드를 동기화하면 동기화 주기가 더 느려집니다.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank" rel="noopener noreferrer">필드 업데이트 차단</a> 한 번 (예: 원래 리드 소스, 원래 리드 소스 세부 정보, 첫 번째 터치 UTM 필드 등)에 쓸 수 있습니다.</td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td>사용자 지정 활동</td>
    <td>정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html">사용자 지정 활동</a> 이는 귀하의 비즈니스에 따라 다릅니다.  </td>
  </tr>
  <tr>
    <td>사용자 지정 개체</td>
    <td>몇 개 검토 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html">사용자 지정 개체</a> 넌 필요해. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html">이러한 사용자 지정 개체를 CRM에 동기화</a>. </td>
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
    <td>CRM 동기화를 시작합니다. 회사에서 사용하는 CRM에 따라 다음 중에서 선택하십시오. <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html">Microsoft Dynamics</a>. <br>CRM에 액세스하는 데 필요한 액세스 유형을 식별합니다. <br>문제 해결을 위해 CRM 관리자를 식별합니다. </td>
  </tr>
  <tr>
    <td>랜딩 페이지</td>
    <td>참고: Launch Pack 고객입니까? 이 단계는 건너뛸 수 있습니다. 컨설턴트는 킥오프 통화 중 IT 설치 지침 문서를 제공합니다. <br>을(를) 사용하여 랜딩 페이지 도메인 설정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">CNAME</a> 및 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">도메인 및 페이지 정보 입력</a>. 형식은 [LandingPageCNAME]이어야 합니다.[CompanyDomain].com <br>랜딩 페이지의 CNAME을 선택합니다. 몇 가지 예: <br>* **go**.[CompanyDomain].com <br>* **www2**.[CompanyDomain].com <br>* **lp**.[CompanyDomain].com <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console">Marketo 지원 문의</a> 을 클릭하여 SSL 인증서 프로비저닝 프로세스를 시작합니다. 이 프로세스를 완료하는 데 영업일 기준으로 최대 3일이 소요될 수 있습니다. <br>팁: 짧게 유지하십시오! 짧은 URL을 기억하기가 더 쉽습니다. 도메인으로 "go"를 제안합니다. <br>Analytics 추적 코드(예: Google Analytics 또는 Adobe Analytics)를 랜딩 페이지 템플릿에 추가합니다. </td>
  </tr>
  <tr>
    <td>먼치킨</td>
    <td>참고: Launch Pack 고객인 경우 이 단계를 건너뛰십시오. 컨설턴트는 IT 설정 지침 문서에 Munchkin 코드 지침을 제공합니다. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.html">Munchkin 추적 코드 추가</a> 웹 사이트로 이동합니다. Munchkin 코드는 다음과 같을 수 있습니다. <a href="https://developers.marketo.com/javascript-api/lead-tracking/">하드 코드됨</a> 또는 Google 태그 관리자를 통해 배포됩니다.  </td>
  </tr>
  <tr>
    <td>웹 서비스</td>
    <td>사용 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.html">ip 제한 사항</a> 해당되는 경우. <br>다음을 수행할 수 있는 사용자/앱 결정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html">API 호출</a> 을 참조하십시오. <br>API 호출을 수행할 모든 앱을 검토하고 API 호출에 대한 증가 또는 삭제가 필요한지 결정합니다.  </td>
  </tr>
  <tr>
    <td>시작 지점</td>
    <td>설정 필요 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html">시작 지점</a> 비즈니스를 위한 서비스. 각 LaunchPoint는 문제 해결을 지원하기 위해 고유한 API 사용자와 연결되어야 합니다.  </td>
  </tr>
  <tr>
    <td>대화형 웨비나(해당되는 경우)</td>
    <td>참고: 대화형 웨비나는 프로덕션 인스턴스에만 프로비저닝됩니다. <br>기본 제공 웨비나 기능인 대화형 웨비나를 만들려면 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management">'사용자' 섹션에 사용자 추가</a> ( 대화형 웨비나 탭). </td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat(해당되는 경우)</td>
    <td>사용용 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html">Dynamic Chat</a>, Marketo Engage의 기본 대화 자동화 채널인 의 아래 단계에 따라 사용자 권한 설정을 계속 진행합니다. <a href="https://adminconsole.adobe.com/">Adobe Admin Console</a>. <br>Adobe 조직 시스템 관리자가 Adobe 제품 관리자 역할을 부여했는지 확인합니다. 연락처 <a href="https://helpx.adobe.com/contact.html">Adobe 고객 지원 센터</a> 콘솔에서 관리자 권한이 있는 사용자를 확인합니다. <br>Accept <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">'Dynamic Chat 제품 관리자' 초대</a>. 다음 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">시작 이메일</a> Dynamic Chat이 Marketo Engage 인스턴스에서 활성화되고 시스템 관리자로 지정되면 전송됩니다.  <br>Adobe Admin Console에서 Dynamic Chat의 제품 프로필에 모든 적절한 사용자를 할당합니다. <br>여러 제품 프로필에 원하지 않는 사용자가 추가되면 모든 제품 프로필에서 해당 사용자를 삭제해야 합니다. 그렇지 않으면 Dynamic Chat에 계속 액세스할 수 있습니다. <br>다음을 수행할 수 있습니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">Dynamic Chat에서 제품 프로필 편집</a> 및 의 사용자 지정 집합으로 사용자 지정 프로필을 만듭니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">구독 내에서 사용 가능한 권한</a>. <br>사용자 할당 대상 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role">'액세스 Dynamic Chat' 역할</a> Marketo Engage/관리자/사용자 및 역할의 . </td>
  </tr>
  <tr>
    <td>Sales Insight(해당되는 경우)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account">Sales Insight 작업 설정</a> Sales Insight&gt;Actions 구성에서 확인할 수 있습니다.  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions">적절한 사용자에게 시트를 발행합니다.</a>  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html">API 구성</a>. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html">잠재 고객 점수를 사용자 지정합니다.</a> </td>
  </tr>
  <tr>
    <td>Sales Connect(해당되는 경우)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance">Sales Connect 인스턴스에 적절한 Marketo Engage 관리자 초대</a>. <br>다음을 완료합니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins">추가 Sales Connect 관리자 설정</a> Sales Connect 및 Salesforce에서 확인할 수 있습니다. </td>
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
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html">보물 상자 활성화</a> 테스트 도구 모음을 표시합니다.  <br>켜거나 끌 기능을 결정합니다. </td>
  </tr>
  <tr>
    <td>캠페인 검사자 </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html">Campaign Inspector 켜기</a> 모든 Smart Campaign을 한 번에 볼 수 있습니다. </td>
  </tr>
</tbody>
</table>

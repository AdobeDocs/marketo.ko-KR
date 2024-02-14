---
description: 새 영역 - Marketo 문서 - 제품 설명서
title: 새 영역
hide: true
hidefromtoc: true
feature: Getting Started
source-git-commit: a1c06c980a6f8955f4f51e2fc85202d77a8f27da
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 2%

---

# 새 영역: 관리자 체크리스트 {#new-area-admin-checklist}

흐림 효과 열기

## 역할 {#roles}

<table>
<thead>
  <tr>
    <th>영역 </th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>역할 </td>
    <td><li>미리 작성된 역할을 검토하고 각 역할에 어떤 권한/액세스 권한이 있는지 확인하십시오.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role">새 역할 만들기</a> 또는 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role">역할 편집</a> 조직의 요구 사항과 사용자 로그인 빈도를 기반으로 합니다.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#assign-roles-to-a-user">적절한 역할에 사용자 할당</a>.</li>
    <li>사용자에 대한 역할을 할당한 후 역할당 사용자 수를 검토하십시오.</li>  <li>간단한 문제 해결을 위해 각 API 사용자에 대해 고유한 역할을 구현합니다.</li></td>
  </tr>
  <tr>
    <td>사용자 가이드 </td>
    <td>조직의 사용자 및 역할을 정의합니다. <br>새 사용자/관리자를 추가하기 위한 프로세스를 정의합니다. </td>
  </tr>
  <tr>
    <td>샌드박스(해당되는 경우) </td>
    <td>샌드박스가 있는 경우 위의 범주를 검토하십시오. </td>
  </tr>
</tbody>
</table>

## 작업 공간 및 파티션 {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>작업 공간 및 파티션 </td>
    <td><li>의 수 결정<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html"> 작업 공간</a> 및/또는 조직에 필요한 파티션 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html">각 작업 영역에 액세스할 수 있는 사용자 수.</a></li>
    <li>각 작업 공간 및 파티션의 주요 목적을 정의합니다.</li>
    <li>작업 영역과 파티션 간의 관계를 정의합니다.</li></td>
  </tr>
  <tr>
    <td>사용자 가이드 </td>
    <td><li>작업 영역의 정의 방법과 데이터베이스 파티션(예: 모든 사용자와 비즈니스 섹터를 볼 수 있는 글로벌 작업 영역)과 관련된 작업을 문서화합니다.</li>
    <li>새 레코드를 적절한 파티션으로 가져옵니다.</li>
    <li>CRM에서 사용자를 적절한 파티션에 배치하는 값을 정의합니다.</li></td>
  </tr>
</tbody>
</table>

## 스마트 캠페인 설정 {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>스마트 캠페인 설정 </td>
    <td><li>추가 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html">스마트 캠페인 크기 제한</a>전체 데이터베이스에 실수로 이메일을 보내는 것을 방지합니다.</li>
    <li>스마트 캠페인에 대한 개인 제한 활성화</li></td>
  </tr>
</tbody>
</table>

## 이메일 설정 {#email-settings}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>이메일 기본값</td>
    <td><li>브랜딩 도메인에서 도메인을 선택하고 이메일 CNAME을 추가합니다. [EmailTrackingCNAME] 형식이어야 합니다.[CompanyDomain].com.</li></td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html">SPF 및 DKIM 설정</a> 이메일 전달성.</li></td>
  </tr>
</tbody>
</table>

## 커뮤니케이션 제한 {#communication-limits}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>커뮤니케이션 제한</td>
    <td><li>위치 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html">커뮤니케이션 제한</a>.</li>
    <li>비즈니스에 통신 제한에 대한 정책이 필요한지 확인합니다.</li></td>
  </tr>
</tbody>
</table>

## 태그 {#tags}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>채널</td>
    <td><li>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html">채널</a>.</li></td>
  </tr>
  <tr>
    <td>태그 </td>
    <td><li>사용 방법 정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">태그</a>.</li></td>
  </tr>
  <tr>
    <td>달력(해당되는 경우) </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html">마케팅 달력 시트 문제 해결</a> 액세스 권한이 필요한 사용자에게</li> 
    <li>설정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">캘린더</a>.</li></td>
  </tr>
</tbody>
</table>

## 데이터베이스 관리 {#database-management}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>필드 관리</td>
    <td><li>에 대한 명명 규칙 구현 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank" rel="noopener noreferrer">사용자 정의 필드.</a> 예를 들어, "MKTO"로 시작합니다.</li>
    <li>동기화하는 필드를 선택합니다. 더 많은 필드를 동기화하면 동기화 주기가 더 느려집니다.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank" rel="noopener noreferrer">필드 업데이트 차단</a> 한 번 (즉, 원래 리드 소스, 원래 리드 소스 세부 사항, 첫 번째 터치 UTM 필드 등)에 쓸 수 있습니다.</li></td>
  </tr>
  <tr>
    <td>사용자 지정 활동 </td>
    <td><li>정의 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank" rel="noopener noreferrer">사용자 지정 활동</a> 이는 귀하의 비즈니스에 따라 다릅니다.</li></td>
  </tr>
  <tr>
    <td>사용자 지정 개체 </td>
    <td><li>몇 개 검토 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank" rel="noopener noreferrer">사용자 지정 개체</a> 넌 필요해.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank" rel="noopener noreferrer">이러한 사용자 지정 개체를 CRM에 동기화</a>.</li></td>
  </tr>
</tbody>
</table>

## 통합 {#integrations}

<table>
<thead>
  <tr>
    <th>영역</th>
    <th>작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM</td>
    <td><li>CRM 동기화를 시작합니다. 회사에서 사용하는 CRM에 따라 다음 중에서 선택하십시오. <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html" target="_blank" rel="noopener noreferrer">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html" target="_blank" rel="noopener noreferrer">Microsoft Dynamics</a>.</li>
    <li>CRM에 액세스하는 데 필요한 액세스 유형을 식별합니다.</li>
    <li>문제 해결을 위해 CRM 관리자를 식별합니다.</li></td>
  </tr>
  <tr>
    <td>Sales Insight(해당되는 경우)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html" target="_blank" rel="noopener noreferrer">Sales Insight 를 설정합니다.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank" rel="noopener noreferrer">적절한 사용자에게 시트를 발행합니다.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank" rel="noopener noreferrer">API 구성</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank" rel="noopener noreferrer">잠재 고객 점수를 사용자 지정합니다.</a></li></td>
  </tr>
</tbody>
</table>

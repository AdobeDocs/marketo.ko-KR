---
description: 새 Marketo Engage 인스턴스를 탐색하기 전에 몇 가지 기본 단계를 완료하여 계속 사용해야 합니다. 이러한 단계에는 사용자 계정 설정, 지원 관리자 설정 및 지속적인 시스템 업데이트 구독이 포함됩니다.
title: 사용자 설정 체크리스트
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: 14583b7fa148aa2b03c8cf6316b9a106c11717b7
workflow-type: tm+mt
source-wordcount: '776'
ht-degree: 0%

---

# 사용자 설정 체크리스트 {#user-setup-checklist}

이제 모든 작업을 완료했으므로 [초기 설정 단계](/help/marketo/getting-started/initial-setup/setup-steps.md)를 통해 원활한 지속적인 사용을 보장하기 위한 몇 가지 기본 요소를 수립해야 할 때입니다. 이를 통해 Marketo Engage을 통한 여정의 토대를 마련하고 기능을 최대한 활용할 수 있습니다. 시작해 보겠습니다!

>[!NOTE]
>
>이 체크리스트를 다운로드할 수도 있습니다. [모범 사례 목록과 함께](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) 를 클릭하고, 이동 중에 단계를 확인합니다.

## Identity Management Adobe Marketo Engage {#marketo-engage-on-adobe-identity-management}

새 Marketo Engage 구독이에 온보딩됨 [Adobe Identity Management 시스템(IMS)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html). Adobe Admin Console에서 다음 사용자 관리 검토를 진행합니다.

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>구독 및 Marketo Engage 제품 관리자</td>
    <td><li>Adobe 조직 시스템 관리자가 Adobe 제품 관리자 역할을 부여했는지 확인합니다.</li>  
    <ul>
    <li>연락처 <a href="https://helpx.adobe.com/contact.html">Adobe 고객 지원 센터</a> 조직의 사용자를 확인하려면 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console 시스템 관리자</a> 권한.</li></ul>
    <li>Adobe ID을 활성화하려면 'Marketo Engage 제품 관리자' 초대를 수락하십시오. 다음 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup.html?lang=en#create-a-product-profile">시작 이메일</a> 은 Adobe Admin Console에서 역할이 할당되면 전송됩니다.</li></td>
  </tr>
  <tr>
    <td>제품 프로필</td>
    <td><li>원하는 모든 사용자를 Marketo Engage에 할당 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup#create-a-product-profile">제품 프로필</a> Adobe Admin Console.</li>
    <ul>
    <li>제품 프로필에 추가하기 전에 Marketo Engage &gt; 관리자 &gt; 사용자 및 역할에서 사용자 역할을 할당할 수 없습니다.</li>
    <li>각 구독은 독립 실행형 제품 프로필이 됩니다. 여러 제품 프로필(예: 프로덕션 및 테스트 샌드박스)에 원하지 않는 사용자가 추가되면 모든 제품 프로필에서 사용자를 삭제해야 합니다. 그렇지 않으면 Marketo Engage에 계속 액세스할 수 있습니다.</li></ul></td>
  </tr>
  <tr>
    <td>사용자</td>
    <td><li>정책 생성 시기 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.html">사용자 만들기</a>.</li> <li>사용자를 제거할 시기에 대한 정책을 만듭니다.</li>
    <li>다음을 보유해야 하는 사람 결정 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe 시스템 관리자 및 Marketo Engage 제품 관리자 권한.</a> <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user">사용자 추가</a> 원하는 제품 프로필로 이동합니다.</li>
    <li>각 API 사용 사례에 대해 하나의 API 사용자를 만듭니다.</li></td>
  </tr>
  <tr>
    <td>User Management API(해당되는 경우)</td>
    <td><li>사용 <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html">Adobe 사용자 관리 API</a> 사용자를 초대, 업데이트 및 삭제합니다.</li>
    <li>사용 <a href="https://developer.adobe.com/umapi/">Adobe 사용자 관리 API</a> 역할(예: 관리자, 지원 관리자, 개발자)을 추가하거나 제거합니다.</li>
    </td>
  </tr>
  <tr>
    <td>제품 지원 관리자</td>
    <td><li>종료 <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#create-a-support-ticket-with-admin-console">Adobe Admin Console에서 지원 티켓 제출</a>, 시스템 관리자가 관리하는 구독에 '제품 지원 관리자' 역할을 할당해야 합니다. 조직의 시스템 관리자만 <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#assign-the-support-admin-role">사용자를 이 역할에 할당</a>.</li>
    <li>시스템 관리자로부터 Marketo Engage 구독에 대한 지원 관리자라는 이메일을 받았을 수 있습니다. 이 경우 다음을 클릭합니다. <a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#assign-the-support-admin-role">'시작'</a> (조직에 가입)를 선택합니다.</li>
    <li>하나 이상의 백업 담당자와 함께 적절한 담당자를 결정하고 그에 따라 시스템 관리자에게 제품 지원 관리자 역할을 할당하도록 합니다.</li></td>
  </tr>
</tbody>
</table>

## Identity Management 설정 Adobe 시 Dynamic Chat {#dynamic-chat-on-adobe-identity-management}

사용 [Dynamic Chat](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html)의 기본 대화 자동화 채널인 Marketo Engage에서 아래 단계에 따라 사용자 권한 설정을 계속 진행합니다. [Adobe Admin Console](https://adminconsole.adobe.com/).

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>구독 및 Dynamic Chat 제품 관리자(해당되는 경우)</td>
    <td><li>Adobe 조직 시스템 관리자가 Adobe 제품 관리자 역할을 부여했는지 확인합니다. 연락처 <a href="https://helpx.adobe.com/contact.html">Adobe 고객 지원 센터</a> 콘솔에서 관리자 권한이 있는 사용자를 확인합니다.</li>
    <li>수락 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">'Dynamic Chat 제품 관리자'</a> 초대합니다. 다음 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">시작 이메일</a> Dynamic Chat이 Marketo Engage 인스턴스에서 활성화되고 시스템 관리자로 지정되면 전송됩니다.</li></td>
  </tr>
  <tr>
    <td>제품 프로필</td>
    <td><li>Adobe Admin Console에서 원하는 모든 사용자를 Dynamic Chat의 제품 프로필에 할당합니다.</li> 
    <ul>
    <li>여러 제품 프로필에 원하지 않는 사용자가 추가되면 모든 제품 프로필에서 해당 사용자를 삭제해야 합니다. 그렇지 않으면 Dynamic Chat에 계속 액세스할 수 있습니다.</li>
    <li>다음을 수행할 수 있습니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">Dynamic Chat에서 제품 프로필 편집</a> 및 의 사용자 지정 집합으로 사용자 지정 프로필을 만듭니다. <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">구독 내에서 사용 가능한 권한</a>.</li></td>
  </tr>
  <tr>
    <td>사용자</td>
    <td><li>채팅 사용자를 추가 및 제거할 시기에 대한 정책을 만듭니다.</li>
    <li>다음을 보유해야 하는 사용자에 대한 정책 만들기 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup#access-admin-console">Adobe Dynamic Chat 제품 관리자 권한.</a></li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-a-chat-user">원하는 제품 프로필에 사용자 추가</a>.</li></td>
  </tr>
</tbody>
</table>

## 지속적인 시스템 업데이트 및 통신 설정 {#system-updates}

<table>
<thead>
  <tr>
    <th style="width:20%">영역</th>
    <th style="width:80%">작업 항목</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Marketo 상태 업데이트 Adobe</td>
    <td><li><a href="https://status.adobe.com/cloud/experience_cloud">Adobe Marketo Engage 상태 업데이트 구독</a>.</li></td>
  </tr>
  <tr>
    <td>알림</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications#subscribe-to-notifications">관리자 알림 구독</a> 스마트 캠페인의 오류 및 CRM 동기화와 함께 발견된 중요한 문제와 같은 중요한 문제에 대해 설명합니다.</li></td>
  </tr>
</tbody>
</table>

<p>

이제 Marketo Engage 계정을 사용할 준비가 되었으므로 [새 Marketo Engage 인스턴스에 대한 우수 사례](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/where-to-start.md) 섹션 을 통해 투자를 최대한 활용하고 장기적인 성공을 위한 환경을 구축할 수 있습니다.

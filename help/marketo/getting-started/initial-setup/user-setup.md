---
description: 새로운 Marketo Engage 인스턴스를 시작하기 전에 지속적인 사용을 위한 몇 가지 기본 단계를 완료해야 합니다. 이러한 단계에는 사용자 계정 설정, 관리자 설정 지원 및 지속적인 시스템 업데이트 구독이 포함됩니다.
short-description: 초기 설정 단계를 완료한 후 원활하고 지속적인 사용을 위해 기본 요소를 설정하는 방법에 대해 알아봅니다.
title: 사용자 설정 체크리스트
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
source-git-commit: 471a777041361cfebdc8b7139b618ff4dc03e8a8
workflow-type: tm+mt
source-wordcount: '823'
ht-degree: 7%

---

# 사용자 설정 체크리스트 {#user-setup-checklist}

[초기 설정 단계](/help/marketo/getting-started/initial-setup/setup-steps.md){target="_blank"}를 모두 완료했으므로 원활한 지속적인 사용을 위해 몇 가지 기본 요소를 설정해야 합니다. 이를 통해 Marketo Engage을 통한 여정의 토대를 마련하고 기능을 최대한 활용할 수 있습니다. 그럼 시작해 보겠습니다!

>[!NOTE]
>
>이 체크리스트와 새 인스턴스에 대한 [모범 사례 목록](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx)을(를) 함께 다운로드하고 단계를 확인할 수도 있습니다.

## Identity Management Adobe Marketo Engage {#marketo-engage-on-adobe-identity-management}

새 Marketo Engage 구독이 [IMS(Adobe Identity Management System)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html)에 온보딩되었습니다. Adobe Admin Console에서 다음 사용자 관리 검토를 진행합니다.

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
    <li>Adobe 계정 팀(계정 관리자)에 문의하거나 <code>marketocares@marketo.com</code>에게 전자 메일을 보내 조직에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console 시스템 관리자</a> 권한을 가진 사람을 확인합니다.</li></ul>
    <li>Adobe ID을 활성화하려면 'Marketo Engage 제품 관리자' 초대를 수락하십시오. 역할이 Adobe Admin Console에 할당되면 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup.html?lang=en#create-a-product-profile">환영 전자 메일</a>이 전송됩니다.</li></td>
  </tr>
  <tr>
    <td>제품 프로필</td>
    <td><li>Adobe Admin Console의 Marketo Engage <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup#create-a-product-profile">제품 프로필</a>에 원하는 모든 사용자를 할당합니다.</li>
    <ul>
    <li>제품 프로필에 추가하기 전에 Marketo Engage &gt; 관리자 &gt; 사용자 및 역할에서 사용자 역할을 할당할 수 없습니다.</li>
    <li>각 구독은 독립 실행형 제품 프로필이 됩니다. 여러 제품 프로필(예: 프로덕션 및 테스트 샌드박스)에 원하지 않는 사용자가 추가되면 모든 제품 프로필에서 사용자를 삭제해야 합니다. 그렇지 않으면 Marketo Engage에 계속 액세스할 수 있습니다.</li></ul></td>
  </tr>
  <tr>
    <td>사용자</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.html">사용자 만들기</a>의 시기에 대한 정책을 만드십시오.</li> <li>사용자를 제거할 시기에 대한 정책을 만듭니다.</li>
    <p><img src="assets/note-icon.png" alt="메모 아이콘"> 참고: 사용자를 제거하려면 시스템 관리자여야 합니다.
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe 시스템 관리자 및 Marketo Engage 제품 관리자 권한을 가져야 하는 사용자를 결정합니다.</a> <li>원하는 제품 프로필에 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user">사용자를 추가</a>합니다.</li>
    <li>각 API 사용 사례에 대해 하나의 API 사용자를 만듭니다.</li></td>
  </tr>
  <tr>
    <td>User Management API(해당되는 경우)</td>
    <td><li><a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html">Adobe 사용자 관리 API</a>를 사용하여 사용자를 초대하고 업데이트하고 삭제합니다.</li>
    <li><a href="https://developer.adobe.com/umapi/">Adobe 사용자 관리 API</a>를 사용하여 역할(예: 관리자, 지원 관리자, 개발자)을 추가하거나 제거합니다.</li>
    </td>
  </tr>
  <tr>
    <td>제품 지원 관리자</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#create-a-support-ticket-with-admin-console">Adobe Admin Console에서 지원 티켓을 제출</a>하려면 시스템 관리자가 관리하는 구독에 '제품 지원 관리자' 역할을 할당해야 합니다. 조직의 시스템 관리자만 <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#assign-the-support-admin-role">사용자를 이 역할에 할당</a>할 수 있습니다.</li>
    <li>시스템 관리자로부터 Marketo Engage 구독에 대한 지원 관리자라는 이메일을 받았을 수 있습니다. 이 경우 전자 메일에서 <a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#assign-the-support-admin-role">'시작하기'</a>를 클릭하여 조직에 가입하십시오.</li>
    <li>하나 이상의 백업 담당자와 함께 적절한 담당자를 결정하고 그에 따라 시스템 관리자에게 제품 지원 관리자 역할을 할당하도록 합니다.</li></td>
  </tr>
</tbody>
</table>

## Identity Management 설정 Adobe 시 Dynamic Chat {#dynamic-chat-on-adobe-identity-management}

Marketo Engage의 기본 대화 자동화 채널인 [Dynamic Chat](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html)을(를) 사용하려면 [Adobe Admin Console](https://adminconsole.adobe.com/){target="_blank"}의 아래 단계에 따라 사용자 권한 설정을 진행하십시오.

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
    <td><li>Adobe 조직 시스템 관리자가 Adobe 제품 관리자 역할을 부여했는지 확인합니다.</li> 
    <ul><li>Adobe 계정 팀(계정 관리자)에 문의하거나 <code>marketocares@marketo.com</code>에게 전자 메일을 보내 조직에서 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console 시스템 관리자</a> 권한을 가진 사람을 확인합니다.</li></ul>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">'Dynamic Chat 제품 관리자'</a> 초대를 수락합니다. Marketo Engage 인스턴스에서 Dynamic Chat이 활성화되어 있고 사용자가 시스템 관리자로 지정되어 있으면 <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">환영 전자 메일</a>이 전송됩니다.</li></td>
  </tr>
  <tr>
    <td>제품 프로필</td>
    <td><li>Adobe Admin Console에서 원하는 모든 사용자를 Dynamic Chat의 제품 프로필에 할당합니다.</li> 
    <ul>
    <li>여러 제품 프로필에 원하지 않는 사용자가 추가되면 모든 제품 프로필에서 사용자를 삭제해야 합니다. 그렇지 않으면 Dynamic Chat에 계속 액세스할 수 있습니다.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">Dynamic Chat에서 제품 프로필을 편집</a>하고, 구독 내에서 사용할 수 있는 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">사용 권한의 사용자 지정 집합으로 사용자 지정 프로필을 만들 수 있습니다</a>.</li></td>
  </tr>
  <tr>
    <td>사용자</td>
    <td><li>채팅 사용자를 추가 및 제거할 시기에 대한 정책을 만듭니다.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup#access-admin-console">Adobe Dynamic Chat 제품 관리자 권한이 있어야 하는 사용자에 대한 정책을 만드십시오.</a></li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-a-chat-user">원하는 제품 프로필에 사용자를 추가</a>.</li></td>
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
    <td><li>스마트 캠페인의 오류 및 CRM 동기화에서 발견되는 중요한 문제와 같은 중요한 문제에 대해 <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications#subscribe-to-notifications">관리자 알림 구독</a>을 참조하십시오.</li></td>
  </tr>
</tbody>
</table>

<p>

이제 Marketo Engage 계정을 사용할 준비가 되었으므로 [새 Marketo Engage 인스턴스에 대한 모범 사례](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/where-to-start.md){target="_blank"} 섹션을 검토하여 투자를 최대한 활용하고 장기적인 성공을 위한 환경을 구축하십시오.

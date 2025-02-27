---
description: Adobe IMS 문제 해결 안내서 - Marketo 문서 - 제품 설명서
title: Adobe IMS 문제 해결 안내서
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: e5c6ac7df0f8f6e7726de1ced598d390a6cf1deb
workflow-type: tm+mt
source-wordcount: '543'
ht-degree: 0%

---

# Adobe IMS 문제 해결 안내서 {#adobe-ims-troubleshooting-guide}

IMS 사용자 마이그레이션 프로세스 중에 마이그레이션되는 각 Marketo Engage 사용자에 대해 Adobe 사용자가 만들어집니다. 경우에 따라 Active Directory의 사용자 레코드 또는 이메일 주소 문제와 관련된 다양한 이유로 만들어지지 않습니다. 이런 경우 Marketo Engage 관리자는 자가 마이그레이션 콘솔의 사용자 마이그레이션 상태 필드에 원인을 보게 됩니다. 아래의 다양한 Adobe 사용자 생성 문제를 해결하는 방법을 참조하십시오.

## 오류 메시지 {#error-messages}

* <a href="#not-in-directory">디렉터리에 없음</a>
* <a href="#gmail-invalid-character">잘못된 문자</a>
* <a href="#inactive-user">비활성 사용자</a>
* <a href="#not-in-domain">도메인에 없음</a>
* <a href="#create-failure">만들기 실패</a>
* <a href="#type2e-user-failure">Type2e 사용자 실패</a>

<table>
<thead>
  <tr>
    <th style="width:20%">오류 메시지</th>
    <th style="width:40%">근본 원인</th>
    <th style="width:40%">해상도</th>
  </tr>
  </thead>
<tbody>
  <tr>
    <td><i><a id="not-in-directory">디렉터리에 없음</a></i></td>
    <td>사용자가 AD(Active Directory)에 없습니다. AD 동기화가 활성화된 SSO가 있는 조직의 경우 IdP(ID 공급자)를 통해서만 사용자 생성이 허용됩니다. 따라서 사용자를 마이그레이션하는 동안 Admin Console을 통해 사용자를 추가할 수 없습니다.</td>
    <td>마이그레이션 - 적절한 사용 권한을 사용하여 사용자를 Active Directory에 추가해야 합니다. Marketo 관리자 : 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행합니다. 
    <br>마이그레이션하지 않음 - Marketo 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 완료 버튼은 마이그레이션 또는 건너뛰기로 모든 사용자를 처리할 때 나타납니다. 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.</td>
  </tr>
  <tr>
    <td><i><a id="gmail-invalid-character">Gmail 잘못된 문자</a></i></td>
    <td>Adobe의 보안 정책에 따라 '.' 및 '+' 기호는 Gmail 도메인의 전자 메일 주소에서만 사용할 수 있습니다.  
    <br>Gmail 도메인이 아닌 전자 메일 주소에는 두 특수 문자를 사용할 수 있습니다. </td>
    <td>마이그레이션 - Adobe의 보안 정책을 준수하려면 Marketo Engage에서 이메일 주소를 업데이트해야 합니다. Marketo 관리자 : 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행합니다.<br>마이그레이션하지 않음 - Marketo 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 완료 버튼은 마이그레이션 또는 건너뛰기로 모든 사용자를 처리할 때 나타납니다. 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.</td>
  </tr>
  <tr>
    <td><i><a id="inactive-user">비활성 사용자</a></i></td>
    <td>AD 동기화가 활성화되었으며 사용자의 페더레이션 계정이 존재하지만 비활성/비활성 상태입니다.</td>
    <td>마이그레이션 - 사용자의 상태 및 적절한 권한을 복원해야 합니다. Marketo 관리자 : 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행합니다.
    <br>마이그레이션하지 않음 - Marketo 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 완료 버튼은 마이그레이션 또는 건너뛰기로 모든 사용자를 처리할 때 나타납니다. 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.</td>
  </tr>
  <tr>
    <td><i><a id="not-in-domain">도메인에 없음</a></i></td>
    <td>Admin Console에서 도메인 적용이 활성화되지만 사용자의 이메일 주소 도메인이 허용된 도메인 중 하나가 아닙니다. 
    <br>도메인 적용 정책이 디렉터리 수준에서 설정됩니다.</td>
    <td>마이그레이션 - 도메인 시행 정책을 준수하려면 Marketo Engage에서 전자 메일 주소를 업데이트해야 합니다. 그렇지 않으면 시스템 관리자가 <a href="https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories">할 수 있습니다. 
    도메인을 DE(Domain Enforcement)가 사용하지 않도록 설정한 다른 디렉터리 </a>(으)로 이동하거나 <a href="https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html">새 디렉터리를 만듭니다</a>. 이 디렉터리는 DE 정책에 포함되지 않습니다. Marketo 관리자 : 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행합니다. <br>마이그레이션하지 않음 - Marketo 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 완료 버튼은 마이그레이션 또는 건너뛰기로 모든 사용자를 처리할 때 나타납니다. 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.</td>
  </tr>
  <tr>
    <td><i><a id="create-failure">만들기 실패</a></i></td>
    <td>백엔드의 다양한 이유.</td>
    <td>지원 사례를 제출하십시오.</td>
  </tr>
  <tr>
    <td><i><a id="type2e-user-failure">Type2e 사용자 실패</a></i></td>
    <td>백엔드의 다양한 이유.</td>
    <td>지원 사례를 제출하십시오.</td>
  </tr>
</tbody>
</table>

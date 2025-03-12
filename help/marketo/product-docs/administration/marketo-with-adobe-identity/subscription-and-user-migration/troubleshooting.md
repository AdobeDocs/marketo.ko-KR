---
description: Adobe IMS 사용자 마이그레이션 문제 해결 안내서 - Marketo 문서 - 제품 설명서
title: Adobe IMS 사용자 마이그레이션 문제 해결 안내서
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: e96bc8676a73694ec60f46bb045f2a6ea5d8069c
workflow-type: tm+mt
source-wordcount: '674'
ht-degree: 0%

---

# Adobe IMS 사용자 마이그레이션 문제 해결 안내서 {#adobe-ims-user-migration-troubleshooting-guide}

IMS 사용자 마이그레이션 프로세스 중에 Adobe 사용자는 마이그레이션되는 각 Marketo Engage 사용자에 대해 만들어집니다(동일한 이메일 주소가 이미 있는 경우가 아니면). Active Directory에 있는 사용자의 레코드 또는 이메일 주소 문제로 인해 만들어지지 않는 경우가 있습니다. 이런 경우 Marketo Engage 관리자는 자가 마이그레이션 콘솔에 있는 사용자의 마이그레이션 상태 필드에 원인을 보게 됩니다.

## 오류 메시지 {#error-messages}

먼저 사용자를 마이그레이션해야 하는지 여부를 결정합니다. 마이그레이션해야 하는 사용자의 문제는 따라야 할 해결 단계에 영향을 미칩니다.

특정 오류로 바로 이동하려면 오른쪽의 &quot;이 페이지에서&quot; 섹션을 사용합니다.

### 디렉터리에 없음 {#not-in-directory}

**근본 원인**: 사용자가 AD(Active Directory)에 없습니다. AD 동기화가 활성화된 SSO가 있는 조직의 경우 IdP(ID 공급자)를 통해서만 사용자 생성이 허용됩니다. 따라서 사용자를 마이그레이션하는 동안 Admin Console을 통해 사용자를 추가할 수 없습니다.

**해상도**:

_사용자를 마이그레이션할 필요가 없는 경우_ - Marketo Engage 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

_사용자를 마이그레이션해야 하는 경우_ - 시스템 관리자가 적절한 사용 권한을 가진 Active Directory에 사용자를 추가해야 합니다. Marketo Engage 관리자를 사용하여 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### Gmail 잘못된 문자 {#gmail-invalid-character}

**근본 원인**: Adobe 보안 정책에 따라 `.` 및 `+` 문자는 Gmail 전자 메일 주소에 사용할 수 없습니다. 두 문자 모두 Gmail이 아닌 이메일 주소에 허용됩니다.

**해상도**:

_사용자를 마이그레이션할 필요가 없는 경우_ - Marketo Engage 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

_사용자를 마이그레이션해야 하는 경우_ - Adobe의 보안 정책을 준수하고 다시 확인하려면 Marketo Engage에서 전자 메일 주소를 업데이트해야 합니다. Marketo 관리자를 사용하여 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### 비활성 사용자 {#inactive-user}

**근본 원인**: AD 동기화가 사용하도록 설정되어 있고 사용자의 페더레이션 계정이 있지만 비활성/비활성 상태입니다.

**해상도**:

_사용자를 마이그레이션할 필요가 없는 경우_ - Marketo Engage 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

_사용자를 마이그레이션해야 하는 경우_ - 사용자의 상태와 적절한 사용 권한을 복원해야 합니다. Marketo Engage 관리자를 사용하여 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### 도메인에 없음 {#not-in-domain}

**근본 원인**: Admin Console에서 도메인 적용을 사용하도록 설정했지만 사용자의 전자 메일 주소 도메인이 허용된 도메인 중 하나가 아닙니다.

**해상도**:

_사용자를 마이그레이션할 필요가 없는 경우_ - Marketo Engage 관리자가 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

_사용자를 마이그레이션해야 하는 경우_ - DE(도메인 시행) 정책을 준수하려면 Marketo Engage에서 전자 메일 주소를 업데이트해야 합니다. 또는 시스템 관리자가 [도메인을 다른 DE(Domain Enforcement) 사용 안 함 디렉터리로 이동](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"}하거나 DE 정책에 없는 [새 디렉터리를 만들기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}할 수 있습니다. Marketo Engage 관리자를 사용하여 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### 만들기 실패 {#create-failure}

**근본 원인**: 이 오류는 백엔드의 다양한 원인으로 인해 발생할 수 있습니다.

**해상도**:

[Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 대한 관련 세부 정보가 포함된 지원 사례를 제출하십시오.

### Type2e 사용자 실패 {#type2e-user-failure}

**근본 원인**: 이 오류는 백엔드의 다양한 원인으로 인해 발생할 수 있습니다.

**해상도**:

[Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 대한 관련 세부 정보가 포함된 지원 사례를 제출하십시오.

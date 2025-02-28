---
description: Adobe IMS 문제 해결 안내서 - Marketo 문서 - 제품 설명서
title: Adobe IMS 문제 해결 안내서
hide: true
hidefromtoc: true
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
source-git-commit: 2a01045abbc23bce9531c64e3494fb12a9adf1bd
workflow-type: tm+mt
source-wordcount: '602'
ht-degree: 0%

---

# Adobe IMS 문제 해결 안내서 {#adobe-ims-troubleshooting-guide}

IMS 사용자 마이그레이션 프로세스 중에 마이그레이션되는 각 Marketo Engage 사용자에 대해 Adobe 사용자가 만들어집니다. 경우에 따라 Active Directory의 사용자 레코드 또는 이메일 주소 문제와 관련된 다양한 이유로 만들어지지 않습니다. 이런 경우 Marketo Engage 관리자는 자가 마이그레이션 콘솔의 사용자 마이그레이션 상태 필드에 원인을 보게 됩니다.

## 오류 메시지 {#error-messages}

오른쪽의 &quot;이 페이지에서&quot; 섹션을 사용하여 특정 오류로 바로 이동하고 해결 방법을 알아봅니다.

### 디렉터리에 없음 {#not-in-directory}

_근본 원인_: 사용자가 AD(Active Directory)에 없습니다. AD 동기화가 활성화된 SSO가 있는 조직의 경우 IdP(ID 공급자)를 통해서만 사용자 생성이 허용됩니다. 따라서 사용자를 마이그레이션하는 동안 Admin Console을 통해 사용자를 추가할 수 없습니다.

_해상도_:

마이그레이션 전 - Marketo Enage 관리자는 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

마이그레이션 후 - 적절한 사용 권한을 가진 사용자를 Active Directory에 추가해야 합니다. Marketo Engage 관리자 를 통해 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### Gmail 잘못된 문자 {#gmail-invalid-character}

_근본 원인_: Adobe 보안 정책에 따라 `.` 및 `+` 문자는 Gmail 전자 메일 주소에 사용할 수 없습니다. 두 문자 모두 Gmail이 아닌 이메일 주소에 허용됩니다.

_해상도_:

마이그레이션 전 - Marketo Enage 관리자는 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

마이그레이션 후 - Adobe의 보안 정책을 준수하려면 Marketo Engage에서 이메일 주소를 업데이트해야 합니다. Marketo 관리자 : 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행합니다.

### 비활성 사용자 {#inactive-user}

_근본 원인_: AD 동기화가 사용하도록 설정되어 있고 사용자의 페더레이션 계정이 있지만 비활성/비활성 상태입니다.

_해상도_:

마이그레이션 전 - Marketo Enage 관리자는 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

마이그레이션 후 - 사용자의 상태 및 적절한 권한을 복원해야 합니다. Marketo Engage 관리자 를 통해 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### 도메인에 없음 {#not-in-domain}

_근본 원인_: Admin Console에서 도메인 적용을 사용하도록 설정했지만 사용자의 전자 메일 주소 도메인이 허용된 도메인 중 하나가 아닙니다.

_해상도_:

마이그레이션 전 - Marketo Enage 관리자는 마이그레이션 콘솔에서 사용자를 건너뜁니다. 마이그레이션 또는 건너뛰기로 모든 사용자를 고려할 때 &quot;마이그레이션 완료&quot; 버튼이 표시됩니다. 버튼을 클릭하여 사용자 마이그레이션 프로세스를 완료합니다.

마이그레이션 후 - DE(Domain Enforcement) 정책을 준수하려면 Marketo Engage에서 이메일 주소를 업데이트해야 합니다. 또는 시스템 관리자가 [도메인을 다른 DE(Domain Enforcement) 사용 안 함 디렉터리로 이동](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"}하거나 DE 정책에 없는 [새 디렉터리를 만들기](https://helpx.adobe.com/kr/enterprise/using/set-up-identity.html){target="_blank"}할 수 있습니다. Marketo Engage 관리자 를 통해 마이그레이션 콘솔에서 이 사용자에 대한 사용자 마이그레이션을 다시 실행하십시오.

### 만들기 실패 {#create-failure}

_근본 원인_: 이 오류는 백엔드의 다양한 원인으로 인해 발생할 수 있습니다.

_해상도_:

마이그레이션 전 - [아직 마이그레이션되지 않음](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 대한 지원 사례를 제출하십시오.

마이그레이션 후 - [이미 마이그레이션됨](https://experienceleague.adobe.com/home?support-tab=home#support){target="_blank"}에 대한 지원 사례를 제출하십시오.

### Type2e 사용자 실패 {#type2e-user-failure}

_근본 원인_: 이 오류는 백엔드의 다양한 원인으로 인해 발생할 수 있습니다.

_해상도_:

마이그레이션 전 - [아직 마이그레이션되지 않음](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 대한 지원 사례를 제출하십시오.

마이그레이션 후 - [이미 마이그레이션됨](https://experienceleague.adobe.com/home?support-tab=home#support){target="_blank"}에 대한 지원 사례를 제출하십시오.

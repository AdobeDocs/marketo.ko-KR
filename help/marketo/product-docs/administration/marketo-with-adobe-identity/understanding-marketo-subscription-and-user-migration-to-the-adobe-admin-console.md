---
description: Marketo 구독 및 Adobe Admin Console으로의 사용자 마이그레이션 이해 - Marketo 문서 - 제품 설명서
title: Marketo 구독 및 Adobe Admin Console으로의 사용자 마이그레이션 이해
exl-id: 91e7b56b-2563-4986-a55c-f9760ea88b05
feature: Marketo with Adobe Identity
source-git-commit: cc7f5880dba926349ddf763e5b28fc4a922aa26d
workflow-type: tm+mt
source-wordcount: '1169'
ht-degree: 0%

---

# Marketo 구독 및 Adobe Admin Console으로의 사용자 마이그레이션 이해 {#understanding-marketo-subscription-and-user-migration-to-the-adobe-admin-console}

Adobe은 Adobe Marketo Engage 구독 및 사용자를 관리하는 방법을 향상시켜 귀사와 조직에 향상된 생산성을 제공합니다. 이 변경의 일부로 Adobe은 Marketo Engage 구독과 사용자를 Adobe Admin Console으로 마이그레이션하고 있습니다. 이는 필요한 마이그레이션이며 마케팅 워크플로우, 콘텐츠, 통합 또는 자산에는 영향을 주지 않습니다.

Adobe Admin Console을 사용하여 를 통해 전체 조직에서 Adobe 권한을 관리하는 방법을 알아봅니다. [Enterprise 및 Teams 관리 안내서](https://helpx.adobe.com/kr/enterprise/admin-guide.html){target="_blank"}.

## 변경 사항 {#what-is-changing}

마이그레이션의 일부로 구독 및 사용자 관리가 Marketo 애플리케이션 내에서 Adobe Admin Console으로 이동합니다.

* **시스템 관리자는 Adobe Admin Console에서 구독을 관리합니다.**. 모든 Adobe 제품을 하나의 콘솔에서 볼 수 있습니다.

* **제품 관리자는 Adobe Admin Console에서의 사용자 및 사용자 액세스를 관리합니다.**. 모든 Adobe 구독에 대한 사용자를 추가하고 제거합니다.

* **사용자가 Adobe ID로 로그인합니다.**. Adobe은 기존 사용자를 Adobe Admin Console으로 마이그레이션합니다. 사용자는 새로운 Adobe ID(Adobe ID 또는 Adobe Federated ID(SSO))를 사용하여 Marketo 구독에 로그인합니다.

* **다른 모든 기능을 관리하는 방법에는 변경 사항이 없습니다** 기능, 사용자 역할, 작업 공간, 기능 및 비헤이비어 관리를 포함하여 Marketo Engage 애플리케이션 자체 내에서.


## 마이그레이션 여정 타임라인 {#migration-journey-timeline}

Adobe은 먼저 Marketo Engage 구독을 Adobe Admin Console으로 마이그레이션한 다음 확인된 이메일 주소가 있는 기존 사용자를 모두 마이그레이션합니다. 시스템 관리자 또는 Marketo 제품 관리자인 경우 마이그레이션 여정을 안내하는 이메일을 받게 됩니다. 다음은 예상할 수 있는 작업의 타임라인입니다.

### 구독 마이그레이션 완료 {#subscription-migration-complete}

시스템 관리자는 Adobe Admin Console으로 구독 마이그레이션이 완료되면 이메일을 받게 됩니다.

시스템 관리자는 Marketo 사용자에게 미치는 영향을 최소화하기 위해 사용자 마이그레이션이 시작되기 전에 몇 가지 필요한 단계를 완료해야 할 수 있습니다.

* Marketo 사용자가 현재 SSO로 로그인한 경우에는 사용자가 SSO로 계속 로그인할 수 있도록 Adobe Admin Console에서 SSO를 설정해야 합니다. Marketo 사용자가 현재 SSO를 활용하지 않지만 Adobe Admin Console에서 설정하려는 경우 마이그레이션 여정에서 이 시점에서 설정할 수 있습니다.

* Adobe Admin Console에서 다른 Adobe 제품을 이미 관리하는 경우, Adobe은 사용자를 기존 콘솔로 자동으로 마이그레이션하는 데 동의할 것을 요청할 수 있습니다. 이메일의 &quot;시작하기&quot; 버튼을 클릭하여 동의 페이지로 이동합니다.

현재 사용자 관리에 대한 변경 사항은 없습니다. Marketo 관리자는 Marketo 관리 영역에서 사용자를 계속 관리하며, 사용자는 사용자 마이그레이션이 완료될 때까지 Marketo ID로 계속 로그인합니다.

### 사용자 마이그레이션 예약 {#schedule-user-migration}

시스템 관리자가 이전 섹션에 설명된 사전 요구 사항을 완료하면 Adobe은 30일 전에 사용자 마이그레이션을 자동으로 예약하고 Marketo 제품 관리자와 통신하여 사용자 마이그레이션을 관리합니다.

Marketo 제품 관리자는 다음 작업을 수행합니다.

* 예약된 사용자 마이그레이션 시작 날짜가 30일 앞으로 다가온 이메일을 수신합니다.

* Marketo 관리 영역 내에 있는 Marketo 마이그레이션 콘솔에 액세스하여 구독의 마이그레이션 날짜를 변경할 수 있습니다.

>[!NOTE]
>
>마이그레이션의 복잡성으로 인해 날짜 변경은 예약된 날짜를 30일 이내로 제한됩니다. 다음으로 이메일 보내기 `marketocares@marketo.com` 더 늦은 날짜가 필요한 경우.

* 사용자 마이그레이션 시작 날짜까지의 카운트다운을 표시하는 My Marketo 배너를 참조하십시오.

* 사용자 마이그레이션 시작일 전날에 미리 알림 이메일을 수신합니다.

### 사용자를 마이그레이션할 날 준비 {#prepare-users-for-migration-day}

Marketo 제품 관리자는 모든 사용자가 마이그레이션할 날을 준비해야 합니다.

* 확인 [전자 메일 확인](/help/marketo/product-docs/administration/users-and-roles/email-verification.md){target="_blank"} Marketo 관리 영역의 모든 사용자에 대한 상태입니다. 이메일 주소를 확인하지 않은 사용자에게 이메일 주소를 확인하도록 권장하고 사용자가 확인 프로세스를 완료하는 데 발생하는 모든 문제를 해결하도록 지원합니다.

* Adobe ID로의 향후 마이그레이션에 대해 모든 사용자를 준비합니다.

>[!NOTE]
>
>사용자가 마이그레이션되면 Adobe에서 Marketo에 로그인하는 방식의 변경 사항을 알리는 이메일을 받게 됩니다. 기존 Adobe ID으로 로그인하거나 동일한 이메일 주소를 사용하여 새 사용자를 설정하여 Adobe ID를 사용하여 로그인하라는 초대를 처음으로 수락하도록 사용자를 초대합니다.

>[!IMPORTANT]
>
>Marketo Engage 사용자가 이메일 주소를 확인하지 않는 경우, 이메일 주소는 Adobe ID으로 마이그레이션되지 않고 구독에 대한 마이그레이션이 완료된 후 Marketo 구독에 대한 액세스 권한을 잃게 됩니다. 액세스 권한을 다시 얻으려면 Marketo 제품 관리자가 새 사용자로 추가해야 합니다.

### 마이그레이션 당일 기대 사항 {#what-to-expect-on-migration-day}

사용자 마이그레이션은 마이그레이션 시작일 자정(태평양 표준시)에 시작됩니다.

**Adobe은 먼저 Marketo 관리자를 자동으로 마이그레이션합니다.**. Marketo 관리자는 Adobe ID로 마이그레이션되면 이전에 수행한 다른 역할과 함께 Marketo 애플리케이션 내에서 Adobe 제품 관리자 역할이 할당됩니다.

**Marketo 구독의 사용자 수가 75명 미만인 경우**, Adobe은 나머지 사용자를 자동으로 마이그레이션합니다. 이 워크플로우는 Adobe Marketo 사용자의 오버헤드를 최소화하기 위해 최고 수준의 자동화를 제공하는 것을 목표로 합니다. 마이그레이션을 실행하는 데 필요한 작업은 없습니다.

**Marketo 구독이 75명 이상인 경우**, Marketo 제품 관리자는 Marketo 관리 영역에 있는 Marketo 마이그레이션 콘솔의 셀프서비스 사용자 마이그레이션 영역에 액세스할 수 있습니다. 사용자 마이그레이션 프로세스 중에 더 세밀한 제어가 필요한 사용자를 위해 Marketo 제품 관리자는 일괄로 마이그레이션하거나 동시에 마이그레이션할 사용자를 선택할 수 있습니다. 사용자를 선택하면 관리자는 나중에 &quot;지금 마이그레이션&quot; 또는 &quot;마이그레이션 예약&quot;할 수 있는 옵션을 제공하므로 관리자는 유연성을 극대화하고 언제 마이그레이션되는지 제어할 수 있습니다.

>[!NOTE]
>
>사용자 마이그레이션 중에도 제품에 대한 액세스 손실이 발생하지 않습니다. 사용자를 마이그레이션하는 동안 사용자가 로그인하면 사용자가 로그아웃되고 마이그레이션이 완료된 후 Adobe ID를 사용하여 몇 분 안에 다시 로그인하라는 메시지가 표시됩니다.

Adobe이 마이그레이션되면 사용자는 Marketo에 로그인하는 방식으로 변경되었음을 알리는 이메일을 사용자로부터 받게 됩니다. 기존 Adobe ID으로 로그인하거나 동일한 이메일 주소를 사용하여 새 Adobe ID을 설정하여 Adobe ID를 사용하여 로그인하라는 초대를 처음으로 수락하도록 사용자를 초대합니다. 자세한 내용은 [Adobe으로 로그인](/help/marketo/product-docs/administration/marketo-with-adobe-identity/user-sign-in-with-adobe-id.md){target="_blank"} 기사.

## 사용자 마이그레이션 완료 {#user-migration-complete}

모든 관리자 및 사용자가 마이그레이션되면 Adobe은 이메일을 통해 모든 시스템 관리자 및 제품 관리자에게 알립니다. 현재 해당 구독의 모든 Marketo 사용자는 Adobe ID를 사용하여 Marketo에 로그인하고 제품 관리자는 Adobe Admin Console에서만 사용자를 관리합니다.

## 지원 받기 {#get-support}

구독 또는 사용자 마이그레이션에 대한 추가 지원이 필요하면 이메일을 보내주십시오. `marketocares@marketo.com`.

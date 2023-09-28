---
description: 내 판매 활동 및 활동 필드가 Salesforce와 동기화되지 않는 이유는 무엇입니까? - Marketo 문서 - 제품 설명서
title: 내 판매 활동 및 활동 필드가 Salesforce와 동기화되지 않는 이유는 무엇입니까?
exl-id: 0836876d-1b89-4464-a841-81320a6e45fd
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# 내 판매 활동 및 활동 필드가 Salesforce와 동기화되지 않는 이유는 무엇입니까? {#why-arent-my-sales-activities-and-activity-fields-syncing-to-salesforce}

**Salesforce에 동기화된 전자 메일 또는 통화 활동이 표시되지 않습니다.**

* Salesforce에 연결되어 있는지 확인하십시오. 각 사용자는 이메일 및 Salesforce 호출을 기록할 수 있는 연결이 필요합니다.
* 다음을 구성했는지 확인합니다. [Salesforce 동기화 설정](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md){target="_blank"}.
* 이메일은 기본 조회로 Salesforce ID를 기반으로 하고 보조 조회로 이메일 주소를 기반으로 레코드 조회를 수행합니다. 개인 레코드에서 Salesforce ID 및 이메일 주소가 연결되어 있는지 확인할 수 있습니다. [작업 웹 앱](https://toutapp.com/next#command_center){target="_blank"}.
* 호출은 Salesforce ID만 기반으로 레코드 조회를 수행합니다. Salesforce ID가 Actions의 개인 레코드에 없으면 호출이 기록되지 않습니다. 에서 개인 레코드에 Salesforce ID가 연결되어 있는지 확인할 수 있습니다. [작업 웹 앱](https://toutapp.com/next#command_center){target="_blank"}.

**Salesforce 업데이트에 활동 필드가 표시되지 않습니다.**

전자 메일이 표시되지 않는 경우 [활동 속성 필드](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} salesforce에서 업데이트하십시오. 팀의 필드 접근성에 대한 제한 때문일 수 있습니다. Salesforce 필드 수준 보안을 사용하면 Salesforce 관리자는 사용자가 보고 편집할 수 있는 정보에 대한 제한을 설정할 수 있습니다. 작업 사용자에게 이러한 필드를 보고 편집할 수 있는 액세스 권한이 없는 경우 작업 활동 동기화에서 이러한 필드를 업데이트하지 못합니다.

* Salesforce 관리자와 협력하여 이러한 보안 설정이 [작업 Salesforce 활동 필드](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"}.
* Salesforce 관리자의 경우 보안 제어 탭에서 필드 접근성을 확인할 수 있습니다. 작업이 상호 작용하는 주요 객체는 가망 고객, 연락처, 계정, 기회 및 작업/활동입니다.

>[!NOTE]
>
>Lead, Contact, Account 및 Opportunity 객체와 연관된 필드는 Sales Insight Salesforce 패키지와 함께 설치됩니다. 연결된 필드 [작업/활동 레코드 유형을 만들어야 합니다.](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-package-configuration/logging-sales-activity-attributes-to-salesforce.md){target="_blank"} Salesforce 관리자

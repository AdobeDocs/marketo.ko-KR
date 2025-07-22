---
unique-page-id: 7515131
description: SFDC 동기화 - 리드/연락처 삭제 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드/연락처 삭제
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 0%

---

# SFDC 동기화: 리드/연락처 삭제 {#sfdc-sync-deleting-a-lead-contact}

다음은 몇 가지 세부 정보입니다.

* [!DNL Salesforce]에서 잠재 고객이 삭제되었다고 해서 Marketo에서 자동으로 사람을 삭제하지 않습니다. 대신 &quot;SFDC이 삭제되었습니다.&quot; 필드가 true로 설정됩니다. 원하는 경우 이 필드를 트리거오프하여 Marketo에서 삭제할 수 있습니다.
* [사용자 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md) 흐름 동작. 이렇게 하면 MKTO에서 개인이 삭제되지만 `Salesforce`에서도 삭제할 수 있습니다.

* [SFDC에서 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) 흐름 작업: 이렇게 하면 SFDC의 리드가 삭제되지만 Marketo에서 사용자를 삭제할 수도 있습니다.
* 리드가 [!DNL Salesforce]에서 삭제된 경우(하지만 사람은 Marketo에서 삭제되지 않음) 이후 [동기화 대상 [!DNL Salesforce]](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 통해 실행되면 [!DNL Salesforce]에 새 리드가 만들어집니다.

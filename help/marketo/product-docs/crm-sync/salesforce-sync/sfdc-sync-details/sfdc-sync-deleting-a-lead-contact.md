---
unique-page-id: 7515131
description: SFDC 동기화 - 리드/연락처 삭제 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 잠재 고객/연락처 삭제
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# SFDC 동기화: 잠재 고객/연락처 삭제 {#sfdc-sync-deleting-a-lead-contact}

다음은 몇 가지 세부 정보입니다.

* Marketo Engage은 Salesforce에서 잠재 고객이 삭제되었다고 해서 자동으로 직원을 삭제하지 않습니다. 대신 필드 &quot;SFDC Is Deleted&quot;가 true로 설정됩니다. 원하는 경우 이 필드를 트리거오프하여 Marketo에서 삭제할 수 있습니다.
* [사용자 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md){target="_blank"} 흐름 동작. 이렇게 하면 MKTO에서 개인이 삭제되지만 `Salesforce`에서도 삭제할 수 있습니다.

* [SFDC에서 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md){target="_blank"} 흐름 작업: SFDC에서 리드가 삭제되지만 Marketo에서 사용자를 삭제할 수도 있습니다.
* 리드가 Salesforce에서 삭제된 경우(하지만 개인이 Marketo에서 삭제되지 않음) 이후에 [Salesforce와 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"} 흐름 작업을 실행하면 Salesforce에 새 리드가 만들어집니다.

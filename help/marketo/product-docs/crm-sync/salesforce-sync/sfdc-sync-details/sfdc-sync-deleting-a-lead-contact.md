---
unique-page-id: 7515131
description: SFDC 동기화 - 리드/연락처 삭제 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드/연락처 삭제
exl-id: b859357e-09c5-48e5-940e-f5b4e955e374
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# SFDC 동기화: 리드/연락처 삭제 {#sfdc-sync-deleting-a-lead-contact}

다음은 몇 가지 세부 사항입니다.

* Marketo은 리드가 Salesforce에서 삭제되었다고 해서 사람을 자동으로 삭제하지 않습니다. 대신 필드 &quot;SFDC가 삭제됨&quot; 플래그가 true로 설정됩니다. 원하는 경우 Marketo에서 삭제하도록 이 필드를 트리거할 수 있습니다.
* [개인 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md) 흐름 작업. MKTO에서 사람을 삭제하지만 삭제할 수 있습니다 `Salesforce` 그것도.

* [SFDC에서 삭제](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) 흐름 작업: 이렇게 하면 SFDC에서 리드가 삭제되지만 Marketo에서 리드를 삭제할 수도 있습니다.
* Salesforce에서 리드가 삭제되었지만 Marketo에서 개인이 삭제되지 않은 경우 이후 를 통해 실행되는 경우 [Salesforce와 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 수행하면 Salesforce에서 새 리드가 만들어집니다.

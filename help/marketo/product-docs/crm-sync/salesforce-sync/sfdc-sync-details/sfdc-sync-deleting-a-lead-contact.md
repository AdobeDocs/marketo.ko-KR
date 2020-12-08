---
unique-page-id: 7515131
description: SFDC 동기화 - 리드/연락처 삭제 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 리드/연락처 삭제
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '199'
ht-degree: 0%

---


# SFDC 동기화:리드/연락처 삭제 {#sfdc-sync-deleting-a-lead-contact}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

다음은 자세한 사항입니다.

* 리드가 Salesforce에서 삭제되었다고 해서 리드가 자동으로 삭제되지 않습니다. 대신 필드 &quot;SFDC가 삭제됨&quot; 플래그가 true로 설정됩니다. 원할 경우 이 필드를 트리거하여 Marketing To에서 삭제할 수 있습니다.
* [사람](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/delete-person.md) 흐름 삭제 작업. MKTO에서 사람을 삭제하지만 삭제할 수도 `Salesforce` 있습니다.

* [SFDC에서](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/delete-person-from-sfdc.md) 삭제 플로우 작업:이렇게 하면 SFDC에서 리드가 삭제되지만 Marketing To에서도 리드를 삭제할 수 있습니다.
* 리드가 Salesforce에서 삭제된 경우(Marketing Cloud에서는 삭제되지 않음) 이후에 Salesforce와 [동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md) 흐름 작업을 통해 실행되면 Salesforce에서 새 리드를 만듭니다.

다시 말해, 그것은 마법처럼 작동합니다!

![--](assets/image2015-5-20-15-3a3-3a27.png)


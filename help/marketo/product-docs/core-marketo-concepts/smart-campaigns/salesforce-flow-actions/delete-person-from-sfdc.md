---
unique-page-id: 1147031
description: SFDC에서 사람 삭제 - Marketing Docs - 제품 설명서
title: SFDC에서 사람 삭제
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 0%

---


# SFDC에서 사람 삭제 {#delete-person-from-sfdc}

Salesforce에서 특정 리드 세트를 제거하고 Marketing To에 있는 사람으로 두어야 하는 경우 SFDC에서 사람 삭제 작업을 사용할 수 있습니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

>[!NOTE]
>
>Salesforce와 통합된 경우에만 제공됩니다.

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **사람 작업을** 클릭하고 **Salesforce를 선택합니다**.

   ![](assets/person-actions-salesforce.png)

1. SFDC에서 **사람 삭제를 선택합니다**.

   ![](assets/delete-person-from-sfdc.png)

1. Marketing **To에서 삭제** 설정이 **false인지**&#x200B;확인하고 지금 **실행을 클릭합니다**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   흐름 단계가 실행된 후에도 Salesforce에서 리드가 아닌 Marketing에 남을 수 있습니다.

   >[!CAUTION]
   >
   >Marketing **To에서** Delete를 **true로 설정하고 Marketing** 사용자와 리드를 Salesforce에서 삭제하면 해당 리드는 영구적으로 삭제됩니다. 취소할 수 없습니다.


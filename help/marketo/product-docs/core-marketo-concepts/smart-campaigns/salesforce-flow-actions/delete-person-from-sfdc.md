---
unique-page-id: 1147031
description: SFDC에서 인물 삭제 - 마케팅 문서 - 제품 설명서
title: SFDC에서 인물 삭제
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---


# SFDC {#delete-person-from-sfdc}에서 인물 삭제

Salesforce에서 특정 리드 세트를 제거하고 Marketing에서 다른 리드를 두어야 하는 경우 SFDC에서 인물 삭제 플로우 작업을 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce와 통합되어야 이용 가능

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **사람 작업**&#x200B;을 클릭하고 **Salesforce**&#x200B;를 선택합니다.

   ![](assets/person-actions-salesforce.png)

1. **SFDC에서 인물 삭제**&#x200B;를 선택합니다.

   ![](assets/delete-person-from-sfdc.png)

1. **Delete in Marketing** 설정이 **false**&#x200B;인지 확인한 다음 **지금 실행**&#x200B;을 클릭합니다.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   흐름 단계가 실행된 후에는 Salesforce에서 리드가 아닌 Marketing에 남게 됩니다.

   >[!CAUTION]
   >
   >**Delete in Marketing**&#x200B;을 **true**&#x200B;로 설정하고 Marketing 사용자와 Salesforce의 리드를 삭제하면 이 리드는 영구적으로 삭제됩니다. 실행 취소할 수 없습니다.


---
unique-page-id: 1147031
description: SFDC에서 개인 삭제 - Marketo 문서 - 제품 설명서
title: SFDC에서 개인 삭제
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# SFDC에서 개인 삭제 {#delete-person-from-sfdc}

Salesforce에서 특정 리드 세트를 제거해야 하지만 Marketo에서 리드를 사용자로 유지해야 하는 경우 SFDC 흐름에서 개인 삭제 작업을 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **개인 작업** 을(를) 선택합니다. **Salesforce**.

   ![](assets/person-actions-salesforce.png)

1. 선택 **SFDC에서 개인 삭제**.

   ![](assets/delete-person-from-sfdc.png)

1. 반드시 **Marketo에서 삭제** 설정 **false**&#x200B;를 클릭한 다음 **지금 실행**.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   흐름 단계가 실행되면 사용자는 더 이상 Salesforce에서 리드가 아니지만 Marketo에 유지됩니다.

   >[!CAUTION]
   >
   >설정 **Marketo에서 삭제** to **true** Marketo에서 사람들을 삭제하고 Salesforce에서 리드를 만들면 영원히 사라집니다. 이 작업은 취소할 수 없습니다.

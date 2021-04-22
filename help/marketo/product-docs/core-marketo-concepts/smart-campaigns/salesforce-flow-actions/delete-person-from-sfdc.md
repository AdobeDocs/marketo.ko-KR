---
unique-page-id: 1147031
description: SFDC에서 인물 삭제 - Marketo 문서 - 제품 설명서
title: SFDC에서 인물 삭제
exl-id: 8245de35-f374-4241-946e-b4c4b87cc85e
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '135'
ht-degree: 0%

---

# SFDC {#delete-person-from-sfdc}에서 인물 삭제

Salesforce에서 특정 리드 세트를 제거하고 Marketo에서 리드를 다른 사람으로 두어야 하는 경우 SFDC에서 인물 삭제 플로우 작업을 사용할 수 있습니다.

>[!NOTE]
>
>Salesforce와 통합되어야 이용 가능

1. 데이터베이스에서 Salesforce에서 제거할 사람을 클릭합니다. 그런 다음 **사람 작업**&#x200B;을 클릭하고 **Salesforce**&#x200B;를 선택합니다.

   ![](assets/person-actions-salesforce.png)

1. **SFDC에서 인물 삭제**&#x200B;를 선택합니다.

   ![](assets/delete-person-from-sfdc.png)

1. Marketo **에서**&#x200B;삭제 설정이 **false**&#x200B;인지 확인한 다음 **지금 실행**&#x200B;을 클릭합니다.

   ![](assets/run-action-delete-lead-from-sfdc.png)

   흐름 단계가 실행된 후에는 Salesforce에서 리드가 아닌 Marketo에 남게 됩니다.

   >[!CAUTION]
   >
   >Marketo **에서** Delete를 **true**&#x200B;로 설정하고 Marketo의 피플 및 리드를 Salesforce에서 삭제하면 해당 리드는 영구적으로 사라집니다. 실행 취소할 수 없습니다.

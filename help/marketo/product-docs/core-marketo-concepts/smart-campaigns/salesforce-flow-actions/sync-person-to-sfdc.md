---
unique-page-id: 1147027
description: SFDC에 사용자 동기화 - Marketo 문서 - 제품 설명서
title: 사용자를 SFDC에 동기화
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '131'
ht-degree: 0%

---

# 사용자를 SFDC에 동기화 {#sync-person-to-sfdc}

이 흐름 단계는 Marketo에서 만든 사람을 Salesforce CRM에 잠재 고객으로 삽입합니다.

![](assets/sync-person-to-sfdc.png)

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

1. 기본적으로 이 흐름 단계는 Salesforce 자동 할당 규칙에 따라 리드 소유자에게 할당됩니다.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Salesforce를 사용하려면 해당 사용자에게 회사 및 성 필드가 채워져 있어야 합니다. 그렇지 않으면 잠재 고객 레코드가 거부됩니다.

1. 특정 Salesforce 사용자 또는 리드 큐를 리드 소유자로 설정할 수 있습니다.

   ![](assets/sync-person-to-sfdc-2.png)

   이 플로우 단계를 사용하면 개인이 즉시 Salesforce 리드로 동기화되므로 정기적인 동기화를 기다릴 필요가 없습니다.

   >[!CAUTION]
   >
   >Salesforce에서는 &quot;연락처&quot;를 잠재 고객 큐에 할당할 수 없습니다. 이 경우 Marketo은 Salesforce에 중복 &quot;잠재 고객&quot;을 만듭니다.

---
unique-page-id: 1147027
description: 사용자를 SFDC에 동기화 - Marketo 문서 - 제품 설명서
title: SFDC에 사용자 동기화
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '125'
ht-degree: 0%

---

# SFDC에 사용자 동기화 {#sync-person-to-sfdc}

이 흐름 단계는 Marketo에서 만든 사람을 Salesforce CRM의 리드로 삽입합니다.

>[!NOTE]
>
>[!DNL Salesforce]과(와) 통합된 경우에만 사용할 수 있습니다.

1. 기본적으로 이 흐름 단계는 Salesforce 자동 할당 규칙에 따라 리드 소유자에게 할당됩니다.

   ![](assets/sync-person-to-sfdc-1.png)

   >[!TIP]
   >
   >[!DNL Salesforce]을(를) 사용하려면 사용자가 회사 및 성 필드를 채워야 합니다. 그렇지 않으면 잠재 고객 레코드가 거부됩니다.

1. 특정 [!DNL Salesforce]명의 사용자 또는 잠재 고객 큐를 잠재 고객 소유자로 설정할 수 있습니다.

   ![](assets/sync-person-to-sfdc-2.png)

   이 흐름 단계를 사용하면 해당 사용자는 즉시 [!DNL Salesforce] 잠재 고객으로 동기화되며 일반 동기화를 기다릴 필요가 없습니다.

   >[!CAUTION]
   >
   >[!DNL Salesforce]에서는 &quot;연락처&quot;를 잠재 고객 큐에 할당할 수 없습니다. 이 경우 Marketo은 [!DNL Salesforce]에 중복 &quot;잠재 고객&quot;을 만듭니다.

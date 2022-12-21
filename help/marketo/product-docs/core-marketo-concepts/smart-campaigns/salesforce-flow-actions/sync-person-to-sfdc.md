---
unique-page-id: 1147027
description: SFDC에 개인 동기화 - Marketo 문서 - 제품 설명서
title: SFDC에 개인 동기화
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '133'
ht-degree: 1%

---

# SFDC에 개인 동기화 {#sync-person-to-sfdc}

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

## 개요 {#overview}

이 흐름 단계에서는 Marketo에서 만든 사람을 리드로 Salesforce CRM에 삽입합니다.

![](assets/sync-person-to-sfdc.png)

## 사용 {#usage}

1. 기본적으로 이 흐름 단계는 Salesforce 자동 할당 규칙에 따라 리드 소유자에게 지정됩니다.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Salesforce에서는 사용자에게 회사 및 성 필드가 채워져 있어야 합니다. 그렇지 않으면 리드 레코드가 거부됩니다.

1. 특정 Salesforce 사용자 또는 리드 큐를 리드 소유자로 설정할 수 있습니다.

   ![](assets/sync-person-to-sfdc-2.png)

   이 흐름 단계를 사용하면 사람이 Salesforce 리드로 즉시 동기화되므로 정규 동기화를 기다릴 필요가 없습니다.

   >[!CAUTION]
   >
   >Salesforce에서는 &quot;연락처&quot;를 리드 큐에 할당할 수 없습니다. 이 경우 Marketo은 Salesforce에서 중복 &quot;리드&quot;를 만듭니다.

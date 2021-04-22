---
unique-page-id: 1147027
description: SFDC에 사람 동기화 - Marketo 문서 - 제품 설명서
title: SFDC에 사람 동기화
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '133'
ht-degree: 0%

---

# 사람을 SFDC {#sync-person-to-sfdc}에 동기화

>[!NOTE]
>
>Salesforce와 통합되어야 이용 가능

## 개요 {#overview}

이 흐름 단계에서는 Marketo에서 만든 사람을 리드로 Salesforce CRM에 삽입합니다.

![](assets/sync-person-to-sfdc.png)

## 사용량 {#usage}

1. 기본적으로 이 흐름 단계는 Salesforce 자동 할당 규칙에 따라 리드 소유자에게 지정됩니다.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Salesforce에서는 회사 및 성 필드가 채워져 있어야 합니다. 그렇지 않으면 리드 레코드가 거부됩니다.

1. 특정 Salesforce 사용자 또는 리드 큐를 리드 소유자로 설정할 수 있습니다.

   ![](assets/sync-person-to-sfdc-2.png)

   이 흐름 단계를 사용하면 해당 사람은 즉시 Salesforce 리드로 동기화되므로 정기적인 동기화를 기다릴 필요가 없습니다.

   >[!CAUTION]
   >
   >Salesforce에서는 &quot;연락처&quot;를 리드 큐에 할당할 수 없습니다. 이 경우 Marketo은 Salesforce에서 &quot;리드&quot;를 복제합니다.

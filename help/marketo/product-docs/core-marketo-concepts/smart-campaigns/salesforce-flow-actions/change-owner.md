---
unique-page-id: 1147021
description: 소유자 변경 - Marketo 문서 - 제품 설명서
title: 소유자 변경
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
source-git-commit: 44c134811242b4136a3137cdd60e60edeb838c8c
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---

# 소유자 변경 {#change-owner}

소유자에게 이미 지정된 기존 사용자가 있는 경우 이 흐름 단계를 사용하여 다른 소유자에게 다시 지정할 수 있습니다.

![](assets/image2014-9-22-15-3a1-3a3.png)

**사용**

1. 변경할 소유자 또는 리드 큐를 선택하고 이동하면 됩니다.

   ![](assets/image2014-9-22-15-3a1-3a6.png)

   >[!CAUTION]
   >
   >Salesforce에서는 연락처를 리드 큐에 할당할 수 없습니다. SFDC 연락처인 레코드의 경우:
   >
   >1. Marketo에서 중복 리드를 만듭니다 **전용** 연락처가 Salesforce에 동기화되는 경우 즉, **[SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 흐름 단계 `AssignTo=<a lead queue>`, Marketo은 Salesforce에서 중복 리드를 만들어 리드 큐에 지정합니다.
   >
   >1. 를 사용하는 경우 **소유자 변경** 연락처의 흐름 단계에서는 Marketo에서 Salesforce에 중복 리드를 만듭니다. 이를 방지하려면 리드로 작업을 제한하는 &#39;SFDC 유형&#39; 필드에 필터를 사용하십시오.


   >[!NOTE]
   >
   >레코드가 Salesforce 계정에 아직 존재하지 않는 경우 동기화한 다음 선택한 사용자에게 할당합니다.

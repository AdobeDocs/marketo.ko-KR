---
unique-page-id: 1147021
description: 소유자 변경 - Marketo 문서 - 제품 설명서
title: 소유자 변경
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---

# 소유자 변경 {#change-owner}

이미 소유자에게 할당된 기존 인력이 있는 경우 이 흐름 단계를 사용하여 해당 인력을 다른 소유자에게 다시 할당할 수 있습니다.

![](assets/image2014-9-22-15-3a1-3a3.png)

**사용량**

1. 변경하려는 소유자 또는 잠재 고객 대기열을 선택하고 이동하기만 하면 됩니다.

   ![](assets/image2014-9-22-15-3a1-3a6.png)

   >[!CAUTION]
   >
   >Salesforce에서는 연락처가 리드 큐에 지정되는 것을 허용하지 않습니다. SFDC 담당자인 레코드의 경우:
   >
   >1. Marketo에서 중복 리드를 생성합니다. **전용** 연락처가 Salesforce에 동기화되는 경우입니다. 즉, **[사용자를 SFDC에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 다음으로 흐름 단계 `AssignTo=<a lead queue>`, Marketo은 Salesforce에서 중복 리드를 만들고 리드 큐에 할당합니다.
   >
   >1. 를 사용하는 경우 **[!UICONTROL 소유자 변경]** 연락처의 흐름 단계에서 Marketo은 Salesforce에서 중복 리드를 만듭니다. 이 문제를 방지하려면 작업을 리드로만 제한하는 &#39;SFDC 유형&#39; 필드의 필터를 사용하십시오.

   >[!NOTE]
   >
   >레코드가 Salesforce 계정에 아직 없으면 동기화한 다음 선택한 사용자에게 할당합니다.

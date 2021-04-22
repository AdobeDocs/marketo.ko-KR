---
unique-page-id: 1147021
description: 소유자 변경 - Marketo 문서 - 제품 설명서
title: 소유자 변경
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '154'
ht-degree: 0%

---

# 소유자 변경 {#change-owner}

이미 소유자에 지정된 기존 사용자가 있는 경우 이 흐름 단계를 사용하여 다른 소유자에게 다시 할당할 수 있습니다.

![](assets/image2014-9-22-15-3a1-3a3.png)

**사용량**

1. 변경할 소유자 또는 리드 큐를 선택하고 진행하면 됩니다.

   ![](assets/image2014-9-22-15-3a1-3a6.png)

   >[!CAUTION]
   >
   >Salesforce에서는 연락처를 리드 큐에 할당할 수 없습니다. SFDC 연락처 기록:
   >
   >1. Marketo은 연락처가 Salesforce에 동기화될 때 중복된 리드 **만**&#x200B;만듭니다. 즉, `AssignTo=<a lead queue>`에서 **[사람을 SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 플로우 단계를 사용하는 경우 Marketo은 Salesforce에서 중복 리드를 만들어 리드 큐에 지정합니다.
      >
      >
   1. 연락처에서 **소유자 변경** 흐름 단계를 사용하려고 하면 Salesforce에서 복사본이 생성되지 않습니다.


   >[!NOTE]
   >
   >레코드가 아직 Salesforce 계정에 없으면 동기화하여 선택한 사용자에게 할당합니다.

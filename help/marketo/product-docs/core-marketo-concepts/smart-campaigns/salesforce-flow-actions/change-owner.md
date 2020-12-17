---
unique-page-id: 1147021
description: 소유자 변경 - 마케팅 문서 - 제품 설명서
title: 소유자 변경
translation-type: tm+mt
source-git-commit: f27e2bac90570f9f795dc6bdd5fcf208c446be14
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
   >1. 연락처가 Salesforce에 동기화될 때 Marketing에서 중복된 리드 **만**&#x200B;을(를) 만듭니다. 즉, `AssignTo=<a lead queue>`에서 **[사람을 SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** 플로우 단계를 사용하는 경우 Marketing에서 중복된 리드를 만들어 리드 큐에 지정합니다.
      >
      >
   2. 연락처에서 **소유자 변경** 흐름 단계를 사용하려고 하면 Salesforce에서 복사본이 생성되지 않습니다.


   >[!NOTE]
   >
   >레코드가 아직 Salesforce 계정에 없으면 동기화하여 선택한 사용자에게 할당합니다.

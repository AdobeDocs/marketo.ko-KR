---
unique-page-id: 1147034
description: SFDC 캠페인에 추가 - 마케팅 문서 - 제품 문서에 추가
title: SFDC 캠페인에 추가
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---


# SFDC 캠페인에 추가 {#add-to-sfdc-campaign}

>[!NOTE]
>
>Salesforce와 통합되어야 이용 가능

## 개요 {#overview}

이 흐름 단계는 Marketing To 캠페인에서 사용하거나 Salesforce 캠페인에서 리드로 사람을 추가하는 단일 흐름 단계로 사용할 수 있습니다. 리드가 아직 Salesforce에 없는 경우 자동으로 동기화되고 지정된 상태의 캠페인에 추가됩니다.

![](assets/image2014-9-22-15-3a43-3a36.png)

## 사용량 {#usage}

1. 리드를 추가할 Salesforce 캠페인을 찾아 선택합니다.

   ![](assets/image2014-9-22-15-3a43-3a45.png)

   >[!TIP]
   >
   >캠페인 목록에 Salesforce 캠페인이 표시되지 않는 경우:
   >
   >    
   >    
   >    1. 캠페인 [동기화가 활성화되어 있는지 확인합니다](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
   >    1. Marketing to Sync [사용자](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 가 Salesforce의 [마케팅](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) 사용자인지 확인합니다.


   >[!TIP]
   >
   >Salesforce 캠페인 [내](../../../../product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md) 토큰을 사용하여 프로그램 복제를 손쉽게 할 수 있습니다.

1. 리드가 추가되면 리드에 할당할 Salesforce 캠페인 멤버 상태를 선택합니다.

   ![](assets/image2014-9-22-15-3a45-3a2.png)

   >[!CAUTION]
   >
   >사용자가 이미 Salesforce 캠페인의 리드 멤버인 경우 건너뛰고 상태가 업데이트되지 않습니다. 대신 SFDC 캠페인에서 [해당 상태를 변경할 수](change-status-in-sfdc-campaign.md) 있습니다.


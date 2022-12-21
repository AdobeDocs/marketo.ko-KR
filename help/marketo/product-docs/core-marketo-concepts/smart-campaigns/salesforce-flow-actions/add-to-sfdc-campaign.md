---
unique-page-id: 1147034
description: SFDC Campaign에 추가 - Marketo 문서 - 제품 설명서
title: SFDC Campaign에 추가
exl-id: a5e14cc7-fd83-4a2c-aacb-e515669c9d21
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 1%

---

# SFDC Campaign에 추가 {#add-to-sfdc-campaign}

>[!NOTE]
>
>Salesforce와 통합된 경우에만 사용할 수 있습니다.

## 개요 {#overview}

이 흐름 단계는 Marketo 캠페인이나 Salesforce 캠페인에서 리드로 사람을 추가하는 단일 흐름 단계로 사용할 수 있습니다. 리드가 Salesforce에 아직 없는 경우 자동으로 동기화되고 지정된 상태의 캠페인에 추가됩니다.

![](assets/image2014-9-22-15-3a43-3a36.png)

## 사용 {#usage}

1. 리드를 추가할 Salesforce 캠페인을 찾아 선택합니다.

   ![](assets/image2014-9-22-15-3a43-3a45.png)

   >[!TIP]
   >
   >Campaign 목록에 Salesforce 캠페인이 표시되지 않는 경우:
   >
   >  1. 다음을 확인합니다. [캠페인 동기화가 활성화됨](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md).
   >  1. 다음 사항을 확인합니다. [Marketo 동기화 사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) is [마케팅 사용자](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) Salesforce에서


   >[!TIP]
   >
   >Salesforce 캠페인을 사용할 수 있습니다 [내 토큰](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md) 프로그램 복제를 쉽게 할 수 있습니다.

1. 리드가 추가되면 리드에 할당할 Salesforce 캠페인 구성원 상태를 선택합니다.

   ![](assets/image2014-9-22-15-3a45-3a2.png)

   >[!CAUTION]
   >
   >사용자가 이미 Salesforce 캠페인의 리드 멤버인 경우 건너뛰고 상태가 업데이트되지 않습니다. 다음을 사용할 수 있습니다 [SFDC 캠페인에서 상태 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md) 을 가리키도록 업데이트하는 것이 좋습니다.

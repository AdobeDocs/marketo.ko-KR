---
unique-page-id: 1147154
description: SFDC Campaign을 프로그램과 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 캠페인을 프로그램과 동기화
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
source-git-commit: 8781c6cf2e64543809fe697e75ae6884969a4e40
workflow-type: tm+mt
source-wordcount: '176'
ht-degree: 0%

---

# SFDC 캠페인을 프로그램과 동기화 {#sync-an-sfdc-campaign-with-a-program}

Marketo을 사용하면 프로그램을 Salesforce 캠페인과 동기화하여 상태를 포함하여 두 시스템에 있는 동일한 사람 목록을 유지할 수 있습니다. 시작해 보겠습니다!

>[!PREREQUISITES]
>
>다음을 수행해야 합니다. [Salesforce 캠페인 동기화 활성화](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md) 먼저

>[!CAUTION]
>
>SFDC 캠페인을 Marketo 프로그램과 동기화할 때 프로그램의 하위 캠페인에 대해 암시된 SFDC 작업(예: SFDC Campaign에 추가, SFDC에 동기화)이 비활성화됩니다.

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-1.png)

1. 프로그램을 선택합니다.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. 클릭 **프로그램 작업**&#x200B;를 선택하고 을 선택합니다. **Salesforce 캠페인 동기화**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. 선택 **새로 만들기** 또는 기존 Salesforce 캠페인을 선택합니다.

   >[!TIP]
   >
   >기존 Salesforce 캠페인을 선택하는 경우 다음을 확인하십시오 [salesforce 캠페인 및 Marketo 프로그램의 프로그램 상태와 일치합니다](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md).

1. 새 캠페인의 이름을 입력하고 **저장**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. 이제 프로그램 요약 페이지에서 캠페인 동기화 세부 사항을 확인할 수 있습니다.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   훌륭해요! 이제 Marketo의 모든 프로그램 상태 변경 사항이 SFDC 캠페인에 동기화되고 그 반대의 경우도 마찬가지입니다.

---
unique-page-id: 2953465
description: SFDC 동기화 - Salesforce에서 리드를 연락처로 전환 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - Salesforce에서 리드를 연락처로 전환
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '144'
ht-degree: 0%

---

# SFDC 동기화: [!DNL Salesforce]에서 잠재 고객을 연락처로 전환합니다. {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

[!DNL Salesforce]에서 세 가지 시나리오를 상상해 보십시오. (Marketo에서 [개인 흐름 전환 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)를 사용하지 않음)

1. 잠재 고객을 **새 연락처 및 새 계정으로 전환**
1. **기존 계정**&#x200B;에서 **새 연락처**(으)로 잠재 고객 전환

1. **기존 계정**&#x200B;에서 **기존 연락처**(으)로 잠재 고객 전환(이는 [병합](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md){target="_blank"}과 동일)

세 가지 경우 모두 **1명의 연락처와 [!DNL Salesforce]의 잠재 고객 및 1명의 연락처와 Marketo의 사용자가 없게 됩니다.**

Marketo에서 레코드는 이제 SFDC Type = Contact 를 갖게 됩니다.

>[!TIP]
>
>[!DNL Salesforce]에서 전환할 때 [리드 사용자 정의 필드가 잘 매핑되었는지 확인](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm)합니다. 데이터를 손실하고 싶지 않을 것입니다.

&quot;[!UICONTROL Lead is Converted]&quot; 및 &quot;[!UICONTROL Lead was Converted]&quot;을(를) 사용하여 트리거하고 필터링할 수 있습니다.

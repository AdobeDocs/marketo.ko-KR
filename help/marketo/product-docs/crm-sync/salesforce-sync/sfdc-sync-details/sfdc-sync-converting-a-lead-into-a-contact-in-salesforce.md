---
unique-page-id: 2953465
description: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# SFDC 동기화: Salesforce에서 리드를 연락처로 변환 {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Salesforce에서 세 가지 다른 시나리오를 상상하십시오. ( [개인 흐름 변환 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) Marketo)

1. 리드를 로 변환 **새 연락처 및 새 계정**
1. 리드를 로 변환 **새 연락처** 에서 **기존 계정**

1. 리드를 로 변환 **기존 연락처** 에서 **기존 계정** (이 작업은 [병합](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md))

세 가지 경우 모두 **Salesforce에서는 1명의 연락처와 리드가 없으며, Marketo에는 1명의 연락처와 연락처가 없습니다.**

Marketo에서 이제 레코드에 SFDC 유형 = Contact가 있습니다.

>[!TIP]
>
>Salesforce에서 변환할 때 [리드 사용자 지정 필드가 잘 매핑됩니다](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). 데이터를 손실하지 않아도 됩니다.

다음을 사용하여 트리거하고 필터링할 수 있습니다. &quot;리드가 전환됨&quot; 및 &quot;리드가 전환됨&quot;

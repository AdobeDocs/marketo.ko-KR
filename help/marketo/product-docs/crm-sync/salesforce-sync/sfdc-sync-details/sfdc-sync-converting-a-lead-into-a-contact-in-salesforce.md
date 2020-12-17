---
unique-page-id: 2953465
description: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환 - Marketing Docs - 제품 설명서
title: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---


# SFDC 동기화:Salesforce에서 리드를 연락처로 변환 {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Salesforce의 3가지 시나리오를 가정해 보십시오.(Marketing To에서 [사람 흐름 전환 단계](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)을 사용하지 않음)

1. 리드를 **새 연락처 및 새 계정**&#x200B;으로 변환
1. 리드를 **기존 계정**&#x200B;에서 **새 연락처**&#x200B;로 변환

1. 리드를 **기존 계정**&#x200B;의 **기존 연락처**&#x200B;로 변환(이 작업은 [병합](sfdc-sync-merging-a-lead-contact-person.md)과 동일하게 작동합니다.)

세 경우 모두 **1 연락처와 Salesforce에 리드가 없고 1개의 연락처와 Marketing에 있는 사람이 없는 것으로 종료됩니다.**

Marketing에서 이제 레코드에 SFDC 유형 = 연락처가 있습니다.

>[!TIP]
>
>Salesforce에서 변환할 때 [리드 사용자 지정 필드가 제대로 매핑되었는지 확인합니다](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). 데이터를 손실하지 마십시오.

다음을 사용하여 트리거하고 필터링할 수 있습니다.&quot;리드가 전환됨&quot; 및 &quot;리드가 전환됨&quot;
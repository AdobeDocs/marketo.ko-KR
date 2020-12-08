---
unique-page-id: 2953465
description: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환 - Marketing Docs - 제품 설명서
title: SFDC 동기화 - Salesforce에서 리드를 연락처로 변환
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '209'
ht-degree: 0%

---


# SFDC 동기화:Salesforce에서 리드를 연락처로 변환 {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Salesforce의 세 가지 시나리오를 생각해 보십시오.(Marketing To에서 [사람 전환 흐름](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) 단계 사용 안 함)

1. 리드를 **새 연락처 및 새 계정으로 전환**
1. 리드를 **기존 계정의** 새 **연락처로 변환**

1. 리드를 **기존 계정** 의 **기존 연락처로** 변환( [병합과](sfdc-sync-merging-a-lead-contact-person.md)동일)

세 경우 모두 Salesforce에 **연락하거나 리드가 없는 경우와 Marketing Cloud에 담당자가 없는 경우가 있습니다.**

Marketing에서, 이제 레코드에는 SFDC 유형 = 연락처가 있습니다.

>[!TIP]
>
>Salesforce에서 전환할 때 [리드 사용자 정의 필드가 제대로](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm)매핑되는지 확인하십시오. 데이터 손실 방지

다음을 사용하여 트리거하고 필터링할 수 있습니다.&quot;리드가 전환됨&quot; 및 &quot;리드가 전환됨&quot;
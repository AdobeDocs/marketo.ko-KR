---
unique-page-id: 7516241
description: SFDC 동기화 - 리드 큐 - Marketing To Docs - 제품 설명서
title: SFDC 동기화 - 리드 큐
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---


# SFDC 동기화:리드 큐 {#sfdc-sync-lead-queue}

Marketing을 사용하면 리드 배포에 도움이 되도록 [Salesforce 리드](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) 큐에 사람을 추가할 수 있습니다. 자세한 내용

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

## Marketing To의 대기열에 사람을 할당하는 방법 {#how-to-assign-a-person-to-a-queue-in-marketo}

다음 흐름 작업 중 하나를 사용하여 Salesforce 리드 큐에 사람을 할당할 수 있습니다.

* [SFDC에 사람 동기화](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [소유자 변경](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>Marketing To에서는 큐를 만들거나 변경할 수 없습니다.

## 개인이 큐에 속해 있는 경우 리드 소유자 정보는 어떻게 저장됩니까? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

리드가 Salesforce의 큐에서 소유한 경우, 리드가 소유자에게 할당될 때까지 이러한 영업 소유자 필드는 비어 있게 유지됩니다.

* 영업 담당자 이름
* 영업 담당자 성
* 영업 소유자 제목
* 영업 담당자 전화 번호
* 영업 담당자 이메일 주소


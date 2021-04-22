---
unique-page-id: 7516241
description: SFDC 동기화 - 리드 큐 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드 큐
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# SFDC 동기화:리드 큐 {#sfdc-sync-lead-queue}

Marketo을 사용하면 리드 배포에 도움이 되도록 [Salesforce 리드 큐](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm)에 사용자를 추가할 수 있습니다. 자세한 내용은

## Marketo의 대기열에 사람을 할당하는 방법{#how-to-assign-a-person-to-a-queue-in-marketo}

다음 흐름 작업 중 하나를 사용하여 Salesforce 리드 큐에 사람을 할당할 수 있습니다.

* [SFDC에 사람 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>Marketo에서는 큐를 만들거나 변경할 수 없습니다.

## 개인이 큐에 속해 있는 경우 리드 소유자 정보는 어떻게 저장됩니까?{#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

리드가 Salesforce의 대기열에 있는 경우 리드가 소유자에게 할당될 때까지 이러한 영업 소유자 필드는 비어 있게 됩니다.

* 영업 담당자 이름
* 영업 소유자 성
* 영업 소유자 제목
* 판매 소유자 전화 번호
* 판매 소유자 이메일 주소

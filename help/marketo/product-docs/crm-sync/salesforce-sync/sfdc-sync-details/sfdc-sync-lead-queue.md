---
unique-page-id: 7516241
description: SFDC 동기화 - 리드 큐 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드 큐
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# SFDC 동기화: 리드 큐 {#sfdc-sync-lead-queue}

Marketo에 사용자를 추가할 수 있습니다. [Salesforce 리드 큐](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) 리드 배포에 도움이 됩니다. 자세한 내용은 다음과 같습니다.

## Marketo의 큐에 개인을 할당하는 방법 {#how-to-assign-a-person-to-a-queue-in-marketo}

다음 흐름 작업 중 하나를 사용하여 Salesforce 리드 큐에 개인을 할당할 수 있습니다.

* [SFDC에 개인 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>Marketo에서는 큐를 만들거나 변경할 수 없습니다.

## 개인이 큐에 속해 있는 경우 리드 소유자 정보는 어떻게 저장됩니까? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

Salesforce의 큐가 리드를 소유한 경우 리드가 소유자에게 할당될 때까지 이러한 영업 소유자 필드는 비어 있게 유지됩니다.

* 영업 담당자 이름
* 영업 소유자 성
* 영업 소유자 제목
* 영업 담당자 전화번호
* 영업 소유자 이메일 주소

---
unique-page-id: 7516241
description: Marketo에서 Salesforce 리드 큐에 사람을 할당하는 방법에 대해 알아봅니다. 리드 배포에 대해 사용자와 SFDC 동기화 또는 소유자 변경 흐름 작업을 사용합니다.
title: SFDC 동기화 - 리드 큐
exl-id: b3b5e14c-f914-429c-a4b9-6b535ad8e882
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '145'
ht-degree: 2%

---

# SFDC 동기화: 리드 대기열 {#sfdc-sync-lead-queue}

Marketo을 사용하면 [[!DNL Salesforce] 리드 큐](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm)에 사람을 추가하여 리드 배포에 도움을 줄 수 있습니다. 세부사항은 다음과 같습니다.

## Marketo에서 대기열에 사람을 할당하는 방법 {#how-to-assign-a-person-to-a-queue-in-marketo}

다음 흐름 작업 중 하나를 사용하여 [!DNL Salesforce] 리드 큐에 사용자를 할당할 수 있습니다.

* [사용자를 SFDC에 동기화](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md){target="_blank"}
* [소유자 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md){target="_blank"}

>[!NOTE]
>
>Marketo에서는 큐를 만들거나 변경할 수 없습니다.

## 대상이 대기열에 속해 있는 경우 잠재 고객 소유자 정보는 어떻게 저장됩니까? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

[!DNL Salesforce]의 대기열에서 잠재 고객을 소유한 경우 잠재 고객이 소유자에게 할당될 때까지 이러한 판매 소유자 필드는 비어 있는 상태로 유지됩니다.

* 영업 담당자 이름
* 영업 담당자 성
* 판매 소유자 제목
* 영업 담당자 전화 번호
* 영업 담당자 이메일 주소

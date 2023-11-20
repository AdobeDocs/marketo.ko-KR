---
unique-page-id: 2953461
description: SFDC 동기화 - 필드 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 필드 동기화
exl-id: fbd66829-53cb-47fd-a530-149d12baee0e
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# SFDC 동기화: 필드 동기화 {#sfdc-sync-field-sync}

Marketo Engage은 Salesforce의 필드 정보를 동기화합니다. 세부사항은 다음과 같습니다.

## 동기화되는 필드는 무엇입니까? {#which-fields-are-synced}

SFDC의 대부분의 표준 필드와 동기화 사용자가 볼 수 있는 권한이 있는 모든 사용자 정의 필드를 동기화합니다.

## Marketo의 레코드가 Salesforce의 잠재 고객인지 또는 연락처인지 어떻게 확인합니까? {#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce}

Marketo에 SFDC Type이라는 필드가 있습니다. 리드, 연락처 또는 비어 있음 등 세 가지 값이 있습니다. 비어 있는 경우 이 Marketo 리드가 SFDC에 존재하지 않음을 의미합니다.

## SFDC에서 잠재 고객 또는 연락처가 삭제되었는지 어떻게 확인합니까? {#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc}

Marketo에 SFDC isDeleted라는 필드가 있습니다. 값이 true이면 리드가 SFDC에서 삭제되었습니다.

## SFDC에서 추가하는 새 필드도 Marketo에 추가되도록 하려면 어떻게 해야 합니까? {#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo}

>[!TIP]
>
>두 시스템에 모두 필드가 필요하면 먼저 SFDC에서 필드를 만들면 Marketo에 자동으로 동기화됩니다.

SFDC에 새 필드를 추가하고 동기화 사용자에게 이를 볼 수 있는 권한이 있는 경우 자동으로 Marketo에 추가됩니다.

## SFDC에서 필드 레이블을 변경하면 어떻게 됩니까? {#what-if-i-change-a-field-label-in-sfdc}

SFDC에서 필드 레이블을 변경해도 Marketo의 필드 레이블에는 영향을 주지 않습니다.

## SFDC에서 필드 유형을 변경하는 경우 어떻게 합니까? {#what-if-i-change-a-field-type-in-sfdc}

필드 유형을 변경하면 Marketo은 필드의 데이터가 일치하지 않으면 해당 데이터를 삭제합니다(하지만 먼저 경고가 표시됨). 데이터를 보존하려면 필드 유형을 변경한 후 내보내고 다시 가져와야 합니다.

## SFDC에서 API 이름을 변경하면 어떻게 됩니까? {#what-if-i-change-an-api-name-in-sfdc}

SFDC에서 필드의 API 이름을 변경하면 Marketo에 새 필드가 만들어집니다.

## SFDC에서 새 선택 목록 값을 추가하면 어떻게 됩니까? {#what-happens-if-i-add-a-new-picklist-value-in-sfdc}

새 선택 목록 값이 SFDC에서 필드에 추가되면 Marketo에서 알림을 보냅니다.

## 사용자 정의 SFDC 조회 필드는 어떻게 됩니까? {#what-about-custom-sfdc-lookup-fields}

SFDC의 조회 필드는 ID는 동기화하지만 참조된 이름은 동기화하지 않습니다.

## SFDC 공식 필드는 어떻습니까? {#what-about-sfdc-formula-fields}

공식 필드는 동기화되지만 공식의 참조에 대한 업데이트는 다음에 대한 업데이트가 있을 때까지 동기화되지 않습니다. [시스템 변경사항 스탬프](https://help.salesforce.com/apex/HTViewSolution?id=000193203&amp;language=en_US){target="_blank"}.

## 이전에 Marketo과 동기화되던 Salesforce에서 필드를 삭제하면 어떻게 됩니까? {#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo}

SFDC에서 필드를 삭제하면 Marketo의 필드가 자동으로 삭제되지 않고 동기화만 중지됩니다.

---
unique-page-id: 2953461
description: SFDC 동기화 - 필드 동기화 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 필드 동기화
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '413'
ht-degree: 0%

---


# SFDC 동기화:필드 동기화 {#sfdc-sync-field-sync}

Marketing To는 Salesforce의 필드 정보를 동기화합니다. 자세한 내용은

## 어떤 필드가 동기화됩니까?{#which-fields-are-synced}

SFDC의 대부분의 표준 필드와 동기화 사용자가 볼 수 있는 권한이 있는 모든 사용자 정의 필드를 동기화합니다.

## Marketing의 레코드가 Salesforce의 리드 또는 담당자인지 어떻게 판단합니까?{#how-do-you-determine-if-a-record-in-marketo-is-a-lead-or-a-contact-in-salesforce}

Marketing에 SFDC 유형이라는 필드가 있습니다. 3개의 가능한 값이 있습니다.리드, 연락처 또는 비어 있음 비어 있는 경우 이 마케팅 리드가 SFDC에 존재하지 않음을 의미합니다.

## SFDC에서 리드 또는 연락처가 삭제되었는지 어떻게 확인할 수 있습니까?{#how-do-you-determine-if-a-lead-or-contact-is-deleted-in-sfdc}

Marketing에 SFDC isDeleted라는 필드가 있습니다. 값이 true이면 리드가 SFDC에서 삭제됩니다.

## SFDC에서 추가하는 새 필드도 Marketing To에 추가되도록 하려면 어떻게 해야 합니까?{#how-do-i-make-sure-a-new-field-i-add-in-sfdc-also-gets-added-to-marketo}

>[!TIP]
>
>두 시스템 모두에서 필드를 사용하려면 먼저 SFDC에서 만들면 Marketing에 자동으로 동기화됩니다.

SFDC에서 새 필드를 추가하면 동기화 사용자에게 해당 필드를 볼 수 있는 권한이 있으면 자동으로 Marketing에 추가됩니다.

## SFDC에서 필드 레이블을 변경하면 어떻게 합니까?{#what-if-i-change-a-field-label-in-sfdc}

SFDC에서 필드 레이블을 변경해도 Marketing의 필드 레이블에는 영향을 주지 않습니다.

## SFDC에서 필드 유형을 변경하는 경우 어떻게 합니까?{#what-if-i-change-a-field-type-in-sfdc}

필드 유형을 변경하면 필드가 일치하지 않으면 데이터가 삭제됩니다(하지만 먼저 경고가 표시됨). 데이터를 보존하려면 필드 유형을 변경한 후 데이터를 내보내고 다시 가져와야 합니다.

## SFDC에서 API 이름을 변경하면 어떻게 됩니까?{#what-if-i-change-an-api-name-in-sfdc}

SFDC에서 필드의 API 이름을 변경하면 Marketing에서 새 필드가 만들어집니다.

## SFDC에서 새 선택 목록 값을 추가하면 어떻게 됩니까?{#what-happens-if-i-add-a-new-picklist-value-in-sfdc}

SFDC에서 필드에 새 선택 목록 값이 추가되면 Marketing에서 알림을 보냅니다.

## 사용자 지정 SFDC 조회 필드는 어떻습니까?{#what-about-custom-sfdc-lookup-fields}

SFDC의 조회 필드는 ID를 동기화하지만 참조된 이름은 동기화하지 않습니다.

## SFDC 공식 필드는 어떻습니까?{#what-about-sfdc-formula-fields}

공식 필드는 동기화되지만 [시스템 모드 스탬프](https://help.salesforce.com/apex/HTViewSolution?id=000193203&amp;language=en_US)에 대한 업데이트가 있을 때까지 공식에 있는 참조에 대한 업데이트가 동기화되지 않습니다.

## 이전에 Marketing To와 동기화하던 Salesforce에서 필드를 삭제하면 어떻게 됩니까?{#what-happens-when-i-delete-a-field-from-salesforce-that-was-previously-syncing-with-marketo}

SFDC에서 필드를 삭제해도 Marketing To의 필드가 자동으로 삭제되지 않으므로 동기화가 중단됩니다.

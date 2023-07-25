---
unique-page-id: 4719312
description: 선택 목록 값 추가/제거 - Marketo 문서 - 제품 설명서
title: 선택 목록 값 추가/제거
exl-id: f1230c43-10cb-47ff-89d7-9f835b034db0
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# 선택 목록 값 추가/제거 {#add-remove-picklist-values}

다음은 Salesforce에서 선택 목록 값을 추가하고 제거하는 방법에 대해 알아 두어야 할 몇 가지 사항입니다.

## 선택 목록 값 추가 {#adding-picklist-values}

1. Salesforce에서 선택 목록 필드 유형에 추가 값을 추가하면 [알림](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md) 영향을 줄 양식을 식별합니다.

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. 양식 편집기로 이동하여 [추가 값 추가](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md) 제안 사항 목록으로 이동합니다.

## 선택 목록 값 제거 {#remove-picklist-values}

Salesforce의 필드에서 선택 목록 값이 제거되면 이 필드를 호스팅하는 모든 양식에서 이 값을 수동으로 제거해야 합니다.

>[!NOTE]
>
>Salesforce의 리드 필드와 연락처 필드에 다른 값이 있는 경우 공통되는 값을 Marketo에서 사용할 수 있습니다.

Salesforce의 리드 필드와 연락처 필드에 값이 다른 경우:

1. SFDC의 추가 값을 선택 목록에 추가하면 알림이 표시됩니다.
1. 알림은 사용 위치를 알려줍니다. 이제 원할 경우 이 새 값을 양식의 옵션으로 추가할 수 있습니다.

SFDC 잠재 고객의 선택 목록에 SFDC 연락처에 대한 선택 목록과 다른 값이 있는 경우 공통 값이 양식의 기본값 옵션으로 사용됩니다.

선택 목록에서 값을 제거하는 경우 양식에서 옵션으로 값을 수동으로 제거해야 합니다.

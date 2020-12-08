---
unique-page-id: 4719312
description: 선택 목록 값 추가/제거 - 마케팅 문서 - 제품 설명서
title: 선택 목록 값 추가/제거
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---


# 선택 목록 값 추가/제거 {#add-remove-picklist-values}

다음은 Salesforce에서 선택 목록 값을 추가 및 제거하는 방법에 대해 알아 두어야 할 몇 가지 정보입니다.

## 선택 목록 값 추가 {#adding-picklist-values}

1. Salesforce에 picklist 필드 유형에 추가 값이 추가되면 영향을 받을 양식을 식별하는 [알림을](../../../product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md) 받게 됩니다.

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. 양식 편집기로 이동하여 제안 목록에 추가 값 [을](../../../product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md) 추가합니다.

## 선택 목록 값 제거 {#remove-picklist-values}

Salesforce의 필드에서 선택 목록 값이 제거되면 이 필드를 호스팅하는 모든 양식에서 이 값을 수동으로 제거해야 합니다.

>[!NOTE]
>
>Salesforce의 리드 필드 및 연락처 필드에 다른 값이 있는 경우 공통 값을 Marketing Cloud에서 사용할 수 있습니다.

Salesforce의 리드 필드 및 연락처 필드에 다른 값이 있는 경우:

1. SFDC에서 선택 목록에 추가 값을 추가하면 알림이 수신됩니다.
1. 알림이 사용되는 위치를 알려줍니다. 이제 원할 경우 이 새 값을 양식에 옵션으로 추가할 수 있습니다.

SFDC 리드의 선택 목록 값이 SFDC 연락처의 선택 목록과 다른 경우 양식에서 공통 값이 기본 값 옵션으로 사용됩니다.

선택 목록에서 값을 제거하는 경우 양식에서 옵션으로 수동으로 제거해야 합니다.

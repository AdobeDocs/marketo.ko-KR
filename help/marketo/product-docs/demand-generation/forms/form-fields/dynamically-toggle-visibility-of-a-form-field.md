---
unique-page-id: 2949962
description: 양식 필드의 가시성을 동적으로 전환 - Marketo 문서 - 제품 설명서
title: 양식 필드의 가시성을 동적으로 전환
exl-id: 51b9283d-bfa1-4535-89ba-96c0ae2ea909
feature: Forms
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '243'
ht-degree: 0%

---

# 양식 필드의 가시성을 동적으로 전환 {#dynamically-toggle-visibility-of-a-form-field}

>[!PREREQUISITES]
>
>* [양식에 국가 선택 목록 추가](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)

Marketo Forms의 멋진 기능 중 하나는 양식 필드를 동적으로 숨기거나 표시할 수 있다는 것입니다. [필드 세트](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md).

>[!NOTE]
>
>**예**
>
>이 예에서는 을(를) 숨기겠습니다. **시/도** 다음 경우가 아니면 필드 **국가** 은(는) &quot;미국&quot;으로 선택됩니다.

1. 다음으로 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-8.png)

1. 양식을 선택하고 **양식 편집**.

   ![](assets/editform-1.png)

1. 동적으로 숨기거나 표시할 필드를 선택하고 다음 링크를 클릭합니다. **가시성 규칙**.

   ![](assets/image2014-9-15-15-3a16-3a0.png)

1. 조건을 작성할 필드를 찾아 선택합니다.

   ![](assets/image2014-9-15-15-3a16-3a12.png)

1. 연산자를 선택합니다.

   >[!TIP]
   >
   >&quot;다음으로 시작&quot;과 같은 퍼지 일치를 선택할 수 있으므로 멋집니다.

   ![](assets/image2014-9-15-15-3a16-3a50.png)

1. 찾을 값을 선택한 다음 드롭다운 외부를 클릭합니다.

   ![](assets/image2014-9-15-15-3a17-3a4.png)

   >[!TIP]
   >
   >드롭다운이 열려 있는 동안 여러 값을 클릭하여 선택할 수 있습니다. 예를 들어 미국 및 캐나다를 선택할 수 있습니다.

   >[!NOTE]
   >
   >이전에 국가를 선택 목록 필드 유형으로 전환했습니다. [모든 국가를 값으로 추가함](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md).

1. 클릭 **저장**.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

다 됐습니다! 이제 사용자가 이 양식을 작성하고 국가를 위한 미국을 선택하면 상태 필드가 지정된 선택 사항과 함께 동적으로 표시됩니다.

>[!IMPORTANT]
>
>다음을 사용하여 사용자 지정 스크립트를 통해 필드 값을 설정/업데이트할 때 양식 필드 동작이 원활하게 작동합니다. [API 함수](https://developers.marketo.com/javascript-api/forms/){target="_blank"} Forms 2.0에서.
>
>필드 값이 Forms 2.0 JavaScript API 이외의 외부 스크립트에 의해 수정되는 경우 조건부 필드가 예상대로 작동하지 않을 수 있습니다.

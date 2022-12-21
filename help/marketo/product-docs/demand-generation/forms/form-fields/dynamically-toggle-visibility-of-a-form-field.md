---
unique-page-id: 2949962
description: 양식 필드의 표시 여부를 동적으로 전환 - Marketo 문서 - 제품 설명서
title: 양식 필드의 표시 여부를 동적으로 전환
exl-id: 51b9283d-bfa1-4535-89ba-96c0ae2ea909
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---

# 양식 필드의 표시 여부를 동적으로 전환 {#dynamically-toggle-visibility-of-a-form-field}

>[!PREREQUISITES]
>
>* [양식에 국가 선택 목록 추가](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)


Marketo Forms의 정말 멋진 기능 중 하나는 양식 필드를 동적으로 표시하거나 숨길 수 있다는 것입니다 [필드 세트](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md).

>[!NOTE]
>
>**예**
>
>이 예제에서는 를 숨깁니다 **주/도** 필드 제외 **국가** 이 &quot;미국&quot;으로 선택됩니다.

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities-8.png)

1. 양식을 선택하고 을(를) 클릭합니다 **양식 편집**.

   ![](assets/editform-1.png)

1. 동적으로 숨기거나 표시할 필드를 선택하고 링크를 클릭합니다 **가시성 규칙**.

   ![](assets/image2014-9-15-15-3a16-3a0.png)

1. 조건을 작성할 필드를 찾아 선택합니다.

   ![](assets/image2014-9-15-15-3a16-3a12.png)

1. 연산자를 선택합니다.

   >[!TIP]
   >
   >&quot;다음으로 시작&quot;과 같은 퍼지 일치를 선택할 수 있기 때문에 이 방법은 좋습니다.

   ![](assets/image2014-9-15-15-3a16-3a50.png)

1. 찾을 값을 선택한 다음 드롭다운 바깥쪽을 클릭합니다.

   ![](assets/image2014-9-15-15-3a17-3a4.png)

   >[!TIP]
   >
   >드롭다운이 열려 있는 동안 여러 값을 클릭하여 선택할 수 있습니다. 예를 들어 미국 및 캐나다를 선택할 수 있습니다.

   >[!NOTE]
   >
   >이전에 국가 를 선택 목록 필드 유형으로 변환했으며 [모든 국가를 값으로 추가했습니다.](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md).

1. 클릭 **저장**.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

그게 다야! 이제 사람들이 이 양식을 작성하고 국가별 미국 을 선택하면 지정된 선택 사항과 함께 주 필드가 동적으로 나타납니다.

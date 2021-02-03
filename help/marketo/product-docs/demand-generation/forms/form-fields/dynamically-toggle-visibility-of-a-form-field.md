---
unique-page-id: 2949962
description: 양식 필드의 동적으로 가시성 전환 - 마케팅 문서 - 제품 설명서
title: 동적으로 양식 필드의 표시 여부 전환
translation-type: tm+mt
source-git-commit: ed83438ae5660d172e845f25c4d72d599574bd91
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---


# 양식 필드 {#dynamically-toggle-visibility-of-a-form-field}의 동적으로 가시성 전환

>[!PREREQUISITES]
>
>* [양식에 국가 선택 목록 추가](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)


Marketing 양식의 가장 멋진 기능 중 하나는 양식 필드 또는 [fieldsets](/help/marketo/product-docs/demand-generation/forms/form-fields/add-a-fieldset-to-a-form.md)를 동적으로 숨기거나 표시할 수 있다는 것입니다.

>[!NOTE]
>
>**예**
>
>이 예에서 **국가**&#x200B;이 &quot;미국&quot;으로 선택되어 있지 않는 한 **상태** 필드를 숨깁니다.

1. **마케팅 활동**&#x200B;으로 이동합니다.

   ![](assets/login-marketing-activities-8.png)

1. 양식을 선택하고 **양식 편집**&#x200B;을 클릭합니다.

   ![](assets/editform-1.png)

1. 동적으로 숨기거나 표시할 필드를 선택하고 **가시성 규칙**&#x200B;에 대한 링크를 클릭합니다.

   ![](assets/image2014-9-15-15-3a16-3a0.png)

1. 조건을 작성할 필드를 찾아 선택합니다.

   ![](assets/image2014-9-15-15-3a16-3a12.png)

1. 연산자를 선택합니다.

   >[!TIP]
   >
   >&quot;다음으로 시작&quot;과 같은 흐릿한 일치를 선택할 수 있으므로 멋진 기능입니다.

   ![](assets/image2014-9-15-15-3a16-3a50.png)

1. 찾을 값을 선택한 다음 드롭다운 바깥쪽을 클릭합니다.

   ![](assets/image2014-9-15-15-3a17-3a4.png)

   >[!TIP]
   >
   >드롭다운이 열려 있는 동안 여러 값을 클릭하여 선택할 수 있습니다. 예를 들어 미국 및 캐나다를 선택할 수 있습니다.

   >[!NOTE]
   >
   >이전에 국가를 선택 목록 필드 유형으로 변환했으며 [모든 국가를 값](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md)으로 추가했습니다.

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-15-15-3a18-3a15.png)

바로 그거야! 이제 사람들이 이 양식을 작성하고 미국(United States for Country)을 선택하면 상태 필드가 지정된 선택 사항과 함께 동적으로 표시됩니다.

---
solution: Marketo Engage
product: marketo
title: 사용자 정의 가능한 조각
description: 일부 필드를 편집할 수 있도록 만들어 조각을 사용자 지정하는 방법을 알아봅니다.
level: Beginner, Intermediate
feature: Email Designer
role: User
exl-id: 3e0232c7-13bd-49e2-b7c7-cd389b5f0704
source-git-commit: cc6c04ca8a72f6efb0bec93cba084fe2993f53f0
workflow-type: tm+mt
source-wordcount: '409'
ht-degree: 1%

---

# 사용자 정의 가능한 조각 {#customizable-fragments}

조각이 이메일 또는 이메일 템플릿에 사용되는 경우 상속으로 인해 기본적으로 잠깁니다. 즉, 조각에 수행된 모든 변경 사항은 조각이 사용되는 모든 자산에 자동으로 전파됩니다. 사용자 지정 가능한 조각을 사용하면 조각을 이메일 또는 이메일 템플릿에 추가할 때 조각 내의 특정 필드를 편집 가능한 것으로 정의할 수 있습니다. 예를 들어 배너, 일부 텍스트 및 버튼이 있는 조각이 있다고 가정해 보겠습니다. 이미지 또는 단추 대상 URL과 같은 특정 필드를 편집 가능한 것으로 지정할 수 있습니다. 이렇게 하면 사용자가 조각을 이메일/이메일 템플릿에 통합할 때 이러한 요소를 수정할 수 있으므로 원본 조각에 영향을 주지 않고 맞춤 경험을 제공합니다.

사용자 지정 가능한 조각을 활용함으로써 완전히 새로운 콘텐츠 블록을 만들거나 원본 조각의 상속을 중단하지 않고도 콘텐츠를 효율적으로 관리하고 개인화할 수 있습니다. 이렇게 하면 조각 수준에서 변경한 사항이 계속 전파되는 동시에 이메일/이메일 템플릿 수준에서 필요한 맞춤화를 수행할 수 있습니다.

시각적 조각과 표현식 조각을 모두 사용자 지정으로 표시할 수 있습니다. 각 조각 유형을 계속 진행하는 방법에 대한 자세한 지침은 아래 섹션을 참조하십시오.

## 시각적 조각에 편집 가능한 필드 추가 {#visual}

시각적 조각의 일부를 편집할 수 있도록 하려면 다음 단계를 수행합니다.

>[!NOTE]
>
>편집 가능한 필드는 **이미지**, **텍스트** 및 **단추** 구성 요소에 추가할 수 있습니다. **HTML** 구성 요소의 경우 표현식 조각과 유사하게 개인화 편집기를 사용하여 편집 가능한 필드가 추가됩니다. [HTML 구성 요소 및 식 조각에서 편집 가능한 필드를 추가하는 방법을 알아봅니다](#expression)

1. 조각 콘텐츠 편집 화면을 엽니다.

1. 조각에서 편집 가능한 필드를 구성할 구성 요소를 선택합니다.

1. 오른쪽에 구성 요소 속성 창이 열립니다. **[!UICONTROL Editable fields]** 탭을 선택한 다음 **[!UICONTROL Enable edition]** 옵션을 전환합니다.

1. 선택한 구성 요소에 대해 편집할 수 있는 모든 필드가 창에 나열됩니다. 편집할 수 있는 필드는 선택한 구성 요소 유형에 따라 다릅니다.

   아래 예에서는 &quot;여기를 클릭&quot; 버튼 URL의 편집을 허용합니다.

   ![](assets/fragment-param-enable.png){width="800" zoomable="yes"}

1. 편집 가능한 모든 필드와 해당 기본값을 확인하려면 **[!UICONTROL Overview]**&#x200B;을(를) 클릭하십시오.

   이 예에서 버튼 URL 필드는 구성 요소에 정의된 기본값으로 표시됩니다. 사용자는 콘텐츠에 조각을 추가한 후 이 값을 사용자 지정할 수 있습니다.

   ![](assets/fragment-param-preview.png){width="800" zoomable="yes"}

1. 완료되면 변경 사항을 저장합니다.

조각을 이메일에 추가하면 사용자는 조각에 구성된 편집 가능한 모든 필드를 사용자 지정할 수 있습니다.
<!--
## Add editable fields in HTML components and expression fragments {#expression}

To make portions of an HTML component or an expression fragment editable, you must use a specific syntax in the expression editor. This involves declaring a _variable_ with a default value that users can override after adding the fragment to their content.

For example, suppose you want to create a fragment to add to your emails, and allow users to customize a specific color used in different locations, such as frames or buttons' background colors. When creating your fragment, you need to declare a variable with a _unique ID_ (e.g., "color"), and call it at the desired locations in the fragment content where you want to apply this color. When adding the fragment to their content, users will be able to customize the color used wherever the variable is referenced.

For HTML components, only specific elements can become editable fields. Expand the section below for more information.

+++Editable elements in HTML components:

The elements below can become editable fields in an HTML component:

* A portion of text
* A full URL for link or image (doesn't work with portion of a URL)
* Entire CSS property (doesn't work with partial property)

For example, in the code below, each element highlighted in red can become a property:

![](assets/fragment-html.png){width="500" zoomable="yes"}

+++
-->
>[!MORELIKETHIS]
>
>[조각](/help/marketo/product-docs/email-marketing/email-designer/fragments.md){target="_blank"}

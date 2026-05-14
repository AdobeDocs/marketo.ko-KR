---
solution: Marketo Engage
product: marketo
title: 사용자 정의 가능한 조각
description: 일부 필드를 편집할 수 있도록 만들어 조각을 사용자 지정하는 방법을 알아봅니다. 이메일 Designer에서 유연한 재사용 가능한 조각을 만듭니다.
level: Beginner, Intermediate
feature: Email Designer
role: User
exl-id: 3e0232c7-13bd-49e2-b7c7-cd389b5f0704
TQID: https://experienceleague.adobe.com/SCmyn9QUECmvQgVltKknlvLuvL15Tz3LYorBFYB1hqI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: fdc003d7aed05d85687427d9455bb806eb33d0b2
workflow-type: tm+mt
source-wordcount: 1398
ht-degree: 0%

---

# 사용자 정의 가능한 조각 {#customizable-fragments}

이메일 또는 이메일 템플릿에서 조각을 사용하는 경우 상속으로 인해 조각이 기본적으로 잠깁니다. 즉, 조각에 대한 모든 변경 사항은 이 조각이 사용되는 모든 에셋에 자동으로 전파됩니다. 사용자 지정 가능한 조각을 사용하면 조각을 이메일 또는 이메일 템플릿에 추가할 때 조각 내의 특정 필드를 편집 가능한 것으로 정의할 수 있습니다. 예를 들어 배너, 일부 텍스트 및 단추가 있는 조각이 있는 경우 이미지 또는 단추 대상 URL과 같은 특정 필드를 편집 가능한 것으로 지정할 수 있습니다.

사용자 지정 가능한 조각을 사용하면 완전히 새로운 콘텐츠 블록을 만들거나 조각 상속을 중단하지 않고도 콘텐츠를 관리하고 개인화할 수 있습니다. 조각 수준에서 변경한 사항은 계속 전파되지만 이메일 또는 이메일 템플릿 수준에서 사용자 지정할 수 있습니다.

시각적 조각과 표현식 조각을 모두 사용자 지정으로 표시할 수 있습니다.

## 시각적 조각에 편집 가능한 필드 추가 {#visual}

시각적 조각의 일부를 편집할 수 있도록 하려면 다음 단계를 수행합니다.

>[!NOTE]
>
>편집 가능한 필드는 **이미지**, **텍스트** 및 **단추** 구성 요소에 추가할 수 있습니다. **HTML** 구성 요소의 경우 표현식 조각과 유사하게 개인화 편집기를 사용하여 편집 가능한 필드가 추가됩니다. [조각의 HTML 구성 요소에서 편집 가능한 필드에 대해 알아봅니다](#editable-html)

1. 조각 콘텐츠 편집 화면을 엽니다.

1. 조각에서 편집 가능한 필드를 구성할 구성 요소를 선택합니다.

1. 오른쪽에 구성 요소 속성 창이 열립니다. **[!UICONTROL Editable fields]** 탭을 선택한 다음 **[!UICONTROL Enable edition]** 옵션을 전환합니다.

1. 선택한 구성 요소에 대해 편집할 수 있는 모든 필드가 창에 나열됩니다. 편집할 수 있는 필드는 선택한 구성 요소 유형에 따라 다릅니다.

   아래 예에서 &quot;여기를 클릭&quot; 버튼 URL은 편집 가능한 것으로 구성되어 있습니다.

   ![](assets/fragment-param-enable.png){width="800" zoomable="yes"}

1. 편집 가능한 모든 필드와 해당 기본값을 확인하려면 **[!UICONTROL Overview]**&#x200B;을(를) 클릭하십시오.

   이 예에서 버튼 URL 필드는 구성 요소에 정의된 기본값으로 표시됩니다. 사용자는 콘텐츠에 조각을 추가한 후 이 값을 사용자 지정할 수 있습니다.

   ![](assets/fragment-param-preview.png){width="800" zoomable="yes"}

1. 완료되면 변경 사항을 저장합니다.

조각을 이메일에 추가한 후 사용자는 조각에 구성된 편집 가능한 모든 필드를 사용자 지정할 수 있습니다.

## 조각에서 편집 가능한 HTML 구성 요소 {#editable-html}

HTML 구성 요소 내에서 다음 유형의 요소를 편집할 수 있습니다.

* **텍스트 콘텐츠**&#x200B;의 일부(예: 헤드라인 또는 CTA 레이블).
* 링크 대상 또는 이미지 소스로 사용되는 전체 **URL**. 부분 URL은 지원되지 않습니다. 변수는 전체 URL 값을 나타내야 합니다.
* 전체 **CSS 속성 값**(예: 전체 색상 값, 전체 패딩 값 또는 전체 너비 값). 부분 CSS 속성 값은 지원되지 않습니다.

매개 변수가 있는 각 CSS 속성 값은 접미사, 추가 텍스트, 여러 변수 및 단일 속성 내의 연결 없이 정확히 `{{{varName}}}`이어야 합니다.

패딩과 같은 다중 측 속성을 매개 변수화하려면 다음 중 하나를 수행합니다.

* 각 면을 별도의 속성 _(권장)_(으)로 선언하거나
* 전체 축약 값을 포함하는 단일 변수를 선언합니다.

## HTML 구성 요소에서 편집 가능한 필드가 작동하는 방식 {#components}

HTML 구성 요소의 편집 가능한 필드는 구성 요소의 소스 코드 내에서 직접 인라인 변수를 선언하여 만듭니다. 각 변수에는 고유한 ID와 기본값이 있습니다. 그러면 마크업에 편집 가능한 값이 표시되어야 하는 모든 곳에서 변수가 참조됩니다.

조각을 저장하고 게시하면 HTML 구성 요소에서 선언된 모든 변수가 조각이 이메일에 추가될 때 편집 가능한 매개 변수로 자동으로 표시됩니다.

그런 다음 이메일 작성자는 기본 Designer을 수정하지 않고 이메일 HTML에서 변수의 기본값을 재정의할 수 있습니다(예: 배경색 변경, CTA URL 대체 또는 헤드라인 업데이트).

## 구문 참조 {#syntax}

편집 가능한 필드는 다음 두 가지 패턴을 사용하여 정의되고 참조됩니다.

### 변수 선언 {#declaring}

인라인 선언을 사용하여 고유 ID와 기본값으로 변수를 정의합니다.

```handlebars
{{#inline "variableID"}}default_value{{/inline}}
```

`variableID`을(를) 편집 가능한 필드의 고유 식별자로 바꿉니다. ID는 구성 요소 내에서 고유해야 하며 공백을 포함해서는 안 됩니다.

`default_value`을(를) 이메일 작성자가 재정의하지 않는 경우 사용해야 하는 값으로 바꿉니다.

### 변수 참조 {#referencing}

마크업에 값이 표시되어야 하는 모든 위치에서 변수를 참조하려면 세 개의 중괄호를 사용합니다.

```handlebars
{{{variableID}}}
```

HTML 내에서 동일한 변수 ID를 여러 번 참조할 수 있습니다. 모든 참조는 이메일 작성자가 설정한 값으로 확인됩니다(또는 무시가 제공되지 않은 경우 기본값으로 확인).

### 선택적 매개 변수 {#optional}

인라인 선언은 편집 가능한 필드가 표시되거나 처리되는 방식을 변경하는 선택적 매개 변수를 지원합니다.

| 작업 | 매개변수 | 예 |
|---|---|---|
| 편집 가능한 필드를 **기본값**(으)로 선언합니다. 조각이 이메일에 추가되면 작성자가 재정의하지 않는 한 이 기본값이 사용됩니다. | 인라인 태그 사이에 기본값을 추가합니다. | `{{#inline "editableFieldID"}}default_value{{/inline}}` |
| 편집 가능한 필드에 대해 **레이블**&#x200B;을(를) 정의합니다. 이 레이블은 이메일 작성자가 조각의 필드를 편집할 때 이메일 Designer에 표시됩니다. | `name="title"` | `{{#inline "editableFieldID" name="title"}}default_value{{/inline}}` |
| **이미지 원본**&#x200B;이 포함된 편집 가능한 필드를 선언하십시오. | `assetType="image"` | `{{#inline "editableFieldID" assetType="image"}}default_value{{/inline}}` |
| 추적해야 하는 **URL**&#x200B;이(가) 포함된 편집 가능한 필드를 선언합니다. | `assetType="url"` | `{{#inline "editableFieldID" assetType="url"}}default_value{{/inline}}` |

## HTML 구성 요소에 편집 가능한 필드 추가 {#adding-editable-fields}

시각적 조각 내의 HTML 구성 요소 일부를 편집할 수 있도록 하려면 다음 단계를 수행합니다.

1. 이메일 Designer에서 편집할 시각적 조각을 엽니다.
1. 구성 요소 패널에서 조각에 **HTML 구성 요소**&#x200B;를 추가하거나 기존 HTML 구성 요소를 선택합니다.
1. HTML 구성 요소를 선택한 상태에서 **소스 코드 표시**&#x200B;를 클릭하여 개인화 편집기에서 HTML 소스 보기를 엽니다.
1. 개인화 편집기에서 인라인 선언 구문을 사용하여 편집 가능한 각 변수를 선언합니다. 가독성을 위해 구성 요소의 맨 위에 모든 변수 선언을 배치하고 각 변수에 고유 ID를 지정합니다.
1. 편집 가능한 값이 나타날 때마다 `{{{variableID}}}` 구문을 사용하여 HTML 마크업의 각 변수를 참조합니다. 동일한 구성 요소에서 동일한 변수를 여러 번 참조할 수 있습니다.
1. HTML 구성 요소를 저장한 다음 조각을 저장합니다.
1. 이메일에 사용할 수 있도록 조각을 게시합니다.

## 이메일에서 조각 사용 {#using-fragment}

조각이 게시되면 HTML 구성 요소에서 선언된 모든 변수가 이메일 Designer에서 편집 가능한 매개 변수로 표시됩니다.

이메일에서 조각을 사용할 때 맞춤화하려면 다음을 수행하십시오.

1. Marketo Engage 이메일 Designer에서 이메일을 열거나 만듭니다.
1. 게시된 조각을 이메일 캔버스에 추가합니다.
1. 조각을 선택하여 속성 창을 엽니다. 편집 가능한 필드 목록이 **편집 가능한 필드** 섹션 아래에 표시되고 각 필드는 해당 변수 ID(또는 `name` 매개 변수를 통해 지정된 친숙한 레이블)로 레이블이 지정됩니다.
1. 속성 창에서 바로 편집 가능한 필드의 값을 업데이트합니다. 변경 사항은 현재 이메일에만 적용되며 게시된 조각 및 이를 참조하는 다른 이메일은 영향을 받지 않습니다.
1. 이메일을 저장합니다.

조각은 사용자 지정된 값으로 렌더링되는 동시에 게시된 조각에 대해 수행된 향후 구조적 업데이트를 상속합니다.

### 예: 편집 가능한 텍스트, 색상 및 URL이 있는 간단한 조각 {#example}

다음 예제에서는 편집 가능한 필드 4개가 있는 작은 홍보 배너를 만듭니다.

* 배경색
* 제목 텍스트
* CTA 레이블
* CTA URL

조각을 게시한 후 이메일 작성자는 이메일에 조각을 추가할 때 이러한 값을 재정의할 수 있습니다.

**간단한 편집 가능한 배너**

```html
<!-- Define editable variables -->
{{#inline "bgColor"}}#0057FF{{/inline}}
{{#inline "headlineText"}}Example Headline{{/inline}}
{{#inline "ctaText"}}Learn More{{/inline}}
{{#inline "ctaUrl" assetType="url"}}https://www.example.com{{/inline}}

<!-- Use the variables in the HTML -->
<table width="100%" cellpadding="0" cellspacing="0"
       style="background-color:{{{bgColor}}}; border-radius:8px;" >
  <tr>
    <td style="padding:30px; text-align:center; font-family:Arial,sans-serif;">
      <h2 style="color:#ffffff; font-size:24px; margin:0;">
        {{{headlineText}}}
      </h2>
      <a href="{{{ctaUrl}}}"
         style="display:inline-block; margin-top:16px; padding:12px 28px;
                background:#ffffff; color:{{{bgColor}}};
                font-weight:bold; border-radius:4px; text-decoration:none;">
        {{{ctaText}}}
      </a>
    </td>
  </tr>
</table>
```

이 예에서,

* `bgColor`이(가) 표 배경색에 대해 한 번, CTA 텍스트 색상에 대해 한 번 두 번 참조됩니다. 두 참조가 동일한 값으로 확인되므로 단일 편집이 두 위치로 전파됩니다.
* `ctaUrl`이(가) `assetType="url"`(으)로 선언되어 해당 값이 추적된 URL로 처리되어야 함을 나타냅니다.

## 모범 사례 {#best-practices}

* 변수가 전체 CSS 값을 나타내도록 변수의 기본값 내에 단위(`px`, `em`, `%`)를 포함하십시오. 이렇게 하면 지원되지 않는 연결이 방지됩니다.
* 각 면을 독립적으로 편집해야 하는 경우 줄바꿈보다 각 면의 길이 및 CSS 속성(`padding-top`, `padding-right`, `padding-bottom`, `padding-left`)을 선호합니다.
* URL을 추적해야 하는 경우 `assetType="url"`(으)로 선언하십시오.
* 편집 가능한 필드에 이미지 소스가 있으면 `assetType="image"`(으)로 선언하십시오.
* 초안 이메일에 조각을 추가하고 편집 가능한 모든 필드가 속성 창에 나타나고 재정의할 때 올바르게 해결되는지 확인하여 조각을 테스트합니다.

## 알아야 할 사항 {#things-to-know}

* HTML 구성 요소의 편집 가능한 필드는 전체 텍스트 컨텐츠, 전체 URL 및 전체 CSS 속성 값을 지원합니다. 부분 URL 및 부분 CSS 속성 값은 매개 변수화할 수 없습니다.
* 단일 CSS 속성 값은 변수를 추가 정적 텍스트나 다른 변수와 결합할 수 없습니다. 매개 변수가 있는 각 속성 값은 정확히 하나의 변수 참조여야 합니다.
* 변수 ID는 HTML 구성 요소 내에서 고유해야 하며 공백을 포함해서는 안 됩니다.
* 구독 취소 링크 및 미러 페이지 URL과 같은 기본 시스템 링크는 편집 가능한 필드로 전환할 수 없습니다.

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

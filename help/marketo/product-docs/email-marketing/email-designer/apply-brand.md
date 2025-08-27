---
solution: Marketo Engage
product: marketo
title: 제목
description: 재사용 가능한 테마 및 모듈을 사용하여 이메일 생성을 간소화하고 디자인의 일관성과 효율성을 보장하는 방법을 알아봅니다.
feature: Email Designer
role: User
level: Beginner, Intermediate
hide: true
hidefromtoc: true
exl-id: 349ee021-7341-40e0-8d8c-d041f1a8f343
source-git-commit: 0c0dd3355f979577ec194f9e8f935615515905c0
workflow-type: tm+mt
source-wordcount: '710'
ht-degree: 4%

---

# 이메일 콘텐츠에 테마 적용 {#apply-email-themes}

>[!AVAILABILITY]
>
>이 기능은 현재 Beta 버전으로 Beta 고객에게만 제공됩니다. Beta 프로그램에 참여하려면 Adobe 담당자에게 문의하십시오.

테마를 사용하면 기술 전문가가 아닌 사용자도 표준 템플릿<!-- to achieve brand specific results--> 위에 사용자 지정 스타일을 추가하여 특정 브랜드 및 디자인 언어에 맞는 재사용 가능한 콘텐츠를 만들 수 있습니다.

이 기능을 통해 마케터는 시각적으로 호소력 있고 브랜드 일관성이 있는 이메일을 적은 노력으로 더 빠르고 활용할 수 있으며, 고유한 디자인 요구 사항에 대한 고급 사용자 지정 옵션을 제공할 수 있습니다.

<!--What is the Enhanced Email Authoring Experience?

This feature introduces two key components to simplify and enhance email creation:

* **Theme Management System**: A centralized system for creating, customizing, and applying reusable themes to emails. Themes ensure consistent styling across campaigns and eliminate the need for repetitive manual styling.

* **Modules**: Pre-designed, reusable content blocks that abstract common email elements (e.g., titles, descriptions, images, and links). Modules are built using customizable low-level components, offering flexibility while maintaining design standards.

Key Benefits:

- **Consistency**: Ensure all emails align with your brand's design guidelines.
- **Efficiency**: Save time by reusing themes and modules across campaigns.
- **Customization**: Add custom CSS and mobile-specific styles for advanced designs.
- **Scalability**: Eliminate repetitive styling tasks, enabling faster email creation.-->

## 가드레일 및 제한 사항 {#themes-guardrails}

* 처음부터 이메일을 만들 때는 테마를 사용하여 콘텐츠 작성을 시작하도록 선택하여 내 브랜드 및 디자인에 맞는 특정 스타일을 빠르게 적용할 수 있습니다.

  _수동 스타일링_ 모드를 선택한 경우 이메일을 다시 설정하지 않으면 테마를 적용할 수 없습니다.

* [조각](/help/marketo/product-docs/email-marketing/email-designer/fragments.md)은(는) _테마 사용_&#x200B;과(와) _수동 스타일 지정_ 모드 간에 서로 호환되지 않습니다.

  테마가 적용되는 콘텐츠에서 조각을 사용하려면 _테마 사용_ 모드에서 이 조각을 만들어야 합니다.

* HTML에서 만든 콘텐츠를 사용하는 경우 [호환성 모드](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html)가 되므로 이 콘텐츠에 테마를 적용할 수 없습니다.

  테마를 포함한 이메일 Designer의 모든 기능을 완전히 활용하려면 _테마 사용_ 모드에서 새 콘텐츠를 만들거나 [가져온 HTML 콘텐츠를 변환](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html)해야 합니다.

<!--If using a content created in Manual Styling mode or HTML, you cannot apply themes to this content. You must create a new content in Use Themes mode.

If you apply a theme to a content using a [fragment](../content-management/fragments.md) created in Manual Styling mode, the rendering may not be optimal.-->

## 테마 만들기 {#create-and-edit-themes}

향후 이메일 콘텐츠에서 활용할 수 있는 테마를 정의하려면 아래 단계를 따르십시오.

1. 시작하려면 새 [전자 메일 서식 파일](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md#create-an-email-template)을 만드세요.

1. **[!UICONTROL Create or edit themes]** 옵션을 선택하십시오.

   `![](assets/theme-create.png)`

1. 기본 테마를 선택하거나 Adobe 또는 사용자 지정 템플릿을 사용할 수 있습니다. 이 예제에서는 기본 테마를 선택하고 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   `![](assets/theme-select.png)`

1. **[!UICONTROL General settings]** 탭에서 브랜드의 특정 이름을 지정하여 테마를 정의합니다. 이메일의 기본 너비를 조정하고 현재 테마를 내보내 샌드박스 간에 공유할 수 있습니다.

   `<!--![](assets/theme-general-settings.png)-->`

1. 오른쪽의 레일을 사용하여 다양한 탭을 탐색하고 디자인 설정을 업데이트합니다.

   `![](assets/theme-right-pane.png)`

1. **[!UICONTROL Colors]** 탭에서:

   * **[!UICONTROL Edit]** 단추를 사용하여 브랜드의 기본 색상으로 **[!UICONTROL Color palette]**&#x200B;을(를) 설정합니다. **[!UICONTROL Preset]**&#x200B;을(를) 선택하여 색 구성표를 빠르게 만들거나 각 테마 색을 개별적으로 조정하세요. 두 가지를 조합하여 사용할 수도 있습니다.

     `![](assets/theme-colors.gif)`

   * 각 변형마다 고유한 색상 팔레트 및 뉘앙스 컨트롤이 있는 밝은 모드 및 어두운 모드와 같은 여러 색상 변형을 만들려면 **[!UICONTROL Add variant]**&#x200B;을(를) 클릭하십시오.

     `![](assets/theme-colors-variant.png)`

   * 각 변형에 대해 편집 아이콘을 클릭하여 개별 요소를 편집합니다. 만든 기본 팔레트 또는 사용자 지정 색상을 사용할 수 있습니다.

     `![](assets/theme-colors-edit-variant.gif)`

1. **[!UICONTROL Text settings]**&#x200B;에서 전체 테마에 사용할 전역 글꼴을 설정할 수 있습니다. 더 세분화된 제어를 위해 각 제목과 단락 유형을 편집하여 글꼴, 크기, 스타일 등을 조정할 수도 있습니다.

   `![](assets/theme-text.png)`

1. **[!UICONTROL Spacing]** 탭의 목록에서 개별 요소를 선택하여 다른 구성 요소 간에 적절하게 공간을 확보합니다.

   `<!--![](assets/theme-spacing.png)-->`

1. 오른쪽의 다른 탭을 사용하여 이 테마의 각 단추 요소, 구분선, 추가 이미지 서식 및 격자 레이아웃 간격을 별도로 관리할 수 있습니다.

   `<!--![](assets/theme-buttons.png)-->`

1. 나중에 사용할 수 있도록 이 테마를 저장하려면 **[!UICONTROL Save]**&#x200B;을(를) 클릭하십시오.

## 전자 메일에 테마 적용 {#apply-themes}

이메일에 기본 또는 사용자 지정 스타일 테마를 적용하려면 아래 단계를 따르십시오.

1. `In [!DNL Marketo Engage], [add an email](create-email.md) action to a journey or campaign, and [edit your email body](get-started-email-design.md#key-steps).`

1. 다음 작업 중 하나를 선택할 수 있습니다.

   * `Select a built-in [email template](use-email-templates.md) to open the Email Designer. A default theme specific to each template is automatically applied.`

   * `Design a [new content from scratch](content-from-scratch.md) and select **[!UICONTROL Use Themes]** to start with a predefined styling theme.`

     `![](assets/theme-from-scratch.png)`

     >[!CAUTION]
     >
     >_수동 스타일링_ 모드를 선택한 경우 이메일을 다시 설정하지 않으면 테마를 적용할 수 없습니다.
     >
     >[테마 사용](/help/marketo/product-docs/email-marketing/email-designer/fragments.md) 모드에서 _조각_&#x200B;을 사용하려면 _테마 사용_ 모드를 사용하여 이 조각을 직접 만들어야 합니다.

1. 이메일 Designer에서 오른쪽 레일의 **[!UICONTROL Themes]** 단추를 클릭합니다. 기본 테마 또는 템플릿의 테마가 표시됩니다. 이 테마의 두 색상 변형 간을 전환할 수 있습니다.

   `![](assets/theme-default-hero.png)`

1. 현재 사용 중인 테마 옆의 화살표를 클릭합니다. 사용 가능한 사용자 지정 및 Adobe 테마 목록이 표시됩니다.

   `![](assets/theme-hero-change.png)`

1. **[!UICONTROL Custom themes]**&#x200B;을(를) 클릭하고 만든 테마를 선택합니다.

   `![](assets/theme-select-custom.png)`

1. 드롭다운 목록 외부를 클릭합니다. 새로 선택한 사용자 지정 테마는 모든 이메일 구성 요소에 스타일을 자동으로 적용합니다. 두 색상 변형 간을 전환할 수 있습니다.

1. 구성 요소를 선택한 경우에도 전용 아이콘을 사용하여 스타일 잠금을 해제할 수 있습니다.

   `![](assets/theme-unlock-style.png)`

언제든지 테마를 전환할 수 있습니다. 이메일 콘텐츠는 변경되지 않지만 스타일은 새 테마를 반영하도록 업데이트됩니다.

<!--
>[!NOTE]
> - Themes apply styles globally. Ensure your theme is finalized before applying it to multiple emails.
> - Switching themes may override custom styles applied to individual components.

>[!CAUTION]
> - When using fragments, the email's theme will override the fragment's styles. A warning will be displayed in the editor if there is a conflict.

## Example Use Cases {#example-use-cases}

### 1. Creating a New Theme
- A marketer creates a theme with their brand's colors, fonts, and button styles.
- The theme is saved and reused across multiple email campaigns.

### 2. Switching Themes
- A marketer applies a holiday-themed design to an existing email by switching to a pre-designed holiday theme.-->

---
solution: Marketo Engage
product: marketo
title: 콘텐츠 구성 요소
description: 설명.
level: Beginner, Intermediate
feature: Email Designer
hide: true
hidefromtoc: true
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '1154'
ht-degree: 0%

---

# 콘텐츠 구성 요소 {#content-components}

전자 메일 콘텐츠를 만들 때 **[!UICONTROL Content components]**&#x200B;을(를) 사용하면 전자 메일에 배치되면 편집할 수 있는 원시 구성 요소로 전자 메일을 추가로 개인화할 수 있습니다.

하나 이상의 구조 구성 요소 내에 필요한 만큼 콘텐츠 구성 요소를 추가하여 이메일의 레이아웃을 정의할 수 있습니다.

## 콘텐츠 구성 요소 추가 {#add-content-components}

이메일에 콘텐츠 구성 요소를 추가하고 필요에 따라 조정하려면 아래 단계를 따르십시오.

1. 이메일 Designer에서 기존 콘텐츠를 사용하거나 **[!UICONTROL Structure components]**&#x200B;을(를) 빈 콘텐츠로 끌어다 놓아 이메일 레이아웃을 정의합니다. `[Learn how](content-from-scratch.md)`

1. **[!UICONTROL Content components]** 섹션에 액세스하려면 [전자 메일 Designer] 왼쪽 창에서 해당 단추를 선택합니다.

   스크린샷

1. 관련 구조 구성 요소 내부에 선택한 콘텐츠 구성 요소를 드래그하여 놓습니다.

   스크린샷

   >[!NOTE]
   >
   >여러 구성 요소를 단일 구조 구성 요소 및 구조 구성 요소의 각 열에 추가할 수 있습니다.

1. 오른쪽의 **[!UICONTROL Settings]** 및 **[!UICONTROL Style]** 탭을 사용하여 각 구성 요소의 특성과 스타일을 조정합니다. 예를 들어 각 구성 요소의 텍스트 스타일, 패딩 또는 여백을 변경할 수 있습니다. `[Learn more about alignment and padding](alignment-and-padding.md)`

   스크린샷

1. **[!UICONTROL Content component]**&#x200B;의 고급 메뉴에서 필요에 따라 콘텐츠 구성 요소를 쉽게 삭제하거나 복제할 수 있습니다.

   스크린샷

## 컨테이너 {#container}

콘텐츠 구성 요소 그룹에 특정 스타일을 적용하려면 **[!UICONTROL Container]** 구성 요소를 추가한 다음 원하는 콘텐츠 구성 요소를 추가할 수 있습니다. 이렇게 하면 컨테이너에 고유한 스타일을 적용할 수 있습니다. 이는 내부의 콘텐츠 구성 요소에 적용된 스타일과 다릅니다.

예를 들어 **[!UICONTROL Container]** 구성 요소를 추가한 다음 해당 컨테이너 내에 [Button](#button) 구성 요소를 추가합니다. 컨테이너에는 특정 배경을 사용하고 단추에는 다른 배경을 사용할 수 있습니다.

스크린샷

## 버튼 {#button}

**[!UICONTROL Button]** 구성 요소를 사용하여 하나 이상의 단추를 전자 메일에 삽입하고 전자 메일 대상자를 다른 페이지로 리디렉션합니다.

1. **[!UICONTROL Content components]**&#x200B;에서 **[!UICONTROL Button]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

1. 텍스트를 개인화하고 이메일 Designer 오른쪽 창의 **[!UICONTROL Settings]** 및 **[!UICONTROL Styles]** 탭에 액세스하려면 새로 추가한 단추를 클릭하십시오.

   스크린샷

1. 단추를 클릭할 때 **[!UICONTROL Link]** 메뉴에서 리디렉션할 URL을 추가합니다.

1. 대상자를 **[!UICONTROL Target]** 드롭다운 목록으로 리디렉션하는 방법을 선택하십시오.

   * **[!UICONTROL None]**: 클릭한 것과 동일한 프레임에서 링크를 엽니다(기본값).
   * **[!UICONTROL Blank]**: 새 창이나 탭에서 링크를 엽니다.
   * **[!UICONTROL Self]**: 클릭한 것과 같은 프레임에서 링크를 엽니다.
   * **[!UICONTROL Parent]**: 부모 프레임에서 링크를 엽니다.
   * **[!UICONTROL Top]**: 창의 전체 본문에서 링크를 엽니다.

   스크린샷

1. **[!UICONTROL Border]**, **[!UICONTROL Size]**, **[!UICONTROL Margin]** 등의 스타일 특성을 변경하여 단추를 추가로 개인화할 수 있습니다. **[!UICONTROL Component settings]** 창에서 액세스할 수 있습니다.

## 텍스트 {#text}

**[!UICONTROL Text]** 구성 요소를 사용하여 전자 메일에 텍스트를 삽입하고 **[!UICONTROL Styles]** 탭을 사용하여 스타일(테두리, 크기, 패딩 등)을 조정합니다.

스크린샷

1. **[!UICONTROL Content components]**&#x200B;에서 **[!UICONTROL Text]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

1. 텍스트를 개인화하고 이메일 Designer 오른쪽 창의 **[!UICONTROL Settings]** 및 **[!UICONTROL Styles]** 탭에 액세스하려면 새로 추가한 구성 요소를 클릭합니다.

1. 도구 모음에서 다음 옵션을 사용하여 텍스트를 변경합니다.

   스크린샷

   * **[!UICONTROL Change text style]**: 텍스트에 굵게, 기울임꼴, 밑줄 또는 취소선을 적용합니다.
   * **맞춤 변경**: 텍스트를 왼쪽, 오른쪽, 가운데 또는 양쪽 맞춤 중에서 선택합니다.
   * **[!UICONTROL Create list]**: 글머리 기호 또는 번호 목록을 텍스트에 추가합니다.
   * **[!UICONTROL Set heading]**: 텍스트에 최대 6개의 제목 수준을 추가합니다.
   * **글꼴 크기**: 텍스트의 글꼴 크기를 픽셀 단위로 선택합니다.
   * **[!UICONTROL Change font color]**: 글꼴 색상을 선택합니다.
   * **[!UICONTROL Insert link]**: 콘텐츠에 모든 유형의 링크를 추가합니다.
   * **[!UICONTROL Edit image]**: 텍스트 구성 요소에 이미지 또는 자산을 추가합니다. `[Learn more about asset management](../integrations/assets.md)`
   * **[!UICONTROL Change font color]**: 글꼴 색상을 선택합니다.
   * **[!UICONTROL Add personalization]**: 프로필 데이터에서 콘텐츠를 사용자 지정할 개인화 필드를 추가합니다. `[Learn more about content personalization](../personalization/personalize.md)`
   * **[!UICONTROL Show the source code]**: 텍스트의 소스 코드를 표시합니다. 수정할 수 없습니다.
   * **[!UICONTROL Enable conditional content]**: 구성 요소의 콘텐츠를 타겟팅된 프로필로 조정하려면 조건부 콘텐츠를 추가하십시오. `[Learn more about dynamic content](../personalization/get-started-dynamic-content.md)`
   * **[!UICONTROL Duplicate]**: 텍스트 구성 요소의 복사본을 추가합니다.
   * **[!UICONTROL Delete]**: 전자 메일에서 선택한 텍스트 구성 요소를 삭제합니다.

1. 텍스트 색상, 글꼴 패밀리, 테두리, 패딩, 여백 등의 다른 스타일 속성을 조정합니다. **[!UICONTROL Styles]** 탭에서.

   스크린샷

## 분할자 {#divider}

**[!UICONTROL Divider]** 구성 요소를 사용하여 전자 메일의 레이아웃과 콘텐츠를 구성하는 구분선을 삽입합니다.

**[!UICONTROL Settings]** 및 **[!UICONTROL Styles]** 탭에서 선 색상, 스타일 및 높이와 같은 스타일 특성을 조정할 수 있습니다.

스크린샷

## HTML {#HTML}

**[!UICONTROL HTML]** 구성 요소를 사용하여 기존 HTML의 다른 부분을 복사하여 붙여 넣으십시오. 이를 통해 자유 모듈식 HTML 구성 요소를 만들어 일부 외부 콘텐츠를 재사용할 수 있습니다.

1. **[!UICONTROL Content Components]**&#x200B;에서 **[!UICONTROL HTML]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

1. 새로 추가한 구성 요소를 클릭한 다음 상황별 도구 모음에서 **[!UICONTROL Show the source code]**&#x200B;을(를) 선택하여 HTML을 추가합니다.

   스크린샷

1. 전자 메일에 추가할 HTML 코드를 복사하여 붙여 넣은 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   스크린샷

>[!NOTE]
>
>단순히 외부 콘텐츠가 이메일 Designer을 준수하도록 하기 위해, Adobe에서는 메시지를 처음부터 만들고 기존 이메일의 콘텐츠를 구성 요소로 복사할 것을 권장합니다.

## 이미지 {#image}

**[!UICONTROL Image]** 구성 요소를 사용하여 컴퓨터의 이미지 파일을 전자 메일 콘텐츠에 삽입합니다.

1. **[!UICONTROL Content components]**&#x200B;에서 **[!UICONTROL Image]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

   스크린샷

1. **[!UICONTROL Settings]** 탭에서 **[!UICONTROL Browse]**&#x200B;을(를) 클릭하여 에셋에서 이미지 파일을 선택하거나 **[!UICONTROL Import media]**&#x200B;을(를) 클릭하여 에셋을 Adobe Experience Manager Assets에 업로드합니다.

   [!DNL Adobe Experience Manager Assets]에 대한 자세한 내용은 [Adobe Experience Manager Assets 설명서](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/introduction.html?lang=ko){target="_blank"}를 참조하세요.

   >[!NOTE]
   >
   > 링크가 활성 상태를 유지하고 만료 문제를 방지하려면 이미지에 대한 소스 URL에 의존하는 대신 Adobe Assets을 사용하는 것이 좋습니다.

1. **[!UICONTROL Find Adobe Stock photos]** 옵션을 사용하여 Adobe Stock에서 직접 검색할 수도 있습니다.

1. 새로 추가한 구성 요소를 클릭하고 이미지 속성을 설정합니다.

   * **[!UICONTROL Image title]**&#x200B;을(를) 사용하면 이미지에 제목을 정의할 수 있습니다.
   * **[!UICONTROL Alt text]** 이미지에 연결된 캡션을 정의할 수 있습니다. 이는 alt HTML 속성에 해당합니다.

   스크린샷

1. **[!UICONTROL Find similar Stock photos]**&#x200B;을(를) 선택할 수도 있습니다. `[Learn more](../integrations/stock.md)`

1. **[!UICONTROL Styles]** 탭에서 여백, 테두리 등의 다른 스타일 특성을 조정합니다. 또는 대상을 **[!UICONTROL Component settings]** 창에서 다른 콘텐츠로 리디렉션하는 링크를 추가합니다.

## 소셜 {#social}

**[!UICONTROL Social]** 구성 요소를 사용하여 소셜 미디어 페이지에 대한 링크를 이메일 콘텐츠에 삽입합니다.

1. **[!UICONTROL Content Components]**&#x200B;에서 **[!UICONTROL Social]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

1. 새로 추가한 구성 요소를 선택합니다.

1. **[!UICONTROL Social]** 탭의 **[!UICONTROL Settings]** 필드에서 추가하거나 제거할 소셜 미디어를 선택합니다.

   스크린샷

1. 전용 필드를 통해 아이콘 크기를 선택합니다.

1. 소셜 미디어 아이콘을 각각 클릭하여 대상자를 리디렉션할 **[!UICONTROL URL]**&#x200B;을(를) 구성합니다.

   스크린샷

1. 필요한 경우 Assets에서 각 소셜 미디어의 아이콘을 변경할 수도 있습니다.

1. 스타일, 여백, 테두리 등의 다른 스타일 특성을 조정합니다. **[!UICONTROL Styles]** 탭에서.

## 오퍼 결정 {#offer-decision}

**[!UICONTROL Offer decision]** 구성 요소를 사용하여 메시지에 오퍼를 삽입합니다. `[decision management](../offers/get-started/starting-offer-decisioning.md)` 엔진은 고객에게 제공할 최상의 오퍼를 선택합니다.

1. **[!UICONTROL Content Components]**&#x200B;에서 **[!UICONTROL Offer decision]** 구성 요소를 **[!UICONTROL Structure component]**(으)로 끌어다 놓습니다.

1. **[!UICONTROL Add]**&#x200B;을(를) 클릭하여 **[!UICONTROL Offer decision]**&#x200B;을(를) 선택합니다.

   스크린샷

1. 드롭다운에서 **[!UICONTROL Placements]**&#x200B;을(를) 선택합니다.  그런 다음 콘텐츠에 추가할 **[!UICONTROL Offer decision]**&#x200B;을(를) 선택하고 **[!UICONTROL Add]**&#x200B;을(를) 클릭합니다.

   스크린샷

1. **[!UICONTROL Offer decision]** 탭에서 삽입된 오퍼를 미리 보거나 변경할 수 있습니다.

`[this section](add-offers-email.md)`에서 개인화된 오퍼를 전자 메일에 추가하는 방법을 알아봅니다.

>[!IMPORTANT]
>
>여정의 메시지에 사용 중인 오퍼 의사 결정이 변경되는 경우 여정 게시를 취소하고 다시 게시해야 합니다.  이렇게 하면 변경 사항이 여정 메시지에 통합되고 메시지가 최신 업데이트와 일관되게 표시됩니다.

---
unique-page-id: 2953419
description: 리치 텍스트 편집기 사용 - Marketo 문서 - 제품 설명서
title: 리치 텍스트 편집기 사용
exl-id: 9b2d6d41-f947-4859-aad9-a10c15eb013a
feature: Email Editor
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '659'
ht-degree: 1%

---

# 리치 텍스트 편집기 사용 {#using-the-rich-text-editor}

리치 텍스트 편집기(RTE)는 Marketo 전체에 표시되며 컨텐츠를 추가하거나 편집할 때마다 사용할 수 있습니다. 랜딩 페이지, 프로그램, 이메일, 양식 및 스니펫에 버전이 표시됩니다. **[!UICONTROL Edit Draft]**&#x200B;을(를) 클릭하면 표시됩니다.

## 편집기 설정 {#editor-settings}

루트 블록 요소 설정은 콘텐츠를 래핑하는 태그를 정의합니다. 기본적으로 전자 메일 루트 블록 요소는 `<p>`개의 태그를 사용합니다. 아래 단계에 따라 변경할 수 있습니다.

>[!TIP]
>
>루트 블록 요소를 선택하는 옵션이 있지만 항상 최상의 사용자 경험을 위해 기본 설정을 사용하는 것이 좋습니다.

1. **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL Email]**&#x200B;을(를) 클릭합니다.

   ![](assets/two.png)

1. **[!UICONTROL Edit Text Editor Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/three.png)

1. **[!UICONTROL Email]/[!UICONTROL Snippet Editor]** 드롭다운에서 `<div>` 또는 [!UICONTROL None]을(를) 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다. 이 예제에서는 `<div>`을(를) 사용합니다.

   ![](assets/four.png)

   이메일 템플릿에 `<div class=“mktEditable”></div>`이(가) 있는 경우 섹션을 열고 편집기에 &quot;Text Goes Here&quot;를 입력하면 다음과 같은 HTML Source 동작이 표시됩니다.

<table> 
 <tbody> 
  <tr> 
   <th>&lt;p&gt;</th> 
   <th>&lt;div&gt;</th> 
   <th>None</th> 
  </tr> 
  <tr> 
   <td><p>&lt;div class="mktEditable"&gt;<br>&lt;p&gt;텍스트 입력&lt;/p&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class="mktEditable"&gt;<br>&lt;div&gt;텍스트 이동&lt;/div&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class="mktEditable"&gt;<br>텍스트 위치<br>&lt;/div&gt;</p></td> 
  </tr> 
 </tbody> 
</table>

>[!TIP]
>
>동일한 단계를 따르되 **[!UICONTROL Landing Page Editor]** / [!UICONTROL Email] 대신 4단계에서 [!UICONTROL Snippet Editor] 드롭다운을 클릭하여 랜딩 페이지 편집기의 루트 블록 요소를 변경할 수도 있습니다.

>[!NOTE]
>
>서식 있는 텍스트 프로그램 토큰의 경우 루트 블록 요소는 항상 `<p>`입니다.

## 기능 {#features}

다음은 RTE에서 확인할 수 있는 기능입니다.

| 아이콘 | 이름 | 기능 |
|---|---|---|
| ![—](assets/image2015-7-9-10-3a23-3a24.png) | [!UICONTROL Font Family] | 스타일을 선택하세요. 많이 있습니다! |
| ![—](assets/image2015-7-9-10-3a22-3a11.png) | [!UICONTROL Font Size] | 얼마나 크게 드릴까요? 8픽셀에서 90픽셀까지 25개 옵션. |
| ![—](assets/image2015-7-9-10-3a59-3a4.png) | [!UICONTROL Styles] | 단락 또는 6개의 제목 스타일(랜딩 페이지의 경우)을 선택합니다. |
| ![—](assets/image2015-7-9-10-3a20-3a1.png) | [!UICONTROL Line Spacing] | 선 사이의 거리를 선택하십시오. |
| ![—](assets/image2015-7-9-10-3a25-3a52.png) | [!UICONTROL Text Color] | 검정색, 빨간색 아니면 당신이 원하는 어떤 것이든. |
| ![—](assets/image2015-7-9-10-3a24-3a38.png) | [!UICONTROL Background Color] | 강조를 강조 표시합니다. |
| ![—](assets/image2015-7-9-10-3a28-3a4.png) | [!UICONTROL Bold] | **어둡고 굵게**. |
| ![—](assets/image2015-7-9-10-3a29-3a1.png) | [!UICONTROL Italic] | *각진, 강조 또는 인용*. |
| ![—](assets/image2015-7-9-10-3a30-3a56.png) | [!UICONTROL Underline] | 텍스트 아래에 줄을 넣습니다. |
| ![—](assets/image2015-7-9-10-3a31-3a57.png) | [!UICONTROL Alignment] | 이 드롭다운을 사용하여 텍스트 및 이미지를 배치합니다. 가운데로 맞추거나 왼쪽 또는 오른쪽 정렬을 선택하거나 전체 정렬 상태로 가장자리에 펼칩니다. |  | ![—](assets/image2015-7-9-10-3a32-3a47.png) | 목록 | 드롭다운에서 글머리 기호 또는 숫자를 선택합니다. 글머리 기호는 목록이 있는 숫자와 단계가 있는 숫자에 적합합니다. |
| ![—](assets/image2015-7-9-10-3a38-3a0.png) | [!UICONTROL Indent] | 들여쓰기를 더 많이 또는 더 적게 선택합니다. 돋보려는 단락이나 텍스트에 을 사용합니다. |
| ![—](assets/image2015-7-9-10-3a38-3a58.png) | [!UICONTROL Insert/Edit Link] | 웹 사이트 또는 기타 컨텐츠에 대한 링크를 넣습니다. 쉽게 변경할 수 있습니다. |
| ![—](assets/image2015-7-9-10-3a39-3a42.png) | [!UICONTROL Insert/Edit Image] | 그림은 천 마디의 말을 할 가치가 있다. 한 대 떨어뜨려 카메라 아이콘을 클릭하여 Design Studio를 찾아봅니다. 이미지를 나란히 드롭할 수 있습니다. |
| ![—](assets/image2015-7-9-10-3a40-3a36.png) | [!UICONTROL Insert Token] | 이메일 개인화 및 데이터 추적에 적합한 강력한 도구입니다. 기본값을 입력하십시오. |
| ![—](assets/image2015-7-9-10-3a41-3a21.png) | [!UICONTROL Undo] | 죄송합니다. 한 단계 뒤로 돌아가서 다시 시도해 보겠습니다. |
| ![—](assets/image2015-7-9-10-3a42-3a13.png) | [!UICONTROL Redo] | 정말 이대로 괜찮다면 다시 원래대로 돌아가세요. |
| ![—](assets/image2015-7-9-10-3a43-3a29.png) | [!UICONTROL Table] | 이것처럼 나만의 것을 만들어라. 드롭다운 메뉴를 사용하여 구성할 수 있습니다. |
| ![—](assets/image2015-7-9-10-3a45-3a1.png) | [!UICONTROL Insert Anchor] | 닻을 내려! |
| ![—](assets/image2015-7-9-10-3a45-3a48.png) | [!UICONTROL Horizontal Line] | 많은 사용 - 섹션 나누기에 적합합니다. |
| ![—](assets/image2015-10-6-12-3a12-3a17.png) | [!UICONTROL Edit HTML] | 코드를 수정할 수 있도록 HTML Source 편집기 팝업을 표시합니다. |
| ![—](assets/image2015-7-9-10-3a47-3a36.png) | [!UICONTROL Subscript] | O`<sub>2</sub>`과(와) 같이 내림이 적은 글자입니다. |
| ![—](assets/image2015-7-9-10-3a48-3a35.png) | [!UICONTROL Superscript] | 넌 힘이 있어! (2`<sup>6</sup>`). |
| ![—](assets/image2015-7-9-10-3a49-3a31.png) | [!UICONTROL Strikethrough] | `<s>Put a line through text, like this</s>`. |
| ![—](assets/image2015-7-9-10-3a50-3a11.png) | [!UICONTROL Special Character] | 유로화에 대해 얘기하고 싶어요? 수학? 243개 중 하나를 선택할 수 있습니다. |
| ![—](assets/image2015-7-9-10-3a52-3a26.png) | [!UICONTROL Find and Replace] | 직접 각 인스턴스를 찾는 것보다 훨씬 빠르게 항목을 검색하고 변경할 수 있습니다. |
| ![—](assets/image2015-7-9-10-3a53-3a37.png) | [!UICONTROL Clear Formatting] | 표준으로 되돌립니다. |
| ![—](assets/image2015-7-9-10-3a55-3a2.png) | [!UICONTROL Cancel] | 단추를 눌러 &quot;신경쓰지 마세요.&quot; 라고 말하세요. |
| ![—](assets/image2015-7-9-10-3a56-3a2.png) | [!UICONTROL Save] | 단추를 눌러 &quot;예, 좋습니다.&quot;라고 말하세요. |

>[!TIP]
>
>별도의 화면에서 HTML 및 텍스트를 편집합니다. **[!UICONTROL Copy from HTML]** 탭에서 **[!UICONTROL Text]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭하여 텍스트가 HTML과 일치하도록 합니다.

>[!NOTE]
>
>드롭다운에서 글꼴에만 국한되지 않습니다. HTML 코드에 액세스하여 나열되지 않은 코드를 사용할 수 있습니다. 모든 웹 글꼴은 Marketo에서 지원되지만 웹 글꼴은 모든 이메일 클라이언트에서 보편적으로 작동하지 않습니다.

## 랜딩 페이지 {#landing-pages}

루트 블록 요소 설정은 콘텐츠를 래핑하는 태그를 정의합니다. 기본적으로 랜딩 페이지 루트 블록 요소는 `<div>`개의 태그를 사용합니다. 아래 단계에 따라 변경할 수 있습니다.

>[!TIP]
>
>루트 블록 요소를 선택하는 옵션이 있지만 항상 최상의 사용자 경험을 위해 기본 설정을 사용하는 것이 좋습니다.

1. **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/one.png)

1. **[!UICONTROL Email]**&#x200B;을(를) 클릭합니다.

   ![](assets/two.png)

1. **[!UICONTROL Edit Text Editor Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/three.png)

1. **[!UICONTROL Landing Page Editor]** 드롭다운에서 `<p>` 또는 [!UICONTROL None]을(를) 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다. 이 예제에서는 `<p>`을(를) 사용합니다.

   ![](assets/five.png)

   다 됐습니다!

---
unique-page-id: 11371040
description: 이메일 템플릿 구문 - Marketo 문서 - 제품 설명서
title: 이메일 템플릿 구문
exl-id: 84d6c0a8-1108-4b7e-8b4f-ac0682c6bdbb
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '2423'
ht-degree: 0%

---

# 이메일 템플릿 구문 {#email-template-syntax}

Marketo의 새로운 이메일 2.0 경험에서 이메일 템플릿은 요소, 변수, 모듈 또는 컨테이너의 모든 조합으로 구성됩니다. 각각 Marketo 관련 구문을 HTML에 추가하여 정의됩니다. 이전(v1.0) 이메일 템플릿은 이메일 편집기 2.0에서 지원되지만, 새 편집기의 모든 기능을 포함하지는 않습니다.

Marketo 이메일 구문은 템플릿과 개별 이메일에서만 작동합니다. **아님** 코드 조각 또는 리치 텍스트 토큰에 임베드된 경우 작동합니다.

>[!NOTE]
>
>Marketo 지원이 CSS/HTML을 지원하도록 설정되지 않았습니다. CSS/HTML에 익숙하지 않은 경우 개발자에게 문의하십시오.

>[!CAUTION]
>
>Marketo 구문이 포함된 클래스 값(예: mktoModule, mktoContainer, mktoText)은 대/소문자를 구분합니다. 사용자 지정 속성 이름(즉, mktoimgwidth, mktoname)은 사용할 수 없습니다.

## 요소 {#elements}

요소는 이메일 템플릿에서 편집 가능한 것으로 정의하는 컨텐츠 영역입니다. 요소의 편집 환경은 해당 유형에 고유하며 간단한 콘텐츠 작업 방법을 제공합니다. 이메일 템플릿에 포함할 수 있는 요소는 다음과 같습니다.

* 리치 텍스트
* 이미지
* 코드 조각
* 비디오

## 리치 텍스트 {#rich-text}

영역을 리치 텍스트로 정의하면 사용자가 해당 콘텐츠를 편집할 수 있습니다 [Marketo의 리치 텍스트 편집기 사용](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). 이메일 템플릿 내에 리치 텍스트 요소를 정의하는 방법에는 mktEditable과 mktoText의 두 가지가 있습니다. 리치 텍스트 요소는 항상 이메일 편집기 내에서 스니펫으로 변환될 수 있습니다.

### 옵션 1 - mktEditable {#option-mkteditable}

이메일 편집기 2.0은 이전 버전과 호환되므로, 일부 이전 이메일 템플릿은 모든 HTML 요소에 class=&quot;mktEditable&quot;을 추가하여 리치 텍스트 요소를 지정할 수 있습니다. 여전히 지원되며, 요소의 ID는 이메일 편집기 내에서 표시 이름으로 사용될 것입니다.

필수 속성

* **클래스**: &quot;mktEditable&quot;.
* **id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.

선택적 속성

* **mktoName** : 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본 값

class=&quot;mktEditable&quot;인 HTML 요소(제공된 경우) 내의 콘텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

### 옵션 2 - mktoText {#option-mktotext}

class=&quot;mktoText&quot; 구문을 사용하여 리치 텍스트 요소를 지정하는 것이 좋습니다. 이렇게 하면 항상 요소에 적절한 표시 이름이 있습니다.

필수 속성

* **클래스**: &quot;mktoText&quot;
* **id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName** : 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본 값

class=&quot;mktoText&quot; 가 있는 HTML 요소(제공된 경우) 내의 콘텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

## 이미지 {#images}

편집 가능한 이미지 요소를 정의하는 두 가지 옵션이 있습니다. 다음 중 하나를 사용할 수 있습니다. `<div>`: 컨테이너를 `<img>` 또는에 삽입되거나 `<img>` 태그에 가깝게 배치하십시오. 최종 사용자가 이미지 URL(DOM이 아님)을 반환하는 이미지를 단순히 선택하려는 경우 아래 섹션의 &quot;이미지 변수&quot;를 참조하십시오. 다음 두 옵션은 HTML을 삽입합니다 `<img>` 요소를 생성하지 않습니다.

### 옵션 1 - 사용 `<div>` {#option-use-a-div}

필수 속성

* **클래스:** &quot;mktoImg&quot;.
* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName :** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoImgClass:** 문자열. 여기에 있는 값이 의 클래스 특성에 추가됩니다. `<img>` div 내의 요소입니다.
* **mktoImgSrc:** 이 div 내에 배치된 이미지의 기본값으로 사용됩니다. 생략된 경우 자리 표시자가 사용됩니다.
* **mktoImgLink:** 다음을 나타냅니다. `<img>` 은(는) 로 둘러싸여야 합니다. `<a>` 이 대상 URL을 사용하여 태그를 지정합니다. 사용자는 이메일 편집기에서 이를 변경할 수 있습니다.
* **mktoImgLinkTarget:** 다음을 나타냅니다. `<a>` mktoImgLink 속성의 태그는 이 대상을 사용해야 합니다. mktoImgLink도 사용되지 않으면 효과가 없습니다.
* **mktoImgWidth:** 둘러싸인 영역의 너비로 사용됩니다. `<img>`.
* **mktoImgHeight:** 둘러싸인 영역의 높이로 사용됩니다. `<img>`.
* **mktoLockImgSize:** 의 잠금을 해제하는 데 사용됨 `<img>` 최종 사용자가 수정할 수 있도록 요소의 height 및 width 속성(생략하면 기본값 true).
* **mktoLockImgStyle:** 을 잠그는 데 사용됩니다. `<img>` 요소의 스타일 속성(기본값은 false임).

기본값(선택 사항)

**`<img>`**: (으)로 사용 `<img>` 이미지가 배치될 요소입니다. 이미지에 인라인 스타일을 추가하려는 경우에 유용합니다. 주변부를 포함해야 합니다. `<a> </a>` 따라서 사용자가 링크를 추가해도 스타일이 제거되지 않습니다.

예:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div></pre>`

### 옵션 2 - \ 사용&lt;img> {#option-use-an-img}

>[!NOTE]
>
>이 옵션은 최종 사용자가 이미지에 링크를 추가하는 것을 허용하지 않습니다. 이것이 템플릿에 중요한 경우 옵션 1을 사용합니다.

필수 속성

* **클래스:** &quot;mktoImg&quot;.
* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.  기본값(선택 사항)
* **src:** 이미지의 기본값으로 사용됩니다. 생략된 경우 자리 표시자가 사용됩니다.
* **mktoLockImgSize:** 의 잠금을 해제하는 데 사용됨 `<img>` 최종 사용자가 수정할 수 있도록 요소의 height 및 width 속성(생략하면 기본값 true).
* **mktoLockImgStyle:** 을 잠그는 데 사용됩니다. `<img>` 요소의 스타일 속성(기본값은 false임).

예:
`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

## 코드 조각 {#snippets}

영역을 스니펫으로 정의하는 경우 최종 사용자는 승인할 항목을 선택할 수 있습니다 [코드 조각](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)이 지역에 삽입하려고 합니다. 이메일 편집기 내에서 리치 텍스트 요소를 스니펫으로 변환할 수 있지만, 영역을 특별히 스니펫으로 정의할 때에는 리치 텍스트로 변환할 수 없습니다. 를 사용하여 코드 조각 영역을 지정할 수 있습니다. `<div>` with class=&quot;mktoSnippet&quot;

필수 속성

* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본값(선택 사항)

**mktoDefaultSnippetId**: 기본적으로 표시되어야 하는 Marketo 코드 조각의 숫자 ID입니다(해당 ID를 가진 코드 조각이 해당 작업 공간에 존재하고 승인된 경우에만 작동됨).

예:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div></pre>`

## 비디오 {#video}

영역을 비디오로 정의하는 경우 최종 사용자는 이메일 내부에 썸네일 이미지(&#39;재생&#39; 버튼 포함)로 표시될 YouTube 또는 Vimeo URL을 삽입할 수 있습니다. 다음을 사용하여 비디오 영역을 지정할 수 있습니다. `<div>` class=&quot;mktoVideo&quot; 포함

필수 속성

* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoImgClass:** 문자열. 여기에 있는 값이 비디오 썸네일의 클래스 속성에 추가됩니다. `<img>` div 내부.

예:

`<pre data-theme="Confluence"><div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div></pre>`

## 변수 {#variables}

변수는 토큰과 같습니다. 먼저 다음 내에서 정의합니다. `<head>` 을 사용하는 이메일 템플릿의 섹션 `<meta>` 그런 다음 템플릿 전체에서 원하는 만큼 태그를 사용합니다. 템플릿에 정의되어 있으므로 최종 사용자는 규칙에 따라 값을 수정할 수 있습니다. 범위에서 변수를 로컬 또는 글로벌로 정의할 수 있습니다. &quot;모듈&quot;(아래 참조) 내에서 변수를 사용하고 최종 사용자가 해당 모듈을 복제하는 경우 로컬 변수에는 독립 값이 적용되고, 글로벌 변수는 두 모듈 모두에 적용됩니다.

## 문자열 {#string}

변수를 문자열로 지정하면 최종 사용자가 이메일 편집기의 텍스트 상자 내에 텍스트를 입력할 수 있습니다. 다음을 사용하여 String 변수를 지정합니다 `<meta>` class=&quot;mktoString&quot; 포함

필수 속성

* **id:** 이메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **allowHTML:** 부울. 변수 값이 HTML 이스케이프되는지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.
* **기본값**: 문자열의 기본값 생략하면 비어 있습니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me"></pre>`

사용 예:

`<pre data-theme="Confluence">${textHeader}</pre>`

## 목록 {#list}

변수를 목록으로 지정하면 이메일 편집기에서 정의한 값 세트에서 최종 사용자가 선택할 수 있습니다. 다음을 사용하여 목록 변수를 지정합니다. `<meta>` class=&quot;mktoList&quot; 사용

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.
* **값:** 쉼표로 구분된 값 목록입니다. 하나 이상의 문자열이 있어야 합니다.

선택적 속성

* **기본값:** 선택 드롭다운의 기본값. 생략하면 &quot;values&quot; 속성의 첫 번째 값이 사용됩니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman"></pre>`

사용 예:

`<pre data-theme="Confluence">${textFontFamily}</pre>`

## 숫자 {#number}

변수를 숫자로 지정하면 최종 사용자가 이메일 편집기에 숫자를 입력할 수 있습니다. 다음을 사용하여 Number 변수를 지정합니다 `<meta>` class=&quot;mktoNumber&quot; 포함

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.
* **기본값:** 변수의 기본 숫자 값입니다.

선택적 속성

* **분:** 최소값이 수락되었습니다.
* **최대:** 허용되는 최대값입니다.
* **단위:** 숫자 값에 추가할 단위(예: px, pt, em 등) 를 이메일 편집기와 결과 코드에 표시할 수 있습니다.
* **단계:** 숫자 변수가 증가/감소해야 하는 단위 수(0.1, 1, 10 등)입니다. 생략하면 기본값이 1로 설정됩니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> </pre>`

사용 예:

`<pre data-theme="Confluence">${textFontSize}</pre>`

## 색상 {#color}

변수를 색상으로 지정하면 최종 사용자가 16진수 색상 값을 입력하거나 이메일 편집기 내의 색상 선택기에서 색상을 선택할 수 있습니다. 다음을 사용하여 Color 변수를 지정합니다 `<meta>` class=&quot;mktoColor&quot; 사용

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본값:** 색상에 대한 기본값. 6자리 16진수 색상 코드. 예: #ffffff.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF"></pre>`

사용 예:

`<pre data-theme="Confluence">${textColor}</pre>`

## 부울 {#boolean}

변수를 부울로 지정하면 최종 사용자가 이메일 편집기 내에서 옵션을 켜거나 끌 수 있습니다. 를 사용하여 부울 변수를 지정합니다 `<meta>` class=&quot;mktoBoolean&quot; 사용

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본값:** 전환 스위치의 기본 상태를 결정하는 부울 값. 생략하면 False입니다.
* **false_value:** 토글이 꺼짐 위치에 있을 때 삽입할 값입니다. 생략하면 False입니다.
* **true_value:** toggle이 ON 위치에 있을 때 삽입할 값입니다. 생략하면 True입니다.
* **false_value_name:** 꺼짐 위치에 있을 때 토글에 표시되는 UI. 생략하면 False입니다.
* **true_value_name:** 켜짐 위치에 있을 때 전환에 표시되는 UI. 생략하면 True입니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES"></pre>`

사용 예:

`<pre data-theme="Confluence">${showFooter}</pre>`

## HTML 블록 {#html-block}

변수를 HTML 블록으로 지정하면 최종 사용자가 이메일 편집기 내에서 축어 HTML을 입력할 수 있습니다. 다음을 사용하여 HTML 블록 변수를 지정합니다 `<meta>` class=&quot;mktoHTML&quot; 포함

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본값:** 블록의 기본 컨텐츠 역할을 하는 인코딩된 HTML 값입니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel"></pre>`

사용 예:

`<pre data-theme="Confluence">${trackingPixel}</pre>`

## 이미지 변수 {#image-variable}

변수를 이미지로 지정하면 최종 사용자가 이메일 편집기 내의 이미지 선택기에서 이미지를 선택할 수 있습니다. 선택한 이미지 URL은 변수의 값이 됩니다. 다음을 사용하여 이미지 변수를 지정합니다 `<meta>` class=&quot;mktoImg&quot; 포함

필수 속성

* **id**: 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본값:** 요소의 기본 이미지 URL입니다.
* **mktoModuleScope**: 부울입니다. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="https://www.company.com/image.jpg"></pre>`

사용 예:

`<pre data-theme="Confluence">${heroBackgroundImage}</pre>`

## 모듈 {#modules}

모듈은 템플릿 수준에서 정의된 템플릿화된 섹션으로, 최종 사용자가 전자 메일에 삽입할 수 있도록 표시됩니다. 이러한 모듈을 미리 빌드했으므로 해당 모듈이 나머지 이메일 콘텐츠와 (완전히 응답하는 방식으로) 정상적으로 상호 작용하는지 확인할 수 있습니다. 컨테이너에는 모듈만 넣을 수 있습니다.

>[!IMPORTANT]
>
>정의된 모듈 구성 요소가 포함된 이메일 템플릿에서 이메일을 생성하면 템플릿의 모듈에 대한 모든 변경 사항이 수행됩니다 **아님** 해당 이메일에 푸시됩니다.

**컨테이너 형식 `<table>`, `<tbody>`, `<thead>`, 또는 `<tfoot>`:**

을 사용하여 지정됨 `<tr>` class=&quot;mktoModule&quot; 포함

**컨테이너 형식 `<td>`:**

을 사용하여 지정됨 `<table>` class=&quot;mktoModule&quot; 포함

필수 속성

* **id**: 이메일 템플릿 내에서 모듈을 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoActive:** 이 모듈이 이메일 편집기 내의 모듈 목록에 표시되는지 여부를 결정합니다. 기본값은 true입니다. false인 경우 최종 사용자가 모듈을 이메일에 추가할 수 없습니다.
* **mktoAddByDefault:** 이 모듈을 만들 때 이 템플릿을 사용하는 새 전자 메일의 캔버스에 포함할지 여부를 결정합니다. 기본값은 true입니다(mktoActive가 false인 경우 이 값이 무시됨).

>[!NOTE]
>
>Marketo 구문이 포함된 클래스 값(예: mktoModule, mktoContainer, mktoText)은 대/소문자를 구분합니다. 사용자 지정 속성 이름(즉, mktoimgwidth, mktoname)은 사용할 수 없습니다.

## 컨테이너 {#containers}

컨테이너에는 모듈이 보관되어 있고 모듈을 배치할 수 있는 위치를 정의합니다. 최종 사용자가 모듈 순서를 다시 지정하고 이메일에 모듈을 삽입하면 컨테이너가 이동할 위치를 제어합니다.

**다음 중 하나를 사용하여 지정됨 `<table>`, `<tbody>`, `<thead>`, `<tfoot>` 또는 `<td>` class=&quot;mktoContainer&quot; 포함**

필수 속성

**id**: 이메일 템플릿 내에서 모듈을 참조하는 방법

>[!CAUTION]
>
>컨테이너에는 모듈만 포함될 수 있습니다. 다른 항목이 있는 경우 컨테이너가 유효하지 않은 것으로 간주됩니다. 템플릿당 하나의 컨테이너만 허용됩니다.

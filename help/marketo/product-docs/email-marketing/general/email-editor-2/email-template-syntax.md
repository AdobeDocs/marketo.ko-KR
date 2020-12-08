---
unique-page-id: 11371040
description: 이메일 템플릿 구문 - 마케팅 문서 - 제품 설명서
title: 이메일 템플릿 구문
translation-type: tm+mt
source-git-commit: f27e2bac90570f9f795dc6bdd5fcf208c446be14
workflow-type: tm+mt
source-wordcount: '2397'
ht-degree: 0%

---


# 이메일 템플릿 구문 {#email-template-syntax}

Marketing의 새로운 이메일 2.0 경험에서 이메일 템플릿은 요소, 변수, 모듈 또는 컨테이너의 조합으로 구성됩니다. 각 구문은 HTML에 마케팅 관련 구문을 추가하여 정의됩니다. 이전(v1.0) 이메일 템플릿은 이메일 편집기 2.0에서 지원됩니다.그러나 새로운 편집기의 모든 기능은 포함되지 않습니다.

Marketing to 이메일 구문은 템플릿과 개별 이메일만 작동합니다.코드 조각 또는 리치 텍스트 토큰에 포함된 경우에는 작동하지 **않습니다** .

>[!NOTE]
>
>CSS/HTML을 지원하도록 Marketing Support가 설정되지 않았습니다. CSS/HTML에 익숙하지 않은 경우 개발자에게 문의하십시오.

>[!CAUTION]
>
>Marketing 구문(예: mktoModule, mktoContainer, mktoText)이 포함된 클래스 값은 대/소문자를 구분합니다. 사용자 지정 속성 이름(예: mktoimgwidth, mktoname)은 그렇지 않습니다.

## 요소 {#elements}

요소는 이메일 템플릿에서 편집할 수 있다고 정의하는 컨텐츠 영역입니다. 요소의 편집 경험은 해당 유형에만 고유하며 컨텐츠로 작업하는 간단한 방법을 제공합니다. 이메일 템플릿에 포함할 수 있는 요소는 다음과 같습니다.

* 리치 텍스트
* 이미지
* 코드 조각
* 비디오

## 리치 텍스트 {#rich-text}

영역을 리치 텍스트로 정의하면 사용자는 Marketing의 리치 텍스트 편집기를 [사용하여 해당 컨텐츠를 편집할 수 있습니다](../../../../product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). 두 가지 방법으로 이메일 템플릿 내에서 리치 텍스트 요소를 정의할 수 있습니다.mktEditable 및 mktoText. 항상 이메일 편집기 내에서 리치 텍스트 요소를 코드 조각으로 변환할 수 있습니다.

### 옵션 1 - mktEditable {#option-mkteditable}

이메일 편집기 2.0은 이전 버전과 호환되므로 일부 오래된 이메일 템플릿은 모든 HTML 요소에 class=&quot;mktEditable&quot;을 추가하여 리치 텍스트 요소를 지정할 수 있습니다. 이 기능은 여전히 지원되며, 요소의 ID는 이메일 편집기 내에서 표시 이름으로 사용될 것입니다.

필수 속성

* **class**:&quot;mktEditable&quot;.
* **id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.

선택적 속성

* **mktoName** :문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

기본값

class=&quot;mktEditable&quot;이 있는 HTML 요소 내의 컨텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

### 옵션 2 - mktoText {#option-mktotext}

class=&quot;mktoText&quot; 구문을 사용하여 리치 텍스트 요소를 지정하는 것이 좋습니다. 이렇게 하면 요소의 표시 이름이 항상 적절하게 표시됩니다.

필수 속성

* **class**:&quot;mktoText&quot;
* **id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName** :문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

기본값

class=&quot;mktoText&quot;가 포함된 HTML 요소 내의 컨텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>`

## 이미지 {#images}

편집 가능한 이미지 요소를 정의하는 두 가지 옵션이 있습니다. 삽입될 컨테이너 `<div>`를 지정하는 a 또는 태그 `<img>` 를 사용할 수 `<img>` 있습니다. 최종 사용자가 이미지 URL(DOM과 반대)을 반환하는 이미지를 선택하기만 하면 아래 섹션에 있는 &quot;이미지 변수&quot;를 참조하십시오. 다음 두 옵션은 HTML `<img>` 요소를 삽입합니다.

### 옵션 1 - \&lt;div\> 사용 {#option-use-a-div}

필수 속성

* **class:** &quot;mktoImg&quot;.
* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **mktoImgClass:** 문자열. 이 값은 div 내의 요소의 클래스 특성에 `<img>` 추가됩니다.
* **mktoImgSrc:** 이 div 내에 배치된 이미지의 기본값으로 사용됩니다. 이 값을 생략하면 자리 표시자가 사용됩니다.
* **mktoImgLink:** 대상 URL이 있는 `<img>` `<a>` 태그로 둘러싸야 함을 나타냅니다. 사용자는 이메일 편집기에서 변경할 수 있습니다.
* **mktoImgLinkTarget:** mktoImgLink 특성의 `<a>` 태그가 이 대상을 사용해야 함을 나타냅니다. mktoImgLink도 사용되지 않는 경우 아무런 영향이 없습니다.
* **mktoImgWidth:** 둘러싸인 너비로 사용됩니다 `<img>`.
* **mktoImgHeight:** 동봉된 부분의 높이 `<img>`로 사용됩니다.
* **mktoLockImgSize:** 최종 사용자가 수정할 수 있도록 `<img>` 요소의 높이와 폭 속성을 잠금 해제하는 데 사용됩니다(생략하면 기본값이 true).
* **mktoLockImgStyle:** 요소의 `<img>` 스타일 속성을 잠그는 데 사용됩니다(기본값은 false).

기본값(선택 사항)

**`<img>`**:이미지를 배치할 `<img>` 요소로 사용됩니다. 이미지에 인라인 스타일을 추가하려는 경우 유용합니다. 주변 `<a> </a>` 태그를 포함해야 하므로 사용자가 링크를 추가해도 스타일이 제거되지 않습니다.

예:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="http://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div></pre>`

### 옵션 2 - \&lt;img\> 사용 {#option-use-an-img}

>[!NOTE]
>
>이 옵션을 사용하면 최종 사용자가 이미지에 링크를 추가할 수 없습니다. 템플릿에 중요한 경우 옵션 1을 사용합니다.

필수 속성

* **class:** &quot;mktoImg&quot;.
* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.  기본값(선택 사항)
* **src:** 이미지의 기본값으로 사용됩니다. 이 값을 생략하면 자리 표시자가 사용됩니다.
* **mktoLockImgSize:** 최종 사용자가 수정할 수 있도록 `<img>` 요소의 높이와 폭 속성을 잠금 해제하는 데 사용됩니다(생략하면 기본값이 true).
* **mktoLockImgStyle:** 요소의 `<img>` 스타일 속성을 잠그는 데 사용됩니다(기본값은 false).

예:
`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

## 코드 조각 {#snippets}

영역을 코드 조각으로 정의하는 경우 최종 사용자는 이 영역에 삽입할 승인된 [](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)스나입페트를 선택할 수 있습니다. 이메일 편집기 내에서 리치 텍스트 요소를 코드 조각으로 변환할 수는 있지만 특정 영역을 코드 조각으로 정의하면 리치 텍스트로 변환할 수 없습니다. class=&quot;mktoSnippet&quot;인 코드 조각 영역을 `<div>` 지정할 수 있습니다.

필수 속성

* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

기본값(선택 사항)

**mktoDefaultSnippetId**:기본적으로 표시되어야 하는 마케팅 코드 조각의 숫자 ID입니다(해당 ID가 있고 해당 작업 공간에서 승인된 코드 조각에만 작동합니다).

예:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div></pre>`

## 비디오 {#video}

영역을 비디오로 정의하면 최종 사용자는 이메일 내에 &#39;재생&#39; 단추가 있는 축소판 이미지로 표시할 YouTube 또는 Vimeo URL을 삽입할 수 있습니다. class=&quot;mktoVideo&quot;가 있는 비디오 영역 `<div>` 을 지정할 수 있습니다.

필수 속성

* **id:** ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **mktoImgClass:** 문자열. 이 값은 div 내에 있는 비디오 축소판의 클래스 속성 `<img>` 에 추가됩니다.

예:

`<pre data-theme="Confluence"><div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div></pre>`

## 변수 {#variables}

변수는 토큰과 같습니다. 먼저 태그를 사용하여 이메일 템플릿 `<head>` 섹션 내에서 `<meta>` 태그를 정의한 다음 템플릿 전체에서 원하는 만큼 사용합니다. 템플릿에 정의되어 있으므로 최종 사용자는 규칙에 따라 값을 수정할 수 있습니다. 변수를 범위에서 로컬 또는 글로벌 변수로 정의할 수 있습니다. &quot;모듈&quot;(아래 참조) 내에서 변수를 사용하고 최종 사용자가 해당 모듈을 중복하면 로컬 변수는 독립적인 값을 가지며 전역 변수는 두 모듈 모두에 적용됩니다.

## 문자열 {#string}

변수를 문자열로 지정하면 최종 사용자가 이메일 편집기의 텍스트 상자 내에 텍스트를 입력할 수 있습니다. class=&quot;mktoString&quot; `<meta>` 과 함께 String 변수를 지정합니다.

필수 속성

* **id:** 이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **allowHTML:** 부울입니다. 변수의 값이 HTML 이스케이프인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.
* **기본값**:문자열의 기본값입니다. 생략하면 비워 둡니다.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me"></pre>`

사용 예:

`<pre data-theme="Confluence">${textHeader}</pre>`

## 목록 {#list}

변수를 목록으로 지정하면 이메일 편집기에서 정의한 값 세트에서 최종 사용자가 선택할 수 있습니다. class=&quot;mktoList&quot;와 함께 List 변수 `<meta>` 를 지정합니다

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.
* **값:** 쉼표로 구분된 값 목록입니다. 하나 이상의 문자열이 있어야 합니다.

선택적 속성

* **default:** 선택 드롭다운의 기본값. 생략하면 &quot;values&quot; 속성의 첫 번째 값이 사용됩니다.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman"></pre>`

사용 예:

`<pre data-theme="Confluence">${textFontFamily}</pre>`

## 숫자 {#number}

변수를 숫자로 지정하는 경우 최종 사용자는 이메일 편집기에 숫자를 입력할 수 있습니다. class=&quot;mktoNumber&quot; `<meta>` 와 함께 Number 변수를 지정합니다.

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.
* **default:** 변수의 기본 숫자 값입니다.

선택적 속성

* **분:** 최소 허용 값.
* **max:** 허용된 최대값.
* **units:** 숫자 값에 추가할 단위(예:px, pt, em 등) 로 표시되던 문제를 수정했습니다.
* **step:** 숫자 변수가 (0.1, 1, 10 등)까지 증가/감소해야 하는 단위 수입니다. 생략하면 기본값은 1입니다.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> </pre>`

사용 예:

`<pre data-theme="Confluence">${textFontSize}</pre>`

## 색상 {#color}

변수를 색상으로 지정하는 경우 최종 사용자는 16진수 색상 값을 입력하거나 이메일 편집기 내의 색상 피커에서 색상을 선택할 수 있습니다. class=&quot;mktoColor&quot;와 함께 Color 변수 `<meta>` 를 지정합니다

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **default:** 색상의 기본값. 6자리 16진수 색상 코드. 예:#ffff.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF"></pre>`

사용 예:

`<pre data-theme="Confluence">${textColor}</pre>`

## 부울 {#boolean}

변수를 부울로 지정하는 경우 최종 사용자는 이메일 편집기 내에서 옵션을 켜거나 끌 수 있습니다. class=&quot;mktoBoolean&quot; `<meta>` 과 함께 부울 변수를 지정합니다

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **default:** 전환 스위치의 기본 상태를 결정하는 부울 값입니다. 생략하면 false입니다.
* **false_value:** 전환 시 삽입되는 값입니다. 생략하면 false입니다.
* **true_value:** 전환 시 삽입되는 값입니다. 생략하면 true입니다.
* **false_value_name:** OFF 위치에 있을 때 전환에 표시되는 UI. 생략하면 false입니다.
* **true_value_name:** 켜짐 위치 전환에서 표시되는 UI. 생략하면 true입니다.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES"></pre>`

사용 예:

`<pre data-theme="Confluence">${showFooter}</pre>`

## HTML 블록 {#html-block}

변수를 HTML 블록으로 지정하는 경우 최종 사용자는 이메일 편집기 내에서 축어 HTML을 입력할 수 있습니다. class=&quot;mktoHTML&quot;과 함께 `<meta>` HTML 블록 변수를 지정합니다.

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **default:** 블록의 기본 컨텐츠로 사용할 HTML 인코딩 값.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel"></pre>`

사용 예:

`<pre data-theme="Confluence">${trackingPixel}</pre>`

## 이미지 변수 {#image-variable}

변수를 이미지로 지정하는 경우 최종 사용자는 이메일 편집기 내의 이미지 선택기에서 이미지를 선택할 수 있습니다. 선택한 이미지 URL은 변수의 값이 됩니다. class=&quot;mktoImg&quot;와 함께 Image 변수 `<meta>` 를 지정합니다

필수 속성

* **id**:이메일 템플릿 내에서 변수를 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **default:** 요소의 기본 이미지 URL.
* **mktoModuleScope**:부울입니다. 모듈에서 변수를 사용할 때 변수가 로컬(true) 또는 전역(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<pre data-theme="Confluence"><meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="http://www.company.com/image.jpg"></pre>`

사용 예:

`<pre data-theme="Confluence">${heroBackgroundImage}</pre>`

## 모듈 {#modules}

모듈은 최종 사용자가 자신의 이메일에 삽입할 수 있도록 템플릿 수준에서 정의된 템플릿화된 섹션입니다. 이러한 모듈은 사전 구축되어 있으므로 나머지 이메일 컨텐츠와 완벽하게 상호 작용할 수 있습니다(완전히 응답형). 모듈만 컨테이너에 넣을 수 있습니다.

**유형, `<table>``<tbody>`, `<thead>`또는 `<tfoot>`컨테이너의 경우:**

class=&quot;mktoModule&quot; `<tr>` 을 사용하여 지정됨

**유형 컨테이너의 경우 `<td>`:**

class=&quot;mktoModule&quot; `<table>` 을 사용하여 지정됨

필수 속성

* **id**:이메일 템플릿 내에서 모듈을 참조하는 방법
* **mktoName**:문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택적 속성

* **mktoActive:** 이메일 편집기 내의 모듈 목록에 이 모듈이 나타나는지 여부를 결정합니다. 기본값은 true입니다. false이면 최종 사용자가 전자 메일에 모듈을 추가할 수 없습니다.
* **mktoAddByDefault:** 이 모듈이 작성 시 이 템플릿을 사용하는 새 이메일의 캔버스에 있는지 여부를 결정합니다. 기본값은 true입니다(mktoActive가 false이면 이 값은 무시됩니다).

>[!NOTE]
>
>**미리 알림**
>
>Marketing 구문(예: mktoModule, mktoContainer, mktoText)이 포함된 클래스 값은 대/소문자를 구분합니다. 사용자 지정 속성 이름(예: mktoimgwidth, mktoname)은 그렇지 않습니다.

## 컨테이너 {#containers}

컨테이너는 모듈을 보유하고 배치할 위치를 정의합니다. 최종 사용자가 이메일에 모듈을 다시 정렬하고 삽입하는 경우 컨테이너는 사용자가 이동할 위치를 제어합니다.

**둘 중 하나 `<table>`, `<tbody>``<thead>`, `<tfoot>` 또는 class=&quot;mktoContainer&quot;를 사용하여 `<td>` 지정합니다.**

필수 속성

**id**:이메일 템플릿 내에서 모듈을 참조하는 방법

>[!CAUTION]
>
>컨테이너는 모듈만 포함할 수 있습니다. 다른 항목이 있는 경우 컨테이너는 잘못된 것으로 간주됩니다. 템플릿당 하나의 컨테이너만 허용됩니다.

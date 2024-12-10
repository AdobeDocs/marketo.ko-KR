---
unique-page-id: 11371040
description: 이메일 템플릿 구문 - Marketo 문서 - 제품 설명서
title: 이메일 템플릿 구문
exl-id: 84d6c0a8-1108-4b7e-8b4f-ac0682c6bdbb
feature: Email Editor
source-git-commit: a9f880bd32d533613020d0472c0e1bee07ab388c
workflow-type: tm+mt
source-wordcount: '2449'
ht-degree: 0%

---

# 이메일 템플릿 구문 {#email-template-syntax}

Marketo의 새로운 이메일 2.0 경험에서 이메일 템플릿은 요소, 변수, 모듈 또는 컨테이너의 모든 조합으로 구성됩니다. 각각 Marketo 관련 구문을 HTML에 추가하여 정의됩니다. 이전(v1.0) 이메일 템플릿은 이메일 편집기 2.0에서 지원되지만, 새 편집기의 모든 기능을 포함하지는 않습니다.

Marketo 이메일 구문은 템플릿과 개별 이메일에서만 작동합니다. 코드 조각 또는 리치 텍스트 토큰에 포함된 경우 **not**&#x200B;할 수 있습니다.

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
* 스니펫
* 비디오

## 리치 텍스트 {#rich-text}

영역을 리치 텍스트로 정의하면 사용자가 Marketo의 리치 텍스트 편집기를 사용하여 [콘텐츠를 편집할 수 있습니다](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). 이메일 템플릿 내에 리치 텍스트 요소를 정의하는 방법에는 mktEditable과 mktoText의 두 가지가 있습니다. 리치 텍스트 요소는 항상 이메일 편집기 내에서 스니펫으로 변환될 수 있습니다.

### 옵션 1 - mktEditable {#option-mkteditable}

이메일 편집기 2.0은 이전 버전과 호환되므로, 일부 이전 이메일 템플릿은 모든 HTML 요소에 class=&quot;mktEditable&quot;을 추가하여 리치 텍스트 요소를 지정할 수 있습니다. 여전히 지원되며, 요소의 ID는 이메일 편집기 내에서 표시 이름으로 사용될 것입니다.

필수 속성

* **클래스**: &quot;mktEditable&quot;.
* **id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.

선택적 속성

* **mktoName** : 문자열입니다. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본 값

class=&quot;mktEditable&quot;인 HTML 요소(제공된 경우) 내의 콘텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div>`

### 옵션 2 - mktoText {#option-mktotext}

class=&quot;mktoText&quot; 구문을 사용하여 리치 텍스트 요소를 지정하는 것이 좋습니다. 이렇게 하면 항상 요소에 적절한 표시 이름이 있습니다.

필수 속성

* **클래스**: &quot;mktoText&quot;
* **id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName** : 문자열입니다. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본 값

class=&quot;mktoText&quot; 가 있는 HTML 요소(제공된 경우) 내의 콘텐츠는 리치 텍스트 요소의 기본값으로 사용됩니다.

예:

`<div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div>`

## 이미지 {#images}

편집 가능한 이미지 요소를 정의하는 두 가지 옵션이 있습니다. `<img>`을(를) 삽입할 컨테이너를 지정하는 `<div>` 또는 `<img>` 태그를 사용할 수 있습니다. 최종 사용자가 이미지 URL(DOM이 아님)을 반환하는 이미지를 단순히 선택하려는 경우 아래 섹션의 &quot;이미지 변수&quot;를 참조하십시오. 다음 두 옵션은 HTML `<img>` 요소를 삽입합니다.

### 옵션 1 - `<div>` 사용 {#option-use-a-div}

필수 속성

* **클래스:** &quot;mktoImg&quot;.
* **id:** ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoImgClass:** 문자열. 여기에 있는 값이 div 내에 있는 `<img>` 요소의 클래스 특성에 추가됩니다.
* **mktoImgSrc:** 이 div 내에 배치된 이미지의 기본값으로 사용됩니다. 생략된 경우 자리 표시자가 사용됩니다.
* **mktoImgLink:** 이 대상 URL을 사용하는 `<a>` 태그로 `<img>`을(를) 둘러싸야 함을 나타냅니다. 사용자는 이메일 편집기에서 이를 변경할 수 있습니다.
* **mktoImgLinkTarget:** mktoImgLink 특성의 `<a>` 태그가 이 대상을 사용해야 함을 나타냅니다. mktoImgLink도 사용되지 않으면 효과가 없습니다.
* **mktoImgWidth:**&#x200B;이(가) 둘러싸인 `<img>`의 너비로 사용됩니다.
* **mktoImgHeight:**&#x200B;은(는) 둘러싸인 `<img>`의 높이로 사용됩니다.
* **mktoLockImgSize:** 최종 사용자가 수정할 수 있도록 `<img>` 요소의 높이 및 너비 속성을 잠금 해제하는 데 사용됩니다(생략된 경우 기본값은 true).
* **mktoLockImgStyle:** `<img>` 요소의 스타일 속성을 잠그는 데 사용됩니다(기본값은 false).

기본값(선택 사항)

**`<img>`**: 이미지를 배치할 `<img>` 요소로 사용합니다. 이미지에 인라인 스타일을 추가하려는 경우에 유용합니다. 주변 `<a> </a>` 태그를 포함해야 합니다. 따라서 사용자가 링크를 추가해도 스타일이 제거되지 않습니다.

예:

`<div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="https://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div>`

### 옵션 2 - \&lt;img\> 사용 {#option-use-an-img}

>[!NOTE]
>
>이 옵션은 최종 사용자가 이미지에 링크를 추가하는 것을 허용하지 않습니다. 이것이 템플릿에 중요한 경우 옵션 1을 사용합니다.

필수 속성

* **클래스:** &quot;mktoImg&quot;.
* **id:** ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.  기본값(선택 사항)
* **src:** 이미지의 기본값으로 사용됩니다. 생략된 경우 자리 표시자가 사용됩니다.
* **mktoLockImgSize:** 최종 사용자가 수정할 수 있도록 `<img>` 요소의 높이 및 너비 속성을 잠금 해제하는 데 사용됩니다(생략된 경우 기본값은 true).
* **mktoLockImgStyle:** `<img>` 요소의 스타일 속성을 잠그는 데 사용됩니다(기본값은 false).

예:
`<img class="mktoImg" id="exampleImg" mktoName="Example Image">`

## 스니펫 {#snippets}

영역을 코드 조각으로 정의하면 최종 사용자는 이 영역에 삽입할 승인된 [코드 조각](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)을 선택할 수 있습니다. 이메일 편집기 내에서 리치 텍스트 요소를 스니펫으로 변환할 수 있지만, 영역을 특별히 스니펫으로 정의할 때에는 리치 텍스트로 변환할 수 없습니다. class=&quot;mktoSnippet&quot;인 `<div>`을(를) 사용하여 코드 조각 영역을 지정할 수 있습니다.

필수 속성

* **id:** ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

기본값(선택 사항)

**mktoDefaultSnippetId**: 기본적으로 표시되어야 하는 Marketo 코드 조각의 숫자 ID입니다(해당 ID를 가진 코드 조각이 해당 작업 영역에 존재하고 승인된 경우에만 작동함).

예:

`<div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div>`

## 비디오 {#video}

영역을 비디오로 정의하는 경우 최종 사용자는 이메일 내부에 썸네일 이미지(&#39;재생&#39; 버튼 포함)로 표시될 YouTube 또는 Vimeo URL을 삽입할 수 있습니다. class=&quot;mktoVideo&quot;인 `<div>`을(를) 사용하여 비디오 영역을 지정할 수 있습니다.

필수 속성

* **id:** ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoImgClass:** 문자열. 여기에 있는 값이 div 내의 비디오 썸네일 `<img>`의 클래스 특성에 추가됩니다.

예:

`<div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div>`

## 변수 {#variables}

변수는 토큰과 같습니다. 먼저 `<meta>` 태그를 사용하여 전자 메일 템플릿의 `<head>` 섹션 내에 태그를 정의한 다음 템플릿 전체에서 원하는 만큼 사용합니다. 템플릿에 정의되어 있으므로 최종 사용자는 규칙에 따라 값을 수정할 수 있습니다. 범위에서 변수를 로컬 또는 글로벌로 정의할 수 있습니다. &quot;모듈&quot;(아래 참조) 내에서 변수를 사용하고 최종 사용자가 해당 모듈을 복제하는 경우 로컬 변수에는 독립 값이 적용되고, 글로벌 변수는 두 모듈 모두에 적용됩니다.

## 문자열 {#string}

변수를 문자열로 지정하면 최종 사용자가 이메일 편집기의 텍스트 상자 내에 텍스트를 입력할 수 있습니다. class=&quot;mktoString&quot;인 `<meta>`을(를) 사용하여 String 변수를 지정합니다.

필수 속성

* **id:** 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **allowHTML:** 부울입니다. 변수 값이 HTML 이스케이프되는지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.
* **기본값**: 문자열의 기본값 생략하면 비어 있습니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me">`

사용 예:

`${textHeader}`

## 목록 {#list}

변수를 목록으로 지정하면 이메일 편집기에서 정의한 값 세트에서 최종 사용자가 선택할 수 있습니다. class=&quot;mktoList&quot;인 `<meta>`을(를) 사용하여 목록 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName:** 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.
* **값:** 쉼표로 구분된 값 목록입니다. 하나 이상의 문자열이 있어야 합니다.

선택적 속성

* 선택 드롭다운의 **기본값:** 기본값 생략하면 &quot;values&quot; 속성의 첫 번째 값이 사용됩니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman">`

사용 예:

`${textFontFamily}`

## 숫자 {#number}

변수를 숫자로 지정하면 최종 사용자가 이메일 편집기에 숫자를 입력할 수 있습니다. 클래스=&quot;mktoNumber&quot;인 `<meta>`을(를) 사용하여 Number 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.
* **기본값:** 변수의 기본 숫자 값입니다.

선택적 속성

* **분:**&#x200B;분이 값을 수락했습니다.
* **max:** 허용되는 최대값입니다.
* **단위:** 단위(예: px, pt, em 등)는 이메일 편집기와 결과 코드에 표시될 때 숫자 값에 추가됩니다.
* **단계:** 숫자 변수가 증가/감소해야 하는 단위 수(0.1, 1, 10 등)입니다. 생략하면 기본값이 1로 설정됩니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> `

사용 예:

`${textFontSize}`

## 색상 {#color}

변수를 색상으로 지정하면 최종 사용자가 16진수 색상 값을 입력하거나 이메일 편집기 내의 색상 선택기에서 색상을 선택할 수 있습니다. class=&quot;mktoColor&quot;인 `<meta>`을(를) 사용하여 Color 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본:** 색상의 기본값입니다. 6자리 16진수 색상 코드. 예: #ffffff.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF">`

사용 예:

`${textColor}`

## 부울 {#boolean}

변수를 부울로 지정하면 최종 사용자가 이메일 편집기 내에서 옵션을 켜거나 끌 수 있습니다. class=&quot;mktoBoolean&quot;인 `<meta>`을(를) 사용하여 부울 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본:** 전환 스위치의 기본 상태를 결정하는 부울 값입니다. 생략하면 False입니다.
* 토글이 꺼짐 위치에 있을 때 삽입할 **false_value:** 값입니다. 생략하면 False입니다.
* 토글이 ON 위치에 있을 때 삽입할 **true_value:** 값입니다. 생략하면 True입니다.
* 꺼짐 위치에 있을 때 전환에 **false_value_name:** UI가 표시됩니다. 생략하면 False입니다.
* **true_value_name:** UI가 켜짐 위치에 있을 때 전환에 표시됩니다. 생략하면 True입니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES">`

사용 예:

`${showFooter}`

## HTML 블록 {#html-block}

변수를 HTML 블록으로 지정하면 최종 사용자가 이메일 편집기 내에서 축어 HTML을 입력할 수 있습니다. 클래스=&quot;mktoHTML&quot;과 함께 `<meta>`을(를) 사용하여 HTML 블록 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본값:** 블록의 기본 콘텐츠 역할을 하는 HTML 인코딩 값입니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel">`

사용 예:

`${trackingPixel}`

## 이미지 변수 {#image-variable}

변수를 이미지로 지정하면 최종 사용자가 이메일 편집기 내의 이미지 선택기에서 이미지를 선택할 수 있습니다. 선택한 이미지 URL은 변수의 값이 됩니다. class=&quot;mktoImg&quot;인 `<meta>`을(를) 사용하여 Image 변수를 지정합니다.

필수 속성

* **id**: 전자 메일 템플릿 내에서 변수를 참조하는 방법입니다.
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **기본:** 요소의 기본 이미지 URL입니다.
* **mktoModuleScope**: 부울. 모듈에서 사용할 때 변수가 로컬(true) 또는 글로벌(false)인지 여부를 제어합니다. 생략하면 기본값이 False로 설정됩니다.

선언 예:

`<meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="https://www.company.com/image.jpg">`

사용 예:

`${heroBackgroundImage}`

## 모듈 {#modules}

모듈은 템플릿 수준에서 정의된 템플릿화된 섹션으로, 최종 사용자가 전자 메일에 삽입할 수 있도록 표시됩니다. 이러한 모듈을 미리 빌드했으므로 해당 모듈이 나머지 이메일 콘텐츠와 (완전히 응답하는 방식으로) 정상적으로 상호 작용하는지 확인할 수 있습니다. 컨테이너에는 모듈만 넣을 수 있습니다.

>[!IMPORTANT]
>
>정의된 모듈 구성 요소가 포함된 전자 메일 템플릿에서 전자 메일이 생성되면 템플릿의 모듈에 대한 변경 사항이 해당 전자 메일에 **반영되지** 않습니다.

**`<table>`, `<tbody>`, `<thead>` 또는 `<tfoot>` 형식의 컨테이너:**

class=&quot;mktoModule&quot;인 `<tr>`을(를) 사용하여 지정됨

`<td>`:**형식의 컨테이너에 대한**

class=&quot;mktoModule&quot;인 `<table>`을(를) 사용하여 지정됨

필수 속성

* **id**: 전자 메일 템플릿 내에서 모듈을 참조하는 방법
* **mktoName**: 문자열. 이메일 편집기 2.0에 표시되는 표시 이름입니다. 가장 좋은 방법은 수사적 이름을 사용하는 것입니다.

선택적 속성

* **mktoActive:** 이 모듈이 전자 메일 편집기 내의 모듈 목록에 표시되는지 여부를 결정합니다. 기본값은 true입니다. false인 경우 최종 사용자가 모듈을 이메일에 추가할 수 없습니다.
* **mktoAddByDefault:** 이 모듈을 만들 때 이 템플릿을 사용하는 새 전자 메일의 캔버스에 포함할지 여부를 결정합니다. 기본값은 true입니다(mktoActive가 false인 경우 이 값이 무시됨).

>[!NOTE]
>
>Marketo 구문이 포함된 클래스 값(예: mktoModule, mktoContainer, mktoText)은 대/소문자를 구분합니다. 사용자 지정 속성 이름(즉, mktoimgwidth, mktoname)은 사용할 수 없습니다.

## 컨테이너 {#containers}

컨테이너에는 모듈이 보관되어 있고 모듈을 배치할 수 있는 위치를 정의합니다. 최종 사용자가 모듈 순서를 다시 지정하고 이메일에 모듈을 삽입하면 컨테이너가 이동할 위치를 제어합니다.

**클래스=&quot;mktoContainer&quot;**&#x200B;인 `<table>`, `<tbody>`, `<thead>`, `<tfoot>` 또는 `<td>`을(를) 사용하여 지정됨

필수 속성

**id**: 전자 메일 템플릿 내에서 모듈을 참조하는 방법

>[!CAUTION]
>
>컨테이너에는 모듈만 포함될 수 있습니다. 다른 항목이 있는 경우 컨테이너가 유효하지 않은 것으로 간주됩니다. 템플릿당 하나의 컨테이너만 허용됩니다.

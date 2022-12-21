---
unique-page-id: 7515401
description: 안내 랜딩 페이지 템플릿 만들기 - Marketo 문서 - 제품 설명서
title: 안내 랜딩 페이지 템플릿 만들기
exl-id: 7d097162-d862-4d09-9440-aba1628450c2
source-git-commit: 115b6e97978778a1d1e13478adf6fee625aa5257
workflow-type: tm+mt
source-wordcount: '1254'
ht-degree: 1%

---

# 안내 랜딩 페이지 템플릿 만들기 {#create-a-guided-landing-page-template}

안내식 랜딩 페이지 템플릿에는 특수 구문이 있습니다. 이 구문을 사용하여 템플릿에 빌드된 각 랜딩 페이지에서 사용자 지정할 수 있는 항목과 콘텐츠가 끝나는 위치를 지정합니다. 편집 가능으로 지정하는 지역 또는 변수만 &quot;안내&quot; 랜딩 페이지 편집기 내에서 사용자 지정할 수 있습니다.

>[!TIP]
>
>이름 지정 규칙을 잘 사용하면 마케팅 팀이 사용자를 사랑하게 됩니다.

페이지에서 편집 가능한 항목을 선언할 때는 두 가지가 있습니다.

* 개체를 &quot;요소&quot;로 선언합니다. 랜딩 페이지 작성자는 이미지, 텍스트 또는 Marketo 자산을 지정된 영역에 추가할 수 있습니다.
* 문자열을 &quot;변수&quot;로 선언합니다. 랜딩 페이지 작성자는 해당 변수를 true/false 레버에서 문자열, 색상 또는 부울 상태로 바꿀 수 있습니다.

## 편집 가능한 요소 {#editable-elements}

템플릿에 일반 DOM 요소를 추가한 다음 요소를 Marketo 특정 클래스 이름으로 장식하여 요소를 선언합니다.

## 텍스트 {#text}

영역을 리치 텍스트로 정의하는 경우 사용자가 해당 콘텐츠를 편집할 수 있습니다 [Marketo의 리치 텍스트 편집기 사용](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md).

필수 속성:\
**클래스**: &quot;mktoText&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
클래스 mktoText(제공된 경우)가 있는 요소의 컨텐츠가 편집 가능 영역의 기본값으로 사용됩니다.

예:

`<div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area.</div>`

## 이미지 {#image}

편집 가능한 이미지 요소를 정의하는 두 가지 옵션이 있습니다. 다음 중 하나를 사용할 수 있습니다 `<div>`- 이미지가 삽입될 컨테이너를 지정하거나 `<img>` 태그에 가깝게 포함했습니다.

## 옵션 1 - `<div>` {#option-use-a-div}

필수 속성:

클래스: &quot;mktoImg&quot;\
id: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
mktoName : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
mktoImgClass: 문자열. 여기서 값은 `<img>` div 내에 있는 요소.

예:

`<div class="mktoImg" id="exampleImg" mktoName="Example Image"></div>`

## 옵션 2 - `<img>` {#option-use-a-img}

필수 속성:\
클래스: &quot;mktoImg&quot;\
id: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
mktoName : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
src: 문자열 URL. 이 값은 이미지의 기본값으로 사용됩니다.

예:

`<img class="mktoImg" id="exampleImg" mktoName="Example Image">`

>[!NOTE]
>
>를 사용할 때 `<img>` version, 렌더링된 HTML에 생성된 div 래퍼가 포함되어 `<img>` 태그에 가깝게 포함했습니다. 수업 시간에 맞춰질 겁니다.&quot;mktoImg.mktoGen,&quot; 및 는 display:inline-block입니다.

## 양식 {#form}

예: 필수 속성:\
**클래스**: &quot;mktoForm&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

`<div class="mktoForm" id="exampleForm" mktoName="Example Form"></div>`

## 코드 조각 {#snippet}

필수 속성:\
**클래스**: &quot;mktoSnippet&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoSnippet" id="exampleSnippet" mktoName="Example Snippet"></div>`

## 공유 단추 {#share-button}

필수 속성:\
**클래스**: &quot;mktoShareButton&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoShareButton" id="exampleShareButton" mktoName="Example Share Button"></div>`

## 비디오 {#video}

>[!NOTE]
>
>Marketo은 랜딩 페이지에서 비디오 요소를 사용할 때 YouTube의 비디오만 지원합니다. 다른 서비스를 사용하는 경우에는 리치 텍스트 상자를 사용하여 비디오의 포함 코드에 붙여넣는 것이 좋습니다.

필수 속성:
**클래스**: &quot;mktoVideo&quot;
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoVideo" id="exampleVideo" mktoName="Example Video"></div>`

## 여론 조사 {#poll}

필수 속성:\
**클래스**: &quot;mktoPoll&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoPoll" id="examplePoll" mktoName="Example Poll"></div>`

## 참조 {#referral}

필수 속성:\
**클래스**: &quot;mktoReferring&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoReferral" id="exampleReferral" mktoName="Example Referral"></div>`

## 경품 추첨 {#sweepstakes}

필수 속성:\
**클래스**: &quot;mktoSweepstakes&quot;\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

예:

`<div class="mktoSweepstakes" id="exampleSweepstakes" mktoName="Example Sweepstakes"></div>`

## 편집 가능한 변수 {#editable-variables}

모든 변수 유형은 ${ } 문자 시퀀스 내에 래핑된 해당 id 속성의 값을 참조하여 사용됩니다. 다른 변수 선언 내부를 제외하고 문서의 어느 곳에서든 사용할 수 있습니다.

예:

`${var1}`

**선언:**

변수는 `<head>` 템플릿의 요소입니다. 사용할 수 있는 변수에는 다음 세 가지 유형이 있습니다. 문자열, 색상 및 부울입니다.

## 문자열 {#string}

필수 속성:\
**클래스** : &quot;mktoString&quot;,\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
**기본**: 특성의 문자열 값입니다. 아무 것도 제공되지 않은 경우 비어 있습니다.\
**allowHtml**: &quot;true&quot; 또는 &quot;false&quot;입니다. HTML 이스케이프되지 않고 값을 인쇄할 것인지 여부를 제어합니다. 설정이 해제된 경우 기본값은 &quot;false&quot;입니다.

기본 예:

`<meta class="mktoString" id="var1" mktoName="My Variable">`

모든 특성이 있는 예:

`<meta class="mktoString" id="var1" mktoName="My Variable" default="This is my default value" allowHtml="true">`

## 색상 {#color}

필수 속성:\
**클래스** : &quot;mktoColor&quot;,\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
**기본**: 7자리 HEX 문자 색상 코드입니다. 예: &quot;#336699&quot;

기본 예:

`<meta class="mktoColor" id="color1" mktoName="My Color Variable">`

모든 특성이 있는 예:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

## 부울 {#boolean}

필수 속성:\
**클래스** : &quot;mktoBoolean&quot;,\
**id**: ID 문자열입니다. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** : 문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 수사적 이름을 사용하는 것이 좋습니다.

선택 사항입니다:\
**기본**: 부울 문자열입니다. &quot;true&quot; 또는 &quot;false&quot;는 값이 ON 또는 OFF 위치에서 시작하는지 여부를 제어합니다. 제공되지 않을 경우 &quot;false&quot;.\
**false_value**: 문자열. 변수가 오프 위치에 있을 때 변수에 삽입할 값입니다. 제공되지 않을 경우 &quot;false&quot;.\
**true_value**: 문자열. 변수가 ON 위치에 있을 때 변수에 삽입할 값입니다. 제공되지 않을 경우 &quot;true&quot;.\
**false_value_name**: 문자열. 값이 오프 위치에 있을 때 랜딩 페이지 편집기에 표시할 표시 이름입니다. 제공되지 않을 경우 &quot;OFF&quot;.\
**true_value_name**: 문자열. 값이 ON 위치에 있을 때 랜딩 페이지 편집기에 표시할 표시 이름입니다. 제공되지 않을 경우 &quot;ON&quot;.

기본 예:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable">`

모든 특성이 있는 예:

이 예는 부울 변수가 css를 사용하여 요소를 ID로 표시/숨기도록 css 표시 속성의 값을 &quot;block&quot; 또는 &quot;none&quot;으로 설정하여 css 요소의 가시성을 제어하는 일반적인 사용 사례를 보여줍니다. 랜딩 페이지 편집기에서는 해제/켜짐 대신 표시 이름 표시/숨기기를 사용합니다.

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable" default="true" true_value="block" false_value="none" false_value_name="Hide" true_value_name="Show"> <style> #myConditionalDisplayArea { display: ${boolean1}; } </style>`

>[!NOTE]
>
>프로그램 토큰(my.token)은 안내가 있는 랜딩 페이지나 자유 형식 랜딩 페이지에서도 사용할 수 있습니다.

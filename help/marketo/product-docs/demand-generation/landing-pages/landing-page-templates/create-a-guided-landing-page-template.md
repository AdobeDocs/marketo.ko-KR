---
unique-page-id: 7515401
description: 안내 랜딩 페이지 템플릿 만들기 - 마케팅 문서 - 제품 설명서
title: 안내 랜딩 페이지 템플릿 만들기
translation-type: tm+mt
source-git-commit: 2969e6f94f5fd781e2167ae2aa8680bb8d134754
workflow-type: tm+mt
source-wordcount: '1269'
ht-degree: 0%

---


# 안내 랜딩 페이지 템플릿 만들기 {#create-a-guided-landing-page-template}

>[!NOTE]
>
>책 읽는 게 지겨워요? [단계별 지침에 따라 이 멋진 ](https://youtu.be/3O7e4GdZKsM) 비디오를 시청하십시오.

안내 랜딩 페이지 템플릿에는 특수 구문이 있습니다. 이 구문을 사용하여 템플릿을 사용하여 만든 각 랜딩 페이지에서 사용자 정의 가능한 항목과 최종 컨텐트 위치를 지정합니다. 편집 가능 영역으로 지정한 영역 또는 변수만 &quot;안내&quot; 랜딩 페이지 편집기 내에서 사용자 정의할 수 있습니다.

>[!TIP]
>
>명명 규칙을 잘 사용하면 마케팅 팀이 고객을 매료시킬 수 있습니다.

페이지의 내용을 편집할 수 있다고 선언할 때는 두 가지 방법이 있습니다.

* 객체를 &quot;요소&quot;로 선언합니다. 랜딩 페이지 작성자는 이미지, 텍스트 또는 마케팅 자산을 지정된 영역에 추가할 수 있습니다.
* 문자열을 &quot;변수&quot;로 선언합니다. 랜딩 페이지 작성자는 true/false 레버에서 해당 변수를 문자열, 색상 또는 부울 상태로 바꿀 수 있습니다.

## 편집 가능한 요소 {#editable-elements}

요소를 템플릿에 일반적인 DOM 요소를 추가한 다음 해당 요소를 시장별 클래스 이름으로 장식하여 선언합니다.

## 텍스트 {#text}

영역을 리치 텍스트로 정의하면 사용자는 Marketing의 리치 텍스트 편집기](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md)를 사용하여 [의 컨텐츠를 편집할 수 있습니다.

필수 속성:\
**클래스**:&quot;mktoText&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
mktoText 클래스가 있는 요소의 컨텐츠(제공된 경우)가 편집 가능 영역의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area.</div></pre>`

### 이미지 {#image}

편집 가능한 이미지 요소를 정의하는 두 가지 옵션이 있습니다. 이미지를 삽입할 컨테이너를 지정하는 `<div>` 또는 `<img>` 태그를 사용할 수 있습니다.

## 옵션 1 - `<div>` {#option-use-a-div} 사용

필수 속성:

class:&quot;mktoImg&quot;\
id:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
mktoName :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
mktoImgClass:문자열. 이 값은 div 내의 `<img>` 요소의 클래스 특성에 추가됩니다.

예:

`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image"></div></pre>`

## 옵션 2 - `<img>` {#option-use-a-img} 사용

필수 속성:\
class:&quot;mktoImg&quot;\
id:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
mktoName :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
src:문자열 URL. 이 값은 이미지의 기본값으로 사용됩니다.

예:

`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>`

>[!NOTE]
>
>`<img>` 버전을 사용할 때 렌더링된 HTML은 `<img>` 태그 주위에 생성된 div 래퍼를 포함합니다. 수업 준비가 될 것이다.&quot;mktoImg.mktoGen&quot;과, display:inline-block이 됩니다.

## 양식 {#form}

예: 필수 속성:\
**클래스**:&quot;mktoForm&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

`<pre data-theme="Confluence"><div class="mktoForm" id="exampleForm" mktoName="Example Form"></div></pre>`

## 코드 단편 {#snippet}

필수 속성:\
**클래스**:&quot;mktoSnippet&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoSnippet" id="exampleSnippet" mktoName="Example Snippet"></div></pre>`

## 공유 단추 {#share-button}

필수 속성:\
**클래스**:&quot;mktoShareButton&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoShareButton" id="exampleShareButton" mktoName="Example Share Button"></div></pre>`

## 비디오 {#video}

>[!NOTE]
>
>랜딩 페이지에서 비디오 요소를 사용하는 경우 Marketing은 YouTube의 비디오만 지원합니다. 다른 서비스를 사용하는 경우 리치 텍스트 상자를 활용하여 비디오의 포함 코드에 붙여넣는 것이 좋습니다.

필수 속성:
**class**:&quot;mktoVideo&quot;
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoVideo" id="exampleVideo" mktoName="Example Video"></div></pre>`

## 투표 {#poll}

필수 속성:\
**클래스**:&quot;mktoPoll&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoPoll" id="examplePoll" mktoName="Example Poll"></div></pre>`

## 참조 {#referral}

필수 속성:\
**클래스**:&quot;mktoReferring&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoReferral" id="exampleReferral" mktoName="Example Referral"></div></pre>`

## 경품 행사 {#sweepstakes}

필수 속성:\
**클래스**:&quot;mktoSweepstakes&quot;\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

예:

`<pre data-theme="Confluence"><div class="mktoSweepstakes" id="exampleSweepstakes" mktoName="Example Sweepstakes"></div></pre>`

## 편집 가능한 변수 {#editable-variables}

모든 변수 유형은 ${ } 문자 시퀀스 내에 래핑된 id 속성의 값을 참조하여 사용됩니다. 다른 변수 선언의 내부를 제외하고 문서의 모든 곳에서 사용할 수 있습니다.

예:

`<pre data-theme="Confluence">${var1}</pre>`

**선언:**

변수는 템플릿의 `<head>` 요소 내에서 메타 태그로 선언됩니다. 사용할 수 있는 변수에는 3가지 유형이 있습니다.문자열, 색상 및 부울 값을 반환합니다.

## 문자열 {#string}

필수 속성:\
**클래스** :&quot;mktoString&quot;,\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
**기본값**:속성의 문자열 값입니다. 아무 것도 제공되지 않으면 비워둡니다.\
**allowHtml**:&quot;true&quot; 또는 &quot;false&quot;입니다. HTML을 이스케이프하지 않고 값을 인쇄할지 여부를 제어합니다. 설정이 해제된 경우 기본값은 &quot;false&quot;입니다.

기본 예:

`<pre data-theme="Confluence"><meta class="mktoString" id="var1" mktoName="My Variable"></pre>`

모든 특성이 있는 예:

`<pre data-theme="Confluence"><meta class="mktoString" id="var1" mktoName="My Variable" default="This is my default value" allowHtml="true"></pre>`

## 색상 {#color}

필수 속성:\
**클래스** :&quot;mktoColor&quot;,\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
**기본값**:7자리 HEX 문자 색상 코드. 예:&quot;#336699&quot;

기본 예:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color1" mktoName="My Color Variable"></pre>`

모든 특성이 있는 예:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699"></pre>`

## 부울 {#boolean}

필수 속성:\
**클래스** :&quot;mktoBoolean&quot;,\
**id**:ID 문자열. 문자, 숫자, 대시 &quot;-&quot; 및 밑줄 &quot;_&quot;만 포함합니다. 공백은 허용되지 않습니다. 고유해야 합니다.\
**mktoName** :문자열. 랜딩 페이지 편집기에 표시되는 표시 이름입니다. 설명형 이름을 사용하는 것이 좋습니다.

선택 사항:\
**기본값**:부울 문자열입니다. &quot;true&quot; 또는 &quot;false&quot;는 값이 ON 또는 OFF 위치에서 시작하는 경우 제어합니다. 제공되지 않는 경우 &quot;false&quot;입니다.\
**false_value**:문자열. OFF 위치에 있을 때 변수에 삽입되는 값입니다. 제공되지 않는 경우 &quot;false&quot;입니다.\
**true_value**:문자열. ON 위치에 있을 때 변수에 삽입되는 값입니다. 제공되지 않는 경우 &quot;true&quot;입니다.\
**false_value_name**:문자열. 값이 OFF 위치에 있을 때 랜딩 페이지 편집기에 표시할 표시 이름입니다. 제공되지 않는 경우 &quot;OFF&quot;입니다.\
**true_value_name**:문자열. 값이 ON 위치에 있을 때 랜딩 페이지 편집기에 표시할 표시 이름입니다. 제공되지 않는 경우 &quot;켜짐&quot;입니다.

기본 예:

`<pre data-theme="Confluence"><meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699"></pre>`

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable"></pre>`

모든 특성이 있는 예:

이 예제는 부울 변수가 css 표시 속성 값을 &quot;block&quot; 또는 &quot;none&quot;으로 설정하여 CSS를 사용하는 ID별로 요소를 표시/숨기도록 css 요소의 가시성을 제어하는 일반적인 사용 사례를 보여줍니다. 랜딩 페이지 편집기에서는 OFF/ON 대신 표시/숨기기를 사용합니다.

`<pre data-theme="Confluence"><meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable" default="true" true_value="block" false_value="none" false_value_name="Hide" true_value_name="Show"> <style> #myConditionalDisplayArea { display: ${boolean1}; } </style></pre>`

>[!NOTE]
>
>프로그램 토큰(my.token)은 안내 또는 자유 형식 랜딩 페이지의 어느 위치에서든 사용할 수 있습니다.

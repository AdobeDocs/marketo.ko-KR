---
unique-page-id: 1147114
description: 프로그램의 내 토큰 이해 - Marketo 문서 - 제품 설명서
title: 프로그램의 내 토큰 이해
exl-id: 01b42272-c419-4cd5-ad30-87413ceb2032
feature: Tokens
source-git-commit: 0200af9b8ce180e15c6a45c5438b8f6f1c4af588
workflow-type: tm+mt
source-wordcount: '422'
ht-degree: 1%

---

# 프로그램의 내 토큰 이해 {#understanding-my-tokens-in-a-program}

토큰은 이메일, 랜딩 페이지 및 스마트 캠페인에 사용하여 생활을 편리하게 할 수 있는 변수입니다.

내 토큰 외에도 프로그램의 기본 제공 토큰을 사용할 수 있습니다. [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"}를 확인하십시오.

## 내 토큰  {#my-tokens}

내 토큰은 누구나 만들 수 있는 사용자 지정 변수입니다. 로컬에서 캠페인 폴더 또는 프로그램에 [생성](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}됩니다.

내 토큰은 다음과 같이 표시됩니다. `{{my.Name Of Token}}`

예:

* `{{my.Event Date}}`
* `{{my.Webinar Speaker}}`

<table> 
 <thead> 
  <tr> 
   <th>토큰 유형</th> 
   <th>설명</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>캘린더 파일 <img alt="—" src="assets/image2014-9-25-16-3a44-3a19.png" data-linked-resource-id="3083230" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>이 토큰을 사용하여 <a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/create-a-calendar-event-ics-file.md">일정 이벤트 파일(.i</a><a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/create-a-calendar-event-ics-file.md">cs)</a>을 전자 메일 및 랜딩 페이지에 추가하십시오.</td> 
  </tr> 
  <tr> 
   <td><p>Date <img alt="--" src="assets/image2014-9-25-16-3a44-3a47.png" data-linked-resource-id="3083231" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></p></td> 
   <td>이 토큰은 날짜 값을 보유합니다. 날짜는 년-월-일(예: 2016-05-23)로 표시됩니다.</td> 
  </tr> 
  <tr> 
   <td>이메일 스크립트 <img alt="--" src="assets/image2014-9-25-16-3a45-3a4.png" data-linked-resource-id="3083232" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>이 토큰을 사용하여 이메일에서 Velocity 스크립트를 실행하십시오. <a href="https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/email-scripting" title="링크 따라가기" rel="nofollow">여기</a>에서 자세히 알아보세요. </td> 
  </tr> 
  <tr> 
   <td>번호<span> <img alt="--" src="assets/image2014-9-25-16-3a45-3a25.png" data-linked-resource-id="3083233" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></span></td> 
   <td>모든 정수. 심지어 부정적일 수도 있습니다.</td> 
  </tr> 
  <tr> 
   <td>리치 텍스트 <img alt="--" src="assets/image2014-9-25-16-3a46-3a22.png" data-linked-resource-id="3083234" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>HTML 입니다. 이메일 및 랜딩 페이지에서 사용합니다.</td> 
  </tr> 
  <tr> 
   <td>점수 <img alt="--" src="assets/image2014-9-25-16-3a46-3a39.png" data-linked-resource-id="3083235" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md">점수 흐름 변경 단계</a>에서 이 토큰을 사용하십시오. </td> 
  </tr> 
  <tr> 
   <td colspan="1">SFDC 캠페인 <img alt="--" src="assets/sfdc-campaign-icon.jpg" data-linked-resource-id="11379761" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114" title="--"></td> 
   <td colspan="1">이 토큰을 사용하여 Marketo 프로그램의 일부가 되는 리드를 SFDC Campaign이 추가되는 요소에도 추가할 수 있습니다.</td> 
  </tr> 
  <tr> 
   <td>텍스트 <img alt="--" src="assets/image2014-9-25-16-3a46-3a54.png" data-linked-resource-id="3083236" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="1147114"></td> 
   <td>문자만 좀 보내요. HTML이 오버킬일 때 사용합니다. 텍스트 토큰의 크기 제한은 524,288자(UTF-8) 또는 2MB입니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!CAUTION]
>
>[!DNL Microsoft Dynamics] 또는 [!DNL Salesforce]에서 Sales Insight에서 전자 메일을 보낼 때 내 토큰이 확인되지 않습니다. 표준 토큰만 채워집니다(Lead, Company 등). 그러나 토큰 _will_&#x200B;의 기본값은 작동합니다.

## 토큰 중첩 {#nesting-tokens}

새 토큰을 만들 때 트리의 다른 오브젝트에서 참조할 수 있습니다. 간편한 관리를 위해 토큰이 생성된 위치에 대한 이름 지정 구조가 있습니다.

* **로컬 토큰:** 토큰이 해당 프로그램 또는 폴더에 바로 만들어졌습니다.
* **상속된 토큰:** 더 높은 수준의 프로그램이나 폴더의 트리 위에 토큰을 만들었습니다.
* **재정의된 토큰:** 토큰이 상속된 다음 누군가 이 프로그램 또는 폴더에서 예외를 만들었습니다.

전역 변수를 만든 다음 트리의 하위 수준에서 재정의할 수 있습니다.

프로그램 및 폴더를 이동하면 토큰에도 영향을 줍니다. 이동 중에 참조가 손상되지 않았는지 항상 확인하십시오.

>[!IMPORTANT]
>
>중첩된 토큰은 [일괄 캠페인](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/understanding-batch-and-trigger-smart-campaigns.md#batch-campaign){target="_blank"}에서 지원되지 않습니다.

>[!NOTE]
>
>참여 프로그램에서 보내는 이메일이 기본 프로그램(참여 프로그램의 로컬이 아님)의 하위 이메일인 경우, 이메일에 사용된 모든 내 토큰은 하위 이메일이 있는 기본 프로그램에서 확인됩니다.

>[!MORELIKETHIS]
>
>* [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"}
>* [내 토큰 관리](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"}

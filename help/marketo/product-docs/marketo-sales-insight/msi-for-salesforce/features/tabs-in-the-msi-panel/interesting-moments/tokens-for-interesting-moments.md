---
unique-page-id: 1146999
description: 흥미로운 순간을 위한 토큰 - Marketing Docs - 제품 설명서
title: 흥미로운 순간을 위한 토큰
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# 흥미로운 순간을 위한 토큰 {#tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>* 흥미로운 [순간 흐름 단계를 사용하는 방법을 알아봅니다](../../../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).
>* 토큰에 대한 자세한 [내용을 살펴보십시오](http://docs.marketo.com/display/docs/tokens).

>



## 사용 가능한 토큰 {#available-tokens}

토큰 [개요](../../../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) 를 확인하여 흥미로운 순간에 넣을 수 있는 모든 토큰을 확인합니다.

## 트리거 토큰 {#trigger-tokens}

스마트 캠페인에 사용된 트리거를 기반으로 추가 트리거 토큰을 사용할 수 있습니다.

* `{{trigger.Trigger Name}}` 그것은 항상 실제 방아쇠 자체이다. 예:이메일에서 링크를 클릭합니다.
* `{{trigger.Name}}` 은 캠페인을 트리거한 자산의 이름입니다. 예:웹 페이지에서 링크를 클릭하는 것은 URL 자체이며 Salesforce 트리거 등의 제목입니다.
* 추가 트리거는 아래에 나열된 제한 사항에 따라 사용할 수 있습니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th><code>{{trigger.Trigger Name}}</code></th> 
   <th><code>{{trigger.Name}}</code></th> 
   <th><code>{{trigger.Link}}</code></th> 
   <th><code>{{trigger.Subject}}</code></th> 
   <th><code>{{trigger.Category}}</code></th> 
   <th><code>{{trigger.Details}}</code></th> 
   <th><code>{{trigger.Web Page}}</code></th> 
   <th><code>{{trigger.Client IP Address}}</code></th> 
   <th><code>{{trigger.Sent By}}</code></th> 
   <th><code>{{trigger.Received By}}</code></th> 
  </tr> 
  <tr> 
   <td>이메일의 링크 클릭 수</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>이메일 바운스 수</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>이메일 바운스 소프트</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>이메일 전달</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>이메일 열기</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>이메일의 가입 해지</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>영업 이메일의 클릭 수 링크</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>보낸 영업 이메일</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>영업 이메일 열기</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>받은 영업 이메일</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
  </tr> 
  <tr> 
   <td colspan="1">바운스된 영업 이메일</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td>양식 채우기</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1">웹 페이지 방문*</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>확인(확인 표시)이 없으면 ![](assets/check.svg) 흥미로운 순간에 빈 문자열(아무것도 없음)이 반환됩니다.

*트리거 방문 **웹 페이지에는** 몇 개의 추가 토큰이 있습니다.

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>항상 흥미로운 순간을 테스트하여 의도한 대로 표현할 수 있습니다.
>
>또한, 판매자에게만 관심 있는 것이 아니라 흥미로운 일인지 확인하십시오. ![(윙크)](assets/wink.svg)>


---
unique-page-id: 1146999
description: 흥미로운 순간을 위한 토큰 트리거 - Marketo 문서 - 제품 설명서
title: 흥미로운 순간에 대한 토큰 트리거
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
translation-type: tm+mt
source-git-commit: f4c773ca76542827a498940f44b018ddb71816d6
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---

# 관심 있는 순간에 대한 토큰 트리거 {#trigger-tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>[흥미로운 모멘트 흐름 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md)를 사용하는 방법에 대해 학습합니다.

## 사용 가능한 토큰 {#available-tokens}

흥미로운 순간에 넣을 수 있는 모든 토큰을 보려면 [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md)를 확인하십시오.

## 트리거 토큰 {#trigger-tokens}

스마트 캠페인에 사용된 트리거를 기반으로 추가 트리거 토큰을 사용할 수 있습니다.

* `{{trigger.Trigger Name}}` 그것은 항상 실제 방아쇠 자체이다. 예:이메일에서 링크를 클릭합니다.
* `{{trigger.Name}}` 은 캠페인을 트리거한 자산의 이름입니다. 예:웹 페이지에 대한 링크 클릭은 URL 자체이며 Salesforce 트리거 등에 적용됩니다.
* 추가 트리거는 아래에 나열된 제한 조건을 기반으로 사용할 수 있습니다.

**이메일 트리거**

<table style="table-layout:auto"> 
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
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>이메일에 있는 링크 클릭 수</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>이메일 바운스 하드</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>이메일 바운스 소프트</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>이메일이 배달됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>이메일 열기</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>친구에게 보낸 이메일 수신</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>친구에게 보낸 이메일</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td>
  </tr> 
  <tr> 
   <td>이메일의 가입 해지</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**Salesforce 트리거**

<table style="table-layout:auto"> 
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
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>영업 이메일의 클릭 수 링크</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>영업 이메일이 전송됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>영업 이메일 열기</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>판매 이메일 바운스 수</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>판매 이메일 수신</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>기회가 업데이트됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>소유자 변경</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>전환된 사람</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>SFDC에서 인물 삭제</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>사람이 SFDC에 동기화됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Opportunity에서 제거됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>SFDC 캠페인에서 제거됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>활동이 기록됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>활동이 업데이트됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>기회에 추가</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>SFDC 캠페인에 추가됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>SFDC 캠페인에서 상태가 변경됨</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**판매 연결 트리거**

<table style="table-layout:auto"> 
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
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>영업 이메일의 클릭 수 링크</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>영업 이메일이 전송됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>영업 이메일 열기</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>판매 이메일 바운스 수</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>판매 이메일 수신</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>판매 캠페인에 추가됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr>
   <td>소유자 변경</td> 
   <td>판매 캠페인에서 제거됨</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>접수 판매 전화</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**기타**

<table style="table-layout:auto"> 
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
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>양식 채우기</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>웹 페이지 방문 횟수</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>웹 페이지에서 링크 클릭 수</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>검사 ![(tick)](assets/check.png)이 없으면 흥미로운 순간에 빈 문자열(아무것도 없음)이 반환됩니다.

*트리거 **방문 웹 페이지**&#x200B;에는 추가적인 토큰이 몇 개 있습니다.

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>흥미로운 순간을 테스트하여 의도한 대로 표현할 수 있습니다.
>
>또한, 판매 담당자에게도 재미있는지 확인해 보십시오. 여러분들에게만은 아닙니다.
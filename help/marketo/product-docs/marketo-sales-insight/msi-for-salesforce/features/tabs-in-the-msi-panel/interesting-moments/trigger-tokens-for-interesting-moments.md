---
unique-page-id: 1146999
description: 흥미로운 순간에 대한 토큰 트리거 - Marketo 문서 - 제품 설명서
title: 흥미로운 순간에 대한 토큰 트리거
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
source-git-commit: f4c773ca76542827a498940f44b018ddb71816d6
workflow-type: tm+mt
source-wordcount: '436'
ht-degree: 0%

---

# 흥미로운 순간에 대한 토큰 트리거 {#trigger-tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>사용 방법 알아보기 [흥미로운 모멘트 흐름 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).

## 사용 가능한 토큰 {#available-tokens}

체크 아웃 [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) 모든 토큰을 확인하는 것이 매우 흥미로운 순간입니다.

## 트리거 토큰 {#trigger-tokens}

스마트 캠페인에 사용된 트리거를 기반으로 추가 트리거 토큰을 사용할 수 있습니다.

* `{{trigger.Trigger Name}}` 항상 실제 트리거 자체입니다. 예: 이메일에서 링크 클릭.
* `{{trigger.Name}}` 은 캠페인을 트리거한 자산의 이름입니다. 예: 웹 페이지에서 클릭 링크 는 URL 자체, Salesforce 트리거 제목 등입니다.
* 추가 트리거는 아래에 나열된 제한을 기반으로 사용할 수 있습니다.

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
   <td>이메일의 클릭 링크</td> 
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
   <td>이메일 바운스 수 하드</td> 
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
   <td>전자 메일 열기</td> 
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
   <td>친구에게 전달 전자 메일 수신</td> 
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
   <td>친구 전자 메일로 보내기</td> 
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
   <td>이메일에서 가입 해지</td> 
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
   <td>영업 전자 메일의 클릭 링크</td> 
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
   <td>판매 이메일을 보냅니다.</td> 
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
   <td>영업 전자 메일 열기</td> 
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
   <td>영업 전자 메일 수신</td> 
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
   <td>Opportunity 가 업데이트됨</td> 
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
   <td>개인 변환</td> 
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
   <td>SFDC에서 개인 삭제</td> 
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
   <td>개인이 SFDC에 동기화됨</td> 
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
   <td>Opportunity에 추가됨</td> 
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
   <td>SFDC Campaign에서 상태가 변경됨</td> 
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

**영업 연결 트리거**

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
   <td>영업 전자 메일의 클릭 링크</td> 
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
   <td>판매 이메일을 보냅니다.</td> 
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
   <td>영업 전자 메일 열기</td> 
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
   <td>영업 전자 메일 수신</td> 
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
   <td>수신한 영업 호출</td> 
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
   <td>웹 페이지에서 링크 클릭</td> 
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
>수표가 없으면 ![(틱)](assets/check.png) 그런 다음 흥미로운 순간에 빈 문자열(아무것도 없음)을 반환합니다.

&#42;트리거 **웹 페이지 방문 횟수** 에는 다음과 같은 몇 가지 추가 토큰이 있습니다.

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>항상 흥미로운 순간을 테스트하여 의도한 대로 렌더링합니다.
>
>또한, 판매 직원에게도 재미있는지, 여러분들에게만이 아닌, 확인하라!

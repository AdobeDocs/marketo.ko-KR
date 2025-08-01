---
unique-page-id: 1146999
description: 즐거운 순간을 위한 트리거 토큰 - Marketo 문서 - 제품 설명서
title: 즐거운 순간을 위한 트리거 토큰
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
feature: Marketo Sales Insights
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '546'
ht-degree: 38%

---

# 즐거운 순간을 위한 트리거 토큰 {#trigger-tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>[관심 있는 순간 흐름 단계](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md)를 사용하는 방법을 알아봅니다.

## 사용 가능한 토큰 {#available-tokens}

흥미로운 순간에 넣을 수 있는 모든 토큰을 보려면 [토큰 개요](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md)를 확인하십시오.

## 트리거 토큰 {#trigger-tokens}

스마트 캠페인에 사용된 트리거를 기반으로 추가 트리거 토큰을 사용할 수 있습니다.

* `{{trigger.Trigger Name}}`은(는) 항상 실제 트리거 자체입니다. 예: 이메일의 링크를 클릭합니다.
* `{{trigger.Name}}`은(는) 캠페인을 트리거한 자산의 이름입니다. 예를 들어 웹 페이지에서 링크 클릭 수는 URL 자체이며 Salesforce 트리거 주체입니다.
* 아래 나열된 제한 사항에 따라 추가 트리거를 사용할 수 있습니다.

### 이메일 트리거 {#email-triggers}

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
   <td>이메일의 링크 클릭 수</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>전자 메일 바운스 소프트</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>이메일 전달됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>친구에게 이메일 발송</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>친구에게 이메일 발송</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
  </tr>
  <tr>
   <td>이메일에서 구독 취소</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

### Salesforce 트리거 {#salesforce-triggers}

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
   <td>영업 이메일의 링크 클릭</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>판매 이메일 전송됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>영업 이메일 열기</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>영업 이메일 반송</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>영업 이메일 수신</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
    <tr>
   <td>영업 기회가 업데이트되었습니다.</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>소유자 변경 사항</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>개인이 전환됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>사용자가 SFDC에서 삭제되었습니다.</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>사용자가 SFDC에 동기화됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>영업 기회에서 제거됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>영업 기회에 추가됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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

### Sales Connect 트리거 {#sales-connect-triggers}

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
   <td>영업 이메일의 링크 클릭</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>판매 이메일 전송됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>영업 이메일 열기</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>영업 이메일 반송</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>영업 이메일 수신</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>Sales Campaign에 추가됨</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>소유자 변경 사항</td>
   <td>이(가) 판매 캠페인에서 제거되었습니다.</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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
   <td>판매 전화를 받음</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
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

### Dynamic Chat 트리거 토큰 {#dynamic-chat-trigger-tokens}

<table>
<thead>
  <tr>
    <th> </th>
    <th><code>{{trigger.Agent Email}}</code></th>
    <th><code>{{trigger.Agent Name}}</code></th>
    <th><code>{{trigger.Conversation Status}}</code></th>
    <th><code>{{trigger.Conversation Summary}}</code></th>
    <th><code>{{trigger.Conversation Transcript}}</code></th>
    <th><code>{{trigger.Document Downloaded}}</code></th>
    <th><code>{{trigger.Document Name}}</code></th>
    <th><code>{{trigger.Document Opened}}</code></th>
    <th><code>{{trigger.Document URL}}</code></th>
    <th><code>{{trigger.Goal name}}</code></th>
    <th><code>{{trigger.meeting status}}</code></th>
    <th><code>{{trigger.Name}}</code></th>
    <th><code>{{trigger.Page URL}}</code></th>
    <th><code>{{trigger.routing queue name}}</code></th>
    <th><code>{{trigger.Scheduled For}}</code></th>
    <th><code>{{trigger.source name}}</code></th>
    <th><code>{{trigger.source type}}</code></th>
    <th><code>{{trigger.Trigger Name}}</code></th>
    <th><code>{{trigger.ui type}}</code></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>대화에 참여함</td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화 양식에 참여</td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
  </tr>
  <tr>
    <td>대화에서 상담원과 상호 작용함</td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화 형식으로 에이전트와 참여</td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화에서 회의를 예약함</td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화 양식의 예약된 회의</td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화 목표를 달성함</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화형 양식 목표에 도달했습니다.</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화에서 문서와 상호 작용함</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>대화형 양식에서 문서와 상호 작용</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td><img src="assets/check.png" alt="확인"></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</tbody>
</table>

### 기타 {#miscellaneous}

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
   <td>양식을 작성함</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
  <tr>
   <td>웹 페이지를 방문함</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
  </tr>
  <tr>
   <td>웹 페이지에서 링크 클릭</td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><img src="assets/check.png" alt="확인"></td>
   <td><br></td>
   <td><br></td>
   <td><br></td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>확인 ![(틱)](assets/check.png)이(가) 없으면 즐거운 순간에 빈 문자열(nothing)이 반환됩니다.

&#42;트리거 **웹 페이지 방문**&#x200B;에 몇 가지 추가 토큰이 있습니다.

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>항상 재미있는 순간을 테스트하여 의도한 방식으로 렌더링하는지 확인하십시오.
>
>또한, 여러분뿐만 아니라 영업 담당자에게도 흥미로운 내용인지 확인하십시오!

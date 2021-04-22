---
unique-page-id: 4719304
description: 암시적인 Salesforce 동작 - Marketo 문서 - 제품 설명서
title: 암시적인 Salesforce 동작
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 0%

---

# 암시적인 Salesforce 동작 {#implied-salesforce-actions}

Salesforce별 흐름 단계가 실행되면 때때로 추가 단계가 자동으로 수행됩니다. 여기 규칙이 있습니다.

이 규칙은 사용자가 현재 [Salesforce.com](https://Salesforce.com)_에 연락처 또는 리드로 있지 않은 경우_&#x200B;이(가) 적용됩니다.

<table> 
 <thead> 
  <tr> 
   <th>Marketo 흐름 단계</th> 
   <th>자동 작업</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>SFDC 캠페인에 추가</td> 
   <td>SFDC에 사람 동기화</td> 
  </tr> 
  <tr> 
   <td>SFDC 캠페인의 상태 변경</td> 
   <td>SFDC<br>SFDC 캠페인에 사람 동기화</td> 
  </tr> 
  <tr> 
   <td>소유자 변경</td> 
   <td><p>SFDC에 사람 동기화</p></td> 
  </tr> 
  <tr> 
   <td>개인 변환</td> 
   <td><p>SFDC에 사람 동기화</p></td> 
  </tr> 
  <tr> 
   <td>작업 만들기</td> 
   <td>SFDC에 사람 동기화</td> 
  </tr> 
 </tbody> 
</table>

연산자가 &quot;is not empty&quot;로 설정된 **SFDC 유형** 필터를 사용하여 스마트 목록에 있는 SFDC 레코드를 필터링할 수 있습니다. 모든 SFDC 레코드에 이 필드에 값이 있습니다.

이러한 자동 작업은 리드가 현재 [Salesforce.com](https://salesforce.com)에 없는 경우에만 발생합니다.

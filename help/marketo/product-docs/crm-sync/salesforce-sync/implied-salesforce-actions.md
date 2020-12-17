---
unique-page-id: 4719304
description: 암시적인 Salesforce 동작 - Marketing To Docs - 제품 설명서
title: 암시적인 Salesforce 동작
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '149'
ht-degree: 0%

---


# 암시적인 Salesforce 동작 {#implied-salesforce-actions}

Salesforce별 흐름 단계가 실행되면 때때로 추가 단계가 자동으로 수행됩니다. 여기 규칙이 있습니다.

이 규칙은 사용자가 현재 [Salesforce.com](http://Salesforce.com)*에 연락처 또는 리드로 있지 않은 경우*&#x200B;이(가) 적용됩니다.

<table> 
 <thead> 
  <tr> 
   <th>마케팅 흐름 단계</th> 
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

이러한 자동 작업은 리드가 현재 [Salesforce.com](http://Salesforce.com)에 없는 경우에만 발생합니다.

Salesforce 동기화는 수월합니다. 그렇죠?

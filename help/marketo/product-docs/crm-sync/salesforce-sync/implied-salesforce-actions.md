---
unique-page-id: 4719304
description: 암시된 Salesforce 작업 - Marketo 문서 - 제품 설명서
title: 암시된 Salesforce 작업
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '143'
ht-degree: 0%

---

# 암시된 Salesforce 작업 {#implied-salesforce-actions}

Salesforce 관련 흐름 단계가 실행될 때 경우에 따라 추가 단계가 자동으로 수행됩니다. 규칙이 있습니다.

이러한 규칙이 적용됩니다 _사용자가 현재 [Salesforce.com](https://Salesforce.com)_ 연락 또는 잠재 고객으로.

<table> 
 <thead> 
  <tr> 
   <th>Marketo 흐름 단계</th> 
   <th>자동 작업</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>SFDC Campaign에 추가</td> 
   <td>SFDC에 개인 동기화</td> 
  </tr> 
  <tr> 
   <td>SFDC Campaign에서 상태 변경</td> 
   <td>SFDC에 개인 동기화<br>SFDC Campaign에 추가</td> 
  </tr> 
  <tr> 
   <td>소유자 변경</td> 
   <td><p>SFDC에 개인 동기화</p></td> 
  </tr> 
  <tr> 
   <td>개인 변환</td> 
   <td><p>SFDC에 개인 동기화</p></td> 
  </tr> 
  <tr> 
   <td>작업 만들기</td> 
   <td>SFDC에 개인 동기화</td> 
  </tr> 
 </tbody> 
</table>

다음을 사용하여 스마트 목록의 SFDC 레코드를 필터링할 수 있습니다 **SFDC 유형** 연산자가 &quot;is not empty&quot;로 설정된 필터입니다. 모든 SFDC 레코드에는 이 필드에 값이 있습니다.

이러한 자동 작업은 리드가 현재 [Salesforce.com](https://salesforce.com)

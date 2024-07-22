---
unique-page-id: 4719304
description: 암시적 Salesforce 작업 - Marketo 문서 - 제품 설명서
title: 암묵적인 Salesforce 작업
exl-id: 88533588-77f2-465e-9644-a4f95b87f99d
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 0%

---

# 암묵적인 Salesforce 작업 {#implied-salesforce-actions}

Salesforce별 흐름 단계가 실행되면 경우에 따라 추가 단계가 자동으로 수행됩니다. 다음은 규칙이므로 다음을 알고 있습니다.

이 규칙은 사용자가 현재 [Salesforce.com](https://Salesforce.com){target="_blank"}에 연락처 또는 잠재 고객으로 있지 않을 때 적용됩니다.

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
   <td>사용자를 SFDC에 동기화</td> 
  </tr> 
  <tr> 
   <td>SFDC 캠페인의 상태 변경</td> 
   <td>사용자를 SFDC에 동기화<br>SFDC 캠페인에 추가</td> 
  </tr> 
  <tr> 
   <td>소유자 변경</td> 
   <td><p>사용자를 SFDC에 동기화</p></td> 
  </tr> 
  <tr> 
   <td>사용자 전환</td> 
   <td><p>사용자를 SFDC에 동기화</p></td> 
  </tr> 
  <tr> 
   <td>작업 만들기</td> 
   <td>사용자를 SFDC에 동기화</td> 
  </tr> 
 </tbody> 
</table>

연산자가 &quot;is not empty&quot;로 설정된 **[!UICONTROL SFDC Type]** 필터를 사용하여 스마트 목록에서 SFDC 레코드를 필터링할 수 있습니다. 모든 SFDC 레코드는 이 필드에 값이 있습니다.

이러한 자동 작업은 잠재 고객이 현재 [Salesforce.com](https://salesforce.com){target="_blank"}에 없는 경우에만 발생합니다

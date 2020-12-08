---
unique-page-id: 4719304
description: 묵시적 Salesforce 동작 - Marketing To Docs - 제품 설명서
title: 묵시적 Salesforce 작업
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '200'
ht-degree: 0%

---


# 묵시적 Salesforce 작업 {#implied-salesforce-actions}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Salesforce별 흐름 단계가 실행되면 때때로 추가 단계가 자동으로 수행됩니다. 여기 규칙이 있습니다.

이 규칙은 해당 사람이 현재 *Salesforce.com [에 연락처 또는 리드로 있지 않을](http://Salesforce.com)* 때 적용됩니다.

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
   <td>SFDCA에 사람<br>동기화SFDC 캠페인에 추가</td> 
  </tr> 
  <tr> 
   <td>소유자 변경</td> 
   <td><p>SFDC에 사람 동기화</p></td> 
  </tr> 
  <tr> 
   <td>개인 전환</td> 
   <td><p>SFDC에 사람 동기화</p></td> 
  </tr> 
  <tr> 
   <td>작업 만들기</td> 
   <td>SFDC에 사람 동기화</td> 
  </tr> 
 </tbody> 
</table>

연산자가 &quot;is not empty&quot;로 설정된 **SFDC 유형** 필터를 사용하여 스마트 목록에 있는 SFDC 레코드를 필터링할 수 있습니다. 모든 SFDC 레코드는 이 필드에 값을 가집니다.

이러한 자동 작업은 리드가 현재 [Salesforce.com에 없는 경우에만 이루어집니다](http://Salesforce.com)

Salesforce의 동기화는 수월합니다.

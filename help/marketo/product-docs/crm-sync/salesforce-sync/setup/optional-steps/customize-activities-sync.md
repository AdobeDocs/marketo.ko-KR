---
unique-page-id: 4719294
description: 활동 동기화 사용자 정의 - Marketing Docs - 제품 설명서
title: 활동 동기화 사용자 지정
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '279'
ht-degree: 0%

---


# 활동 동기화 사용자 지정 {#customize-activities-sync}

Sales Insight를 사용하지 않는 경우 Marketing에서 [특정 이벤트에](http://docs.marketo.com/display/DOCS/Marketo+Sales+Insight)대한 Salesforce 활동 내역 레코드를 만들 수 있습니다. 이를 구현하는 방법을 살펴보십시오.

1. **관리로 이동합니다. **

   ![](assets/admin.png)

1. Salesforce **를**&#x200B;클릭한 다음 **동기화 옵션 편집을 클릭합니다**.

   ![](assets/two-1.png)

1. Marketing to가 Salesforce에 푸시할 활동 옆의 상자를 선택하고 **저장을 클릭합니다**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >활성화되면 Marketing은 3개월 분량의 활동 내역을 데이터 양에 따라 *완료하는 데 며칠이 걸릴 수 있습니다*. 초기 활동 푸시 중에 발생하는 업데이트는 초기 활동 동기화가 완료된 후까지 지연될 수 있습니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <thead> 
  <tr> 
   <th>활동 유형</th> 
   <th>설명</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>양식 작성</td> 
   <td>마케팅 양식 작성</td> 
  </tr> 
  <tr> 
   <td>목록에 추가됨</td> 
   <td><p>흐름 단계:정적 목록에 추가됨</p></td> 
  </tr> 
  <tr> 
   <td>보낸 이메일</td> 
   <td>흐름 단계:이메일 전송</td> 
  </tr> 
  <tr> 
   <td>이메일 전달</td> 
   <td>받는 사람(바운스되지 않음)</td> 
  </tr> 
  <tr> 
   <td>이메일 열림</td> 
   <td>이메일 열기(이미지 차단 안 함)</td> 
  </tr> 
  <tr> 
   <td>이메일에서 클릭한 링크</td> 
   <td>Marketing To가 보낸 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>목록에서 제거됨</td> 
   <td>흐름 단계:정적 목록에서 제거됨</td> 
  </tr> 
  <tr> 
   <td>흐름에서 제거</td> 
   <td>흐름 단계:흐름에서 제거</td> 
  </tr> 
  <tr> 
   <td>이메일 전송</td> 
   <td>Marketing To Sales Insight를 통해 이메일 전송</td> 
  </tr> 
  <tr> 
   <td>영업 이메일 열림</td> 
   <td>Marketing to Sales Insight를 통해 보낸 이메일 열기</td> 
  </tr> 
  <tr> 
   <td>영업 이메일의 링크를 클릭합니다.</td> 
   <td>Marketing to Sales Insight를 통해 전송된 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>받은 영업 이메일</td> 
   <td>MSI Outlook 플러그인의 Sales 담당자가 이메일을 수신하고 로깅했습니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>**미리 알림**
>
>
>&quot;받은 세일즈 이메일&quot;은 전달을 의미하지 **않습니다** . Sales Insight를 통해 전송된 이메일에 대해 배달된 상태가 캡처되지 않습니다.

>[!TIP]
>
>Salesforce에 더 많은 Marketing To 정보를 제공하려면 Adobe Marketing [To Sales Insight 제품을](../../../../../product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) 확인하십시오.


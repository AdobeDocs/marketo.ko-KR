---
unique-page-id: 4719294
description: 활동 동기화 사용자 정의 - Marketo 문서 - 제품 설명서
title: 활동 동기화 사용자 지정
exl-id: 938d83dc-b9b1-41d8-bf98-04548b074ec4
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# 활동 동기화 사용자 지정 {#customize-activities-sync}

Marketo Sales Insight를 사용하지 않는 경우 Marketo에서 특정 이벤트에 대한 Salesforce 활동 내역 레코드를 만들 수 있습니다. 이를 구현하는 방법을 설명합니다.

1. **관리**&#x200B;로 이동합니다.

   ![](assets/admin.png)

1. **Salesforce**&#x200B;를 클릭한 다음 **동기화 옵션 편집**&#x200B;을 클릭합니다.

   ![](assets/two-1.png)

1. Marketo에서 Salesforce로 푸시할 활동 옆의 상자를 선택하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >활성화되면 Marketo은 3개월 분량의 활동 내역을 푸시합니다. 데이터의 양에 따라 _이(가) 완료하는 데 몇 일 정도 걸릴 수 있습니다_. 초기 활동 푸시 중에 발생하는 업데이트는 초기 활동 동기화가 완료될 때까지 지연될 수 있습니다.

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
   <td>채워진 양식</td> 
   <td>Marketo 양식 작성</td> 
  </tr> 
  <tr> 
   <td>목록에 추가됨</td> 
   <td><p>흐름 단계:정적 목록에 추가됨</p></td> 
  </tr> 
  <tr> 
   <td>보낸 이메일</td> 
   <td>흐름 단계:전자 메일을 보냈습니다.</td> 
  </tr> 
  <tr> 
   <td>배달된 이메일</td> 
   <td>받은 이메일(반송되지 않음)</td> 
  </tr> 
  <tr> 
   <td>이메일 열림</td> 
   <td>이메일 열기(이미지 차단 없이)</td> 
  </tr> 
  <tr> 
   <td>이메일에서 클릭한 링크</td> 
   <td>Marketo이 보낸 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>목록에서 제거됨</td> 
   <td>흐름 단계:정적 목록에서 제거되었습니다.</td> 
  </tr> 
  <tr> 
   <td>흐름에서 제거</td> 
   <td>흐름 단계:흐름에서 제거</td> 
  </tr> 
  <tr> 
   <td>전송된 영업 이메일</td> 
   <td>Marketo Sales Insight를 통해 이메일 전송</td> 
  </tr> 
  <tr> 
   <td>영업 이메일 열림</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일을 열었습니다.</td> 
  </tr> 
  <tr> 
   <td>영업 이메일의 링크를 클릭합니다.</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>받은 영업 이메일</td> 
   <td>MSI Outlook 플러그인의 판매 담당자가 이메일을 수신하고 로깅했습니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>&quot;받은 영업 이메일&quot;은 **배달되지 않음**&#x200B;을 의미합니다. Sales Insight를 통해 전송된 이메일에 대해 배달된 상태가 캡처되지 않습니다.

>[!TIP]
>
>Salesforce에 Marketo 정보를 더 많이 제공하려면 [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) 제품을 확인하십시오.

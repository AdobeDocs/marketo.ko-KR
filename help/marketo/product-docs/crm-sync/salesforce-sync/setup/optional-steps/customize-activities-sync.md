---
unique-page-id: 4719294
description: 활동 동기화 사용자 지정 - Marketo 문서 - 제품 설명서
title: 활동 동기화 사용자 지정
exl-id: 938d83dc-b9b1-41d8-bf98-04548b074ec4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# 활동 동기화 사용자 지정 {#customize-activities-sync}

Marketo Sales Insight를 사용하지 않는 경우 Marketo에서 특정 이벤트에 대한 Salesforce 활동 기록 레코드를 만들 수 있습니다. 이러한 기능을 활성화하는 방법은 다음과 같습니다.

1. 이동 **관리**.

   ![](assets/admin.png)

1. 클릭 **Salesforce**&#x200B;를 클릭한 다음 **동기화 옵션 편집**.

   ![](assets/two-1.png)

1. Salesforce에 푸시할 활동 옆에 있는 상자를 선택하고 를 클릭합니다 **저장**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >활성화되면 Marketo은 3개월 동안의 활동 내역을 푸시합니다. 데이터의 양에 따라, _이 작업을 완료하는 데 며칠이 걸릴 수 있습니다._. 초기 활동 푸시 중에 발생하는 업데이트는 초기 활동 동기화가 완료된 후까지 지연될 수 있습니다.

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
   <td>양식 입력됨</td> 
   <td>모든 Marketo 양식 채우기</td> 
  </tr> 
  <tr> 
   <td>목록에 추가됨</td> 
   <td><p>흐름 단계: 정적 목록에 추가되었습니다.</p></td> 
  </tr> 
  <tr> 
   <td>보낸 이메일</td> 
   <td>흐름 단계: 이메일 전송</td> 
  </tr> 
  <tr> 
   <td>배달된 이메일</td> 
   <td>이메일 수신(바운스되지 않음)</td> 
  </tr> 
  <tr> 
   <td>전자 메일 열림</td> 
   <td>이미지를 차단하지 않고 이메일을 열었습니다.</td> 
  </tr> 
  <tr> 
   <td>이메일에 있는 링크를 클릭함</td> 
   <td>Marketo에서 보낸 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>목록에서 제거됨</td> 
   <td>흐름 단계: 정적 목록에서 제거되었습니다.</td> 
  </tr> 
  <tr> 
   <td>흐름에서 제거</td> 
   <td>흐름 단계: 흐름에서 제거</td> 
  </tr> 
  <tr> 
   <td>보낸 영업 전자 메일</td> 
   <td>Marketo Sales Insight를 통해 이메일이 전송되었습니다</td> 
  </tr> 
  <tr> 
   <td>영업 전자 메일 열림</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일을 열었습니다.</td> 
  </tr> 
  <tr> 
   <td>영업 이메일의 링크를 클릭합니다.</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>판매 전자 메일 수신</td> 
   <td>MSI Outlook 플러그인의 영업 사원이 전자 메일을 받고 로그인했습니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>&quot;받은 영업 이메일&quot;은 **not** 배달되는 평균입니다. Sales Insight를 통해 전송된 이메일에 대해 게재된 상태는 캡처되지 않습니다.

>[!TIP]
>
>Salesforce에 Marketo 정보를 더 많이 제공하려면 Adobe에서 [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) 제품.

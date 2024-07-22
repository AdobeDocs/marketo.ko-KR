---
unique-page-id: 4719294
description: 활동 동기화 사용자 지정 - Marketo 문서 - 제품 설명서
title: 활동 동기화 사용자 지정
exl-id: 938d83dc-b9b1-41d8-bf98-04548b074ec4
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# 활동 동기화 사용자 지정 {#customize-activities-sync}

Marketo Sales Insight를 사용하지 않는 경우에는 Marketo Engage이 특정 이벤트에 대한 Salesforce 활동 기록 레코드를 만들 수 있습니다. 활성화 방법은 다음과 같습니다.

1. **[!UICONTROL 관리자]**(으)로 이동합니다.

   ![](assets/admin.png)

1. **[!DNL Salesforce]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL 동기화 옵션 편집]**&#x200B;을 클릭합니다.

   ![](assets/two-1.png)

1. Marketo에서 Salesforce로 푸시할 활동 옆의 확인란을 선택하고 **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >활성화되면 Marketo은 3개월 분량의 활동 내역을 푸시합니다. 데이터의 양에 따라 _완료하는 데 며칠이 걸릴 수 있습니다_. 초기 활동 푸시 동안 발생하는 업데이트는 초기 활동 동기화가 완료될 때까지 지연될 수 있습니다.

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
   <td>작성된 양식</td> 
   <td>모든 Marketo 양식을 작성했습니다.</td> 
  </tr> 
  <tr> 
   <td>목록에 추가됨</td> 
   <td><p>흐름 단계: 정적 목록에 추가되었습니다.</p></td> 
  </tr> 
  <tr> 
   <td>이메일 전송됨</td> 
   <td>흐름 단계: 이메일이 전송됨</td> 
  </tr> 
  <tr> 
   <td>이메일 전달됨</td> 
   <td>이메일 수신(반송 안 함)</td> 
  </tr> 
  <tr> 
   <td>이메일 열림</td> 
   <td>이메일을 열었습니다(이미지를 차단하지 않음).</td> 
  </tr> 
  <tr> 
   <td>이메일의 클릭한 링크</td> 
   <td>Marketo에서 보낸 이메일의 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>목록에서 제거됨</td> 
   <td>흐름 단계: 정적 목록에서 제거됨</td> 
  </tr> 
  <tr> 
   <td>플로우에서 제거</td> 
   <td>흐름 단계: 흐름에서 제거</td> 
  </tr> 
  <tr> 
   <td>영업 이메일 전송됨</td> 
   <td>Marketo Sales Insight를 통해 이메일을 보냈습니다.</td> 
  </tr> 
  <tr> 
   <td>영업 이메일 열림</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일을 열었습니다.</td> 
  </tr> 
  <tr> 
   <td>영업 이메일에서 링크 클릭</td> 
   <td>Marketo Sales Insight를 통해 전송된 이메일에서 링크를 클릭함</td> 
  </tr> 
  <tr> 
   <td>영업 이메일 수신됨</td> 
   <td>MSI Outlook 플러그인의 영업 담당자가 이메일을 수신하여 기록했습니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>&quot;받은 판매 전자 메일&quot;은 배달된 것을 의미하지 _않습니다_. Sales Insight를 통해 전송된 이메일에는 게재됨 상태가 캡처되지 않습니다.

>[!TIP]
>
>Salesforce에 더 많은 Marketo 정보를 가져오려면 [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md){target="_blank"} 제품을 확인하십시오.

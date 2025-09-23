---
description: Salesforce에 판매 활동 속성 로깅 - Marketo 문서 - 제품 설명서
title: 세일즈 활동 속성을 Salesforce에 로깅
exl-id: fdefe53b-eb99-48ce-a04e-3666be33fea4
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '225'
ht-degree: 14%

---

# [!DNL Salesforce]에 판매 활동 특성 로깅 중 {#logging-sales-activity-attributes-to-salesforce}

Salesforce 관리자는 사용자 지정 활동 필드를 [!DNL Salesforce]에 수동으로 추가할 수 있습니다.

1. [!DNL Salesforce] 계정에서 **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

1. 빠른 검색 필드에서 &quot;활동 사용자 정의 필드&quot;를 검색하고 클릭합니다.

1. **[!UICONTROL New]**&#x200B;를 클릭합니다.

1. 아래 표에 따라 추가할 필드에 해당하는 데이터 형식을 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

1. 추가할 필드에 해당하는 필드 이름과 레이블을 입력합니다.

아래 표의 각 열에 대한 설명:

* **필드 레이블**: UI에 표시되는 필드 이름(팀에서 가독성을 개선하기 위해 이 이름을 사용자 지정할 수 있음)
* **필드 이름**: 필드의 기술적 이름(입력한 필드 이름이 아래 표의 필드 이름과 일치하는지 확인)
* **API 이름**: API에 대한 필드의 기술적 이름(입력한 API 이름이 아래 표의 API 이름과 일치하는지 확인)
* **데이터 형식**: 필드의 형식
* **크기**: 텍스트 필드의 크기

<table>
 <tr>
  <th>필드 레이블</th>
  <th>필드 이름</th>
  <th>API 이름</th>
  <th>데이터 유형</th>
  <th>크기</th>
 </tr>
  <tr>
  <td>[!UICONTROL Call Outcomes]</td>
  <td>mktosales_call_result</td>
  <td>mktosales_call_result__c</td>
  <td>텍스트</td>
  <td>50</td>
 </tr>
 <tr>
  <td>[!UICONTROL Call Reasons]</td>
  <td>mktosales_call_reason</td>
  <td>mktosales_call_reason__c</td>
  <td>텍스트</td>
  <td>50</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Call Local Presence ID]</td>
  <td>MSE_Call_Local_Presence_ID</td>
  <td>MSE_Call_Local_Presence_ID__c</td>
  <td>텍스트</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Call Recording URL]</td>
  <td>MSE_Call_Recording</td>
  <td>MSE_Call_Recording__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign]</td>
  <td>MSE_캠페인</td>
  <td>MSE_Campaign __c</td>
  <td>텍스트</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign Current Step]</td>
  <td>MSE_Current_Campaign_Step</td>
  <td>MSE_Current_Campaign_Step__c</td>
  <td>텍스트</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Campaign URL]</td>
  <td>MSE_Campaign_Details_Link</td>
  <td>MSE_Campaign_Details_Link__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Attachment Viewed]</td>
  <td>MSE_Presentation_Viewed</td>
  <td>MSE_Presentation_Viewed__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Clicked]</td>
  <td>MSE_Clicked</td>
  <td>MSE_Clicked__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Replied]</td>
  <td>MSE_회신함</td>
  <td>MSE_Replaced__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Status]</td>
  <td>MSE_Email_Status</td>
  <td>MSE_Email_Status__c</td>
  <td>텍스트</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Template]</td>
  <td>MSE_Template</td>
  <td>MSE_Template__c</td>
  <td>텍스트</td>
  <td>255</td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Template URL]</td>
  <td>MSE_Template_Details</td>
  <td>MSE_Template_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email URL]</td>
  <td>MSE_Details</td>
  <td>MSE___c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>[!UICONTROL Marketo Sales Email Viewed]</td>
  <td>MSE_Viewed</td>
  <td>MSE_Viewed__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
</table>

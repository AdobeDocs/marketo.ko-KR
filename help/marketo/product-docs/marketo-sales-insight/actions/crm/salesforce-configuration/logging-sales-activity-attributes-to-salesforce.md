---
description: Salesforce에 판매 활동 속성 로깅 - Marketo 문서 - 제품 설명서
title: Salesforce에 영업 활동 속성 로깅
exl-id: fdefe53b-eb99-48ce-a04e-3666be33fea4
source-git-commit: 9f3b91e7b0626b2a229f4a98fb734e926a141ec0
workflow-type: tm+mt
source-wordcount: '363'
ht-degree: 3%

---

# Salesforce에 영업 활동 속성 로깅 {#logging-sales-activity-attributes-to-salesforce}

Salesforce 관리자는 Salesforce에 사용자 지정 활동 필드를 수동으로 추가할 수 있습니다.

1. Salesforce 계정에서 **설정**.

1. 빠른 검색 필드에서 &quot;활동 사용자 지정 필드&quot;를 검색하고 클릭합니다.

1. 클릭 **새로 만들기**.

1. 아래 표를 기반으로 추가할 필드에 해당하는 데이터 유형을 선택하고 를 클릭합니다 **다음**.

1. 추가할 필드에 해당하는 필드 이름과 레이블을 입력합니다.

아래 표에서 각 열에 대한 설명:

* **필드 레이블**: UI에 표시되는 필드 이름(팀이 읽기 쉽게 사용할 수 있도록 이 이름을 사용자 지정할 수 있음)
* **필드 이름**: 필드의 기술 이름(입력하는 필드 이름이 아래 테이블의 필드 이름과 일치하는지 확인)
* **API 이름**: API용 필드의 기술 이름(입력하는 API 이름이 아래 테이블의 API 이름과 일치하는지 확인)
* **데이터 유형**: 필드 유형
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
  <td>통화 결과</td>
  <td>mktosales_call_result</td>
  <td>mktosales_call_result__c</td>
  <td>텍스트</td>
  <td>50</td>
 </tr>
 <tr>
  <td>통화 이유</td>
  <td>mktosales_call_reason</td>
  <td>mktosales_call_reason__c</td>
  <td>텍스트</td>
  <td>50</td>
 </tr>
 <tr>
  <td>Marketo 영업 호출 로컬 현재 상태 ID</td>
  <td>MSE_Call_Local_Presence_ID</td>
  <td>MSE_Call_Local_Presence_ID__c</td>
  <td>텍스트</td>
  <td>255년</td>
 </tr>
 <tr>
  <td>Marketo 영업 호출 기록 URL</td>
  <td>MSE_Call_Recording</td>
  <td>MSE_Call_Recording__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo 영업 캠페인</td>
  <td>MSE_Campaign</td>
  <td>MSE_Campaign__c</td>
  <td>텍스트</td>
  <td>255년</td>
 </tr>
 <tr>
  <td>Marketo 영업 캠페인 현재 단계</td>
  <td>MSE_Current_Campaign_Step</td>
  <td>MSE_Current_Campaign_Step__c</td>
  <td>텍스트</td>
  <td>255년</td>
 </tr>
 <tr>
  <td>Marketo 영업 캠페인 URL</td>
  <td>MSE_Campaign_Details_Link</td>
  <td>MSE_Campaign_Details_Link__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email 첨부 파일 조회</td>
  <td>MSE_Presentation_Viewed</td>
  <td>MSE_Presentation_Viewed__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>클릭한 Marketo 영업 이메일</td>
  <td>MSE_Clicked</td>
  <td>MSE_Clicked__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo 판매 전자 메일 회신됨</td>
  <td>MSE_Resolved</td>
  <td>MSE_Resolved__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo 영업 이메일 상태</td>
  <td>MSE_Email_Status</td>
  <td>MSE_Email_Status__c</td>
  <td>텍스트</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo 영업 이메일 템플릿</td>
  <td>MSE_Template</td>
  <td>MSE_Template__c</td>
  <td>텍스트</td>
  <td>255년</td>
 </tr>
 <tr>
  <td>Marketo 영업 이메일 템플릿 URL</td>
  <td>MSE_Template_Details</td>
  <td>MSE_Template_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo 영업 이메일 URL</td>
  <td>MSE_Details</td>
  <td>MSE_Details__c</td>
  <td>URL</td>
  <td></td>
 </tr>
 <tr>
  <td>Marketo Sales Email 조회</td>
  <td>MSE_Viewed</td>
  <td>MSE_Viewed__c</td>
  <td>확인란</td>
  <td></td>
 </tr>
</table>

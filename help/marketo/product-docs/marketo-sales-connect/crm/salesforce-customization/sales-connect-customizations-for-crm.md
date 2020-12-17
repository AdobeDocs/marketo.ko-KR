---
unique-page-id: 14745793
description: CRM용 Sales Connect Customization - Marketing To Docs - 제품 설명서
title: CRM용 Sales Connect 사용자 지정
translation-type: tm+mt
source-git-commit: 07ae1b3f3ee3e9d7f35373eea039d336bd786f97
workflow-type: tm+mt
source-wordcount: '641'
ht-degree: 0%

---


# CRM {#sales-connect-customizations-for-crm}에 대한 Sales Connect 사용자 지정

아래의 필드 및 단추는 Salesforce CRM의 메타데이터 API를 통해 만들어집니다. 필드가 만들어지면 관리자는 CRM에서 페이지 레이아웃을 구성하여 노출시켜야 합니다. 지침은 [여기](http://docs.marketo.com/display/docs/assets/marketo-sales-engage-for-salesforce-installation-and-success-guide.pdf)에 있습니다.

>[!NOTE]
>
>ToutApp 및 Sales Connect 고객 모두에 영향을 줍니다.

## Salesforce {#how-to-install-customizations-in-salesforce}에서 사용자 정의 설치 방법

1. Sales Connect에서 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one.png)

1. 관리 설정에서 **Salesforce**&#x200B;를 선택합니다.

   ![](assets/two.png)

1. **Marketing To Sales Connect Customizations**&#x200B;를 클릭합니다.

   ![](assets/three.png)

1. **Salesforce 연결**&#x200B;을 클릭합니다.

   ![](assets/four.png)

1. Salesforce에 로그인

   ![](assets/five.png)

## 사용자 지정 활동 필드 {#custom-activity-fields}

Marketing To는 새 필드 만들기를 감지한 다음 데이터의 1회 채우기, 다시 매핑 및 값의 지속적인 동기화를 **new** 필드에만 수행합니다. 이전 필드는 업데이트되지 않습니다.

| **필드 이름** | **설명** |
|---|---|
| MSE에 로컬 현재 상태 ID 호출 | 사용자는 MSE Phone에서 전화를 할 때 옵션으로 로컬 현재 상태를 선택할 수 있습니다. 들어오는 호출에는 수신자의 로컬 번호가 표시됩니다. |
| MSE 호출 기록 URL | 호출을 기록할 수 있으며 레코딩에 대한 링크가 여기에 기록됩니다. |
| MSE 캠페인 | 연락처/리드가 구성원으로 있는 MSE 캠페인의 로그 이름입니다. |
| MSE 캠페인 URL | MSE에서 만든 캠페인에 URL을 기록합니다. 이 아이콘을 클릭하면 MSE 웹 앱에서 캠페인이 열립니다. |
| MSE 캠페인 현재 단계 | 연락처/리드가 캠페인의 일부인 경우 이 필드는 리드/담당자가 현재 있는 단계의 이름을 기록합니다. |
| MSE 이메일 첨부 파일 조회 | 첨부 파일이 있는 이메일을 보내고 수신자가 첨부 파일을 볼 때 데이터를 기록합니다. |
| MSE 이메일 클릭됨 | 수신자가 이메일의 링크를 클릭할 때 확인 표시를 기록합니다. |
| MSE 이메일 회신 | 수신자가 이메일에 회신할 때 확인 표시를 기록합니다. |
| MSE 이메일 상태 | 바운스된 이메일이 전송/진행 중/반송되었는지 여부를 표시합니다(바운스된 이메일 추적은 사용된 전달 채널에 따라 다름). |
| MSE 이메일 템플릿 | 리드/연락처로 보낸 이메일에 사용된 MSE 템플릿의 로그 이름입니다. |
| MSE 이메일 템플릿 URL | MSE에서 만든 템플릿에 URL을 기록합니다. 이 아이콘을 클릭하면 MSE 웹 앱에서 템플릿이 열립니다. |
| MSE 이메일 URL | 이 URL을 클릭하면 MSE의 명령 센터가 열리고 보낸 이메일을 볼 수 있는 사람 세부 사항 보기 내역 탭이 열립니다. |
| MSE 조회한 이메일 | 수신자가 이메일을 볼 때 확인 표시를 기록합니다. |

## 롤업 로깅 필드 {#roll-up-logging-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>필드 이름</strong></td> 
   <td><strong>설명</strong></td> 
  </tr> 
  <tr> 
   <td>MSE - 마지막 마케팅 참여</td> 
   <td>마케팅에서 마지막으로 들어오는 참여. </td> 
  </tr> 
  <tr> 
   <td>MSE - 마지막 마케팅 참여 날짜</td> 
   <td>마케팅의 참여 타임스탬프</td> 
  </tr> 
  <tr> 
   <td>MSE - 마지막 마케팅 참여 설명</td> 
   <td>참여 설명입니다.</td> 
  </tr> 
  <tr> 
   <td>MSE - 마지막 마케팅 참여 소스</td> 
   <td>마케팅 참여 출처.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 마지막 마케팅 참여 유형</td> 
   <td colspan="1">참여 유형.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 판매별 마지막 활동<br></td> 
   <td colspan="1">영업 팀이 수행한 마지막 나가는 활동.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 마지막 응답</td> 
   <td colspan="1">세일즈 이메일에 대한 마지막 이메일 회신.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 현재 판매 캠페인</td> 
   <td colspan="1">리드/연락처가 구성원으로 있는 MSE 캠페인의 로그 이름입니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 마지막 판매 참여</td> 
   <td colspan="1">판매에서 들어오는 마지막 참여. </td> 
  </tr> 
  <tr> 
   <td colspan="1">MSE - 옵트아웃</td> 
   <td colspan="1">옵트아웃 필드.</td> 
  </tr> 
 </tbody> 
</table>

## 단추 {#buttons}

| **단추 이름** | **설명** |
|---|---|
| MSE 이메일 보내기 | Salesforce에서 세일즈 이메일 전송 |
| MSE 캠페인에 추가 | Salesforce의 MSE 캠페인에 추가합니다. |
| MSE로 푸시 | Salesforce에서 MSE로 연락처 푸시 |
| 전화 문의(MSE) | Salesforce에서 세일즈 요청 |

## 벌크 작업 단추 {#bulk-action-buttons}

| **단추 이름** | **설명** |
|---|---|
| MSE 캠페인에 추가 | Salesforce의 MSE 캠페인에 추가합니다. |
| MSE로 푸시 | Salesforce에서 MSE로 연락처 푸시 |

## 사용자 안내서 {#user-guides}

[Salesforce의 MSE 사용자 지정 보고서](http://docs.marketo.com/display/docs/assets/mse-custom-reports-in-sf.docx)

[Salesforce용 MSE](http://docs.marketo.com/display/docs/assets/mse-for-sf-classic.pdf)

[Salesforce Lightning용 MSE](http://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf)

## 관련 비디오 {#related-videos}

**Salesforce**에서 사용자 정의**
`<iframe width="630" height="470" src="//play.vidyard.com/YEPWYBfFEa4nKCo2F6bKKc.html?v=3.1.1" frameborder="0" allowfullscreen></iframe>`  기능을 설치하는 방법 Salesforce에서 사용자 정의 기능을 사용할 수 있는 이점** 
`<iframe width="630" height="470" src="//play.vidyard.com/4PzSDb6o8Qg8WbvBsq8wJD.html?v=3.1.1" frameborder="0" allowfullscreen></iframe>`
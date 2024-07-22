---
description: Salesforce 활동 세부 정보 사용자 지정 구성 - Marketo 문서 - 제품 설명서
title: Salesforce 활동 세부 정보 사용자 지정 구성
exl-id: 534ebdb5-7a5b-48eb-98f7-2d05a9eae8e8
feature: Sales Insight Actions
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '699'
ht-degree: 1%

---

# Salesforce 활동 세부 정보 사용자 지정 구성 {#configure-salesforce-activity-detail-customization}

>[!PREREQUISITES]
>
>* Salesforce 및 Sales Insight 작업 [이(가) 연결되어 있어야 함](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/connect-your-sales-insight-actions-account-to-salesforce.md)
>* API를 통해 전자 메일 활동을 로깅하려면 [을(를) 사용하도록 설정해야 합니다](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md)

활동 세부 사항 사용자 지정을 사용하면 관리자는 Sales Insight Actions 활동/미리 알림 작업이 Salesforce에 동기화될 때 Salesforce 작업 - 제목 필드에 기록할 정보를 구성할 수 있습니다.

>[!NOTE]
>
>* Activity Detail 사용자 지정에서 `{{activity_subject}}` 동적 필드를 사용하는 경우 미리 알림 작업의 Sales Insight 작업 제목 필드에 대한 업데이트가 해당 Salesforce 작업의 제목 필드에 반영됩니다.
>* Salesforce 제목 필드에 정보를 기록할 때 줄 바꿈이 지원되지 않습니다. 영업 작업 주체가 업데이트되면 Activity Detail Customization 편집기의 모든 줄 바꿈이 제거됩니다.

![](assets/configure-salesforce-activity-detail-customization-1.png)

![](assets/configure-salesforce-activity-detail-customization-2.png)

<table>
 <tr>
  <td><strong>1</td>
  <td>InMail 미리 알림 작업</td>
 </tr>
 <tr>
  <td><strong>2</td>
  <td>이메일 활동</td>
 </tr>
 <tr>
  <td><strong>3</td>
  <td>호출 활동</td>
 </tr>
</table>

이 기능은 다음과 같은 이점을 활용하는 데 사용할 수 있습니다.

* 제목 필드에 표시되는 정보를 사용자 정의하여 Salesforce의 판매에 대한 활동 세부 정보를 쉽게 스캔할 수 있습니다.
* 관리자는 제목 필드에 &quot;Mkto_sales&quot;와 같은 고유 식별자로 태그를 지정할 수 있으므로 Sales Insight Actions 의 활동을 다른 이메일 활동, 호출 활동 및 작업과 쉽게 식별하고 구분할 수 있습니다.
* 사용자 지정 활동 필드의 필요성을 줄입니다. Salesforce에서는 보고서에 사용할 수 있는 데이터를 제한할 수 있는 사용자 지정 활동 필드 수에 대한 제한을 적용합니다. 활동 동적 필드를 사용하여 제목 줄에 주요 데이터를 추가하면 Salesforce 인스턴스에서 생성해야 하는 사용자 지정 활동 필드의 수를 줄일 수 있습니다.
* 활동 및 작업의 주제 필드는 Sales Insight 작업 관리자가 정의한 일관된 패턴을 따릅니다.

>[!NOTE]
>
>이메일 답글을 Salesforce에 활동으로 기록하는 경우 Salesforce 활동 세부 정보 사용자 지정 설정을 사용하지 않습니다. 대신 &quot;회신: 이메일 제목&quot;으로 기록됩니다.

## 활동 동적 필드 지원됨 {#activity-dynamic-fields-supported}

활동 동적 필드는 데이터를 채우기 위한 판매 활동에 대한 정보를 참조합니다. 현재는 Salesforce 활동 세부 사항 사용자 지정에 사용할 수 있습니다.

>[!NOTE]
>
>특정 활동/작업에 대한 동적 필드를 채울 값이 없는 경우 Salesforce 작업 - 제목 필드가 업데이트되면 해당 동적 필드에 대한 데이터를 채우지 않습니다.

<table>
 <tr>
  <th>필드</th>
  <th>설명</th>
 </tr>
 <tr>
  <td>{{activity_type}}</td>
  <td>작업 유형이 이메일, 호출, InMail 또는 사용자 지정으로 채워집니다.</td>
 </tr>
 <tr>
  <td>{{activity_subject}}</td>
  <td><p>작업의 제목을 채웁니다.</p>
      <p>이메일의 경우 이메일의 제목 줄이 채워집니다.</p>
      <p>호출, inMail 또는 사용자 지정의 경우 작업 이름/제목 필드에 값으로 만든 미리 알림 작업이 있으면 값이 채워집니다.</p></td>
 </tr>
 <tr>
  <td>{{sales_campaign_name}}</td>
  <td>활동이 판매 캠페인에서 시작된 경우 판매 캠페인의 이름이 채워집니다.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_day}}</td>
  <td>활동이 판매 캠페인에서 시작된 경우 이 활동이 발생한 판매 캠페인 일자 번호가 채워집니다.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_step}}</td>
  <td>활동이 판매 캠페인에서 시작된 경우, 이 활동이 발생한 영업 캠페인 일자 내에 단계 번호가 채워집니다.</td>
 </tr>
 <tr>
  <td>{{call_outcome}}</td>
  <td>활동이 호출이고 호출 결과가 선택된 경우 호출 결과 값이 채워집니다.</td>
 </tr>
 <tr>
  <td>{{call_reason}}</td>
  <td>활동이 호출이고 호출 사유를 선택한 경우, 호출 사유 값이 채워집니다.</td>
 </tr>
</table>

## Salesforce 활동 세부 정보 사용자 지정 구성 {#configuring-salesforce-activity-detail-customization}

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

활동 세부 사항을 구성할 때는 Salesforce의 작업 내역을 검토할 때 매출과 가장 관련이 있는 데이터를 고려하십시오.

1. 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/configure-salesforce-activity-detail-customization-3.png)

1. **Salesforce**&#x200B;을(를) 클릭합니다.

   ![](assets/configure-salesforce-activity-detail-customization-4.png)

1. **동기화 설정**&#x200B;을 클릭합니다.

   ![](assets/configure-salesforce-activity-detail-customization-5.png)

1. 활동 세부 사항 사용자 지정 편집기에서 원하는 자유 텍스트를 추가합니다. 추가하는 텍스트는 비동적이며 Salesforce에 동기화된 모든 작업의 제목 필드에 대해 변경되지 않습니다.

   ![](assets/configure-salesforce-activity-detail-customization-6.png)

   >[!TIP]
   >
   >필수는 아니지만, 추가된 텍스트를 꺾쇠 괄호로 묶으면 일부 사람들이 Salesforce의 제목 필드에 데이터를 입력할 때 해당 데이터를 보다 쉽게 구분할 수 있습니다. 예: `[Sales Insight Actions] - {{Activity_type}}`

1. **동적 필드 추가** 단추를 클릭하여 원하는 동적 필드를 추가합니다.

   ![](assets/configure-salesforce-activity-detail-customization-7.png)

1. 원하는 동적 필드를 선택합니다.

   ![](assets/configure-salesforce-activity-detail-customization-8.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/configure-salesforce-activity-detail-customization-9.png)

>[!NOTE]
>
>Salesforce에서는 255자로 제한됩니다. 활동 세부 사항이 이를 초과하면 정보가 Salesforce 제목 필드에 저장되도록 잘립니다.

>[!MORELIKETHIS]
>
>* [영업 활동을 Salesforce에 동기화](/help/marketo/product-docs/marketo-sales-insight/actions/crm/salesforce-integration/sync-sales-activities-to-salesforce.md)
>* [Salesforce와 작업 동기화 알림](/help/marketo/product-docs/marketo-sales-insight/actions/tasks/reminder-task-sync-with-salesforce.md)

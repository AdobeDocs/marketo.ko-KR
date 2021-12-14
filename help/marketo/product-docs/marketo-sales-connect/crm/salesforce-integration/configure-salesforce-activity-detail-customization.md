---
description: Salesforce 활동 세부 정보 사용자 지정 구성 - Marketo 문서 - 제품 설명서
title: Salesforce 활동 세부 사항 사용자 지정 구성
hide: true
hidefromtoc: true
exl-id: 4b20ca29-18d6-4026-9bf9-77656ad1442d
source-git-commit: 87f43fb58b5739c0465a1a74fb60cdf5c5f6b759
workflow-type: tm+mt
source-wordcount: '573'
ht-degree: 0%

---

# Salesforce 활동 세부 사항 사용자 지정 구성 {#configure-salesforce-activity-detail-customization}

Activity Detail Customization을 사용하면 관리자는 Sales Connect 활동/미리 알림 작업이 Salesforce에 동기화될 때 Salesforce 작업 - 제목 필드에 로그인할 정보를 구성할 수 있습니다.

![](assets/configure-salesforce-activity-detail-customization-1.png)

![](assets/configure-salesforce-activity-detail-customization-2.png)

<table>
 <tr>
  <td><strong>1</td>
  <td>인메일 미리 알림 작업</td>
 </tr>
 <tr>
  <td><strong>2개</td>
  <td>이메일 활동</td>
 </tr>
 <tr>
  <td><strong>3</td>
  <td>통화 활동</td>
 </tr>
</table>

이 기능을 사용하여 다음과 같은 이점을 잠금 해제할 수 있습니다.

* 제목 필드에 표시되는 정보를 사용자 지정함으로써 Salesforce에서 영업을 위해 활동 세부 사항을 쉽게 확장할 수 있습니다.
* 관리자는 제목 필드에 &quot;Mkto_sales&quot;와 같은 고유한 식별자를 태깅하여 Sales Connect의 활동을 쉽게 식별하고 다른 이메일 활동, 호출 활동 및 작업과 구별할 수 있습니다.
* 사용자 지정 활동 필드의 필요성을 줄입니다. Salesforce에서는 사용자 지정 활동 필드 수에 제한을 적용하여 보고서에서 사용할 수 있는 데이터를 제한할 수 있습니다. 활동 동적 필드를 사용하여 제목 줄에 주요 데이터를 추가하면 Salesforce 인스턴스에서 만들어야 하는 사용자 지정 활동 필드의 수를 줄일 수 있습니다.
* 활동 및 작업의 제목 필드는 Sales Connect 관리자가 정의한 일관된 패턴을 따릅니다.

## 지원되는 활동 동적 필드 {#activity-dynamic-fields-supported}

활동 동적 필드는 판매 활동에 대한 정보를 참조하여 데이터를 채웁니다. 현재 Salesforce 활동 세부 사항 사용자 지정과 함께 사용할 수 있습니다.

>[!NOTE]
>
>특정 활동/작업에 대한 동적 필드를 채울 값이 없는 경우 Salesforce 작업 - 제목 필드가 업데이트될 때 해당 동적 필드에 대한 데이터를 채우지 않습니다.

<table>
 <tr>
  <th>필드</th>
  <th>설명</th>
 </tr>
 <tr>
  <td>{{activity_type}}</td>
  <td>작업 유형을 이메일, 호출, InMail 또는 Custom으로 채웁니다.</td>
 </tr>
 <tr>
  <td>{{activity_subject}}</td>
  <td><p>작업 제목을 채웁니다.</p>
      <p>이메일의 경우 이메일의 제목란이 채워집니다.</p>
      <p>호출의 경우, inMail 또는 custom의 경우 작업 이름/제목 필드에 값으로 만든 미리 알림 작업이 있는 경우 값이 채워집니다.</p></td>
 </tr>
 <tr>
  <td>{{sales_campaign_name}}</td>
  <td>영업 캠페인에서 활동이 시작된 경우 영업 캠페인의 이름이 채워집니다.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_day}}</td>
  <td>영업 캠페인에서 활동이 시작된 경우 이 활동이 발생한 영업 캠페인 일 번호를 채웁니다.</td>
 </tr>
 <tr>
  <td>{{sales_campaign_step}}</td>
  <td>영업 캠페인에서 활동이 시작된 경우 이 활동이 발생한 영업 캠페인 일 내의 단계 번호를 채웁니다.</td>
 </tr>
 <tr>
  <td>{{call_result}}</td>
  <td>활동이 호출이고 호출 결과를 선택하면 호출 결과 값이 채워집니다.</td>
 </tr>
 <tr>
  <td>{{call_reason}}</td>
  <td>활동이 호출이고 호출 이유가 선택된 경우 호출 사유 값이 채워집니다.</td>
 </tr>
</table>

## Salesforce 활동 세부 정보 사용자 지정 구성 {#configuring-salesforce-activity-detail-customization}

>[!NOTE]
>
>**관리자 권한이 필요합니다.**

활동 세부 사항을 구성할 때 Salesforce에서 작업 내역을 검토할 때 매출과 가장 관련이 있는 데이터를 고려하십시오.

1. 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

PICC

1. 클릭 **Salesforce**.

PICC

1. 클릭 **동기화 설정**.

PICC

1. 활동 세부 사항 사용자 지정 편집기에서 원하는 자유 텍스트를 추가하면 Salesforce에 동기화된 모든 작업의 제목 필드에 대해 변경되지 않습니다.

1. 동적 필드 단추를 클릭하고 목록에서 사용할 동적 필드를 선택하여 추가할 동적 필드를 추가합니다.

1. 클릭 **저장**.

>[!NOTE]
>
>Salesforce에서는 255자 제한을 적용합니다. 활동 세부 사항이 초과되면 Salesforce 제목 필드에 정보를 저장할 수 있도록 잘립니다.

>[!MORELIKETHIS]
>
>* [동기화 설정](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/salesforce-sync-settings.md)
>* [Salesforce와 작업 동기화 미리 알림](/help/marketo/product-docs/marketo-sales-connect/tasks/reminder-task-sync-with-salesforce.md)
>* [CRM용 Sales Connect 사용자 지정](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md)


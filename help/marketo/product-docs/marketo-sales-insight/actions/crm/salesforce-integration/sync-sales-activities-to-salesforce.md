---
description: 영업 활동을 Salesforce에 동기화 - Marketo 문서 - 제품 설명서
title: 영업 활동을 Salesforce에 동기화
exl-id: fa13ced2-6184-485f-a0ef-813ccab4f0fe
source-git-commit: 02354356949aef7aa8836d4753ec538b7819a65a
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 영업 활동을 Salesforce에 동기화 {#sync-sales-activities-to-salesforce}

Salesforce 동기화 설정 작업을 구성하여 Salesforce에 이메일 및 호출 활동을 기록할 수 있습니다. 이렇게 하면 CRM을 사용하여 작업하는 팀에 더 나은 가시성을 제공하고 관리자가 이러한 활동을 사용하여 사용자 정의 Salesforce 보고서를 작성하여 팀 성과를 추적할 수 있습니다.

## API를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-api}

이 기능을 사용하려면 Enterprise/Unlimited 버전의 Salesforce를 사용해야 하며, 웹 서비스 API를 통해 통합을 구입한 경우에는 Professional 버전을 사용해야 합니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Insight Actions 이 연결되어 있어야 합니다.

1. Sales Insight Actions에서 톱니바퀴 아이콘을 클릭하고 **설정**.

   ![](assets/sync-sales-activities-to-salesforce-1.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-2.png)

1. 다음을 클릭합니다. **동기화 설정** 탭.

   ![](assets/sync-sales-activities-to-salesforce-3.png)

1. Salesforce에 이메일 활동 기록 옆에 있는 화살표를 클릭합니다.

   ![](assets/sync-sales-activities-to-salesforce-4.png)

1. 다음을 클릭합니다. **Salesforce API** 탭. 이 카드에서 Salesforce에 정보를 기록하는 기본 설정을 지정할 수 있습니다. 클릭 **저장** 완료 시.

   ![](assets/sync-sales-activities-to-salesforce-5.png)

## BCC(Salesforce에 이메일)를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;Salesforce에 이메일(BCC)&quot;을 활성화하면 판매 이메일의 BCC를 받게 되고 이메일은 기회, 리드 및 연락처에 대한 활동으로 기록됩니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Insight Actions 이 연결되어 있어야 합니다.

**이메일(BCC)을 통해 Salesforce에 이메일을 기록하려면**

1. Marketo Sales에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다. **설정**.

   ![](assets/sync-sales-activities-to-salesforce-6.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-7.png)

1. 다음을 클릭합니다. **동기화 설정** 탭.

   ![](assets/sync-sales-activities-to-salesforce-8.png)

1. 다음을 클릭합니다. **Salesforce로 이메일 보내기(BCC)** tab 키를 누른 다음 클릭 **활성화**.

   ![](assets/sync-sales-activities-to-salesforce-9.png)

어떤 이유로든 Salesforce로 이메일 주소를 가져오지 않는 경우 다음 단계에 따라 Salesforce 계정에서 BCC 기능을 활성화하십시오.

1. Salesforce 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. 선택 **내 설정**.
1. 선택 **이메일**.
1. 선택 **Salesforce에 보낸 내 이메일**.
1. 이 페이지에는 &quot;Salesforce 주소로 이메일&quot;이라는 레이블이 지정된 필드가 표시됩니다. 옆에 채워진 항목이 없으면 아래로 스크롤하여 &quot;허용 가능한 내 이메일 주소&quot;를 표시합니다.
1. 숨은 참조를 보낼 이메일 주소를 입력합니다.
1. 클릭 **변경 내용 저장**.

**내 설정에서 Salesforce로 보내는 내 이메일을 찾을 수 없음**

설정에서 Salesforce로 보내는 내 이메일이 표시되지 않으면 관리자가 활성화하지 않았을 수 있습니다. 이 문제는 팀이 Salesforce를 처음 사용하거나 팀이 Salesforce에서 제공하는 BCC 주소를 사용한 적이 없는 경우 발생할 수 있습니다.

>[!NOTE]
>
>이를 설정하려면 관리자 권한이 필요합니다.

1. 클릭 **설정**.
1. 클릭 **이메일 관리**.
1. 클릭 **Salesforce로 이메일 보내기**.
1. 클릭 **편집**.
1. &quot;활성&quot; 옆에 있는 상자를 선택합니다.
1. 클릭 **저장**.

## Sales Insight 작업 작업/미리 알림을 Salesforce 작업에 동기화 {#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks}

1. Sales Insight Actions에서 톱니바퀴 아이콘을 클릭하고 **설정**.

   ![](assets/sync-sales-activities-to-salesforce-10.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/sync-sales-activities-to-salesforce-11.png)

1. 다음을 클릭합니다. **동기화 설정** 탭.

   ![](assets/sync-sales-activities-to-salesforce-12.png)

1. Marketo 판매 작업/미리 알림을 Salesforce 작업에 동기화 옆에 있는 화살표를 클릭합니다.

   ![](assets/sync-sales-activities-to-salesforce-13.png)

1. 원하는 옵션(&quot;Salesforce 작업에 동기화 안 함&quot;이 기본적으로 선택됨)을 선택합니다.

   ![](assets/sync-sales-activities-to-salesforce-14.png)

## 처음으로 Sales Insight 작업 작업을 Salesforce와 동기화 {#syncing-sales-insight-ations-tasks-with-salesforce-for-the-first-time}

먼저 Sales Insight 작업과 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. Sales Insight Actions에 있는 현재 작업을 Salesforce로 푸시하지 않습니다. 혼란을 줄이고 중복을 줄이기 위해 Sales Insight Actions에서 Salesforce로 동기화되는 작업은 Sales Insight Actions을 SFDC와 동기화한 후에 생성된 작업뿐입니다.

다음은 Sales Insight 작업 및 SFDC 작업을 동기화할 때 수행되는 작업입니다.

* 작업 동기화 시 저장 을 클릭하면 다시 동기화됩니다. 처음에는 시간이 좀 걸릴 것입니다.

* 지난 24시간 동안 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Insight Actions으로 가져옵니다. 동기화는 만기일을 기준으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만, 명령 센터에서는 오늘과 내일의 작업만 표시됩니다.

* 이전에 동기화가 켜져 있고 SFDC에서 작업을 삭제하면 최근 15일 동안 삭제된 모든 작업이 명령 센터에서 삭제됩니다.

* 동기화가 활성화되어 있는 한 Sales Insight Actions 과 SFDC 간에 작업을 지속적으로 동기화합니다.

* 초기 동기화 후 Sales Insight Actions에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록과 동기화됩니다. 또한 Salesforce에서 생성, 편집, 완료 또는 삭제된 모든 항목은 Sales Insight Actions의 작업 목록을 업데이트합니다.

* 이 동기화를 켜려면 웹 응용 프로그램의 설정 페이지에 있는 동기화 상자를 선택하면 됩니다.

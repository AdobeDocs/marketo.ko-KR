---
description: Salesforce 동기화 설정 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 설정
exl-id: fa13ced2-6184-485f-a0ef-813ccab4f0fe
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '709'
ht-degree: 0%

---

# Salesforce 동기화 설정 {#salesforce-sync-settings}

## API를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-api}

이 기능을 사용하려면 Enterprise/Unlimited edition of Salesforce를 사용하고, Web Services API를 통해 통합을 구매한 경우 Professional Edition을 사용해야 합니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Insight Action 은 연결되어 있어야 합니다.

1. Sales Insight Actions에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다. **설정**.

   ![](assets/salesforce-sync-settings-1.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/salesforce-sync-settings-2.png)

1. 을(를) 클릭합니다. **동기화 설정** 탭.

   ![](assets/salesforce-sync-settings-3.png)

1. Salesforce에 이메일 활동 기록 옆에 있는 화살표를 클릭합니다.

   ![](assets/salesforce-sync-settings-4.png)

1. 을(를) 클릭합니다. **Salesforce API** 탭. 이 카드에서 Salesforce에 정보를 로깅하기 위한 기본 설정을 설정할 수 있습니다. 클릭 **저장** 완료 시.

   ![](assets/salesforce-sync-settings-5.png)

## Salesforce에 이메일 활동 로깅(BCC)을 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;Email to Salesforce (BCC)&quot;를 활성화하면 판매 이메일의 숨은 참조를 받게 되고 이메일이 기회, 리드 및 연락처에 대한 활동으로 기록됩니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Insight Action 은 연결되어 있어야 합니다.

**이메일(BCC)을 통해 Salesforce에 이메일을 기록하려면**

1. Marketo Sales에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/salesforce-sync-settings-6.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/salesforce-sync-settings-7.png)

1. 을(를) 클릭합니다. **동기화 설정** 탭.

   ![](assets/salesforce-sync-settings-8.png)

1. 을(를) 클릭합니다. **Salesforce로 이메일 보내기(BCC)** 탭을 클릭하고 **활성화**.

   ![](assets/salesforce-sync-settings-9.png)

일부 이유로 Salesforce에 전자 메일 주소가 가져올 수 없는 경우 다음 단계에 따라 Salesforce 계정에서 BCC 기능을 활성화합니다.

1. Salesforce 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. 선택 **내 설정**.
1. 선택 **이메일**.
1. 선택 **Salesforce에 내 이메일 보내기**.
1. 이 페이지에는 &quot;Email to Salesforce Address&quot;라는 레이블이 지정된 필드가 표시됩니다. 그 옆에 채워지지 않은 것이 있으면 아래로 스크롤하여 &quot;My Acceptable Email Addresses&quot;로 이동합니다.
1. 숨은 참조를 원하는 이메일 주소를 입력합니다.
1. 클릭 **변경 내용 저장**.

**내 설정에서 Salesforce에 전자 메일을 찾을 수 없음**

설정 아래에 Salesforce에 내 이메일이 표시되지 않으면 관리자가 이를 활성화하지 않았을 수 있습니다. 팀이 Salesforce를 처음 사용하거나 팀이 Salesforce에서 제공하는 BCC 주소를 사용하지 않은 경우 이러한 문제가 발생할 수 있습니다.

>[!NOTE]
>
>이 설정을 사용하려면 관리자 권한이 필요합니다.

1. 클릭 **설정**.
1. 클릭 **이메일 관리**.
1. 클릭 **Salesforce에 이메일 보내기**.
1. 클릭 **편집**.
1. &quot;활성&quot; 옆의 상자를 선택합니다.
1. 클릭 **저장**.

## Salesforce 작업에 Sales Insight 작업/미리 알림 동기화 {#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks}

1. Sales Insight Actions에서 톱니바퀴 아이콘을 클릭하고 을 선택합니다. **설정**.

   ![](assets/salesforce-sync-settings-10.png)

1. 관리자 설정 (또는 관리자가 아닌 경우 &quot;내 계정&quot;)에서 **Salesforce**.

   ![](assets/salesforce-sync-settings-11.png)

1. 을(를) 클릭합니다. **동기화 설정** 탭.

   ![](assets/salesforce-sync-settings-12.png)

1. Salesforce 작업에 Marketo Sales Tasks/Recommendations 동기화 옆에 있는 화살표를 클릭합니다.

   ![](assets/salesforce-sync-settings-13.png)

1. 원하는 옵션을 선택합니다(기본적으로 &quot;Salesforce 작업에 동기화 안 함&quot; 옵션이 선택되어 있음).

   ![](assets/salesforce-sync-settings-14.png)

## Salesforce와 처음 Sales Insight Actions 작업 동기화 {#syncing-sales-insight-ations-tasks-with-salesforce-for-the-first-time}

처음 Sales Insight Actions와 Salesforce 작업 간의 동기화를 켜면 Salesforce 작업을 가져옵니다. Salesforce에 Sales Insight Actions에 있는 현재 작업을 푸시하지 않습니다. 낮은 복잡성과 중복을 줄이기 위해 Sales Insight Actions에서 Salesforce로 동기화되는 유일한 작업은 SFDC와 Sales Insight Actions를 동기화한 후 생성된 작업입니다.

다음은 Sales Insight Actions 및 SFDC 작업을 동기화할 때 수행되는 작업입니다.

작업 동기화 시 저장을 클릭하면 동기화가 시작됩니다. 처음에는 시간이 좀 걸릴 겁니다

지난 24시간 내에 업데이트되거나 생성된 모든 미리 알림은 SFDC에서 Sales Insight Actions로 가져옵니다. 동기화는 만기 날짜를 기반으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만 Command Center에서는 오늘과 내일 작업만 표시됩니다.

이전에 동기화가 켜져 있고 SFDC에서 모든 작업을 삭제하면 지난 15일 동안 삭제된 작업은 명령 센터에서 삭제됩니다.

동기화가 활성화되면 Sales Insight Actions와 SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 Sales Insight Actions에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 Salesforce의 작업 목록에 동기화됩니다. Salesforce에서 생성, 편집, 완료 또는 삭제된 작업은 Sales Insight Actions에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 애플리케이션의 설정 페이지에서 동기화 상자를 선택합니다.

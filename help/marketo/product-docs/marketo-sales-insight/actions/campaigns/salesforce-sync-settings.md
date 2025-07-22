---
description: Salesforce 동기화 설정 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 설정
exl-id: fa13ced2-6184-485f-a0ef-813ccab4f0fe
feature: Sales Insight Actions
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 1%

---

# [!DNL Salesforce] 동기화 설정 {#salesforce-sync-settings}

## API를 통해 [!DNL Salesforce]에 전자 메일 활동 로깅 {#logging-email-activity-to-salesforce-via-api}

이 기능을 사용하려면 Enterprise/Unlimited 버전의 [!DNL Salesforce]을(를) 사용해야 하며, Web Services API를 통해 통합을 구입한 경우에는 Professional 버전을 사용해야 합니다.

>[!PREREQUISITES]
>
>[!DNL Salesforce] 및 [!DNL Sales Insight Actions]이(가) 연결되어 있어야 합니다.

1. [!DNL Sales Insight Actions]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/salesforce-sync-settings-1.png)

1. [!UICONTROL Admin Settings]&#x200B;(또는 관리자가 아닌 경우 &quot;[!UICONTROL My Account]&quot;) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-settings-2.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/salesforce-sync-settings-3.png)

1. [!UICONTROL Log Email Activity]에서 [!DNL Salesforce]까지 옆에 있는 화살표를 클릭합니다.

   ![](assets/salesforce-sync-settings-4.png)

1. **[!UICONTROL Salesforce API]** 탭을 클릭합니다. 이 카드에서 정보를 [!DNL Salesforce]&#x200B;(으)로 로깅하는 기본 설정을 설정할 수 있습니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-settings-5.png)

## [!DNL Salesforce]&#x200B;(BCC)에 전자 메일을 통해 [!DNL Salesforce]에 전자 메일 활동 로깅 {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;[!UICONTROL Email to Salesforce (BCC)]&quot;을(를) 활성화하면 영업 이메일의 숨은 참조를 받게 되며 영업 기회, 잠재 고객 및 연락처에 대한 활동으로 전자 메일이 기록됩니다.

>[!PREREQUISITES]
>
>[!DNL Salesforce] 및 [!DNL Sales Insight Actions]이(가) 연결되어 있어야 합니다.

**BCC(전자 메일)를 통해 [!DNL Salesforce]에 전자 메일을 기록하려면**

1. Marketo Sales에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/salesforce-sync-settings-6.png)

1. [!UICONTROL Admin Settings]&#x200B;(또는 관리자가 아닌 경우 &quot;[!UICONTROL My Account]&quot;) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-settings-7.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/salesforce-sync-settings-8.png)

1. **[!UICONTROL Email to Salesforce (BCC)]** 탭을 클릭하고 **[!UICONTROL Activate]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-settings-9.png)

어떤 이유로든 [!DNL Salesforce] 주소로 이메일을 보낼 수 없는 경우 다음 단계에 따라 [!DNL Salesforce] 계정에서 BCC 기능을 활성화하십시오.

1. [!DNL Salesforce] 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. **[!UICONTROL My Settings]**&#x200B;를 선택합니다.
1. **[!UICONTROL Email]**&#x200B;를 선택합니다.
1. **[!UICONTROL My Email to Salesforce]**&#x200B;를 선택합니다.
1. 이 페이지에는 &quot;[!UICONTROL Email to Salesforce Address]&quot;(이)라는 필드가 표시됩니다. 그 옆에 채워진 항목이 없으면 &quot;[!UICONTROL My Acceptable Email Addresses]&quot;(으)로 스크롤합니다.
1. 숨은 참조를 보낼 이메일 주소를 입력합니다.
1. **[!UICONTROL Save Changes]**&#x200B;을(를) 클릭합니다.

**내 설정에서 [!DNL Salesforce]에게 보낸 내 전자 메일을 찾을 수 없습니다**

설정에서 [!DNL Salesforce]에게 보낸 내 전자 메일이 표시되지 않으면 관리자가 활성화하지 않았을 수 있습니다. 이 문제는 팀이 [!DNL Salesforce]을(를) 처음 사용하거나 팀이 [!DNL Salesforce]에서 제공하는 BCC 주소를 사용한 적이 없는 경우 발생할 수 있습니다.

>[!NOTE]
>
>이를 설정하려면 관리자 권한이 필요합니다.

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Email Administration]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Email to Salesforce]**&#x200B;을(를) 클릭합니다.
1. **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.
1. &quot;활성&quot; 옆에 있는 상자를 선택합니다.
1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## [!DNL Sales Insight Actions]개 작업/미리 알림을 [!DNL Salesforce]개 작업에 동기화 {#sync-sales-insight-actions-tasks-reminders-to-salesforce-tasks}

1. [!DNL Sales Insight Actions]에서 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/salesforce-sync-settings-10.png)

1. [!UICONTROL Admin Settings]&#x200B;(또는 관리자가 아닌 경우 &quot;[!UICONTROL My Account]&quot;) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-settings-11.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/salesforce-sync-settings-12.png)

1. [!DNL Salesforce] 작업에 Marketo 판매 작업/미리 알림 동기화 옆에 있는 화살표를 클릭합니다.

   ![](assets/salesforce-sync-settings-13.png)

1. 원하는 옵션을 선택합니다(&quot;[!DNL Salesforce]개 작업에 동기화 안 함&quot;이 기본적으로 선택됨).

   ![](assets/salesforce-sync-settings-14.png)

## [!DNL Sales Insight Actions]개 작업을 [!DNL Salesforce]과(와) 처음 동기화 중 {#syncing-sales-insight-ations-tasks-with-salesforce-for-the-first-time}

[!DNL Sales Insight Actions]과(와) [!DNL Salesforce] 작업 간의 동기화를 처음 켜면 [!DNL Salesforce] 작업을 가져옵니다. [!DNL Sales Insight Actions]에 있는 현재 작업을 [!DNL Salesforce]&#x200B;(으)로 푸시하지 않습니다. 혼란을 줄이고 중복을 줄이기 위해 [!DNL Sales Insight Actions]에서 [!DNL Salesforce]&#x200B;(으)로 동기화되는 작업은 [!DNL Sales Insight Actions]을(를) SFDC과 동기화한 후 생성된 작업뿐입니다.

[!DNL Sales Insight Actions] 및 SFDC 작업을 동기화할 때 발생하는 상황은 다음과 같습니다.

작업 동기화 시 저장 을 클릭하면 다시 동기화됩니다. 처음에는 시간이 좀 걸릴 것입니다.

지난 24시간 동안 업데이트되거나 만들어진 모든 미리 알림은 SFDC에서 [!DNL Sales Insight Actions]&#x200B;(으)로 가져옵니다. 동기화는 만기일을 기준으로 하며 이러한 모든 작업은 백 엔드에서 동기화되지만, 명령 센터에서는 오늘과 내일의 작업만 표시됩니다.

이전에 동기화가 켜져 있고 SFDC에서 작업을 삭제하면 지난 15일 동안 삭제된 모든 항목이 명령 센터에서 삭제됩니다.

동기화가 활성화되어 있는 한 [!DNL Sales Insight Actions]과(와) SFDC 간에 작업을 지속적으로 동기화합니다.

초기 동기화 후 [!DNL Sales Insight Actions]에서 생성, 편집, 완료 또는 삭제하는 모든 작업은 [!DNL Salesforce]의 작업 목록에 동기화됩니다. [!DNL Salesforce]에서 생성, 편집, 완료 또는 삭제된 모든 작업은 [!DNL Sales Insight Actions]에서 작업 목록을 업데이트합니다.

이 동기화를 켜려면 웹 응용 프로그램의 [!UICONTROL Settings] 페이지에서 동기화 상자를 선택하면 됩니다.

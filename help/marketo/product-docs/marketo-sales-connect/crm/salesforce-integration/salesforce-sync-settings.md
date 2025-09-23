---
unique-page-id: 18317669
description: Salesforce 동기화 설정 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 설정
exl-id: 024c60ac-569f-4051-9eee-1e8d00f7296c
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '358'
ht-degree: 5%

---

# Salesforce 동기화 설정 {#salesforce-sync-settings}

## API를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-api}

이 기능을 사용하려면 Salesforce Enterprise/Unlimited 에디션 또는 웹 서비스 API를 통해 통합을 구입한 경우 Professional 에디션을 사용해야 합니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Connect가 연결되어 있어야 합니다.

1. [!DNL Sales Connect]에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/one-2.png)

1. [!UICONTROL My Account]&#x200B;(관리자의 경우 [!UICONTROL Admin Settings]) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/two-2.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. [!DNL Salesforce]에 전자 메일 활동 기록 옆에 있는 화살표를 클릭합니다.

   ![](assets/four-1.png)

1. **[!UICONTROL Salesforce API]** 탭을 클릭합니다. 이 카드에서 정보를 [!DNL Salesforce]&#x200B;(으)로 로깅하는 기본 설정을 설정할 수 있습니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/five.png)

## BCC(Salesforce)로 이메일을 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;Salesforce으로 이메일(BCC)&quot;을 활성화하면 판매 이메일의 BCC를 받게 되며 이메일은 기회, 리드 및 연락처에 대한 활동으로 기록됩니다.

>[!PREREQUISITES]
>
>[!DNL Salesforce] 및 [!DNL Sales Connect]이(가) 연결되어 있어야 합니다.

**BCC(전자 메일)를 통해 Salesforce에 전자 메일을 기록하려면**

1. [!UICONTROL Sales Connect]에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/one-3.png)

1. [!UICONTROL My Account]&#x200B;(관리자의 경우 [!UICONTROL Admin Settings]) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/two-3.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. **[!UICONTROL Email to Salesforce (BCC)]** 탭을 클릭하고 **[!UICONTROL Activate]**&#x200B;을(를) 클릭합니다.

   ![](assets/six-2.png)

어떤 이유로든 [!DNL Salesforce] 주소로 이메일을 보낼 수 없는 경우 다음 단계에 따라 [!DNL Salesforce] 계정에서 BCC 기능을 활성화하십시오.

1. [!DNL Salesforce] 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. **[!UICONTROL My Settings]**&#x200B;를 선택합니다.
1. **[!UICONTROL Email]**&#x200B;를 선택합니다.
1. **[!UICONTROL My Email to Salesforce]**&#x200B;를 선택합니다.
1. 이 페이지에는 &quot;Salesforce 주소로 이메일&quot;이라는 레이블이 지정된 필드가 표시됩니다. 옆에 채워진 항목이 없으면 아래로 스크롤하여 &quot;허용 가능한 내 이메일 주소&quot;를 표시합니다.
1. 숨은 참조를 보낼 이메일 주소를 입력합니다.
1. **[!UICONTROL Save Changes]**&#x200B;를 클릭합니다.

**내 설정에서 [!DNL Salesforce]에게 보낸 내 전자 메일을 찾을 수 없습니다**

설정에서 Salesforce으로 보내는 내 이메일이 표시되지 않으면 관리자가 활성화하지 않았을 수 있습니다. 이 문제는 팀이 [!DNL Salesforce]을(를) 처음 사용하거나 팀이 [!DNL Salesforce]에서 제공하는 BCC 주소를 사용한 적이 없는 경우 발생할 수 있습니다.

>[!NOTE]
>
>이를 설정하려면 관리자 권한이 필요합니다.

1. **[!UICONTROL Setup]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Email Administration]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Email to Salesforce]**&#x200B;를 클릭합니다.
1. **[!UICONTROL Edit]**&#x200B;를 클릭합니다.
1. &quot;[!UICONTROL Active]&quot; 옆의 확인란을 선택합니다.
1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

## [!DNL Salesforce]개 작업에 Sales Connect 작업/미리 알림 동기화 {#sync-sales-connect-tasks-reminders-to-salesforce-tasks}

1. 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/one-3.png)

1. [!UICONTROL My Account]&#x200B;(관리자의 경우 [!UICONTROL Admin Settings]) 아래에서 **[!UICONTROL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/two-2.png)

1. **[!UICONTROL Sync Settings]** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. [!UICONTROL Sync Sales Engage Tasks/Reminders to Salesforce Tasks] 옆에 있는 화살표를 클릭합니다.

   ![](assets/seven-2.png)

1. 원하는 옵션을 선택합니다(&quot;[!UICONTROL Do not sync to Salesforce tasks]&quot;이(가) 기본적으로 선택됨).

   ![](assets/eight.png)

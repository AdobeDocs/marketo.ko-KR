---
unique-page-id: 18317669
description: Salesforce 동기화 설정 - Marketing To Docs - 제품 설명서
title: Salesforce 동기화 설정
translation-type: tm+mt
source-git-commit: 1dd80b7de801df78ac7dde39002455063f9979b7
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---


# Salesforce 동기화 설정 {#salesforce-sync-settings}

## API {#logging-email-activity-to-salesforce-via-api}를 통해 Salesforce에 이메일 활동 로깅

Web Services API를 통해 통합을 구입한 경우 이 기능을 사용하려면 Enterprise/Unlimited edition of Salesforce 또는 Professional 에디션에 있어야 합니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Engage는 연결되어 있어야 합니다.

1. Sales Engage에서 오른쪽 상단에 있는 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-2.png)

1. 내 계정(관리자라면 관리 설정)에서 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/two-2.png)

1. **설정 동기화** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. Salesforce에 이메일 활동 로그 옆의 화살표를 클릭합니다.

   ![](assets/four-1.png)

1. **Salesforce API** 탭을 클릭합니다. 이 카드에서 Salesforce에 정보 로깅에 대한 환경 설정을 설정할 수 있습니다. 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/five.png)

## Salesforce에 전자 메일을 통해 Salesforce에 전자 메일 활동 로깅(BCC) {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;Salesforce에 이메일(BCC)&quot;을 활성화하면 판매 이메일의 숨은 참조 정보가 수신되고 이메일은 기회, 리드 및 연락처에 대한 활동으로 기록됩니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Engage는 연결되어 있어야 합니다.

**이메일을 통해 Salesforce에 이메일을 기록하려면 숨은 참조**

1. Sales Engage에서 오른쪽 상단에 있는 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-3.png)

1. 내 계정(관리자라면 관리 설정)에서 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/two-3.png)

1. **설정 동기화** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. **Email to Salesforce (BCC)** 탭을 클릭하고 **활성화**&#x200B;를 클릭합니다.

   ![](assets/six-2.png)

Salesforce로 전자 메일 주소를 가져올 수 없는 이유가 있는 경우 다음 단계에 따라 Salesforce 계정에서 BCC 기능을 활성화합니다.

1. Salesforce 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. **내 설정**&#x200B;을 선택합니다.
1. **이메일**&#x200B;을 선택합니다.
1. **Salesforce에 내 이메일**&#x200B;을 선택합니다.
1. 이 페이지에는 &quot;Salesforce에 이메일 주소&quot;라는 레이블이 있는 필드가 표시됩니다. 여기에 채워진 것이 없으면 &quot;My Acceptable Email Addresses&quot;로 스크롤하십시오.
1. 숨은 참조를 원하는 이메일 주소를 입력합니다.
1. **변경 내용 저장**&#x200B;을 클릭합니다.

**내 설정에서 Salesforce에 전자 메일을 찾을 수 없습니다.**

사용자의 설정 아래에 Salesforce에 내 전자 메일이 표시되지 않는 경우 관리자가 이를 활성화하지 않았을 수 있습니다. 팀이 Salesforce를 처음 사용하거나 팀이 Salesforce에서 제공하는 숨은 참조 주소를 사용하지 않은 경우 이러한 문제가 발생할 수 있습니다.

>[!NOTE]
>
>이 설정을 하려면 관리자 권한이 필요합니다.

1. **설정**&#x200B;을 클릭합니다.
1. **이메일 관리**&#x200B;를 클릭합니다.
1. **Salesforce에 이메일**&#x200B;을 클릭합니다.
1. **편집**&#x200B;을 클릭합니다.
1. &quot;활성&quot; 옆의 상자를 선택합니다.
1. **저장**&#x200B;을 클릭합니다.

## 세일즈 참여 작업/미리 알림을 Salesforce 작업에 동기화 {#sync-sales-engage-tasks-reminders-to-salesforce-tasks}

1. 오른쪽 상단에 있는 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-3.png)

1. 내 계정(관리자라면 관리 설정)에서 **Salesforce**&#x200B;를 클릭합니다.

   ![](assets/two-2.png)

1. **설정 동기화** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. Salesforce 작업에 대한 Sales Engage Tasks/Renotifications 동기화 옆에 있는 화살표를 클릭합니다.

   ![](assets/seven-2.png)

1. 원하는 옵션(&quot;Salesforce 작업에 동기화 안 함&quot;이 기본적으로 선택되어 있음)을 선택합니다.

   ![](assets/eight.png)

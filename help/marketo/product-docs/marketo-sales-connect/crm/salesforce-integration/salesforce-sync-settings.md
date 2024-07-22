---
unique-page-id: 18317669
description: Salesforce 동기화 설정 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 설정
exl-id: 024c60ac-569f-4051-9eee-1e8d00f7296c
feature: Marketo Sales Connect
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 0%

---

# Salesforce 동기화 설정 {#salesforce-sync-settings}

## API를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-api}

이 기능을 사용하려면 Enterprise/Unlimited 버전의 Salesforce를 사용해야 하며, 웹 서비스 API를 통해 통합을 구입한 경우에는 Professional 버전을 사용해야 합니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Connect가 연결되어 있어야 합니다.

1. Sales Connect에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-2.png)

1. 내 계정(관리자의 경우 관리자 설정)에서 **Salesforce**&#x200B;을 클릭합니다.

   ![](assets/two-2.png)

1. **동기화 설정** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. Salesforce에 이메일 활동 기록 옆에 있는 화살표를 클릭합니다.

   ![](assets/four-1.png)

1. **Salesforce API** 탭을 클릭합니다. 이 카드에서 Salesforce에 정보를 기록하는 기본 설정을 지정할 수 있습니다. 완료되면 **저장**&#x200B;을 클릭합니다.

   ![](assets/five.png)

## BCC(Salesforce에 이메일)를 통해 Salesforce에 이메일 활동 로깅 {#logging-email-activity-to-salesforce-via-email-to-salesforce-bcc}

&quot;Salesforce로 이메일(BCC)&quot;을 활성화하면 판매 이메일의 BCC를 받게 되고 이메일은 기회, 리드 및 연락처에 대한 활동으로 기록됩니다.

>[!PREREQUISITES]
>
>Salesforce 및 Sales Connect가 연결되어 있어야 합니다.

**BCC(전자 메일)를 통해 Salesforce에 전자 메일을 기록하려면**

1. Sales Connect에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-3.png)

1. 내 계정(관리자의 경우 관리자 설정)에서 **Salesforce**&#x200B;을 클릭합니다.

   ![](assets/two-3.png)

1. **동기화 설정** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. **BCC(Salesforce로 전자 메일 보내기)** 탭을 클릭하고 **활성화**&#x200B;를 클릭합니다.

   ![](assets/six-2.png)

어떤 이유로든 Salesforce로 이메일 주소를 가져오지 않는 경우 다음 단계에 따라 Salesforce 계정에서 BCC 기능을 활성화하십시오.

1. Salesforce 인스턴스에 로그인합니다.
1. 오른쪽 상단 모서리에서 사용자 이름을 찾고 드롭다운 막대를 선택합니다.
1. **내 설정**&#x200B;을 선택하세요.
1. **전자 메일**&#x200B;을 선택하세요.
1. **Salesforce로 보내는 내 전자 메일**&#x200B;을 선택합니다.
1. 이 페이지에는 &quot;Salesforce 주소로 이메일&quot;이라는 레이블이 지정된 필드가 표시됩니다. 옆에 채워진 항목이 없으면 아래로 스크롤하여 &quot;허용 가능한 내 이메일 주소&quot;를 표시합니다.
1. 숨은 참조를 보낼 이메일 주소를 입력합니다.
1. **변경 내용 저장**&#x200B;을 클릭합니다.

**내 설정에서 Salesforce로 보내는 전자 메일을 찾을 수 없습니다**

설정에서 Salesforce로 보내는 내 이메일이 표시되지 않으면 관리자가 활성화하지 않았을 수 있습니다. 이 문제는 팀이 Salesforce를 처음 사용하거나 팀이 Salesforce에서 제공하는 BCC 주소를 사용한 적이 없는 경우 발생할 수 있습니다.

>[!NOTE]
>
>이를 설정하려면 관리자 권한이 필요합니다.

1. **설치**&#x200B;를 클릭합니다.
1. **전자 메일 관리**&#x200B;를 클릭합니다.
1. **Salesforce로 전자 메일 보내기**&#x200B;를 클릭합니다.
1. **편집**&#x200B;을 클릭합니다.
1. &quot;활성&quot; 옆에 있는 상자를 선택합니다.
1. **저장**&#x200B;을 클릭합니다.

## Sales Connect 작업/미리 알림을 Salesforce 작업에 동기화 {#sync-sales-connect-tasks-reminders-to-salesforce-tasks}

1. 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/one-3.png)

1. 내 계정(관리자의 경우 관리자 설정)에서 **Salesforce**&#x200B;을 클릭합니다.

   ![](assets/two-2.png)

1. **동기화 설정** 탭을 클릭합니다.

   ![](assets/three-1.png)

1. Salesforce 작업에 Sales Connect 작업/미리 알림 동기화 옆에 있는 화살표를 클릭합니다.

   ![](assets/seven-2.png)

1. 원하는 옵션(&quot;Salesforce 작업에 동기화 안 함&quot;이 기본적으로 선택됨)을 선택합니다.

   ![](assets/eight.png)

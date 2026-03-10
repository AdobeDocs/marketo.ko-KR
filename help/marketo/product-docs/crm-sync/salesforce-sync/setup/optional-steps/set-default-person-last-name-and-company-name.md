---
unique-page-id: 4719291
description: Salesforce 동기화를 위해 기본 개인 성 및 회사 이름을 설정하는 방법을 알아봅니다. 부분 레코드가 기본값과 동기화되도록 [관리] 및 [동기화 옵션]을 사용합니다.
title: 기본 사용자 성 및 회사 이름 설정
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
feature: Salesforce Integration
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '141'
ht-degree: 12%

---

# 기본 사용자 성 및 회사 이름 설정 {#set-default-person-last-name-and-company-name}

[!DNL Salesforce]에는 리드 및 연락처에 성과 회사 이름이 필요합니다(최소). 불완전한 레코드가 [!DNL Salesforce]에 동기화되지 않습니다. 부분 레코드를 동기화하려면 Marketo에서 [!DNL Salesforce]에 사용할 기본값을 설정해야 합니다.

1. **[!UICONTROL Admin]**(으)로 이동하여 **[!DNL Salesforce]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. **[!UICONTROL Edit Sync Options]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. **[!UICONTROL Default person last name]** 및 **[!UICONTROL Default person company]**&#x200B;을(를) 입력한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo Engage은 레코드가 Salesforce에 처음 동기화될 때만 기본값을 할당하며 필수 필드 중 하나가 비어 있는 경우에만 기본값을 할당합니다.

바로 그거야! 성 및/또는 회사 이름이 누락된 사용자가 있을 때마다 Marketo은 레코드를 동기화할 때 기본값을 추가합니다.

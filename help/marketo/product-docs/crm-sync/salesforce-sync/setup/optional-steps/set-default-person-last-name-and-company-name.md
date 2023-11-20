---
unique-page-id: 4719291
description: 기본 사용자 성 및 회사 이름 설정 - Marketo 문서 - 제품 설명서
title: 기본 사용자의 성 및 회사 이름 설정
exl-id: 0216fb41-adf0-4ccf-be22-c064e90be65a
feature: Salesforce Integration
source-git-commit: 756a38ba87dd5af9ee783e9709056d444d4f415b
workflow-type: tm+mt
source-wordcount: '142'
ht-degree: 0%

---

# 기본 사용자의 성 및 회사 이름 설정 {#set-default-person-last-name-and-company-name}

Salesforce에는 가망 고객 및 연락처에 성과 회사 이름이 필요합니다(최소). 미완료 레코드는 Salesforce에 동기화되지 않습니다. 부분 레코드를 동기화하려면 Salesforce에서 사용할 Marketo의 기본값을 설정해야 합니다.

1. 다음으로 이동 **[!UICONTROL 관리자]** 및 클릭 **[!DNL Salesforce]**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. 클릭 **[!UICONTROL 동기화 옵션 편집]**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. 입력 **[!UICONTROL 기본 사용자의 성]** 및 a **[!UICONTROL 기본 개인 회사]**&#x200B;을 클릭한 다음 을 클릭합니다 **[!UICONTROL 저장]**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo Engage은 레코드가 Salesforce에 처음 동기화될 때만 기본값을 할당하며 필수 필드 중 하나가 비어 있을 경우에만 기본값을 할당합니다.

바로 그거야! 성 및/또는 회사 이름이 누락된 사용자가 있을 때마다 Marketo은 레코드를 동기화할 때 기본값을 추가합니다.

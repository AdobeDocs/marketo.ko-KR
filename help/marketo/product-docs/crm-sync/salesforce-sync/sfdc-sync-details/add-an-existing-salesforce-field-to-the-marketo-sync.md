---
unique-page-id: 4719308
description: 기존 Salesforce 필드를 Marketo 동기화 - Marketo 문서 - 제품 설명서에 추가
title: 기존 Salesforce 필드를 Marketo 동기화에 추가
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '146'
ht-degree: 6%

---

# Marketo 동기화에 기존 [!DNL Salesforce] 필드 추가 {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**관리자 권한 필요**

일반적으로 Salesforce의 새 사용자 정의 필드는 Marketo Engage에 자동으로 동기화됩니다. 그렇지 않으면 Marketo 동기화 사용자에게 필드가 표시되지 않을 수 있습니다. 이 문제를 해결하는 방법은 다음과 같습니다.

1. 이름을 클릭한 다음 **[!UICONTROL Setup]**&#x200B;을(를) 선택합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-1.png)

1. 왼쪽 검색 창에 &quot;프로필&quot;을 입력하고 **[!UICONTROL Profiles]** 아래의 **[!UICONTROL Manage Users]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-2.png)

1. 동기화 사용자의 프로필을 클릭합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-3.png)

1. **[!UICONTROL Field-Level Security]** 섹션에서 필드가 있는 개체 옆에 있는 **[!UICONTROL View]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-4.png)

1. **[!UICONTROL Edit]**&#x200B;를 클릭합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-5.png)

1. 동기화에 추가할 필드에 대한 **[!UICONTROL Visible]** 확인란을 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-6.png)

   다음 동기화 사이클에서 Marketo이 필드를 보고 마법을 시작합니다.

   >[!NOTE]
   >
   > 필드에 이미 [!DNL Salesforce]의 값이 있는 경우 다음 레코드가 업데이트될 때까지 해당 값이 Marketo에 동기화되지 않습니다.

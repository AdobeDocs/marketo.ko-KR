---
unique-page-id: 2360364
description: 3단계 중 2단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)
exl-id: 871f335c-7b1e-47e1-8320-a18fbf21a970
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 2%

---

# 2단계/3단계: Marketo용 [!DNL Salesforce] 사용자 만들기(Enterprise/Unlimited) {#step-of-create-a-salesforce-user-for-marketo-enterprise-unlimited}

>[!NOTE]
>
>[!DNL Salesforce] 관리자가 이 단계를 완료해야 합니다.

>[!PREREQUISITES]
>
>[3단계 중 1단계:  [!DNL Salesforce] (Enterprise/Unlimited)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)

이 문서에서는 [!DNL Salesforce] 프로필에서 사용자 권한을 설정하고 Marketo-[!DNL Salesforce] 통합 계정을 만듭니다.

## 프로필 만들기 {#create-a-profile}

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-6-11-16-3a15-3a27.png)

1. 탐색 검색 창에 &quot;profiles&quot;를 입력하고 **[!UICONTROL Profiles]** 링크를 클릭합니다.

   ![](assets/sfdc-profiles-hands.png)

1. **[!UICONTROL New]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-9-3a19-3a15.png)

1. **[!UICONTROL Standard User]**&#x200B;을(를) 선택하고 프로필 이름을 &quot;Marketo-Salesforce 동기화&quot;로 지정한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-9-3a19-3a22.png)

## 프로필 권한 설정 {#set-profile-permissions}

1. 보안 권한을 설정하려면 **[!UICONTROL Edit]**&#x200B;을(를) 클릭하십시오.

   ![](assets/image2014-12-9-9-3a19-3a30.png)

1. **[!UICONTROL Administrative Permissions]** 섹션에서 다음 상자가 선택되어 있는지 확인하십시오.

   * [!UICONTROL API Enabled]
   * [!UICONTROL Edit HTML Templates]
   * [!UICONTROL Manage Public Documents]
   * [!UICONTROL Manage Public Templates]

   ![](assets/image2014-12-9-9-3a19-3a38.png)

   >[!TIP]
   >
   >**[!UICONTROL Password Never Expires]** 상자를 확인하십시오.

1. [!UICONTROL General User Permissions] 섹션에서 다음 상자가 선택되어 있는지 확인하십시오.

   * [!UICONTROL Convert Leads]
   * [!UICONTROL Edit Events]
   * [!UICONTROL Edit Tasks]

   ![](assets/image2014-12-9-9-3a19-3a47.png)

1. [!UICONTROL Standard Object Permissions] 섹션에서 [!UICONTROL Read, Create, Edit, and Delete] 사용 권한이 확인되었는지 확인합니다.

   * [!UICONTROL Accounts]
   * [!UICONTROL Campaigns]
   * [!UICONTROL Contacts]
   * [!UICONTROL Leads]
   * [!UICONTROL Opportunities]

   >[!NOTE]
   >
   >Campaign Sync를 사용하려면 [!UICONTROL Campaigns]에 권한을 부여하십시오.

   ![](assets/image2014-12-9-9-3a19-3a57.png)

1. 완료되면 페이지 하단의 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-9-3a20-3a5.png)

## 필드 권한 설정 {#set-field-permissions}

1. 동기화에 필요한 사용자 지정 필드를 확인하려면 마케터와 상의하십시오.

   >[!NOTE]
   >
   >이 단계는 Marketo에 필요하지 않은 필드가 표시되지 않도록 하여 혼란을 줄이고 동기화 속도를 높입니다.

1. 프로필 세부 정보 페이지에서 **[!UICONTROL Field-Level Security]** 섹션으로 이동합니다. **[!UICONTROL View]**&#x200B;을(를) 클릭하여 개체에 대한 액세스 가능성을 편집합니다.

   * [!UICONTROL Lead]
   * [!UICONTROL Contact]
   * [!UICONTROL Account]
   * [!UICONTROL Opportunity]

   >[!TIP]
   >
   >조직의 필요에 따라 다른 객체를 구성할 수 있습니다.

   ![](assets/image2014-12-9-9-3a20-3a14.png)

1. 각 개체에 대해 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/sfdc-sync-field-edit1.png)

1. 불필요한 필드를 찾아 **[!UICONTROL Read Access]** 및 **[!UICONTROL Edit Access]**&#x200B;이(가) 선택 취소되었는지 확인하십시오. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >사용자 정의 필드에 대한 액세스 가능성만 편집하십시오.

   ![](assets/sfdc-sync-field-edit2.png)

1. 필요하지 않은 모든 필드 비활성화가 끝나면 다음 개체 필드에 대해 **[!UICONTROL Read Access and Edit Access]**&#x200B;을(를) 확인해야 합니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

<table> 
 <tbody> 
  <tr> 
   <th>오브젝트</th> 
   <th>필드</th> 
  </tr> 
  <tr> 
   <td>계정</td> 
   <td>필드 입력</td> 
  </tr> 
  <tr> 
   <td>이벤트</td> 
   <td>모든 필드</td> 
  </tr> 
  <tr> 
   <td>작업</td> 
   <td>모든 필드</td> 
  </tr> 
 </tbody> 
</table>

![](assets/sfdc-check-the-boxes.png)

## Marketo-Salesforce 동기화 계정 만들기 {#create-marketo-salesforce-sync-account}

>[!TIP]
>
>Marketo의 변경 사항과 다른 [!DNL Salesforce] 사용자를 구별하기 위해 전용 [!DNL Salesforce] 계정(예: marketo@yourcompany.com)을 만듭니다.

1. 탐색 검색 창에 &quot;사용자 관리&quot;를 입력한 다음 **[!UICONTROL Users]**&#x200B;을(를) 클릭합니다. **[!UICONTROL New User]**&#x200B;을(를) 클릭합니다.

   ![](assets/sfdc-new-users.png)

1. 필수 필드를 채웁니다. 그런 다음 **[!UICONTROL User License: Salesforce]**&#x200B;과(와) 이전에 만든 프로필을 선택합니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-9-3a20-3a56.png)

3단계 중 2단계가 완료되었습니다.

>[!NOTE]
>
>[3단계 중 3단계: Marketo 및 [!DNL Salesforce] (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)

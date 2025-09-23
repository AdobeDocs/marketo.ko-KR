---
unique-page-id: 3571797
description: 3단계 중 2단계 - Marketo용 Salesforce 사용자 만들기(전문가) - Marketo 문서 - 제품 설명서
title: 2/3단계 - Marketo용 Salesforce 사용자 만들기(Professional)
exl-id: 7eb4bf89-b6e4-45e0-adee-e2976cb01dd3
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---

# 2단계/3단계: Marketo용 [!DNL Salesforce] 사용자 만들기(Professional) {#step-of-create-a-salesforce-user-for-marketo-professional}

>[!NOTE]
>
>Salesforce 관리자가 이러한 단계를 완료해야 합니다.

>[!PREREQUISITES]
>
>[3단계 중 1단계: Salesforce(Professional)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-1-of-3-add-marketo-fields-to-salesforce-professional.md){target="_blank"}

이 문서에서는 [!DNL Salesforce] 페이지 레이아웃으로 필드 권한을 사용자 지정하고 Marketo-[!DNL Salesforce] 동기화 사용자를 만듭니다.

## 페이지 레이아웃 설정 {#set-page-layouts}

[!DNL Salesforce] Professional은 [!DNL Salesforce] Enterprise/Unlimited의 프로필이 아닌 페이지 레이아웃으로 필드 수준 접근성을 설정합니다. 이 단계를 수행하면 Marketo 동기화 사용자가 사용자 정의 필드를 업데이트할 수 있습니다.

1. [!UICONTROL page layouts]을(를) 누르지 않고 탐색 검색 창에 &quot;**[!UICONTROL Enter]**&quot;을(를) 입력한 다음 **[!UICONTROL Page Layout]** 아래의 **[!UICONTROL Leads]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-2-26-12-3a58-3a32.png)

1. 잠재 고객 레이아웃 옆에 있는 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-2-26-13-3a2-3a46.png)

1. 새 **[!UICONTROL Section]**&#x200B;을(를) 클릭하여 페이지 레이아웃으로 끕니다.

   ![](assets/image2014-12-9-12-3a56-3a40.png)

1. **[!UICONTROL Section Name]**&#x200B;에 대해 &quot;Marketo&quot;를 입력하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-12-3a56-3a52.png)

1. 필드 **[!UICONTROL Acquisition Date]**&#x200B;을(를) 클릭하여 **Marketo** 섹션으로 끌어옵니다.

   ![](assets/image2014-12-9-12-3a57-3a0.png)

1. 다음 필드에 대해 위의 단계를 반복합니다.

   * [!UICONTROL Acquisition Program]
   * [!UICONTROL Acquisition Program Id]
   * [!UICONTROL Email Opt Out]
   * [!UICONTROL Inferred City]
   * [!UICONTROL Inferred Company]
   * [!UICONTROL Inferred Country]
   * [!UICONTROL Inferred Metropolitan Area]
   * [!UICONTROL Inferred Phone Area Code]
   * [!UICONTROL Inferred Postal Code]
   * [!UICONTROL Inferred State Region]
   * [!UICONTROL Lead Score]
   * [!UICONTROL Original Referrer]
   * [!UICONTROL Original Search Engine]
   * [!UICONTROL Original Search Phrase]
   * [!UICONTROL Original Source Info]
   * [!UICONTROL Original Source Type]

   >[!NOTE]
   >
   >Marketo에서 필드를 읽고 쓸 수 있도록 이러한 필드는 페이지 레이아웃에 있어야 합니다.

   >[!TIP]
   >
   >페이지의 오른쪽으로 끌어 놓아 필드에 대한 두 개의 열을 만듭니다. 열 길이의 균형을 맞추기 위해 필드를 한 쪽에서 다른 쪽으로 이동할 수 있습니다.

1. 필드 추가를 마치면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-12-3a57-3a10.png)

1. Salesforce **[!UICONTROL Contact Page Layout]**&#x200B;에 대해 위의 모든 단계를 반복합니다.

   ![](assets/image2016-2-26-13-3a10-3a1.png)

1. **[!UICONTROL Save]** 작업이 완료되면 **[!UICONTROL Contact Page Layout]**&#x200B;을(를) 클릭해야 합니다.

   ![](assets/image2014-12-9-12-3a57-3a30.png)

   >[!NOTE]
   >
   >**[!UICONTROL All-Day Event]** 필드가 **[!UICONTROL Event Page Layout]**&#x200B;에 추가되었는지 확인하십시오.

## 동기화 사용자 만들기 {#create-sync-user}

Marketo에서 [!DNL Salesforce]에 액세스하려면 자격 증명이 필요합니다. 이 작업은 아래 단계로 만든 전용 사용자로 수행하는 것이 가장 좋습니다.

>[!NOTE]
>
>조직에 추가 Salesforce 라이선스가 없는 경우 시스템 관리자 프로필에서 기존 마케팅 사용자를 사용할 수 있습니다.

1. 탐색 검색 창에 &quot;사용자&quot;를 입력하고 **[!UICONTROL Users]** 아래의 **[!UICONTROL Manage Users]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-12-3a57-3a42.png)

1. **[!UICONTROL New User]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-9-12-3a58-3a1.png)

1. 필수 필드를 입력하고 **[!UICONTROL User License: Salesforce]**&#x200B;을(를) 선택한 뒤 **[!UICONTROL Profile: System Administrator]**&#x200B;을(를) 설정하고 **[!UICONTROL Marketing User]**&#x200B;을(를) 확인한 뒤 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-9-12-3a58-3a11.png)

   >[!TIP]
   >
   >입력한 이메일 주소가 유효한지 확인하십시오. 암호를 재설정하려면 동기화 사용자로 로그인해야 합니다.

훌륭합니다! 이제 Marketo에서 [!DNL Salesforce]에 연결하는 데 사용할 수 있는 계정이 있습니다. 해보자.

>[!MORELIKETHIS]
>
>[3단계 중 3단계: Marketo 및 Salesforce 연결(Professional)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/professional-edition/step-3-of-3-connect-marketo-and-salesforce-professional.md){target="_blank"}

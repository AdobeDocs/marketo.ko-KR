---
unique-page-id: 7511512
description: Salesforce1 - Marketo 설명서 - 제품 설명서에서 Marketo Sales Insight 설치 및 구성
title: Salesforce1에서 Marketo Sales Insight 설치 및 구성
exl-id: 9f26e90b-3199-4ef8-92bc-95e8bd81f1c5
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 4%

---

# [!DNL Marketo Sales Insight]에서 [!DNL Salesforce1] 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-salesforce}

>[!NOTE]
>
>기존 고객은 계속하기 전에 [MSI 패키지를 업그레이드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md)하십시오!

>[!PREREQUISITES]
>
>Salesforce Enterprise/Unlimited가 있는 경우
>
>* [3단계 중 1단계:  [!DNL Salesforce] (Enterprise/Unlimited)에 Marketo 필드 추가](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [3단계 중 2단계:  [!DNL Salesforce] Marketo용 사용자 만들기(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [3단계 중 3단계: Marketo 및 [!DNL Salesforce] (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
>* [구성 [!DNL Marketo Sales Insight] in [!DNL Salesforce] Enterprise/Unlimited](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)
>
>Salesforce Professional이 있는 경우:
>
>* [Salesforce Professional Edition에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)
>

>[!NOTE]
>
>[!DNL Marketo Sales Insight]의 [!DNL Salesforce1]에는 [!DNL B최고의 베팅], 리드 피드, 즐거운 순간 및 Marketo 캠페인에 추가 기능이 포함됩니다.

## [!DNL Salesforce1] 모바일 앱 사용 {#enable-the-salesforce1-mobile-app}

1. **[!DNL Setup]**&#x200B;을(를) 클릭한 다음 **[!DNL Mobile Administration]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-21-15-3a29-3a22.png)

1. **[!UICONTROL Salesforce1]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-21-15-3a30-3a51.png)

1. **[!UICONTROL Salesforce1 Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-21-15-3a32-3a21.png)

1. **[!UICONTROL Enable the Salesforce1 mobile browser app]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-21-15-3a34-3a27.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-21-15-3a42-3a48.png)

1. **[!UICONTROL Mobile Administration]**&#x200B;를 선택합니다.

   ![](assets/image2015-4-22-11-3a10-3a14.png)

1. **[!UICONTROL Manage the mobile navigation menu]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-11-3a13-3a10.png)

1. **[!UICONTROL Marketo]**&#x200B;을(를) 선택하고 **[!UICONTROL Add]** 메뉴 항목에 **[!UICONTROL Selected]**&#x200B;합니다.

   ![](assets/image2015-4-22-14-3a55-3a37.png)

1. **[!UICONTROL Marketo]**&#x200B;을(를) 선택하고 **[!UICONTROL Up]**&#x200B;을(를) 원하는 영역으로 이동한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-17-3a20-3a56.png)

## 오래된 Marketo 사용자 지정 개체 숨기기 {#hide-outdated-marketo-custom-object}

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-15-3a13-3a48.png)

1. **[!UICONTROL Manage Users]**&#x200B;를 선택합니다.

   ![](assets/image2015-5-5-11-3a13-3a45.png)

1. **[!UICONTROL Profiles]**&#x200B;를 선택합니다.

   ![](assets/image2015-5-5-11-3a15-3a21.png)

1. 원하는 프로필을 **[!UICONTROL Edit]**&#x200B;하려면 클릭하세요.

   ![](assets/image2015-5-5-13-3a51-3a36.png)

1. **[!UICONTROL Tab Settings]**&#x200B;에서 _처음_ **[!UICONTROL Marketo]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-5-5-13-3a55-3a36.png)

1. **[!UICONTROL Tab Hidden]**&#x200B;를 선택합니다.

   ![](assets/image2015-5-5-14-3a2-3a29.png)

   >[!NOTE]
   >
   >원하는 모든 프로필에 대해 Marketo 탭을 숨기십시오!

## 탭 맞춤화 {#customize-tabs}

1. **+**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-17-3a14-3a49.png)

1. **[!UICONTROL Customize My Tabs]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-17-3a16-3a22.png)

1. **[!UICONTROL Marketo]**&#x200B;을(를) 선택하고 선택한 탭에 **[!UICONTROL Add]**&#x200B;합니다.

   ![](assets/image2015-4-22-17-3a17-3a15.png)

1. **[!UICONTROL Marketo]**&#x200B;을(를) 선택하고 **[!UICONTROL Up]**&#x200B;을(를) 원하는 영역으로 이동한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-18-3a29-3a47.png)

## 페이지 레이아웃 사용자 지정 {#customize-page-layouts}

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-17-3a26-3a56.png)

1. **[!UICONTROL Setup]**&#x200B;을(를) 클릭하고 **[!UICONTROL Page Layouts]**&#x200B;을(를) 입력한 다음 잠재 고객 아래의 **[!UICONTROL Page Layouts]**&#x200B;을(를) 클릭합니다.

   >[!NOTE]
   >
   >Contact, Account 및 Opportunity 객체에 대해 조직에서 사용하는 모든 페이지 레이아웃(마케팅, 영업 등)에 대해 이 단계를 반복합니다.

   ![](assets/image2015-4-22-17-3a34-3a33.png)

1. 잠재 고객 레이아웃을 변경하려면 **[!UICONTROL Edit]**&#x200B;을(를) 클릭하십시오.

   ![](assets/image2015-4-22-17-3a44-3a0.png)

1. **[!UICONTROL Visualforce Pages]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Lead Mobile]**&#x200B;을(를) 모바일 카드 섹션으로 끕니다.

   ![](assets/image2015-4-22-17-3a49-3a37.png)

1. 높이를 66으로 변경하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-17-3a52-3a15.png)

1. **[!UICONTROL Fields]**&#x200B;을(를) 클릭하고 **[!UICONTROL Add to Marketo Campaign]**&#x200B;을(를) **[!UICONTROL Marketo Sales Insight]** 섹션으로 끌어옵니다.

   ![](assets/configure-step-6.png)

   >[!TIP]
   >
   >Marketo Campaign에 추가를 쉽게 찾을 수 있도록 빠른 찾기에 &quot;추가&quot;를 입력합니다.

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-22-18-3a1-3a56.png)

휴! [!DNL Marketo Sales Insight]에 대한 [!DNL Salesforce1] 설치를 완료했습니다! 어서 허리를 쓰다듬어 봐.

>[!MORELIKETHIS]
>
>* [[!DNL Best Bets] in [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/best-bets-in-salesforce1.md)
>* [관심 있는 순간 [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/interesting-moments-in-salesforce1.md)
>* [다음 위치에서 Marketo 전자 메일 및 Campaign과 Watchlist 작업 보내기 [!DNL Salesforce1]](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/send-marketo-email-and-campaign-and-watchlist-actions-in-salesforce1.md)

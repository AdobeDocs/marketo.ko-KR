---
description: Salesforce의 판매 Insight 작업 구성 - Marketo 문서 - 제품 설명서
title: Salesforce의 영업 Insight 작업 구성
exl-id: 2d842886-3501-4aca-96fb-0d6763ab2b01
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 0%

---

# [!DNL Sales Insight Actions]의 [!DNL Salesforce] 구성 {#sales-insight-actions-configuration-in-salesforce}

>[!PREREQUISITES]
>
>* [ 인스턴스에서 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)설치[ 또는 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md)업그레이드[!DNL Salesforce] Sales Insight 패키지
>* [Enterprise/Unlimited에서 Marketo Sales Insight 구성 [!DNL Salesforce] 2&rbrace;](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

## [!DNL Salesforce]에 새 원격 사이트 추가 {#add-new-remote-site-in-salesforce}

1. [!DNL Salesforce]에서 **[!UICONTROL Setup]**&#x200B;을(를) 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-1.png)

1. &quot;[!UICONTROL remote site]&quot;을(를) 검색하고 **[!UICONTROL Remote Site Settings]**&#x200B;을(를) 선택합니다.
   ![](assets/msi-actions-configuration-in-salesforce-2.png)

1. **[!UICONTROL New Remote Site]**&#x200B;을(를) 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-3.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoSalesInsight1&quot;과 같은 이름일 수 있음). 원격 사이트 URL `https://ims-na1.adobelogin.com`을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-4.png)

1. **[!UICONTROL New Remote Site]**&#x200B;을(를) 다시 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-4a.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoSalesInsight2&quot;와 같은 것일 수 있음). 원격 사이트 URL `https://mkto-sales-connect.adobe.io`을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

## CRM에서 [!DNL Sales Insight Actions] 사용 {#enabling-sales-insight-actions-across-the-crm}

1. [!DNL Salesforce]에서 **[!UICONTROL Marketo Sales Insight Config]** 탭을 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-5.png)

   >[!NOTE]
   >
   >상단 표시줄에 &quot;[!UICONTROL Marketo Sales Insight Config]&quot;이(가) 없으면 **+** 기호를 클릭하고 모든 탭에서 찾습니다.

1. **[!UICONTROL Enable MSI Actions]** 확인란을 선택합니다.

   ![](assets/msi-actions-configuration-in-salesforce-6.png)

1. [!UICONTROL API Secret Key] 입력.

   ![](assets/msi-actions-configuration-in-salesforce-7.png)

   >[!NOTE]
   >
   >[!UICONTROL API Secrey Key]을(를) 사용할 수 없는 경우 [이 문서](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)의 단계에 따라 찾을 수 있습니다.

1. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

이렇게 하면 기능 개요 문서에 설명된 모든 MSI 작업 기능이 자동으로 활성화됩니다.

>[!NOTE]
>
>&quot;MSI 작업 활성화&quot; 확인란의 선택을 취소하면 모든 MSI 작업 기능을 비활성화할 수 있습니다.

## MSI-Actions 거버넌스 {#msi-actions-governance}

1. 예정된 섹션에서 판매 캠페인 및/또는 작업 탭을 비활성화할 수 있습니다. 이 기능은 리드, 연락처, 계정 및 영업 기회 패널에 적용됩니다.

   ![](assets/msi-actions-configuration-in-salesforce-8.png)

1. [!UICONTROL Actions settings]에서 해당 기능을 선택 취소하여 MSI 작업을 비활성화할 수 있습니다.

   ![](assets/msi-actions-configuration-in-salesforce-9.png)

>[!NOTE]
>
>거버넌스 설정은 모든 MSI 사용자에게 적용됩니다.

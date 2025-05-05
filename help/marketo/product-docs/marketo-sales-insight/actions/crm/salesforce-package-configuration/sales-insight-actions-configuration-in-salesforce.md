---
description: Salesforce의 Sales Insight 작업 구성 - Marketo 문서 - 제품 설명서
title: Salesforce의 Sales Insight 작업 구성
exl-id: 2d842886-3501-4aca-96fb-0d6763ab2b01
source-git-commit: 544dfc0892016223c1e5976bd8c9d108ade7c984
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 0%

---

# Salesforce의 Sales Insight 작업 구성 {#sales-insight-actions-configuration-in-salesforce}

>[!PREREQUISITES]
>
>* Salesforce 인스턴스에 [설치](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) 또는 [업그레이드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md) Sales Insight 패키지
>* [Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)

## Salesforce에서 새 원격 사이트 추가 {#add-new-remote-site-in-salesforce}

1. Salesforce에서 **설정**&#x200B;을 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-1.png)

1. &quot;원격 사이트&quot;를 검색하고 **원격 사이트 설정**&#x200B;을 선택합니다.
   ![](assets/msi-actions-configuration-in-salesforce-2.png)

1. **새 원격 사이트**&#x200B;를 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-3.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoSalesInsight1&quot;과 같은 이름일 수 있음). 원격 사이트 URL `https://ims-na1.adobelogin.com`을(를) 입력하고 **저장**&#x200B;을(를) 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-4.png)

1. **새 원격 사이트**&#x200B;를 다시 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-4a.png)

1. 원격 사이트 이름을 입력합니다(&quot;MarketoSalesInsight2&quot;와 같은 것일 수 있음). 원격 사이트 URL `https://mkto-sales-connect.adobe.io`을(를) 입력하고 **저장**&#x200B;을(를) 클릭합니다.

## CRM에서 Sales Insight 작업 활성화 {#enabling-sales-insight-actions-across-the-crm}

1. Salesforce에서 **Marketo Sales Insight 구성** 탭을 클릭합니다.

   ![](assets/msi-actions-configuration-in-salesforce-5.png)

   >[!NOTE]
   >
   >상단 표시줄에 &quot;Marketo Sales Insight Config&quot;가 표시되지 않으면 **+** 기호를 클릭하고 모든 탭에서 찾습니다.

1. **MSI 동작 사용** 확인란을 선택하십시오.

   ![](assets/msi-actions-configuration-in-salesforce-6.png)

1. API 비밀 키를 입력합니다.

   ![](assets/msi-actions-configuration-in-salesforce-7.png)

   >[!NOTE]
   >
   >API 비밀 키가 없으면 [이 문서](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)의 단계를 따라 찾을 수 있습니다.

1. 완료되면 **저장**&#x200B;을 클릭합니다.

이렇게 하면 기능 개요 문서에 설명된 모든 MSI 작업 기능이 자동으로 활성화됩니다.

>[!NOTE]
>
>&quot;MSI 작업 활성화&quot; 확인란의 선택을 취소하면 모든 MSI 작업 기능을 비활성화할 수 있습니다.

## MSI-Actions 거버넌스 {#msi-actions-governance}

1. 예정된 섹션에서 판매 캠페인 및/또는 작업 탭을 비활성화할 수 있습니다. 이 기능은 리드, 연락처, 계정 및 영업 기회 패널에 적용됩니다.

   ![](assets/msi-actions-configuration-in-salesforce-8.png)

1. 작업 설정에서 해당 기능을 선택 취소하여 MSI 작업을 비활성화할 수 있습니다.

   ![](assets/msi-actions-configuration-in-salesforce-9.png)

>[!NOTE]
>
>거버넌스 설정은 모든 MSI 사용자에게 적용됩니다.

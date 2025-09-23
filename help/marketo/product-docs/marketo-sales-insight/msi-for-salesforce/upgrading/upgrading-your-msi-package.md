---
unique-page-id: 37357050
description: MSI 패키지 업그레이드 - Marketo 문서 - 제품 설명서
title: MSI 패키지 업그레이드
exl-id: 45004990-8452-4824-a9b2-89cd8302fe43
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 3%

---

# MSI 패키지 업그레이드 {#upgrading-your-msi-package}

>[!IMPORTANT]
>
>Salesforce의 향상된 보안 기능으로 인해 Sales Insight 패키지는 더 이상 표준 오브젝트에 대한 권한을 부여할 수 없습니다. 앞으로 Sales Insight 사용자의 Salesforce 프로필에는 리드, 연락처, 계정 및 영업 기회와 같은 표준 오브젝트에 대한 읽기 액세스 권한이 있어야 합니다. [여기에서 구성하는 방법을 알아보세요](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md#grant-sales-insight-users-profile-access){target="_blank"}.

1. [appexchange의 이 페이지](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000001SVZmEAO){target="_blank"}(으)로 이동합니다.

1. 1단계의 페이지 오른쪽 상단에서 [!DNL Salesforce] 인스턴스(Marketo 인스턴스에 연결된 인스턴스는 샌드박스 또는 프로덕션일 수 있음)에 로그인합니다. [!DNL Salesforce]에서 관리되는 패키지를 설치/업그레이드하려면 관리자 권한이 있어야 합니다.

1. **지금 가져오기** 단추를 클릭합니다. 설치할 위치를 선택하라는 메시지가 표시됩니다. 이전 버전의 MSI가 이미 있으므로 업그레이드할 수 있는 옵션이 제공됩니다. 1단계 동안 로그인한 계정을 기반으로 옵션을 선택합니다.

   >[!TIP]
   >
   >프로덕션 인스턴스를 업그레이드하기 전에 샌드박스 인스턴스에서 이를 테스트하는 것이 좋습니다.

1. &quot;관리자만 설치&quot;(및 나중에 특정 프로필에 대한 MSI 액세스 권한 제공), &quot;모든 사용자에 대해 설치&quot; 또는 &quot;특정 프로필에 대해 설치&quot;를 선택하여 패키지를 업그레이드할 수 있습니다. 이 예제에서는 관리자만 선택합니다. 선택했으면 **업그레이드**&#x200B;를 클릭합니다.

   ![](assets/four.png)

>[!NOTE]
>
>관리자용 패키지만 업데이트한 다음 [특정 사용자에게 액세스 권한을 제공](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-access-to-profiles.md){target="_blank"}하는 것이 좋습니다. 구매한 MSI 시트 수에 따라. 또는 MSI 사용자에 대한 특정 Salesforce 프로필을 만들고 해당 사용자에 대해서만 패키지를 설치하거나 업그레이드할 수 있습니다.

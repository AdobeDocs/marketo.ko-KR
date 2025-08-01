---
unique-page-id: 3571844
description: Microsoft Dynamics 동기화 - 영업 기회 동기화 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 - 영업 기회 동기화
exl-id: dcb72f28-c980-4183-8473-a1e5ad0c8d3c
feature: Microsoft Dynamics
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '303'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화: 영업 기회 동기화 {#microsoft-dynamics-sync-opportunity-sync}

[!DNL Dynamics] 동기화로의 Marketo은 매우 강력합니다. 다음은 영업 기회 동기화에 대한 모든 세부 정보입니다.

## 두 시스템 간에 영업 기회 세부 정보가 어떻게 동기화됩니까? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

영업 기회 동기화는 Marketo에 [!DNL Dynamics]하는 한 가지 방법입니다. [!DNL Dynamics]에서 영업 기회를 변경하면 업데이트가 Marketo에 반영됩니다.

## Marketo을 사용하여 [!DNL Dynamics]에서 영업 기회를 만들 수 있습니까? {#can-i-create-an-opportunity-in-dynamics-using-marketo}

아니요. [!DNL Dynamics]에서 영업 기회를 만들어야 하며 자동으로 Marketo에 동기화됩니다.

## 어떤 필드가 Marketo에 동기화됩니까? {#what-fields-will-sync-to-marketo}

설치하는 동안 [동기화할 필드를 선택](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md#select-fields-to-sync){target="_blank"}할 수 있습니다.

## Opportunity 와 Account/Contact 는 어떤 식으로 연계됩니까? {#how-is-an-account-contact-associated-with-an-opportunity}

연락처/계정은 다음 두 가지 방법으로 Opportunity에 연결할 수 있습니다.

* 영업 기회를 만드는 동안 연락처(연락할 양식의 조회 필드) 및/또는 계정(계산할 양식의 조회 필드)을 설정할 수 있습니다. 두 경우 모두 이 값은 Dynamics의 잠재적 고객(customerid) 필드에 저장됩니다. 이 필드는 Opportunity Form에 표시되지 않지만 설정에서 추가할 수 있습니다. 이 필드에는 연락처 또는 계정 중 하나의 값만 포함될 수 있습니다. Marketo은 다음을 수행합니다.

   * 연락처 값이 설정되어 있고 계정을 비워 두면 Marketo은 `opportunitycontactrole`을(를) 만들고 기회에 대한 계정을 연락처 계정으로 설정합니다. 연락처에 계정이 없으면 이 필드는 비어 있습니다.
   * 계정 값을 설정하고 연락처를 비워 두면 Marketo은 기회에 대한 계정만 이 계정에 설정합니다.
   * 두 값이 모두 설정되면 Dynamics에서는 계정을 고객 ID의 값으로 선택하므로 동작은 위와 같습니다.


* 이해 당사자를 통해: Dynamics는 연결을 사용하여 기회 생성 페이지에서 이해 당사자를 통해 연락하는 기회를 연결합니다. 이를 위해 모든 새 관련자에 대해 `opportunitycontactrole` 레코드를 만듭니다.

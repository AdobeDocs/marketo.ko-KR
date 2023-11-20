---
unique-page-id: 2953471
description: SFDC 동기화 - 사용자 지정 개체 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 사용자 지정 개체 동기화
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 0%

---

# SFDC 동기화: 사용자 지정 개체 동기화 {#sfdc-sync-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 지정 개체도 Marketo Engage의 일부일 수 있습니다. 설정 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!PREREQUISITES]
>
>사용자 지정 개체를 사용하려면 개체에 연결해야 합니다 [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md){target="_blank"}, [contact](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"}, or [account](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"} salesforce의 개체입니다.

>[!IMPORTANT]
>
>Marketo 동기화 사용자는 나열하고 동기화를 수행하려면 사용자 지정 개체에 대한 읽기 액세스 권한이 필요합니다.

## 사용자 지정 개체 사용  {#enable-custom-object}

1. 클릭 **[!UICONTROL 관리자]** 및 **[!UICONTROL Salesforce 개체 동기화]** 링크를 클릭합니다.

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. 첫 번째 사용자 지정 개체인 경우 **[!UICONTROL 동기화 스키마]**.

   ![](assets/rtaimage-2.png)

1. 클릭 **[!UICONTROL 전역 동기화 비활성화]**.

   ![](assets/image2015-4-22-10-3a45-3a0.png)

   >[!NOTE]
   >
   >Salesforce 사용자 지정 개체 스키마의 초기 동기화는 몇 분 정도 걸릴 수 있습니다.

   ![](assets/image2015-4-22-10-3a45-3a18.png)

1. 동기화하려는 사용자 지정 개체를 캔버스로 드래그합니다.

   ![](assets/image2015-4-22-10-3a45-3a30.png)

   >[!NOTE]
   >
   >사용자 지정 개체에는 고유한 이름이 있어야 합니다. Marketo은 이름이 같은 두 개의 서로 다른 사용자 지정 개체를 지원하지 않습니다.

1. 클릭 **[!UICONTROL 동기화 활성화]**.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. 클릭 **[!UICONTROL 동기화 활성화]** 다시.

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >전역 동기화를 다시 활성화하는 것을 잊지 마십시오!

1. 로 돌아가기 **Salesforce** 탭.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. 클릭 **[!UICONTROL 동기화 활성화]**.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. 모든 Salesforce 사용자 지정 개체를 보려면 **[!UICONTROL 관리자]** 및 **[!UICONTROL Salesforce 개체 동기화]** 링크(위의 1단계와 동일).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >Marketo은 1~2단계 수준의 표준 엔티티에 연결된 사용자 지정 엔티티만 지원합니다.

### 다음 단계: {#whats-next}

[사용자 지정 개체 필드를 스마트 목록/트리거 제한으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}

훌륭합니다! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

---
unique-page-id: 2953471
description: SFDC 동기화 - 사용자 지정 개체 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 사용자 지정 개체 동기화
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
feature: Salesforce Integration
source-git-commit: 79ae0d56dd4bb8bf563c6546cba54b89b5841425
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 0%

---

# SFDC 동기화: 사용자 지정 개체 동기화 {#sfdc-sync-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 지정 개체도 Marketo Engage의 일부일 수 있습니다. 설정 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!PREREQUISITES]
>
>사용자 지정 개체를 사용하려면 Salesforce의 [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md){target="_blank"}, [연락처](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md){target="_blank"} 또는 [계정](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md){target="_blank"} 개체와 연결되어 있어야 합니다.

>[!IMPORTANT]
>
>Marketo 동기화 사용자는 나열하고 동기화를 수행하려면 사용자 지정 개체에 대한 읽기 액세스 권한이 필요합니다.

## 사용자 지정 개체 사용  {#enable-custom-object}

1. **[!UICONTROL 관리자]** 및 **[!UICONTROL Salesforce 개체 동기화]** 링크를 클릭합니다.

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. 첫 번째 사용자 지정 개체인 경우 **[!UICONTROL 스키마 동기화]**&#x200B;를 클릭합니다.

   ![](assets/rtaimage-2.png)

1. **[!UICONTROL 전역 동기화 사용 안 함]**&#x200B;을 클릭합니다.

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

1. **[!UICONTROL 동기화 사용]**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. **[!UICONTROL 동기화 활성화]**&#x200B;를 다시 클릭합니다.

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >전역 동기화를 다시 활성화하는 것을 잊지 마십시오!

1. **Salesforce** 탭으로 돌아갑니다.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. **[!UICONTROL 동기화 사용]**&#x200B;을 클릭합니다.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. 모든 Salesforce 사용자 지정 개체를 보려면 **[!UICONTROL 관리자]** 및 **[!UICONTROL Salesforce 개체 동기화]** 링크(위의 1단계와 동일)를 클릭하십시오.

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >* Marketo은 1~2단계 수준의 표준 엔티티에 연결된 사용자 지정 엔티티만 지원합니다.
   >
   >* 사용자 지정 개체 트리는 주 개체 중 하나와의 직접 연결(예: 리드, 연락처 또는 계정 또는 중간 개체를 통한 간접 연결) 때문에 동일한 개체를 두 번 이상 표시할 수 있습니다. 이러한 경우 주 오브젝트와 가장 가까운 오브젝트를 선택하고 하나만 선택합니다. 동일한 개체를 여러 번 선택하면 해당 사용자 지정 개체의 동기화가 방해될 수 있습니다.

### 다음 단계: {#whats-next}

[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}

훌륭합니다! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

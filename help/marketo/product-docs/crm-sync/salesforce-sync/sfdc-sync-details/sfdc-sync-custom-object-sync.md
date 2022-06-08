---
unique-page-id: 2953471
description: SFDC 동기화 - 사용자 지정 개체 동기화 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 사용자 지정 개체 동기화
exl-id: e491e0bc-04a9-4e78-97c3-a25b945d546a
source-git-commit: e04e2d6932830535493c431de50d6cf9e2298fb1
workflow-type: tm+mt
source-wordcount: '214'
ht-degree: 0%

---

# SFDC 동기화: 사용자 지정 개체 동기화 {#sfdc-sync-custom-object-sync}

Salesforce 인스턴스에서 만든 사용자 지정 개체도 Marketo의 일부일 수 있습니다.  설정 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리 권한 필요**

>[!PREREQUISITES]
>
>사용자 지정 개체를 사용하려면 [리드](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-field-sync.md), [연락처](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-contact-sync.md), 또는 [account](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-account-sync.md) Salesforce의 개체

## 사용자 지정 개체 활성화  {#enable-custom-object}

1. 클릭 **관리** 그리고 **Salesforce 개체 동기화** 링크를 클릭합니다.

   ![](assets/image2015-11-19-10-3a28-3a5.png).

1. 첫 번째 사용자 지정 개체인 경우 **스키마 동기화**.

   ![](assets/rtaimage-2.png)

1. 클릭 **전역 동기화 비활성화**.

   ![](assets/image2015-4-22-10-3a45-3a0.png)

   >[!NOTE]
   >
   >Salesforce 사용자 지정 개체 스키마의 초기 동기화는 몇 분 정도 걸릴 수 있습니다.

   ![](assets/image2015-4-22-10-3a45-3a18.png)

1. 동기화할 사용자 지정 개체를 캔버스에 드래그합니다.

   ![](assets/image2015-4-22-10-3a45-3a30.png)

   >[!NOTE]
   >
   >사용자 지정 개체에는 고유한 이름이 있어야 합니다. Marketo에서는 이름이 같은 두 개의 다른 사용자 지정 개체를 지원하지 않습니다.

1. 클릭 **동기화 활성화**.

   ![](assets/image2015-4-22-10-3a45-3a50.png)

1. 클릭 **동기화 활성화** 다시 한 번

   ![](assets/image2015-4-22-10-3a46-3a10.png)

   >[!NOTE]
   >
   >글로벌 동기화를 다시 활성화하는 것을 잊지 마십시오!

1. 로 돌아갑니다. **Salesforce** 탭.

   ![](assets/image2015-4-22-10-3a46-3a25.png)

1. 클릭 **동기화 활성화**.

   ![](assets/image2015-4-22-10-3a50-3a26.png)

1. 모든 Salesforce 사용자 지정 개체를 보려면 **관리** 그리고 **Salesforce 개체 동기화** 링크(위의 1단계와 동일함).

   ![](assets/image2016-6-23-9-3a28-3a23.png)

   >[!NOTE]
   >
   >Marketo은 하나 또는 두 수준 깊이에 표준 엔티티에 연결된 사용자 지정 엔티티만 지원합니다.

### 다음은 무엇입니까? {#whats-next}

[사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/add-remove-custom-object-field-as-smart-list-trigger-constraints.md)

훌륭해요! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

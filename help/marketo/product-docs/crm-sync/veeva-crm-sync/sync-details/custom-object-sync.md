---
description: 사용자 지정 개체 동기화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 동기화
hide: true
hidefromtoc: true
exl-id: 68bc14e7-dfc9-4dce-b159-24d734ee3c6f
feature: Veeva CRM
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '201'
ht-degree: 0%

---

# 사용자 지정 개체 동기화 {#custom-object-sync}

Veeva CRM 인스턴스에서 만든 사용자 지정 개체도 Marketo Engage의 일부가 될 수 있습니다. 다음은 설정하는 방법입니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!PREREQUISITES]
>
>사용자 지정 개체를 사용하려면 Veeva CRM의 연락처 또는 계정 개체에 연결해야 합니다.

## 사용자 지정 개체 사용 {#enable-custom-object}

1. Marketo에서 **관리자**, 그런 다음 **Veeva 개체 동기화**.

   ![](assets/custom-object-sync-1.png)

1. 첫 번째 사용자 지정 개체인 경우 **동기화 스키마**.

   ![](assets/custom-object-sync-2.png)

1. 클릭 **전역 동기화 비활성화**.

   ![](assets/custom-object-sync-3.png)

   >[!NOTE]
   >
   >Veeva 사용자 지정 개체 스키마의 초기 동기화는 몇 분 정도 걸릴 수 있습니다.

1. 동기화하려는 사용자 지정 개체를 캔버스로 드래그합니다.

   ![](assets/custom-object-sync-4.png)

   >[!NOTE]
   >
   >사용자 지정 개체에는 고유한 이름이 있어야 합니다. Marketo은 이름이 같은 두 개의 서로 다른 사용자 지정 개체를 지원하지 않습니다.

1. 클릭 **동기화 활성화**.

   ![](assets/custom-object-sync-5.png)

1. 클릭 **동기화 활성화** 다시.

   ![](assets/custom-object-sync-6.png)

1. 로 돌아가기 **베바** 탭.

   ![](assets/custom-object-sync-7.png)

1. 클릭 **동기화 활성화**.

   ![](assets/custom-object-sync-8.png)

1. Veeva 사용자 지정 개체를 모두 보려면 [관리] 및 [Veeva 개체 동기화]를 클릭하십시오.

   ![](assets/custom-object-sync-9.png)

   >[!NOTE]
   >
   >Marketo은 1~2단계 수준의 표준 엔티티에 연결된 사용자 지정 엔티티만 지원합니다.

훌륭합니다! 이제 스마트 캠페인 및 스마트 목록에서 이 사용자 지정 개체의 데이터를 사용할 수 있습니다.

>[!MORELIKETHIS]
>
>* [통화 및 통화 키 메시지 동기화](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/syncing-call-and-call-key-messages.md){target="_blank"}
>* [사용자 지정 개체 필드를 스마트 목록/트리거 제약 조건으로 추가/제거](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/add-remove-custom-object-field-as-smart-list-trigger-constraints.md){target="_blank"}

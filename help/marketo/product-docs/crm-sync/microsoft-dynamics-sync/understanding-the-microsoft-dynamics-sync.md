---
unique-page-id: 10098625
description: ' [!DNL Microsoft Dynamics] 동기화 이해 - Marketo 문서 - 제품 설명서'
title: Microsoft Dynamics 동기화 이해
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '209'
ht-degree: 3%

---

# [!DNL Microsoft Dynamics] 동기화 이해 {#understanding-the-microsoft-dynamics-sync}

Marketo과 [!DNL Microsoft Dynamics]이(가) 함께 제공됩니다. Dell은 고객의 판매 및 마케팅 데이터를 동기화합니다.

>[!CAUTION]
>
>현재 [!DNL Marketo Dynamics] 동기화에 대한 샌드박스 새로 고침을 지원하지 않습니다. [!DNL Dynamics] CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

## 동기화 작동 방식 {#how-sync-works}

Marketo은 매일 하루 종일 데이터를 [!DNL Microsoft Dynamics]과(와) 계속 동기화합니다. 실시간으로 동기화되지 않고 백그라운드 동기화를 일괄적으로 사용하여 수행됩니다.

>[!NOTE]
>
>데이터베이스의 크기에 따라 구독의 첫 번째 동기화에 몇 분에서 몇 시간이 걸립니다. Marketo은 [!DNL Dynamics]에서 전체 데이터베이스를 복사합니다. 이후 각 동기화는 일반적으로 초 또는 분이 소요되며 변경된 데이터만 동기화합니다.

Marketo과 [!DNL Dynamics] 간의 동기화는 리드나 연락처에 양방향 동기화입니다. Marketo 또는 [!DNL Dynamics]에서 변경 작업을 수행하면 업데이트가 두 시스템에 반영됩니다. 계정 및 기회와 같은 다른 모든 필드는 [!DNL Dynamics]에서 Marketo으로 한 방향으로만 동기화됩니다.

## Marketo과 [!DNL Microsoft Dynamics] 간에 동기화되는 것은 무엇입니까? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [잠재 고객](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [연락처](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [계정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [사용자](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* 팀(SystemUsers 그룹)
* [기회](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [사용자 지정 엔티티](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/enable-sync-for-a-custom-entity.md)

[에 대해 Marketo에 입력한  [!DNL Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)자격 증명은 데이터를 동기화하는 데 사용됩니다.

>[!NOTE]
>
>원본 인스턴스가 [!DNL Microsoft Dynamics]과(와) 통합되는 경우 인스턴스 복사가 지원되지 않습니다.

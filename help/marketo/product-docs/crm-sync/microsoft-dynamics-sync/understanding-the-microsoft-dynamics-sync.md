---
unique-page-id: 10098625
description: Microsoft Dynamics 동기화 이해 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 이해
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
source-git-commit: 80651a7d3d416f27ef13184b11757943c98bd781
workflow-type: tm+mt
source-wordcount: '242'
ht-degree: 0%

---

# Microsoft Dynamics 동기화 이해 {#understanding-the-microsoft-dynamics-sync}

Marketo과 Microsoft Dynamics가 함께 제공됩니다. Adobe는 귀사의 영업 및 마케팅 자료를 계속 동기화합니다.

>[!NOTE]
>
>Marketo은 현재 Java 7과 호환되는 SSL 세트만 지원합니다.

>[!CAUTION]
>
>현재 Marketo Dynamics Sync에 대한 샌드박스 새로 고침을 지원하지 않습니다. Dynamics CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

## 동기화 작동 방식 {#how-sync-works}

Marketo은 매일 데이터를 Microsoft Dynamics와 지속적으로 동기화합니다. 백그라운드 동기화를 사용하지 않고 일괄적으로 수행합니다.

>[!NOTE]
>
>구독의 첫 번째 동기화는 데이터베이스 크기에 따라 몇 분에서 몇 시간 정도가 소요됩니다. Marketo은 Dynamics에서 전체 데이터베이스를 복사합니다. 이후 각 동기화는 일반적으로 초 또는 분이 걸리며 변경된 데이터만 동기화합니다.

Marketo과 Dynamics 간의 동기화는 리드와 연락처에 대한 양방향 동기화입니다. Marketo 또는 Dynamics에서 변경 작업을 수행하면 업데이트가 두 시스템 모두에 반영됩니다. 계정 및 기회와 같은 다른 모든 필드는 Dynamics에서 Marketo으로 한 방향으로만 동기화됩니다.

## Marketo과 Microsoft Dynamics 간에 동기화되는 기능 {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [리드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [연락처](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [계정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [사용자](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* 팀(SystemUsers 그룹)
* [기회](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [사용자 지정 엔티티](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md)용 Marketo에 입력하는 [자격 증명은 데이터를 동기화하는 데 사용됩니다.

>[!NOTE]
>
>원본 인스턴스가 Microsoft Dynamics와 통합된 경우 인스턴스 복사본이 지원되지 않습니다.

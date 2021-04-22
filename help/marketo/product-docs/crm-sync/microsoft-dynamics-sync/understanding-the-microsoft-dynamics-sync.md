---
unique-page-id: 10098625
description: Microsoft Dynamics Sync 이해 - Marketo Docs - 제품 설명서
title: Microsoft Dynamics Sync 이해
exl-id: bc87f744-7f1c-421b-8507-1a6e23d27fa2
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 0%

---

# Microsoft Dynamics 동기화 이해 {#understanding-the-microsoft-dynamics-sync}

Marketo과 Microsoft Dynamics 간의 긴밀한 통합을 활용하여 Adobe는 귀사의 세일즈 및 마케팅 데이터를 일관되게 유지합니다.

>[!NOTE]
>
>Marketo은 현재 Java 7과 호환되는 SSL 인증서만 지원합니다.

## 동기화 작동 방식 {#how-sync-works}

Marketo은 하루 종일 Microsoft Dynamics와 데이터를 지속적으로 동기화합니다. 백그라운드 동기화를 실시간으로 수행하지 않고 일괄적으로 수행할 수 있습니다.

>[!NOTE]
>
>구독의 첫 번째 동기화는 데이터베이스의 크기에 따라 몇 분에서 몇 시간 정도 소요됩니다. Marketo은 Dynamics에서 전체 데이터베이스를 복사합니다. 이후 각 동기화는 일반적으로 몇 초 또는 몇 분이 걸리고 변경된 데이터만 동기화합니다.

Marketo과 Dynamics 간의 동기화는 리드와 연락처에 양방향 방식으로 이루어집니다. Marketo 또는 Dynamics에서 변경 작업을 수행하면 업데이트가 두 시스템에 모두 반영됩니다. 계정 및 기회 등 다른 모든 필드는 Dynamics에서 Marketo으로 한 방향으로만 동기화됩니다.

## Marketo과 Microsoft Dynamics 간에 동기화되는 내용은 무엇입니까?{#what-is-synced-between-marketo-and-microsoft-dynamics}

* [리드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [연락처](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [계정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [사용자](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* 팀(SystemUsers 그룹)
* [기회](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [맞춤형 엔티티](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

>[!NOTE]
>
>Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md)용 Marketo에 입력한 [자격 증명은 데이터를 동기화하는 데 사용됩니다.

>[!CAUTION]
>
>현재 Marketo Dynamics Sync에 대한 샌드박스 새로 고침을 지원하지 않습니다. Dynamics CRM 샌드박스를 새로 고쳐야 하는 경우 새 Marketo 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

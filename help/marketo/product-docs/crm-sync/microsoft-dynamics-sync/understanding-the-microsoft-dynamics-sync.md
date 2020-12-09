---
unique-page-id: 10098625
description: Microsoft Dynamics Sync 이해 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 이해
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---


# Microsoft Dynamics 동기화 이해 {#understanding-the-microsoft-dynamics-sync}

Marketing Cloud와 Microsoft Dynamics 간의 긴밀한 협력 관계 Adobe는 귀사의 세일즈 및 마케팅 데이터를 일관되게 유지합니다.

>[!NOTE]
>
>Marketing은 현재 Java 7과 호환되는 SSL 인증서만 지원합니다.

## 동기화 방법 {#how-sync-works}

Marketing Cloud는 하루 종일 데이터를 Microsoft Dynamics와 지속적으로 동기화합니다. 백그라운드 동기화 기능을 사용하면 실시간으로 수행할 수 없습니다.

>[!NOTE]
>
>사용료 지불 옵션의 최초 동기화 작업은 데이터베이스 크기에 따라 몇 분에서 몇 시간 정도 소요됩니다. Marketing은 Dynamics에서 전체 데이터베이스를 복사합니다. 이후 각 동기화는 일반적으로 몇 초 또는 몇 분이 소요되며 변경된 데이터만 동기화합니다.

Marketing To와 Dynamics 간의 동기화는 리드 및 연락처에 양방향 개념입니다. Marketing 또는 Dynamics 중 하나를 변경하면 업데이트가 두 시스템에 모두 반영됩니다. 계정 및 기회와 같은 다른 모든 필드는 Dynamics에서 Marketing에 이르기까지 한 방향으로만 동기화됩니다.

## Marketing To와 Microsoft Dynamics 간에 동기화되는 것은 무엇입니까? {#what-is-synced-between-marketo-and-microsoft-dynamics}

* [리드](microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md)
* [연락처](microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md)
* [계정](microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md)
* [사용자](microsoft-dynamics-sync-details/microsoft-dynamics-sync-user-sync.md)
* 팀(SystemUsers 그룹)
* [기회](microsoft-dynamics-sync-details/microsoft-dynamics-sync-opportunity-sync.md)
* [사용자 지정 엔티티](microsoft-dynamics-sync-details/microsoft-dynamics-sync-custom-entity-sync.md)

>[!NOTE]
>
>Dynamics용 Marketing [에 입력하는 자격](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-2-of-3-set-up.md) 증명은 데이터를 동기화하는 데 사용됩니다.

Dynamics 동기화에 대한 미묘한 차이와 기능이 많습니다. 자세한 내용은 [Microsoft Dynamics 동기화 세부 정보 섹션에서 확인하십시오](http://docs.marketo.com/display/docs/microsoft+dynamics+sync+details).

>[!CAUTION]
>
>현재 Marketing to Dynamics Sync에 대한 샌드박스 새로 고침을 지원하지 않습니다. Dynamics CRM 샌드박스를 새로 고쳐야 하는 경우 새로운 Marketing To 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

>[!MORELIKETHIS]
>
>* [설정 동기화](http://docs.marketo.com/display/docs/sync+setup)
   >
   >
* [Microsoft Dynamics 동기화 세부 정보](http://docs.marketo.com/display/docs/microsoft+dynamics+sync+details)


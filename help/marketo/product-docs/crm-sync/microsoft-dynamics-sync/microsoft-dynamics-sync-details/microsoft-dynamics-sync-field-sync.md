---
unique-page-id: 3571838
description: Microsoft Dynamics 동기화 -필드 동기화 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 - 필드 동기화
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '364'
ht-degree: 0%

---


# Microsoft Dynamics 동기화:필드 동기화 {#microsoft-dynamics-sync-field-sync}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

Marketing to Dynamics 동기화가 매우 강력합니다. 자세한 내용

## 필드 세부 정보는 두 시스템 간에 어떻게 동기화됩니까? {#how-are-field-details-kept-in-sync-between-the-two-systems}

동기화는 리드 및 연락처 개체에 대한 양방향 동기화입니다. Dynamics 또는 Marketing To에서 리드 또는 담당자를 변경하면 업데이트 내용이 두 시스템 모두에 반영됩니다.

계정, 사용자, 기회, 팀 및 맞춤형 엔티티의 경우 동기화가 단방향으로 이루어집니다.Adobe Marketing Cloud Dynamics에서 이러한 엔티티를 변경하면 업데이트가 Marketing To에 반영됩니다.

## 두 시스템에서 동시에 동일한 필드를 변경하면 어떻게 됩니까? (데이터 충돌) {#what-if-changes-are-made-to-the-same-field-in-both-systems-at-the-same-time-data-collision}

이러한 경우가 드물지만 Marketing은 사람(리드)에게 유리하며 Dynamics는 고객 접점에 유리합니다. 이는 Adobe가 마케팅 부서가 사람들에게 권위적이라고 간주하는 반면 연락처의 공식 기록 시스템은 판매(CRM) 부서에 있기 때문입니다. 단방향 동기화 개체의 경우 Dynamics는 항상 이기게 됩니다.

## Marketing To를 사용하여 Dynamics 필드를 만들 수 있습니까? {#can-i-create-a-field-in-dynamics-using-marketo}

아니요, 현재 지원되지 않습니다.

## Dynamics에서 필드를 만들었습니다. Marketing To에 동기화할 수 있습니까? {#i-created-a-field-in-dynamics-can-i-sync-it-to-marketo}

예. 동기화 사용자가 Dynamics에서 해당 필드에 [액세스할 수](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) 있는 한 필드를 동기화할 수 있습니다.

어떤 필드가 Marketing To와 동기화됩니까?

설정하는 동안 동기화할 [필드를](https://docs.marketo.com/pages/viewpage.action?pageId=3571830#Step3of3:ConnectMicrosoftDynamicswithMarketo(Online)-SelectFieldstoSync) 선택할 수 있습니다.

## Marketing To 및 Dynamics가 동기화된 후 사용자 정의 필드를 추가해야 하는 경우 어떻게 됩니까? {#what-if-i-need-to-add-a-custom-field-after-marketo-and-dynamics-are-synced}

언제든지 필드를 추가할 수 있으며 데이터가 Dynamics에서 Marketing으로 새로 고쳐질 것으로 예상합니다. 자세한 [내용은 Microsoft Dynamics와 빠른 동기화 사용을](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md) 참조하십시오.

>[!NOTE]
>
>**관련 문서**
>
>* [Microsoft Dynamics와 빠른 동기화를 사용하여 새 사용자 지정 필드 사용](microsoft-dynamics-sync-field-sync/use-quick-sync-with-microsoft-dynamics-for-a-new-custom-field.md)

>




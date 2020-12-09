---
unique-page-id: 4719283
description: Salesforce 동기화 이해 - Marketing To Docs - 제품 설명서
title: Salesforce 동기화 이해
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---


# Salesforce 동기화 이해 {#understanding-the-salesforce-sync}

Marketing과 Salesforce는 완두콩 및 당근과 같이 통합됩니다. Adobe는 귀사의 세일즈 및 마케팅 데이터를 일관되게 유지합니다.

## 동기화 방법 {#how-sync-works}

Marketing to는 하루 종일 Salesforce와 동기화됩니다. 각 동기화에는 약간의 시간이 소요되고 5분 동안 일시 정지한 다음 다시 시작됩니다.

>[!NOTE]
>
>Marketing to가 Salesforce에서 전체 데이터베이스를 복사하고 있으므로 사용료 지불 옵션의 최초 동기화 작업은 몇 시간 또는 며칠이 걸릴 수 있습니다. 이후 각 동기화는 일반적으로 몇 초 또는 몇 분이 소요되며 변경된 데이터만 동기화합니다.

![](assets/sync-illustration.png)

Salesforce와 Marketing의 동기화는 리드, 연락처 및 Salesforce 캠페인에 대해서만 양방향 개념으로 이루어집니다. 이러한 경우 Salesforce 또는 Marketing Cloud 중 하나를 변경하면 업데이트가 두 시스템 모두에 반영됩니다. 다른 모든 동기들은 Salesforce에서 Marketing에만 제공됩니다. 각 링크에 대한 자세한 내용을 보려면 아래 링크를 클릭하십시오.

## Marketing To와 Salesforce 간에 동기화되는 항목 {#what-is-synced-between-marketo-and-salesforce}

* [리드](sfdc-sync-details/sfdc-sync-lead-sync.md)
* [연락처](sfdc-sync-details/sfdc-sync-contact-sync.md)
* [계정](sfdc-sync-details/sfdc-sync-account-sync.md)
* [사용자](sfdc-sync-details/sfdc-sync-lead-account-owner-sync.md)
* [기회](sfdc-sync-details/sfdc-sync-opportunity-sync.md)
* [Salesforce 캠페인](sfdc-sync-details/sfdc-sync-campaign-sync.md)
* [사용자 정의 개체](sfdc-sync-details/sfdc-sync-custom-object-sync.md)
* [활동](sfdc-sync-details/sfdc-sync-activity-sync.md)

>[!NOTE]
>
>Salesforce용 [Marketing](setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) 에서 입력한 자격 증명은 데이터를 동기화하는 데 사용됩니다. 액세스 권한이 있는 데이터만 포함됩니다.

Salesforce 동기화에 대한 많은 미묘한 점과 기능이 있습니다. SFDC 동기화 세부 정보 섹션에서 [세부 사항을 확인하십시오](http://docs.marketo.com/display/docs/sfdc+sync+details).

>[!MORELIKETHIS]
>
>* [Salesforce 동기화 설정](http://docs.marketo.com/display/docs/setup)
>* [SFDC 동기화 세부 정보](http://docs.marketo.com/display/docs/sfdc+sync+details)

>



Marketing&#39;s는 Salesforce와 동기화되어 있으며 세계에서 가장 강력한 기능을 제공합니다. 마치 마술처럼 느껴집니다. 변화가 일어나고 다른 시스템이 곧 최신입니다.
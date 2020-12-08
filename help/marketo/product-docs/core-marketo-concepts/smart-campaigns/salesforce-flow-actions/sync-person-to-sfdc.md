---
unique-page-id: 1147027
description: SFDC에 사람 동기화 - Marketing To Docs - 제품 설명서
title: SFDC에 사람 동기화
translation-type: tm+mt
source-git-commit: 00887ea53e395bea3a11fd28e0ac98b085ef6ed8
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 0%

---


# SFDC에 사람 동기화 {#sync-person-to-sfdc}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

>[!NOTE]
>
>Salesforce와 통합된 경우에만 제공됩니다.

## 개요 {#overview}

이 흐름 단계에서는 Salesforce CRM에 리드로 Marketing에서 만든 사람을 삽입합니다.

![](assets/sync-person-to-sfdc.png)

## 사용 {#usage}

1. 기본적으로 이 흐름 단계는 Salesforce 자동 할당 규칙에 따라 리드 소유자에게 지정됩니다.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Salesforce에서는 회사 및 성 필드가 채워져야 합니다. 그렇지 않으면 리드 레코드가 거부됩니다.

1. 특정 Salesforce 사용자 또는 리드 큐를 리드 소유자로 설정할 수 있습니다.

   ![](assets/sync-person-to-sfdc-2.png)

   이 흐름 단계를 사용하면 Salesforce 리드로 즉시 동기화되므로 정기적인 동기화를 기다릴 필요가 없습니다.

   >[!CAUTION]
   >
   >Salesforce에서는 &quot;연락처&quot;를 리드 대기열에 할당할 수 없습니다. 이 경우 Marketing은 Salesforce에 중복된 &quot;리드&quot;를 만듭니다.


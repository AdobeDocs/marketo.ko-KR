---
unique-page-id: 7515133
description: SFDC 동기화 - 리드/담당자 병합 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드/담당자 병합
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---

# SFDC 동기화:리드/연락처/사람 병합 {#sfdc-sync-merging-a-lead-contact-person}

때때로 규칙을 나열하는 것이 가장 좋습니다. 여기 있습니다.

* **Salesforce**&#x200B;에서 2개의 리드를 병합하면 일반 동기화가 Marketo에 지시하고 리드가 Marketo의 리드로 자동으로 병합됩니다.
* **Marketo**&#x200B;에서 두 사람을 병합하면 실제로 Salesforce에서 리드로 병합하는 것과 동일한 프로세스가 호출됩니다. 자동으로 작동합니다.
* **리드(개인)를 담당자**&#x200B;에 병합하는 것도 같은 방식으로 작동합니다. 양쪽에 하나의 접촉을 갖게 됩니다.
* 병합하면 기본 점수가 합해집니다.

>[!NOTE]
>
>3개의 리드(사람)를 각각 10개의 점수로 병합하면 1개의 리드(사람)가 30점을 얻게 됩니다.

* 충돌하는 필드 값은 &quot;우승 레코드&quot;에서 가져옵니다. (레코드 = 결과 리드 또는 연락처)
* &quot;패자 기록&quot;(사라지는 기록)에 값이 있고 우승 기록이 없으면, 우리는 패하는 기록을 유지할 것이다. 즉, &quot;어떤 값은 없는 것보다 낫다.&quot;
* 모든 활동 로그 항목이 병합됩니다.

>[!NOTE]
>
>Marketo](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md)의 사람 병합에 대한 자세한 내용은 자세히 참조하십시오.[

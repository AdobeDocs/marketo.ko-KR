---
unique-page-id: 7515133
description: SFDC 동기화 - 잠재 고객/연락처/사용자 병합 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 잠재 고객/연락처/사용자 병합
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
feature: Salesforce Integration
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '192'
ht-degree: 3%

---

# SFDC 동기화: 리드/연락처/개인 병합 {#sfdc-sync-merging-a-lead-contact-person}

가끔은 규칙만 나열하는 것이 가장 좋습니다. 이제 시작하겠습니다.

* **[!DNL Salesforce]**&#x200B;에서 두 개의 리드를 병합하면 일반 동기화가 Marketo에 알려주고 리드는 Marketo의 사용자로 자동으로 병합됩니다.
* **Marketo**&#x200B;에서 두 사람을 병합하면 실제로 [!DNL Salesforce]의 리드로 병합하는 것과 동일한 프로세스가 호출됩니다. 여전히 자동으로 작동합니다.
* **잠재 고객(개인)을 연락처에 병합**&#x200B;하는 동일한 방식으로 작동합니다. 결국 양쪽에 단일 접점이 생깁니다.
* 병합하면 기본 점수가 합산됩니다.

>[!NOTE]
>
>점수가 각각 10인 3개의 리드(사람)를 병합하면 점수가 30인 1개의 리드(사람)의 결과가 생성됩니다.

* 충돌하는 필드 값은 &quot;우승 레코드&quot;에서 가져옵니다. (레코드 = 결과 리드 또는 연락처)
* &#39;패배 기록&#39;(사라지는 기록)이 가치가 있고 우승 기록이 없다면 패배 기록을 그대로 유지하겠다는 것이다. 즉, &quot;어떤 가치가 없는 것보다 낫다.&quot;
* 모든 활동 로그 항목이 병합됩니다.

>[!NOTE]
>
>[Marketo에서 사용자 병합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target="_blank"}에 대한 자세한 내용을 자세히 알아보세요.

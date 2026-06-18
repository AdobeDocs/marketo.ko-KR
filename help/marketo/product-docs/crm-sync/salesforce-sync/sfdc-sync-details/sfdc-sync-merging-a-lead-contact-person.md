---
unique-page-id: 7515133
description: Salesforce 및 Marketo의 잠재 고객, 연락처 및 사용자 병합이 작동하는 방식을 이해합니다. 점수, 필드 값 및 활동 로그에 대한 병합 규칙에 대해 알아봅니다.
title: SFDC 동기화 - 잠재 고객/연락처/사용자 병합
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
feature: Salesforce Integration
TQID: https://experienceleague.adobe.com/alPa6YMG0tgo08ruZAZlWhujV54iVcUMAAejXJbEQFw
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
source-git-commit: 18ccc13ddd9cfb998015bb581373a7ca7c064d59
workflow-type: tm+mt
source-wordcount: 268
ht-degree: 2%

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
* &#39;패소 기록&#39;(사라지는 기록)에 값이 있고 우승 기록에 값이 없다면(또는 null이면) 패소 기록을 유지한다. 즉, &quot;어떤 가치가 없는 것보다 낫다.&quot;
* 모든 활동 로그 항목이 병합됩니다.

>[!NOTE]
>
>API 병합의 부울 필드 동작이 2026년 3월 릴리스에서 변경되었습니다. 이제 False 값은 해당 필드에 대한 값이 있는 것으로 올바르게 처리됩니다. 충돌하는 필드를 평가할 때는 null 값만 &quot;비어 있음&quot;으로 처리됩니다. 자세한 내용은 [이 커뮤니티 게시물](https://experienceleaguecommunities.adobe.com/adobe-marketo-engage-27/api-merge-functionality-for-boolean-fields-251219?profile.language=ko){target="_blank"}을 참조하세요.

>[!MORELIKETHIS]
>
>[Marketo에서 사용자 병합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md)에 대한 자세한 내용을 자세히 알아보세요.

---
unique-page-id: 7515133
description: SFDC 동기화 - 리드/연락처/사람 병합 - Marketo 문서 - 제품 설명서
title: SFDC 동기화 - 리드/연락처/사람 병합
exl-id: 0e755c80-27cd-4ba3-b540-d7918264c5f6
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '190'
ht-degree: 0%

---

# SFDC 동기화: 리드/연락처/개인 병합 {#sfdc-sync-merging-a-lead-contact-person}

가끔 규칙을 나열하는 것이 가장 좋은 방법이에요. 여기 있습니다.

* 두 리드를 병합할 때 **Salesforce**&#x200B;의 경우 일반 동기화는 Marketo에 알리며 리드가 Marketo의 사용자로 자동으로 병합됩니다.
* 두 사람 병합 **Marketo** 실제로 는 Salesforce에서 리드로 병합하는 것과 동일한 프로세스를 호출합니다. 여전히 자동으로 작동합니다.
* 병합 **연락처에 리드(사람)** 같은 방식으로 작동합니다. 양쪽에 한 번의 접촉으로 끝납니다.
* 병합할 때 기본 점수가 합산됩니다.

>[!NOTE]
>
>3개의 리드(사람)를 각각 10개의 점수와 병합하면 1개의 리드(사람)와 30개의 점수가 생성됩니다.

* 충돌하는 필드 값은 &quot;우승 레코드&quot;에서 가져옵니다. (레코드 = 결과 리드 또는 연락처)
* &quot;패킹 레코드&quot;(사라지는 레코드)에 값이 있고 우승 레코드가 없으면 우리는 패하는 레코드를 유지할 것입니다. 즉, &quot;어떤 값은 없는 것보다 낫다.&quot;
* 모든 활동 로그 항목이 병합됩니다.

>[!NOTE]
>
>자세히 알아보기 [Marketo의 사람 병합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md).

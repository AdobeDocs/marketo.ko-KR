---
unique-page-id: 7515133
description: SFDC 동기화 - 리드/연락처/담당자 병합 - 마케팅 문서 - 제품 설명서
title: SFDC 동기화 - 리드/연락처/사람 병합
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '244'
ht-degree: 0%

---


# SFDC 동기화:리드/연락처/사람 병합 {#sfdc-sync-merging-a-lead-contact-person}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

경우에 따라 규칙을 나열하는 것이 가장 좋습니다. 여기 있습니다.

* Salesforce에서 두 개의 리드를 **병합하면 일반**&#x200B;동기화가 Marketing To에 연결되고 리드가 Marketing To의 리드로 자동으로 병합됩니다.
* Marketing **에서** 두 사람을 병합하면 Salesforce에서 리드로 병합하는 것과 동일한 프로세스를 불러옵니다. 자동으로 작동합니다.
* 담당자 **에 리드(사람)를 병합하는** 방법은 동일하게 작동합니다. 양쪽에 한 번의 접촉으로 끝납니다.
* 병합하면 기본 점수가 합해집니다.

>[!NOTE]
>
>**예**
>
>3개의 리드(사람)를 각각 10점으로 병합하면 1개의 리드(사람)가 30점을 얻게 됩니다.

* 충돌하는 필드 값은 &quot;우승 레코드&quot;에서 가져옵니다. (레코드 = 결과 리드 또는 연락처)
* 만약 &quot;패자 기록&quot;(사라지는 기록)이 가치가 있고 우승 기록이 없다면, 우리는 패자 기록을 유지할 것이다. 즉, &quot;어떤 값은 없는 것보다 낫다.&quot;
* 모든 활동 로그 항목이 병합됩니다.

>[!NOTE]
>
>**딥 다이브**
>
>Marketing [에서 사용자를 통합하는 방법에 대한 자세한 내용을 살펴보십시오](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md).


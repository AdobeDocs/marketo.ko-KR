---
unique-page-id: 11375827
description: Dynamics와 Marketo 동기화를 위한 필수 필드 - Marketo 문서 - 제품 설명서
title: Dynamics와 Marketo 동기화를 위한 필수 필드
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Dynamics와 Marketo 동기화를 위한 필수 필드 {#required-fields-for-syncing-marketo-with-dynamics}

다음 필드 *반드시* Lead 와 Sales Insight 의 Contact for Lead 가 모두 작동하기 위해 Marketo 와 동기화됩니다.

* 우선 순위
* 긴급성
* 상대 점수

이러한 필드가 누락된 경우 누락된 필드의 이름이 있는 오류 메시지가 Marketo에 표시됩니다. 이 문제를 해결하려면 인스턴스에서 두 필드를 모두 동기화하는지 확인합니다 **리드** 및 **연락처**. 없는 경우 추가합니다.

동기화 필드를 확인하고 추가하는 방법은 다음과 같습니다.

1. Admin으로 이동하고 다음을 클릭합니다. **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 클릭 **편집** 필드 동기화 세부 정보

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Lead에서 Priority 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. 이제 아래로 스크롤하여 긴급성 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...및 상대 점수 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. 다음으로 연락처에 대한 우선순위, 긴급성 및 상대 점수의 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. 클릭 **저장**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>문제가 해결되었는지 확인하기 전에 동기화가 실행될 때까지 최소 10분을 대기하십시오.

>[!MORELIKETHIS]
>
>[리드/연락처 레코드에 대한 별과 불길 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

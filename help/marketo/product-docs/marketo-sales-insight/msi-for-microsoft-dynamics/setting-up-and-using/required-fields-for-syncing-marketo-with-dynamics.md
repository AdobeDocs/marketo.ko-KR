---
unique-page-id: 11375827
description: Marketo과 Dynamics 동기화 필수 필드 - Marketo 문서 - 제품 설명서
title: Marketo과 Dynamics 동기화 필수 필드
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Marketo과 Dynamics 동기화 필수 필드 {#required-fields-for-syncing-marketo-with-dynamics}

이 필드 *필수* 리드 및 Sales Insight 의 연락처가 작동하도록 Marketo 와 동기화합니다.

* 우선 순위
* 긴급도
* 상대 스코어

이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 인스턴스를 체크인하여 필드가 둘 다에 대해 동기화되었는지 확인합니다 **리드** 및 **연락처**. 그렇지 않으면 추가합니다.

다음은 동기화 필드를 확인하고 추가하는 방법입니다.

1. 관리자로 이동하여 **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 클릭 **편집** 필드 동기화 세부 정보.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Lead에서 Priority 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. 이제 아래로 스크롤하여 긴급도 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...및 상대 점수 확인란입니다.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. 다음으로 연락처의 우선 순위, 긴급도 및 상대 점수에 대한 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. 클릭 **저장**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>문제가 해결되었는지 확인하기 전에 동기화가 실행될 때까지 최소 10분 정도 기다리십시오.

>[!MORELIKETHIS]
>
>[Lead/Contact Records에 Stars 및 Flames 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

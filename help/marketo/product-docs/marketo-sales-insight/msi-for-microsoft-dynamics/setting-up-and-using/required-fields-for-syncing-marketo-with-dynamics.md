---
unique-page-id: 11375827
description: Marketo과 Dynamics 동기화 필수 필드 - Marketo 문서 - 제품 설명서
title: Marketo과 Dynamics 동기화 필수 필드
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 1%

---

# Marketo과 Dynamics 동기화 필수 필드 {#required-fields-for-syncing-marketo-with-dynamics}

Sales Insight가 작동하려면 리드 및 연락처의 다음 필드를 *반드시* Marketo과 동기화해야 합니다.

* 우선 순위
* 긴급도
* 상대 스코어

이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 인스턴스를 확인하여 **리드** 및 **연락처**&#x200B;에 대해 필드가 동기화되었는지 확인하십시오. 그렇지 않으면 추가합니다.

다음은 동기화 필드를 확인하고 추가하는 방법입니다.

1. 관리자로 이동하여 **Microsoft Dynamics**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 동기화 세부 정보에서 **편집**&#x200B;을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Lead에서 Priority 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. 이제 아래로 스크롤하여 긴급도 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...및 상대 점수 확인란입니다.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. 다음으로 연락처의 우선 순위, 긴급도 및 상대 점수에 대한 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>문제가 해결되었는지 확인하기 전에 동기화가 실행될 때까지 최소 10분 정도 기다리십시오.

>[!MORELIKETHIS]
>
>[잠재 고객/연락처 레코드에 대한 별과 불꽃놀이 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

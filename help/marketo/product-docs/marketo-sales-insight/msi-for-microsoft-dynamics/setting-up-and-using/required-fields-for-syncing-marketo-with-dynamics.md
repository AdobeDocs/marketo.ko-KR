---
unique-page-id: 11375827
description: Marketo과 Dynamics 동기화 필수 필드 - Marketo 문서 - 제품 설명서
title: Marketo과 Dynamics 동기화 필수 필드
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '150'
ht-degree: 1%

---

# Marketo을 [!DNL Dynamics]과(와) 동기화하기 위한 필수 필드 {#required-fields-for-syncing-marketo-with-dynamics}

*이(가) 작동하려면*&#x200B;과(와) [!UICONTROL Lead]에 대해 이 필드 [!UICONTROL Contact]은(는) Marketo과 동기화되어야[!DNL Sales Insight]합니다.

* 우선순위
* 긴급도
* 상대 스코어

이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 인스턴스를 검사하여 **[!UICONTROL Lead]**&#x200B;과(와) **[!UICONTROL Contact]** 모두에 대해 필드가 동기화되었는지 확인하십시오. 그렇지 않으면 추가합니다.

다음은 동기화 필드를 확인하고 추가하는 방법입니다.

1. [!UICONTROL Admin]&#x200B;(으)로 이동하여 **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. **[!UICONTROL Edit]**&#x200B;에서 [!UICONTROL Field Sync Details]을(를) 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. [!UICONTROL Lead]에서 [!UICONTROL Priority] 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. 이제 아래로 스크롤하여 [!UICONTROL Urgency] 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...및 [!UICONTROL Relative Score] 확인란입니다.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. [!UICONTROL Priority]에 대해 [!UICONTROL Urgency], [!UICONTROL Relative Score] 및 [!UICONTROL Contact]의 확인란을 선택합니다.

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>문제가 해결되었는지 확인하기 전에 동기화가 실행될 때까지 최소 10분 정도 기다리십시오.

>[!MORELIKETHIS]
>
>[잠재 고객/연락처 레코드에 대한 별과 불꽃놀이 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

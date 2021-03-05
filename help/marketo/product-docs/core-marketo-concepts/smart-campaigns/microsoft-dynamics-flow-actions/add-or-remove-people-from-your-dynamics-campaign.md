---
description: Dynamics 캠페인 - Marketing To Docs - 제품 문서에서 인물 추가 또는 제거
title: Dynamics 캠페인에서 인물 추가 또는 제거
translation-type: tm+mt
source-git-commit: 1649aae540204bb5de205e3f5b75ec7e968a7da4
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 0%

---


# Dynamics 캠페인 {#add-or-remove-people-from-your-dynamics-campaign}에서 인물 추가 또는 제거

## Dynamics 캠페인 {#add-to-dynamics-campaign}에 추가

이 흐름 단계는 Marketing to Smart Campaigns에서 사용하여 Microsoft 캠페인에서 리드나 연락처로 사람을 추가할 수 있습니다. 리드가 아직 Dynamics에 없는 경우 자동으로 동기화되고 캠페인에 추가됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

스마트한 캠페인에서 사람을 추가할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* 캠페인 동기화가 작동하는지 확인합니다.
>* Microsoft Dynamics에서 캠페인이 활성화되지 않았습니다.


시스템은 리드 및 연락처에 대해 각각 캠페인을 위한 특정 정적 마케팅 목록을 자동으로 만들어 개인을 추가합니다. 일회성 작업이며, 후속 캠페인에 대해 동일한 마케팅 목록이 사용됩니다. 정적 마케팅 목록 이름에 대해 채택된 이름 지정 표준은 리드의 경우 `Mkto-leads-<uniqueID>`, 연락처의 경우 `Mkto-contacts-<uniqueID>`입니다.

이러한 마케팅 생성 마케팅 목록을 다른 캠페인에 연결하면 잘못된 행동이 발생할 수 있습니다. 예:한 캠페인에 추가하면 두 번째 캠페인에 추가되어 마찬가지로 Dynamics의 캠페인에서 마케팅에서 생성된 마케팅 목록을 비활성화하는 것도 좋습니다.

## Dynamics 캠페인 {#remove-from-dynamics-campaign}에서 제거

이 흐름 단계는 Marketing to Smart Campaigns에서 사용하여 Microsoft 캠페인에서 사용자를 제거할 수 있습니다. 이렇게 하면 흐름 작업 &quot;Microsoft Campaign에 추가&quot;를 통해 이전에 캠페인에 추가한 캠페인에서 해당 리드만 제거됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

스마트한 캠페인에서 인물을 제거할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* 캠페인 동기화가 작동하는지 확인합니다.
>* Microsoft Dynamics에서 캠페인이 활성화되지 않았습니다.


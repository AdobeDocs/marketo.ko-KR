---
description: Dynamics Campaign - Marketo 문서 - 제품 설명서에서 사람 추가 또는 제거
title: Dynamics Campaign에서 사람 추가 또는 제거
exl-id: 4fea2f7c-0655-4816-8640-76878f760b6e
feature: Smart Campaigns, Microsoft Dynamics
source-git-commit: 2eeb7ea7fd43ba75a3c802a91ce07c90dc8abd91
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 0%

---

# Dynamics Campaign에서 사람 추가 또는 제거 {#add-or-remove-people-from-your-dynamics-campaign}

## Dynamics Campaign에 추가 {#add-to-dynamics-campaign}

이 흐름 단계는 스마트 캠페인 Marketo Engage에서 Microsoft 캠페인의 잠재 고객 또는 연락처로 사용자를 추가하는 데 사용할 수 있습니다. 잠재 고객이 아직 Dynamics에 존재하지 않는 경우 자동으로 동기화되어 캠페인에 추가됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

Smart Campaign에서 직원을 추가할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* Campaign 동기화가 작동하는지 확인합니다.
>* 캠페인이에서 활성화되지 않음 [!DNL Microsoft Dynamics]

시스템은 캠페인 특정 정적 마케팅 목록(각각 잠재 고객 및 연락처에 대해)을 자동으로 만들어 사용자를 추가합니다. 일회성 작업이며, 이후 캠페인에 동기화할 때 한 번 동일한 마케팅 목록이 사용됩니다. 정적 마케팅 목록 이름에 사용되는 이름 지정 표준은 다음과 같습니다. `Mkto-leads-<uniqueID>` 리드 및 `Mkto-contacts-<uniqueID>` 연락처용입니다.

이러한 Marketo 생성 마케팅 목록을 다른 캠페인에 연결하면 혼동을 줄 수 있습니다. 예를 들어 한 캠페인에 를 추가하면 두 번째 캠페인에도 추가됩니다. 마찬가지로 Dynamics의 캠페인에서 Marketo 생성 마케팅 목록을 분리하지 않는 것도 좋습니다.

## Dynamics Campaign에서 제거 {#remove-from-dynamics-campaign}

이 흐름 단계는 Marketo 스마트 캠페인에서 Microsoft 캠페인에서 사람을 제거하는 데 사용할 수 있습니다. 이렇게 하면 &quot;Microsoft Campaign에 추가됨&quot; 흐름 작업을 통해 이전에 Campaign에 추가된 잠재 고객만 캠페인에서 제거됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

Smart Campaign에서 직원을 제거할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* Campaign 동기화가 작동하는지 확인합니다.
>* 캠페인이에서 활성화되지 않음 [!DNL Microsoft Dynamics]

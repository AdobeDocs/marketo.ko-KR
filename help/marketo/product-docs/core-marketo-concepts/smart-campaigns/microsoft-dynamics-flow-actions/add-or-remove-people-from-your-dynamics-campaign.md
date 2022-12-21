---
description: Dynamics Campaign에서 사람 추가 또는 제거 - Marketo 문서 - 제품 설명서
title: Dynamics Campaign에서 사람 추가 또는 제거
exl-id: 4fea2f7c-0655-4816-8640-76878f760b6e
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 0%

---

# Dynamics Campaign에서 사람 추가 또는 제거 {#add-or-remove-people-from-your-dynamics-campaign}

## Dynamics Campaign에 추가 {#add-to-dynamics-campaign}

이 흐름 단계는 Marketo Smart Campaign에서 사용자를 Microsoft 캠페인에서 리드 또는 연락처로 추가하는 데 사용할 수 있습니다. 리드가 Dynamics에 아직 없으면 자동으로 동기화되어 캠페인에 추가됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

스마트 캠페인에서 사용자를 추가할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* Campaign 동기화가 작동하는지 확인합니다
>* Microsoft Dynamics에서 캠페인이 활성 상태가 아닙니다


시스템은 리드와 연락처에 대해 각각 캠페인별 정적 마케팅 목록을 자동으로 만들어 사용자를 추가합니다. 일회성 작업이며, 이후에 캠페인에 동기화되면 동일한 마케팅 목록이 사용됩니다. 정적 마케팅 목록 이름에 사용되는 이름 지정 표준은 `Mkto-leads-<uniqueID>` 리드 및 `Mkto-contacts-<uniqueID>` 연락처

이러한 Marketo에서 생성한 마케팅 목록을 다른 캠페인에 연결하면 잘못된 동작이 발생할 수 있습니다. 예: 하나의 캠페인에 를 추가하면 두 번째 캠페인에 추가하게 됩니다. 마찬가지로 Dynamics의 Campaign에서 Marketo에서 생성한 마케팅 목록을 비활성화하는 것도 권장되지 않습니다.

## Dynamics Campaign에서 제거 {#remove-from-dynamics-campaign}

이 흐름 단계는 Marketo Smart Campaign에서 Microsoft 캠페인에서 사용자를 제거하는 데 사용할 수 있습니다. 따라서 흐름 작업 &quot;Microsoft Campaign에 추가&quot;를 통해 이전에 Campaign에 추가된 Campaign에서 이러한 리드만 제거됩니다.

>[!NOTE]
>
>이 흐름 작업은 트리거 캠페인에만 사용할 수 있습니다.

스마트 캠페인에서 사용자를 제거할 Dynamics 캠페인을 찾아 선택합니다.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>캠페인 목록에 Dynamics 캠페인이 표시되지 않는 경우:
>
>* Campaign 동기화가 작동하는지 확인합니다
>* Microsoft Dynamics에서 캠페인이 활성 상태가 아닙니다


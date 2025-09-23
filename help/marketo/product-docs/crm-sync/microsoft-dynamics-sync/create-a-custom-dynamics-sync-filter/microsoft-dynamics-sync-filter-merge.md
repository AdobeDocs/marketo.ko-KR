---
unique-page-id: 10092969
description: Microsoft Dynamics 동기화 필터 - 병합 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 병합
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '159'
ht-degree: 0%

---

# [!DNL Microsoft] Dynamics 동기화 필터: 병합 {#microsoft-dynamics-sync-filter-merge}

[!DNL Microsoft Dynamics]에서 잠재 고객을 병합하면 동기화 필터 = 예(TRUE) 및 동기화 필터 = 아니요(FALSE)라는 두 가지 옵션 유형이 사용됩니다. 두 레코드를 병합하면 결과는 어느 레코드가 True이고 어느 레코드가 False인지에 따라 달라집니다.

잠재 고객 레코드는 관리자가 정의한 워크플로 규칙에 따라 true 또는 false가 되어 승자를 결정합니다. 우승 레코드에 대한 동기화 필터는 [!DNL MS Dynamics] 레코드가 Marketo과 동기화되는지 여부를 최종적으로 결정합니다.

하나의 기록이 참이고 하나가 거짓일 때 까다로워집니다.

| 손실되는 레코드에 대한 동기화 필터가 다음과 같은 경우 | 그리고 우승 레코드에 대한 동기화 필터는 다음과 같습니다. | 이것은 Marketo의 결과입니다 |
|---|---|---|
| [!UICONTROL True] | [!UICONTROL True] | 우승 기록은 Marketo과 계속 동기화됩니다. |
| [!UICONTROL False] | [!UICONTROL False] | 우승 기록은 Marketo과 계속 **계속**&#x200B;동기화되지 않습니다. |
| [!UICONTROL False] | [!UICONTROL True] | 우승 기록은 Marketo과 동기화됩니다. |
| [!UICONTROL True] | [!UICONTROL False] | 우승 기록은 Marketo과 동기화되지 않습니다. |

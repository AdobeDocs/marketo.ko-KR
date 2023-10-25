---
unique-page-id: 10092969
description: Microsoft Dynamics 동기화 필터 - 병합 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 병합
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 4%

---

# Microsoft Dynamics 동기화 필터: 병합 {#microsoft-dynamics-sync-filter-merge}

Microsoft Dynamics에서 리드를 병합하면 동기화 필터 = 예(TRUE) 및 동기화 필터 = 아니오(FALSE)의 두 가지 옵션 유형이 사용됩니다. 두 레코드를 병합하면 결과는 어느 레코드가 True이고 어느 레코드가 False인지에 따라 달라집니다.

잠재 고객 레코드는 관리자가 정의한 워크플로 규칙에 따라 true 또는 false가 되어 승자를 결정합니다. 우수성이 검증된 레코드에 대한 동기화 필터는 MS Dynamics 레코드가 Marketo과 동기화되는지 여부를 최종적으로 결정합니다.

하나의 기록이 참이고 하나가 거짓일 때 까다로워집니다.

| 손실되는 레코드에 대한 동기화 필터가 다음과 같은 경우 | 그리고 우승 레코드에 대한 동기화 필터는 다음과 같습니다. | 이것은 Marketo의 결과입니다 |
|---|---|---|
| 참 | 참 | 우승 기록은 Marketo과 계속 동기화됩니다. |
| False | False | 우승 기록은 계속 이어집니다 _아님_ Marketo과 동기화 |
| False | 참 | 우승 기록은 Marketo과 동기화됩니다. |
| 참 | False | 우승 기록은 Marketo과 동기화되지 않습니다. |

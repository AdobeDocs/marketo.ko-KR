---
unique-page-id: 10092969
description: Microsoft Dynamics 동기화 필터 - 병합 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 병합
exl-id: f8da9c3c-0f04-4f61-be03-7e7953d25afe
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 4%

---

# Microsoft Dynamics 동기화 필터: 병합 {#microsoft-dynamics-sync-filter-merge}

Microsoft Dynamics에서 리드를 병합하면 두 가지 옵션 유형(동기화 필터 = 예(TRUE) 및 동기화 필터 = 아니요(FALSE)가 사용됩니다. 두 레코드를 병합하면 결과는 True이고 False인 레코드에 따라 달라집니다.

리드 레코드는 관리자가 승자를 판별하기 위해 정의한 워크플로우 규칙에 따라 true 또는 false가 됩니다. 우승 레코드의 동기화 필터는 MS Dynamics 레코드가 Marketo과 동기화되는지 여부를 결정하는 것입니다.

한 개의 레코드가 참이고 한 개의 기록은 거짓인 경우 까다로워집니다.

| 손실된 레코드의 동기화 필터가 다음과 같은 경우: | 그리고 우승 레코드에 대한 동기화 필터는 다음과 같습니다. | Marketo의 결과입니다 |
|---|---|---|
| 참 | 참 | 우승 레코드는 Marketo과 계속 동기화됩니다 |
| 거짓 | 거짓 | 우승 기록은 계속 이어지고 있습니다 **not** Marketo과 동기화 |
| 거짓 | 참 | 우승 레코드는 Marketo과 동기화됩니다 |
| 참 | 거짓 | 우승 레코드는 Marketo과 동기화되지 않습니다 |

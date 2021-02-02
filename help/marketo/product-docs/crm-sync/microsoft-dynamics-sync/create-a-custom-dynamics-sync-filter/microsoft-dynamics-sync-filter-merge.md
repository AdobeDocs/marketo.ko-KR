---
unique-page-id: 10092969
description: Microsoft Dynamics 동기화 필터 -병합 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 필터 -병합
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '172'
ht-degree: 0%

---


# Microsoft Dynamics 동기화 필터:{#microsoft-dynamics-sync-filter-merge} 병합

Microsoft Dynamics에서 리드를 병합하면 2가지 옵션 유형(동기화 필터 = 예(TRUE) 및 동기화 필터 = 아니요(FALSE)가 사용됩니다. 두 레코드를 병합하면 결과는 True인 레코드와 False인 레코드에 따라 달라집니다.

리드 레코드는 우승자를 결정하기 위해 관리자가 정의한 워크플로우 규칙에 따라 true 또는 false가 됩니다. 우승 레코드에 대한 동기화 필터는 MS Dynamics 레코드가 Marketing과 동기화되는지 최종적으로 결정하는 것입니다.

한 개의 기록이 진실이고, 하나는 거짓일 때 그것은 교묘해진다.

| 손실된 레코드에 대한 동기화 필터가 다음과 같은 경우: | 우승 레코드에 대한 동기화 필터는 다음과 같습니다. | Marketing To의 결과입니다. |
|---|---|---|
| True | True | 우승 레코드가 Marketing To와 계속 동기화됩니다. |
| False | False | 우승 레코드는 Marketing To와 동기화된 **이(가) 아닌**&#x200B;로 계속됩니다. |
| False | True | 우승 레코드는 Marketing To와 동기화됩니다. |
| True | False | 우승 레코드는 Marketing To와 동기화되지 않습니다. |

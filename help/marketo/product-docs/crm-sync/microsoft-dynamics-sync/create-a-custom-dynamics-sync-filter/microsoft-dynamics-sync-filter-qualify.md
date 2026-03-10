---
unique-page-id: 10092977
description: 잠재 고객을 연락처로 전환할 때의 Dynamics 동기화 필터 자격 부여 프로세스에 대해 알아봅니다. 리드 및 연락처 동기화 필터 값이 Marketo 동기화에 미치는 영향을 이해합니다.
title: Microsoft Dynamics 동기화 필터 - 선별
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
source-git-commit: 2b29f05a27f847184e0968442012d443e9e0597d
workflow-type: tm+mt
source-wordcount: '125'
ht-degree: 0%

---

# [!DNL Microsoft Dynamics] 동기화 필터: 정규화 {#microsoft-dynamics-sync-filter-qualify}

[!DNL Microsoft Dynamics]에서 잠재 고객을 연락처로 전환하려면 이 기본 검증 프로세스를 사용하십시오. 그런 다음 Marketo에 동기화합니다.

## 변환 프로세스 {#the-conversion-process}

다음은 전환 프로세스 동안 필터가 작동하는 방식입니다.

| 리드 동기화 필터가 다음과 같은 경우: | 연락처 동기화 필터는 다음과 같습니다. | 이것은 Marketo의 결과입니다 |
|---|---|---|
| [!UICONTROL False] | [!UICONTROL False] | Marketo에서 동기화된 항목이 없습니다. |
| [!UICONTROL True] | [!UICONTROL True] | 연락처가 Marketo에서 동기화되었습니다. |
| [!UICONTROL False] | [!UICONTROL True] | Marketo에 새 연락처 레코드가 생성됨 |
| [!UICONTROL True] | [!UICONTROL False] | [!DNL MS Dynamics]이(가) Marketo의 잠재 고객 정보를 업데이트하지만 연락처 레코드가 동기화되지 않습니다. |

>[!CAUTION]
>
>기본 제공 자격 변환 프로세스만 지원합니다.

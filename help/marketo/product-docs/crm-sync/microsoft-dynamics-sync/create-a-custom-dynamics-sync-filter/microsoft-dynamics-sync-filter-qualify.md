---
unique-page-id: 10092977
description: Microsoft Dynamics 동기화 필터 - 적격 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 선별
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '123'
ht-degree: 6%

---

# Microsoft Dynamics 동기화 필터: 선별 {#microsoft-dynamics-sync-filter-qualify}

잠재 고객을 Microsoft Dynamics의 연락처로 전환하려면 이 기본 선별 프로세스를 사용하십시오. 그런 다음 Marketo Engage에 동기화합니다.

## 변환 프로세스 {#the-conversion-process}

다음은 전환 프로세스 동안 필터가 작동하는 방식입니다.

| 리드 동기화 필터가 다음과 같은 경우: | 연락처 동기화 필터는 다음과 같습니다. | 이것은 Marketo의 결과입니다 |
|---|---|---|
| False | False | Marketo에서 동기화된 항목이 없습니다. |
| 참 | 참 | 연락처가 Marketo에서 동기화되었습니다. |
| False | 참 | Marketo에 새 연락처 레코드가 생성됨 |
| 참 | False | MS Dynamics는 Marketo의 잠재 고객 정보를 업데이트하지만 연락처 레코드가 동기화되지 않음 |

>[!CAUTION]
>
>기본 제공 자격 변환 프로세스만 지원합니다.

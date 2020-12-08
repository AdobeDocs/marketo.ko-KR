---
unique-page-id: 10092977
description: Microsoft Dynamics 동기화 필터 -자격 조건 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 자격 조건
translation-type: tm+mt
source-git-commit: 96cc6a30c63c8e8dca793a52e4bf7ecaef8c08dc
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 0%

---


# Microsoft Dynamics 동기화 필터:자격 조건 {#microsoft-dynamics-sync-filter-qualify}

Microsoft Dynamics에서 리드를 연락처로 변환하려면 이 기본 자격 부여 프로세스를 사용해야 합니다. 그런 다음 Marketing Cloud에 동기화합니다.

## 전환 프로세스 {#the-conversion-process}

다음은 전환 프로세스 동안 필터가 작동하는 방식입니다.

| 리드 동기화 필터가 다음과 같은 경우입니다. | 연락처 동기화 필터는 다음과 같습니다. | Marketing To의 결과입니다. |
|---|---|---|
| False | False | Marketing To에 동기화되지 않은 상태 |
| True | True | 연락처가 Marketing To에 동기화됨 |
| False | True | Marketing To에서 새 연락처 레코드 만들기 |
| True | False | Marketing에서 MS Dynamics 업데이트 리드 정보가 있지만 연락처 레코드는 동기화되지 않습니다. |

>[!CAUTION]
>
>Adobe는 바로 이용 가능한 제품 검증 전환 과정만 지원합니다.


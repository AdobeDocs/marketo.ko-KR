---
unique-page-id: 10092977
description: Microsoft Dynamics 동기화 필터 - 자격 증명 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 동기화 필터 - 자격
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 6%

---

# Microsoft Dynamics 동기화 필터: 자격 부여 {#microsoft-dynamics-sync-filter-qualify}

Microsoft Dynamics에서 리드를 연락처로 전환하려면 이 기본 자격 프로세스를 사용해야 합니다. 그런 다음 Marketo에 동기화합니다.

## 변환 프로세스 {#the-conversion-process}

다음은 전환 프로세스 중에 필터가 작동하는 방식입니다.

| 리드 동기화 필터가 다음과 같은 경우: | 연락처 동기화 필터는 다음과 같습니다. | Marketo의 결과입니다 |
|---|---|---|
| 거짓 | 거짓 | Marketo에서는 아무 것도 동기화되지 않습니다 |
| 참 | 참 | 연락처는 Marketo에서 동기화됩니다 |
| 거짓 | 참 | 새 연락처 레코드가 Marketo에 만들어집니다 |
| 참 | 거짓 | MS Dynamics는 Marketo의 리드 정보를 업데이트하지만 연락처 레코드가 동기화되지 않습니다 |

>[!CAUTION]
>
>Adobe는 즉시 사용 가능한 전환 확인 프로세스만 지원합니다.

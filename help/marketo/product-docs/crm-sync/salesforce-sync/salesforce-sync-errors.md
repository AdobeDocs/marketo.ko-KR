---
description: Salesforce 동기화 오류 - Marketing To Docs - 제품 설명서
title: Salesforce 동기화 오류
translation-type: tm+mt
source-git-commit: 9f88e7cebc5e9d0d4491d65d332ccfdd9a31c395
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---


# Salesforce 동기화 오류 {#salesforce-sync-errors}

동기화 프로세스 중에 발생한 오류에 대한 요약을 봅니다. 호환되지 않는 데이터를 동기화하지 못해 발생한 오류가 여기에 포함됩니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 동기화 오류 보기 {#view-sync-errors}

1. **관리**&#x200B;를 클릭합니다.

   ![](assets/salesforce-sync-errors-1.png)

1. 통합에서 **Salesforce**&#x200B;을 클릭한 다음 **오류 동기화** 탭을 클릭합니다.

   ![](assets/salesforce-sync-errors-2.png)

>[!NOTE]
>
>현재 시간의 오류부터 현재 동기화 5일 전까지 나열된 오류가 있습니다.

| 필드 | 설명 |
|---|---|
| 실패 설정 | 레코드 수준 _또는_ 작업 수준 |
| 실패 날짜/시간 | 오류 정보 |
| 오류 유형 | SFDC 반환 메시지 |

>[!TIP]
>
>레코드 수준 레코드를 클릭하면 관련 개체의 Marketing 및 Salesforce ID가 표시됩니다. 경우에 따라 기록 및 작업 수준 오류에 대한 메시지는 Salesforce에서 직접 제공됩니다. 온라인으로 검색하여 자세한 내용을 찾을 수 있습니다.

## 필터 동기화 오류 {#filter-sync-errors}

1. 데이터를 필터링하려면 페이지의 맨 오른쪽에 있는 필터 아이콘을 클릭합니다.

   ![](assets/salesforce-sync-errors-3.png)

1. 날짜 및 시간 범위를 선택한 다음 오류 유형(작업 수준 또는 레코드 수준)별로 필터링합니다. 완료되면 **적용**&#x200B;을 클릭합니다.

   ![](assets/salesforce-sync-errors-4.png)

**선택적 단계**:동기화 오류를 내보내려면 내보내기를  **클릭합니다**. 데이터는 CSV로 내보내집니다.

![](assets/salesforce-sync-errors-5.png)

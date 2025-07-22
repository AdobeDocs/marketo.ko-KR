---
description: Salesforce 동기화 오류 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 오류
exl-id: 4819f423-30c6-48e3-8cec-5d298ceb7b56
feature: Salesforce Integration
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '173'
ht-degree: 1%

---

# [!DNL Salesforce] 동기화 오류 {#salesforce-sync-errors}

동기화 프로세스 중에 발생한 오류 요약을 확인합니다. 여기에는 호환되지 않는 데이터를 동기화하지 못해 발생하는 오류가 포함됩니다.

>[!NOTE]
>
>**관리자 권한 필요**

## 동기화 오류 보기 {#view-sync-errors}

1. **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-errors-1.png)

1. 통합에서 **Salesforce**&#x200B;을 클릭한 다음 **[!UICONTROL Sync Errors]** 탭을 클릭합니다.

   ![](assets/salesforce-sync-errors-2.png)

>[!NOTE]
>
>나열된 오류 범위는 현재 시간부터 현재 동기화 5일 전까지입니다.

| 필드 | 설명 |
|---|---|
| 실패 날짜 | 레코드 수준 _또는_ 작업 수준 |
| 실패 날짜/시간 | 오류 세부 정보 |
| 오류 유형 | SFDC 반환 메시지 |

>[!TIP]
>
>레코드 수준 레코드를 클릭하면 관련 개체의 Marketo 및 [!DNL Salesforce] ID가 표시됩니다. 기록 및 작업 수준 오류에 대한 메시지는 [!DNL Salesforce]에서 직접 가져온 경우도 있습니다. 온라인으로 검색하는 경우 추가 세부 정보를 제공할 수 있습니다.

## 동기화 오류 필터링 {#filter-sync-errors}

1. 데이터를 필터링하려면 페이지의 맨 오른쪽에 있는 필터 아이콘을 클릭합니다.

   ![](assets/salesforce-sync-errors-3.png)

1. 날짜 및 시간 범위를 선택한 다음 오류 유형(작업 수준 또는 레코드 수준)별로 필터링합니다. 완료되면 **[!UICONTROL Apply]**&#x200B;을(를) 클릭합니다.

   ![](assets/salesforce-sync-errors-4.png)

**선택적 단계**: 동기화 오류를 내보내려면 **[!UICONTROL Export]**&#x200B;을(를) 클릭합니다. 데이터는 CSV로 내보내집니다.

![](assets/salesforce-sync-errors-5.png)

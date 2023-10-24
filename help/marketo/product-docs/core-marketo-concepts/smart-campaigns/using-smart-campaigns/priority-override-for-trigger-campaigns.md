---
description: 트리거 캠페인에 대한 우선 순위 재정의 - Marketo 문서 - 제품 설명서
title: 트리거 캠페인에 대한 우선 순위 재정의
exl-id: cf9b4d27-0e4c-40cf-accd-4f4a102160cc
feature: Smart Campaigns
source-git-commit: 47bc93665a7efa0d64cd4d5f34b868895d407527
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 0%

---

# 트리거 캠페인에 대한 우선 순위 재정의 {#priority-override-for-trigger-campaigns}

관리자는 트리거 캠페인에 대해 결정된 Marketo Engage 우선 순위를 재정의하여 비즈니스 목표에 더 잘 부합하는 우선 순위를 설정할 수 있습니다.

>[!NOTE]
>
>이 기능은 트리거 캠페인 및 이 부여된 사용자만 사용할 수 있습니다. [&quot;트리거 캠페인 우선 순위 편집&quot; 권한](#grant-priority-override-access).

>[!CAUTION]
>
>이 기능은 제한된 비즈니스 크리티컬 캠페인 집합(권장 최대값 25)에서 사용하는 것이 좋습니다. 대규모 세트에서 해당 기능을 느슨하게 사용하면 전체 캠페인 실행에 부정적인 영향을 줄 수 있습니다.

## 우선 순위 재정의 액세스 권한 부여 {#grant-priority-override-access}

>[!NOTE]
>
>관리자 또는 관리자 권한이 있는 사용자만 캠페인 우선 순위 대체 액세스 권한을 가져야 합니다.

1. 다음에서 [!UICONTROL 관리자] 영역, 클릭 **[!UICONTROL 사용자 및 역할]**.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. 다음을 클릭합니다. **[!UICONTROL 역할]** 탭에서 액세스 권한을 부여할 사용자를 선택한 다음 **[!UICONTROL 역할 편집]**.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. 아래 [!UICONTROL 마케팅 활동 액세스], 선택 **[!UICONTROL 트리거 캠페인 우선 순위 편집]**. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/priority-override-for-trigger-campaigns-3.png)

## 우선 순위 재정의 {#override-priority}

1. 트리거 캠페인을 찾습니다. 마우스 오른쪽 단추로 클릭하고 를 선택합니다. **[!UICONTROL 캠페인 우선 순위 재정의]**.

   ![](assets/priority-override-for-trigger-campaigns-4.png)

1. 다음을 클릭합니다. **[!UICONTROL 캠페인 우선 순위 재정의]** 슬라이더를 사용하십시오. 새 우선 순위 수준을 선택하고 **[!UICONTROL 확인]**.

   ![](assets/priority-override-for-trigger-campaigns-5.png)

   새 우선 순위 수준이 [예약] 탭에 표시됩니다.

   ![](assets/priority-override-for-trigger-campaigns-6.png)

>[!NOTE]
>
>* 캠페인의 기본 우선 순위는 [!UICONTROL 캠페인 대기열] 아래에 [!UICONTROL 마케팅 활동]. 실행 속도를 높이려면 캠페인 우선 순위를 기본값보다 높은 한 수준으로 설정하는 것이 좋습니다.
>* 사용자 설정 우선 순위는 캠페인에 적합한 새 사용자에게만 적용됩니다. 이미 대기열에 있는 사람은 영향을 받지 않습니다.
>* 우선 순위 재정의는 다음 위치에서 캡처됩니다. [감사 추적](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md){target="_blank"}.

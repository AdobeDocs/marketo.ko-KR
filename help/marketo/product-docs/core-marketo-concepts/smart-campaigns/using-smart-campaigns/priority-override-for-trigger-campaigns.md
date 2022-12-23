---
description: 트리거 캠페인에 대한 우선순위 무시 - Marketo 문서 - 제품 설명서
title: 트리거 캠페인에 대한 우선순위 무시
exl-id: cf9b4d27-0e4c-40cf-accd-4f4a102160cc
source-git-commit: 48a49faa6a1fde1e9ac391c2bf0800123f6a5bac
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 0%

---

# 트리거 캠페인에 대한 우선순위 무시 {#priority-override-for-trigger-campaigns}

관리자는 트리거 캠페인에 대해 Marketo에서 결정한 우선 순위를 재정의하여 비즈니스 목표에 더 잘 맞는 우선순위를 설정할 수 있습니다.

>[!NOTE]
>
>이 기능은 트리거 캠페인 및 [&quot;트리거 캠페인 우선 순위 편집&quot; 권한](#grant-priority-override-access).

>[!CAUTION]
>
>제한된 비즈니스 크리티컬 캠페인 세트에서 이 기능을 사용하는 것이 좋습니다(최대 25개가 권장). 큰 세트에 느슨하게 기능을 사용하면 전체 캠페인 실행에 부정적인 영향을 줄 수 있습니다.

## 우선 순위 무시 액세스 권한 부여 {#grant-priority-override-access}

>[!NOTE]
>
>관리자 또는 관리자 권한이 있는 사용자만 캠페인 우선 순위 무시 액세스 권한이 있어야 합니다.

1. 에서 [!UICONTROL 관리] 영역을 클릭합니다. **[!UICONTROL 사용자 및 역할]**.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. 을(를) 클릭합니다. **[!UICONTROL 역할]** 탭에서 액세스 권한을 부여할 사용자를 선택한 다음 **[!UICONTROL 역할 편집]**.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. 아래 [!UICONTROL 마케팅 활동 액세스], 선택 **[!UICONTROL 트리거 캠페인 우선 순위 편집]**. 클릭 **[!UICONTROL 저장]**.

   ![](assets/priority-override-for-trigger-campaigns-3.png)

## 우선 순위 무시 {#override-priority}

1. 트리거 캠페인을 찾습니다. 마우스 오른쪽 단추를 클릭하고 을 선택합니다. **[!UICONTROL 캠페인 우선 순위 무시]**.

   ![](assets/priority-override-for-trigger-campaigns-4.png)

1. 을(를) 클릭합니다. **[!UICONTROL 캠페인 우선 순위 무시]** 슬라이더를 사용하여 활성화하십시오. 새 우선 순위 수준을 선택하고 **[!UICONTROL 확인]**.

   ![](assets/priority-override-for-trigger-campaigns-5.png)

   새 우선순위 수준은 예약 탭에 표시됩니다.

   ![](assets/priority-override-for-trigger-campaigns-6.png)

>[!NOTE]
>
>* 캠페인의 기본 우선 순위를 [!UICONTROL 캠페인 큐] 아래에 [!UICONTROL 마케팅 활동]. 실행 비율을 높이려면 캠페인 우선 순위를 기본값보다 높은 한 수준 높게 설정하는 것이 좋습니다.
>* 사용자 설정 우선 순위는 캠페인을 사용할 수 있는 새로운 대상에만 적용됩니다. 이미 큐에 있는 사람은 영향을 받지 않습니다.
>* 우선 순위 재정의가 캡처됩니다. [감사 추적](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md).


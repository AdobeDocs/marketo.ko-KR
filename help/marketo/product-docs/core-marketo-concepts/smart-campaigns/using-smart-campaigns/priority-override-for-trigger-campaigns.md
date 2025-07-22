---
description: 트리거 캠페인에 대한 우선 순위 재정의 - Marketo 문서 - 제품 설명서
title: 트리거 캠페인에 대한 우선 순위 재정의
exl-id: cf9b4d27-0e4c-40cf-accd-4f4a102160cc
feature: Smart Campaigns
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# 트리거 캠페인에 대한 우선 순위 재정의 {#priority-override-for-trigger-campaigns}

관리자는 트리거 캠페인에 대해 Marketo Engage이 결정한 우선 순위를 재정의하여 비즈니스 목표에 더 잘 부합하는 우선 순위를 설정할 수 있습니다.

>[!NOTE]
>
>이 기능은 트리거 캠페인 및 [&quot;트리거 캠페인 우선 순위 편집&quot; 권한](#grant-priority-override-access)이 부여된 사용자만 사용할 수 있습니다.

>[!CAUTION]
>
>이 기능은 제한된 비즈니스 크리티컬 캠페인 집합(권장 최대값 25)에서 사용하는 것이 좋습니다. 대규모 세트에서 해당 기능을 느슨하게 사용하면 전체 캠페인 실행에 부정적인 영향을 줄 수 있습니다.

## 우선 순위 재정의 액세스 권한 부여 {#grant-priority-override-access}

>[!NOTE]
>
>관리자 또는 관리자 권한이 있는 사용자만 캠페인 우선 순위 대체 액세스 권한을 가져야 합니다.

1. **[!UICONTROL Admin]** 영역에서 **[!UICONTROL Users & Roles]**&#x200B;을(를) 클릭합니다.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. **[!UICONTROL Roles]** 탭을 클릭하고 액세스 권한을 부여할 사용자를 선택한 다음 **[!UICONTROL Edit Role]**&#x200B;을(를) 클릭합니다.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. **[!UICONTROL Access Marketing Activities]**&#x200B;에서 **[!UICONTROL Edit Trigger Campaign Priority]**&#x200B;을(를) 선택합니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/priority-override-for-trigger-campaigns-3.png)

## 우선 순위 재정의 {#override-priority}

1. 트리거 캠페인을 찾습니다. 마우스 오른쪽 단추를 클릭하고 **[!UICONTROL Override Campaign Priority]**&#x200B;을(를) 선택합니다.

   ![](assets/priority-override-for-trigger-campaigns-4.png)

1. 활성화하려면 **[!UICONTROL Override Campaign Priority]** 슬라이더를 클릭하십시오. 새 우선 순위 수준을 선택하고 **[!UICONTROL Confirm]**&#x200B;을(를) 클릭합니다.

   ![](assets/priority-override-for-trigger-campaigns-5.png)

   새 우선 순위 수준이 **[!UICONTROL Schedule]** 탭에 표시됩니다.

   ![](assets/priority-override-for-trigger-campaigns-6.png)

>[!NOTE]
>
>* [!UICONTROL Campaign Queue] 아래 [!UICONTROL Marketing Activities]에서 캠페인의 기본 우선 순위를 볼 수 있습니다. 실행 속도를 높이려면 캠페인 우선 순위를 기본값보다 높은 한 수준으로 설정하는 것이 좋습니다.
>* 사용자 설정 우선 순위는 캠페인에 적합한 새 사용자에게만 적용됩니다. 이미 대기열에 있는 사람은 영향을 받지 않습니다.
>* 우선 순위 재정의는 [감사 추적](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md){target="_blank"}에서 캡처됩니다.

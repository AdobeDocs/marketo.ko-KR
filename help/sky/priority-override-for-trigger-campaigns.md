---
title: priority-override-for-trigger-campaigns
description: 트리거 캠페인에 대한 우선 순위 무시
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---


# 트리거 캠페인에 대한 우선 순위 무시

<br> 

관리자는 캠페인 트리거 시 Marketing To에서 정한 우선 순위를 무시하고 비즈니스 목표에 보다 잘 맞는 우선 순위를 설정할 수 있습니다.

>[!NOTE]
>
>이 기능은 트리거 캠페인 및 &quot;트리거 캠페인 우선 순위 편집&quot; 권한이 부여된 사용자만 사용할 수 있습니다.

>[!CAUTION]
>
>제한된 비즈니스 크리티컬 캠페인 세트에서 이 기능을 사용하는 것이 좋습니다(권장 최대 25개). 큰 세트에 이 기능을 느슨하게 사용하면 전체 캠페인 실행에 부정적인 영향을 줄 수 있습니다.

## 우선 순위 재정의

1. 트리거 캠페인에서 **[!UICONTROL Schedule]** 탭을 클릭한 다음 을 클릭합니다 **[!UICONTROL Override Priority]**.

   ![이미지 원](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-1.png)

1. 드롭다운에서 새 우선 순위 수준을 선택합니다. 을 **[!UICONTROL Confirm]**&#x200B;클릭합니다.

   ![이미지 2](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-2.png)

   ![이미지 3](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-3.png)

>[!NOTE]
>
>* 아래에서 캠페인의 기본 우선 순위를 볼 수 [!UICONTROL Campaign Queue] 있습니다 [!UICONTROL Marketing Activities]. 실행 비율을 높이려면 캠페인 우선 순위를 기본값보다 한 수준 높은 수준으로 설정하는 것이 좋습니다.
>* 사용자 설정 우선 순위는 캠페인을 이용할 수 있는 신규 고객에게만 적용됩니다.이미 대기열에 있는 사람은 영향을 받지 않습니다.


## 우선 순위 재설정

1. 캠페인 우선 순위를 시스템 기본값으로 다시 설정하려면 트리거 캠페인의 **[!UICONTROL Schedule]** 탭으로 이동한 후 을 클릭합니다 **[!UICONTROL Reset Priority]**.

   ![이미지 4](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-4.png)

1. 을 **[!UICONTROL Reset]** 클릭하여 확인합니다.

   ![이미지 5](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-5.png)

>[!NOTE]
>
>우선 순위 무시 및 재설정은 감사 추적에서 캡처됩니다. 클래식 경험의 [영역을](https://docs.marketo.com/x/GZ2t) 통해 감사 추적 [!UICONTROL Admin] 을 볼 수 있습니다.

## 우선 순위 무시 액세스 권한 부여

>[!CAUTION]
>
>관리자 또는 관리자 권한이 있는 사용자만 캠페인 우선 순위 무시 액세스 권한을 가져야 합니다.

1. 영역에서 [!UICONTROL Admin] 을 클릭합니다 **[!UICONTROL Users & Roles]**.

   ![이미지 6](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-6.png)

1. 탭을 **[!UICONTROL Roles]** 클릭하고 액세스 권한을 부여할 사용자를 선택한 다음 을 클릭합니다 **[!UICONTROL Edit Role]**.

   ![이미지 7](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-7.png)

1. 아래 [!UICONTROL Access Marketing Activities]에서 확인 **[!UICONTROL Edit Trigger Campaign Priority]**&#x200B;하세요 을 **[!UICONTROL Save]**&#x200B;클릭합니다.

   ![이미지 8](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-8.png)

## Marketing To Classic에서 캠페인 우선 순위 보기

트리거 캠페인 내 [!DNL Classic] 탭을 클릭하여 경험에서 캠페인 우선 **[!UICONTROL Schedule]** 순위를 볼 수 있습니다.

![이미지 9](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-9.png)

>[!NOTE]
>
>경험의 우선 순위는 [!DNL Classic] 보기 전용입니다. 캠페인 우선 순위 변경 또는 재설정은 Marketo Sky을 통해서만 사용할 수 있습니다.

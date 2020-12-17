---
title: priority-override-for-trigger-campaigns
description: 트리거 캠페인에 대한 우선순위 무시
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '301'
ht-degree: 0%

---


# 트리거 캠페인에 대한 우선순위 무시

<br> 

관리자는 캠페인을 트리거하는 Marketing To의 정해진 우선 순위를 무시하고 비즈니스 목표에 맞게 우선 순위를 설정할 수 있습니다.

>[!NOTE]
>
>이 기능은 트리거 캠페인 및 &quot;트리거 캠페인 우선 순위 편집&quot; 권한이 부여된 사용자만 사용할 수 있습니다.

>[!CAUTION]
>
>제한된 비즈니스 중요 캠페인 세트에서 이 기능을 사용하는 것이 좋습니다(최대 25개 권장). 큰 세트에 이 기능을 느슨하게 사용하면 전체 캠페인 실행에 부정적인 영향을 줄 수 있습니다.

## 우선 순위 재정의

1. 트리거 캠페인에서 **[!UICONTROL Schedule]** 탭을 클릭한 다음 **[!UICONTROL Override Priority]**&#x200B;을 클릭합니다.

   ![이미지 원](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-1.png)

1. 드롭다운에서 새 우선순위 수준을 선택합니다. **[!UICONTROL Confirm]**&#x200B;을 클릭합니다.

   ![이미지 2](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-2.png)

   ![이미지 3](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-3.png)

>[!NOTE]
>
>* [!UICONTROL Marketing Activities] 아래의 [!UICONTROL Campaign Queue]에서 캠페인의 기본 우선 순위를 볼 수 있습니다. 실행 비율을 높이려면 캠페인 우선 순위를 기본값보다 높은 한 수준으로 설정하는 것이 좋습니다.
>* 사용자 설정 우선 순위는 캠페인에 대한 자격이 있는 새로운 사람에게만 적용됩니다.이미 대기열에 있는 사람은 영향을 받지 않습니다.


## 우선 순위 재설정

1. 캠페인 우선 순위를 시스템 기본값으로 다시 설정하려면 트리거 캠페인의 **[!UICONTROL Schedule]** 탭으로 이동하여 **[!UICONTROL Reset Priority]**&#x200B;를 클릭합니다.

   ![이미지 4](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-4.png)

1. **[!UICONTROL Reset]**&#x200B;을 클릭하여 확인합니다.

   ![이미지 5](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-5.png)

>[!NOTE]
>
>우선 순위 무시 및 재설정은 감사 추적에서 캡처됩니다. 클래식 환경의 [!UICONTROL Admin] 영역을 통해 [감사 추적](https://docs.marketo.com/x/GZ2t)을 볼 수 있습니다.

## 우선 순위 무시 액세스 권한 부여

>[!CAUTION]
>
>관리자 또는 관리자 권한이 있는 사용자만 캠페인 우선 순위 재정의 액세스 권한을 가져야 합니다.

1. [!UICONTROL Admin] 영역에서 **[!UICONTROL Users & Roles]**&#x200B;을 클릭합니다.

   ![이미지 6](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-6.png)

1. **[!UICONTROL Roles]** 탭을 클릭하고 액세스 권한을 부여할 사용자를 선택한 다음 **[!UICONTROL Edit Role]**&#x200B;을 클릭합니다.

   ![이미지 7](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-7.png)

1. [!UICONTROL Access Marketing Activities] 아래에서 **[!UICONTROL Edit Trigger Campaign Priority]**&#x200B;을 선택합니다. **[!UICONTROL Save]**&#x200B;을 클릭합니다.

   ![이미지 8](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-8.png)

## Marketing To Classic에서 캠페인 우선순위 보기

트리거 캠페인 내의 **[!UICONTROL Schedule]** 탭을 클릭하여 [!DNL Classic] 경험에서 캠페인 우선순위를 볼 수 있습니다.

![이미지 9](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-9.png)

>[!NOTE]
>
>[!DNL Classic] 경험의 우선 순위는 보기 전용입니다. 캠페인 우선 순위 변경 또는 재설정은 Marketo Sky을 통해서만 사용할 수 있습니다.

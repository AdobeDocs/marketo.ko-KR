---
unique-page-id: 4719300
description: 사용자 지정 개체 필드를 스마트 목록/트리거 제한으로 추가/제거 - Marketo 문서 - 제품 설명서
title: 사용자 지정 개체 필드를 스마트 목록/트리거 제한으로 추가/제거
exl-id: 639e73eb-9a8c-4b10-8e97-892abf5c5db0
feature: Salesforce Integration
source-git-commit: 6293a11b9d48a20da4cb2448c8374c469679abdb
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 1%

---

# 사용자 지정 개체 필드를 스마트 목록/트리거 제한으로 추가/제거 {#add-remove-custom-object-field-as-smart-list-trigger-constraints}

Marketo Engage은 Salesforce 사용자 지정 개체 동기화를 세밀하게 제어할 수 있습니다. 이렇게 하면 사용자 지정 개체 필터의 제약 조건으로 사용할 수 있는 필드를 선택하고 스마트 캠페인의 트리거로 사용할 수 있습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. **[!UICONTROL Admin]** 영역에 연결했습니다.

   ![](assets/add-remove-custom-object-field-1.png)

1. **[!UICONTROL Salesforce Objects Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-12-11-15-3a11-3a41.png)

1. **[!UICONTROL Salesforce Objects Sync]**&#x200B;이(가) 왼쪽 열에 나타납니다.

   ![](assets/image2015-12-11-15-3a15-3a15.png)

1. 수정할 객체를 선택합니다.

   ![](assets/image2014-12-10-13-3a10-3a11.png)

1. **[!UICONTROL Edit Visible Fields]**&#x200B;을(를) 클릭합니다.

   >[!TIP]
   >
   >**[!UICONTROL Edit Visible Fields]** 단추가 회색으로 표시된 경우 해당 개체는 현재 스마트 목록 또는 스마트 캠페인에서 사용 중입니다. 계속하려면 모든 연결을 제거하십시오.

   ![](assets/image2014-12-10-13-3a10-3a25.png)

1. 전역 동기화가 활성화된 경우 **[!UICONTROL Disable Global Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a10-3a36.png)

1. 필요한 필터/트리거 제약 조건 옆의 확인란을 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-10-13-3a10-3a47.png)

   >[!NOTE]
   >
   >모든 필드는 기본적으로 필터에 대한 제약 조건으로 선택됩니다.

1. **[!UICONTROL Fields]** 탭을 클릭하여 변경 내용을 확인합니다.

   ![](assets/image2014-12-10-13-3a10-3a56.png)

   >[!NOTE]
   >
   >전역 동기화를 다시 활성화하는 것을 잊지 마십시오!

이제 스마트 목록과 스마트 캠페인이 더 강력한 기능을 제공합니다.

>[!MORELIKETHIS]
>
>[사용자 지정 개체 동기화 사용/사용 안 함](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-custom-object-sync.md){target="_blank"}

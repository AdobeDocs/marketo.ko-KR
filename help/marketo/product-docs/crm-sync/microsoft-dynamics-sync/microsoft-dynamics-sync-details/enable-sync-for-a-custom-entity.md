---
unique-page-id: 2953384
description: 사용자 지정 엔터티에 대해 동기화 활성화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 엔터티에 대해 동기화 활성화
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
feature: Microsoft Dynamics
source-git-commit: 4f36194fb76fd8e26c2fd6fe49526d88d355a24a
workflow-type: tm+mt
source-wordcount: '299'
ht-degree: 0%

---

# 사용자 지정 엔터티에 대해 동기화 활성화 {#enable-sync-for-a-custom-entity}

Marketo Engage에서 사용할 수 있도록 [!DNL Dynamics]의 사용자 지정 엔터티 데이터가 필요한 경우 이에 대한 동기화를 사용하도록 설정하는 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>사용자 지정 개체를 사용하려면 Microsoft Dynamics의 [리드](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-lead-sync.md){target="_blank"}, [연락처](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-contact-sync.md){target="_blank"} 또는 [계정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-account-sync.md){target="_blank"} 개체와 연결되어 있어야 합니다.

>[!NOTE]
>
>* 사용자 지정 엔터티에 대해 동기화를 활성화하면 Marketo에서 초기 동기화를 수행하여 사용자 지정 개체에 대한 모든 데이터를 가져옵니다.
>* 현재 마케팅 목록 및 마케팅 목록 구성원은 _지원되지 않습니다_.

>[!IMPORTANT]
>
>Marketo 동기화 사용자는 나열하고 동기화를 수행하려면 사용자 지정 개체에 대한 읽기 액세스 권한이 필요합니다.

1. **[!UICONTROL Admin]** 섹션으로 이동합니다.

   ![](assets/enable-sync-for-a-custom-entity-1.png)

1. **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 선택하고 **[!UICONTROL Disable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-2.png)

   >[!NOTE]
   >
   >사용자 지정 엔터티를 활성화하거나 비활성화하려면 전역 동기화를 일시적으로 비활성화해야 합니다.

1. [!UICONTROL Database Management]에서 **[!UICONTROL Dynamics Entities Sync]** 링크를 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-3.png)

1. **[!UICONTROL Sync schema]** 링크를 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-4.png)

1. 동기화할 엔터티를 선택하고 **[!UICONTROL Enable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-5.png)

1. 동기화하거나 스마트 목록의 [제약 조건](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) 및/또는 트리거로 사용할 필드를 선택하십시오. 완료되면 **[!UICONTROL Enable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-6.png)

   >[!NOTE]
   >
   >동기화 프로세스 중에 &quot;[!UICONTROL Dynamic Entities Sync]&quot; 항목이 탐색 트리에서 사라지는 것을 볼 수 있습니다. 이는 예상되는 동작이며 동기화가 완료된 후 다시 나타납니다.

1. 이제 엔티티에 녹색 확인 표시가 있습니다.

   ![](assets/enable-sync-for-a-custom-entity-7.png)

1. 전역 동기화를 다시 활성화하는 것을 잊지 마십시오!

   ![](assets/enable-sync-for-a-custom-entity-8.png)

   >[!NOTE]
   >
   >* Marketo은 1~2단계 수준의 표준 엔티티에 연결된 사용자 지정 엔티티만 지원합니다.
   >
   >* 사용자 지정 개체 트리는 주 개체 중 하나와의 직접 연결(예: 리드, 연락처 또는 계정 또는 중간 개체를 통한 간접 연결) 때문에 동일한 개체를 두 번 이상 표시할 수 있습니다. 이러한 경우 주 오브젝트와 가장 가까운 오브젝트를 선택하고 하나만 선택합니다. 동일한 개체를 여러 번 선택하면 해당 사용자 지정 개체의 동기화가 방해될 수 있습니다.

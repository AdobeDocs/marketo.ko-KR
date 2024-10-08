---
unique-page-id: 2953384
description: 사용자 지정 엔터티에 대해 동기화 활성화 - Marketo 문서 - 제품 설명서
title: 사용자 지정 엔터티에 대해 동기화 활성화
exl-id: 4b075bf3-f10b-4725-8c8e-a6ecee63d756
feature: Microsoft Dynamics
source-git-commit: d522950af40c5e3e702a6522101ebe9550432be5
workflow-type: tm+mt
source-wordcount: '222'
ht-degree: 0%

---

# 사용자 지정 엔터티에 대해 동기화 활성화 {#enable-sync-for-a-custom-entity}

Marketo Engage에서 사용할 수 있도록 Dynamics의 사용자 지정 엔티티 데이터가 필요한 경우 여기에 해당 동기화를 활성화하는 방법이 있습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>* 사용자 지정 엔터티에 대해 동기화를 활성화하면 Marketo에서 초기 동기화를 수행하여 사용자 지정 개체에 대한 모든 데이터를 가져옵니다.
>* 현재 마케팅 목록 및 마케팅 목록 구성원은 _지원되지 않습니다_.

>[!IMPORTANT]
>
>Marketo 동기화 사용자는 나열하고 동기화를 수행하려면 사용자 지정 개체에 대한 읽기 액세스 권한이 필요합니다.

1. **[!UICONTROL 관리자]** 섹션으로 이동합니다.

   ![](assets/enable-sync-for-a-custom-entity-1.png)

1. **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 선택하고 **[!UICONTROL 동기화 비활성화]**&#x200B;를 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-2.png)

   >[!NOTE]
   >
   >사용자 지정 엔터티를 활성화하거나 비활성화하려면 전역 동기화를 일시적으로 비활성화해야 합니다.

1. 데이터베이스 관리에서 **[!UICONTROL Dynamics Entities 동기화]**&#x200B;를 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-3.png)

1. **[!UICONTROL 스키마 동기화]**&#x200B;를 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-4.png)

1. 동기화할 엔터티를 선택하고 **[!UICONTROL 동기화 사용]**&#x200B;을 클릭합니다.

   ![](assets/enable-sync-for-a-custom-entity-5.png)

1. 스마트 목록에서 동기화하거나 [제약 조건](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-a-constraint-to-a-smart-list-filter.md) 및/또는 트리거(추가된 레코드의 경우 _업데이트되지 않음_)로 사용할 필드를 선택하십시오. 완료되면 **[!UICONTROL 동기화 사용]**&#x200B;을 클릭하세요.

   ![](assets/enable-sync-for-a-custom-entity-6.png)

   >[!NOTE]
   >
   >동기화 프로세스 중에 탐색 트리에서 &quot;[!UICONTROL Dynamic Entities Sync]&quot; 항목이 사라지는 것을 볼 수 있습니다. 이는 예상되는 동작이며 동기화가 완료된 후 다시 나타납니다.

1. 이제 엔티티에 녹색 확인 표시가 있습니다.

   ![](assets/enable-sync-for-a-custom-entity-7.png)

1. 전역 동기화를 다시 활성화하는 것을 잊지 마십시오!

   ![](assets/enable-sync-for-a-custom-entity-8.png)

---
description: Dynamics - Marketo 문서 - 제품 설명서에서 삭제하기 전에 동기화할 필드 편집
title: Dynamics에서 삭제하기 전에 동기화할 필드 편집
exl-id: 6fa9f6c0-c69d-478f-b333-13a5c910f577
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# [!DNL Dynamics]에서 삭제하기 전에 동기화할 필드 편집 {#editing-fields-to-sync-before-deleting-them-in-dynamics}

경우에 따라 [!DNL Dynamics]에서 필드를 삭제할 수 있습니다. Marketo은 동기화를 기반으로 필드 목록을 참조로 유지합니다. 동기화가 켜져 있는 동안 [!DNL Dynamics]에서 필드가 삭제되면 동기화에서 오류가 발생할 수 있습니다. 필드를 삭제하기 전에 아래 단계를 수행합니다.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. [!UICONTROL Integration]에서 **[!UICONTROL Microsoft Dynamics]**&#x200B;을(를) 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. **[!UICONTROL Disable Sync]**&#x200B;을(를) 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. 브라우저의 새 탭에서 [!DNL Dynamics]에 로그인하고 원하는 필드를 삭제합니다.

1. Marketo으로 돌아가서 [!DNL Microsoft Dynamics]에서 &quot;**[!UICONTROL Edit]**&quot; 옆에 있는 [!UICONTROL Step 2: Select Fields to Sync]을(를) 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. 필드를 검토하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>변경된 내용이 없는 경우에도 동기화를 위해 업데이트된 스키마를 저장하려면 **[!UICONTROL Save]**&#x200B;을(를) 클릭해야 합니다.

>[!NOTE]
>
>[!DNL Dynamics]에서 필드를 삭제하기 전에 동기화를 중지하지 않으면 동기화에서 오류가 발생할 수 있습니다. 이 경우 동기화가 중지됩니다. 다시 시작하기 전에 Marketo 관리자가 &quot;[!UICONTROL Select Fields to Sync]&quot;(위에서 설명)을 검토하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭하여 동기화에서 스키마 변경 내용을 적용해야 합니다.

변경 사항이 저장된 후 동기화를 활성화해야 합니다!

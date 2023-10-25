---
description: Dynamics - Marketo 문서 - 제품 설명서에서 삭제하기 전에 동기화할 필드 편집
title: Dynamics에서 삭제하기 전에 동기화할 필드 편집
exl-id: 6fa9f6c0-c69d-478f-b333-13a5c910f577
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '208'
ht-degree: 0%

---

# Dynamics에서 삭제하기 전에 동기화할 필드 편집 {#editing-fields-to-sync-before-deleting-them-in-dynamics}

Dynamics에서 필드를 삭제할 수도 있습니다. Marketo Engage은 동기화를 기반으로 필드 목록을 참조로 유지합니다. 동기화가 켜져 있는 동안 Dynamics에서 필드가 삭제되면 동기화에 오류가 발생할 수 있습니다. 필드를 삭제하기 전에 아래 단계를 수행합니다.

1. Marketo에서 **[!UICONTROL 관리자]**.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. 통합에서 **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. 클릭 **[!UICONTROL 동기화 비활성화]**.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. 브라우저의 새 탭에서 Dynamics에 로그인하여 원하는 필드를 삭제합니다.

1. Marketo으로 돌아가서 Microsoft Dynamics에서 **[!UICONTROL 편집]** &quot;2단계: 동기화할 필드 선택&quot; 옆에 있습니다.

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. 필드를 검토하고 다음을 클릭합니다. **[!UICONTROL 저장]**.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>클릭 **[!UICONTROL 저장]** 변경하지 않은 경우에도 동기화를 위해 업데이트된 스키마를 저장하는 데 필요합니다.

>[!NOTE]
>
>Dynamics에서 필드를 삭제하기 전에 동기화가 중지되지 않으면 동기화에 오류가 발생할 수 있습니다. 이 경우 동기화가 중지됩니다. 다시 시작하기 전에 Marketo 관리자는 &quot;동기화할 필드 선택&quot;(위에서 설명)을 검토하고 다음을 클릭해야 합니다. **[!UICONTROL 저장]** 동기화에서 스키마 변경 내용을 수락하도록 합니다.

변경 사항이 저장된 후 동기화를 활성화해야 합니다!

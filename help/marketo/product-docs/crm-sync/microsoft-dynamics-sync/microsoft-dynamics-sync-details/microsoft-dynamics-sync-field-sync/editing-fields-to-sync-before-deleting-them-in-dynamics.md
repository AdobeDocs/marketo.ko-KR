---
description: Dynamics - Marketing To Docs - 제품 문서에서 필드를 삭제하기 전에 동기화할 필드 편집
title: Dynamics에서 필드를 삭제하기 전에 동기화할 필드 편집
translation-type: tm+mt
source-git-commit: ed9399396c82a3b2fb93c83ffdaa1dc7b0827306
workflow-type: tm+mt
source-wordcount: '207'
ht-degree: 0%

---


# Dynamics {#editing-fields-to-sync-before-deleting-them-in-dynamics}에서 필드를 삭제하기 전에 동기화할 필드 편집

Dynamics에서 필드를 삭제할 수도 있습니다. Marketing은 필드 목록을 동기화를 기반으로 하는 참조로 유지합니다. 동기화가 켜져 있는 동안 Dynamics에서 필드를 삭제하면 동기화 오류가 발생할 수 있습니다. 필드를 삭제하기 전에 아래 절차를 따르십시오.

1. Marketing에서 **관리**&#x200B;를 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-1.png)

1. 통합에서 **Microsoft Dynamics**&#x200B;을 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-2.png)

1. **동기화 비활성화**&#x200B;를 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-3.png)

1. 브라우저의 새 탭에서 Dynamics에 로그인하고 원하는 필드를 삭제합니다.

1. Marketing의 Microsoft Dynamics에서 &quot;2단계:동기화할 필드를 선택합니다.&quot;****

   ![](assets/sync-before-deleting-them-in-dynamics-4.png)

1. 필드를 검토하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/sync-before-deleting-them-in-dynamics-5.png)

>[!CAUTION]
>
>동기화를 위해 업데이트된 스키마를 저장하려면 변경 사항이 없더라도 **저장**&#x200B;을 클릭해야 합니다.

>[!NOTE]
>
>Dynamics에서 필드를 삭제하기 전에 동기화를 중지하지 않으면 동기화 오류가 발생할 수 있습니다. 이 경우 동기화가 중지됩니다. 다시 시작하기 전에, 동기화를 통해 스키마 변경 사항을 수락하려면 Marketing To 관리자가 &quot;동기화할 필드 선택&quot;(위에서 설명됨)을 검토하고 **저장**&#x200B;을 클릭해야 합니다.

변경 내용을 저장한 후 동기화를 활성화해야 합니다.

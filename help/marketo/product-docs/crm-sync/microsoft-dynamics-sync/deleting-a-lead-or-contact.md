---
unique-page-id: 45417322
description: Microsoft Dynamics과 Marketo 간에 리드 및 연락처 삭제가 작동하는 방식을 이해합니다. 필요에 따라 Microsoft이 삭제됨 플래그 및 개인 흐름 삭제 작업을 사용합니다.
title: 리드 또는 연락처 삭제
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
feature: Microsoft Dynamics
TQID: https://experienceleague.adobe.com/4BwBuLQFJ2pRehuS8EqW-UrEcg5sVeqcstu3azh0NvQ
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 167
ht-degree: 5%

---

# 리드 또는 연락처 삭제 {#deleting-a-lead-or-contact}

[!DNL Microsoft Dynamics]에서 잠재 고객/연락처를 삭제할 때 알아야 할 몇 가지 사항이 있습니다.

* [!DNL Dynamics]에서 잠재 고객이 삭제되었기 때문에 Marketo에서 자동으로 사람을 삭제하지 않습니다. 대신 &quot;Microsoft이 삭제되었습니다.&quot; 필드가 true로 설정됩니다. 원하는 경우 이 필드를 트리거오프하여 Marketo에서 레코드를 삭제할 수 있습니다.

* &quot;개인 삭제&quot; 흐름 작업: Marketo에서 개인만 삭제됩니다(Dynamics에서도 삭제할 수 있는 옵션을 사용할 수 없음).

* 잠재 고객이 Marketo에서 삭제되고([!DNL Dynamics]에서는 삭제되지 않음) [!DNL Dynamics]에서 업데이트되면 Marketo에 새 사용자(동일한 이메일 주소, 새 사용자 ID)가 만들어집니다.

* 리드가 [!DNL Dynamics]에서 삭제된 후(Marketo에서는 삭제되지 않음) &quot;사용자를 Microsoft에 동기화&quot; 흐름 작업을 통해 실행되면 [!DNL Dynamics]에 새 리드가 만들어집니다.

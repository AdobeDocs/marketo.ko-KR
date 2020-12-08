---
unique-page-id: 45417322
description: 리드 또는 연락처 삭제 - 마케팅 문서 - 제품 설명서
title: 리드 또는 연락처 삭제
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---


# 리드 또는 연락처 삭제 {#deleting-a-lead-or-contact}

Microsoft Dynamics에서 리드/연락처를 삭제하는 경우 몇 가지 알아 두어야 합니다.

&quot;리드가 Dynamics에서 삭제되었다고 해서 Marketing에서 사람을 자동으로 삭제하지 않습니다. 대신 필드 &quot;Microsoft is Deleted&quot; 플래그가 true로 설정됩니다. 원할 경우 이 필드를 트리거하여 Marketing의 레코드를 삭제할 수 있습니다.

- &quot;사람 삭제&quot; 플로우 작업:이렇게 하면 Marketing To의 한 사람만 삭제됩니다. Dynamics에서는 이 사람을 삭제할 수 없습니다.

-리드가 Markto(Dynamics에서는 제외)에서 삭제되고 그 후 Dynamics에서 업데이트되면 Marketing To에 새 사람(동일한 이메일 주소, 새 사람 ID)이 만들어집니다.

-Dynamics(Marketing To에서는 제외)에서 리드를 삭제한 다음 나중에 &quot;사람과 Microsoft 동기화&quot; 흐름 작업을 통해 실행되면 Dynamics에서 새 리드가 만들어집니다.

---
unique-page-id: 45417322
description: 리드 또는 연락처 삭제 - Marketo 문서 - 제품 설명서
title: 리드 또는 연락처 삭제
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '158'
ht-degree: 0%

---

# 리드 또는 연락처 삭제 {#deleting-a-lead-or-contact}

Microsoft Dynamics에서 리드/연락처를 삭제할 때 알아야 할 몇 가지 사항이 있습니다.

* Dynamics에서 리드가 삭제되었다고 해서 Marketo Engage이 자동으로 사람을 삭제하지 않습니다. 대신 &quot;Microsoft이 삭제되었습니다.&quot; 필드가 true로 설정됩니다. 원하는 경우 이 필드를 트리거오프하여 Marketo에서 레코드를 삭제할 수 있습니다.

* &quot;개인 삭제&quot; 흐름 작업: Marketo에서 개인만 삭제됩니다(Dynamics에서도 삭제할 수 있는 옵션을 사용할 수 없음).

* 리드가 Marketo에서 삭제되고(Dynamics에서는 삭제되지 않음) 그 이후에 Dynamics에서 업데이트되면 Marketo에 새 사용자(동일한 이메일 주소, 새 사용자 ID)가 만들어집니다.

* 리드가 Dynamics에서 삭제된 경우(Marketo에서는 삭제되지 않음) 이후 &quot;사용자를 Microsoft에 동기화&quot; 흐름 작업을 통해 실행되면 Dynamics에서 새 리드가 만들어집니다.

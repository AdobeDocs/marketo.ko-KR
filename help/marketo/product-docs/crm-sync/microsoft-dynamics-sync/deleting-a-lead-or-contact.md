---
unique-page-id: 45417322
description: 리드 삭제 또는 연락처 - Marketo 문서 - 제품 설명서
title: 리드 또는 연락처 삭제
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# 리드 또는 연락처 삭제 {#deleting-a-lead-or-contact}

Microsoft Dynamics에서 리드/연락처를 삭제하는 문제를 몇 가지 알고 있어야 합니다.

* Marketo은 리드가 Dynamics에서 삭제되었다고 해서 사람을 자동으로 삭제하지 않습니다. 대신 필드 &quot;Microsoft이 삭제됨&quot; 플래그가 true로 설정됩니다. 원하는 경우 이 필드를 트리거하여 Marketo에서 레코드를 삭제할 수 있습니다.

* &quot;개인 삭제&quot; 흐름 작업: 이렇게 하면 Marketo에서 한 사람만 삭제됩니다. Dynamics에서도 사람을 삭제할 수 없습니다.

* 리드가 Marketo(Dynamics에서는 아님)에서 삭제되고 해당 후 Dynamics에서 업데이트되면 Marketo에 새 사람(동일한 이메일 주소, 새 개인 ID)이 만들어집니다.

* 리드가 Dynamics(Marketo에서는 아님)에서 삭제된 다음 나중에 &quot;개인을 Microsoft에 동기화&quot; 흐름 작업을 통해 실행되면 Dynamics에서 새 리드가 만들어집니다.

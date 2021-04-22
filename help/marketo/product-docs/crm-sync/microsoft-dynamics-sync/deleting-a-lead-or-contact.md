---
unique-page-id: 45417322
description: 리드 또는 연락처 삭제 - Marketo 문서 - 제품 설명서
title: 리드 또는 연락처 삭제
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# 리드 삭제 또는 {#deleting-a-lead-or-contact} 연락처

Microsoft Dynamics에서 리드/연락처 삭제 작업을 할 때 알아야 할 몇 가지 사항이 있습니다.

* Marketo은 Dynamics에서 리드가 삭제되었기 때문에 사람을 자동으로 삭제하지 않습니다. 대신 필드 &quot;Microsoft is Deleted&quot; 플래그가 true로 설정됩니다. 원할 경우 이 필드를 트리거하여 Marketo의 레코드를 삭제할 수 있습니다.

* &quot;사람 삭제&quot; 플로우 작업:이렇게 하면 Marketo의 사용자만 삭제됩니다. Dynamics에서는 사람을 삭제할 수 없습니다.

* 리드가 Marketo(Dynamics에서는 제외)에서 삭제되고 그 후 Dynamics에서 업데이트되는 경우 Marketo에 새 사람(동일한 이메일 주소, 새 사람 ID)이 만들어집니다.

* Dynamics에서 리드가 삭제되고(Marketo에서는 제외) 나중에 &quot;사람과 Microsoft 동기화&quot; 흐름 작업을 통해 실행되면 Dynamics에서 새 리드가 만들어집니다.

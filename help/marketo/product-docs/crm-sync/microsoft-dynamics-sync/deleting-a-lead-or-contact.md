---
unique-page-id: 45417322
description: 리드 또는 연락처 삭제 - 마케팅 문서 - 제품 설명서
title: 리드 또는 연락처 삭제
translation-type: tm+mt
source-git-commit: 2b5ccd7220557a5e966d33436d0f0d2a65e4589d
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---


# 리드 삭제 또는 {#deleting-a-lead-or-contact} 연락처

Microsoft Dynamics에서 리드/연락처 삭제 작업을 할 때 알아야 할 몇 가지 사항이 있습니다.

* 리드가 Dynamics에서 삭제되었다고 해서 Marketing에서 사람을 자동으로 삭제할 수 없습니다. 대신 필드 &quot;Microsoft is Deleted&quot; 플래그가 true로 설정됩니다. 원할 경우 이 필드를 트리거하여 Marketing의 레코드를 삭제할 수 있습니다.

* &quot;사람 삭제&quot; 플로우 작업:이렇게 하면 Marketing To의 사용자만 삭제됩니다. Dynamics에서는 사람을 삭제할 수 없습니다.

* 리드가 Marketing To(Dynamics에서는 제외)에서 삭제되고 그 후 Dynamics에서 업데이트되면 Marketing To에 새 사람(동일한 이메일 주소, 새 사람 ID)이 만들어집니다.

* 리드가 Dynamics(Marketing에서는 제외)에서 삭제된 다음 &quot;Microsoft에 사람 동기화&quot; 흐름 작업을 통해 실행되면 Dynamics에서 새 리드가 만들어집니다.

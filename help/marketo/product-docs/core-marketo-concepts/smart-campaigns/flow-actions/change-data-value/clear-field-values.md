---
unique-page-id: 1147324
description: 필드 값 지우기 - Marketo 문서 - 제품 설명서
title: 필드 값 지우기
exl-id: cddc7697-4e8f-4a62-865c-efd451abea0c
feature: Smart Campaigns
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '102'
ht-degree: 0%

---

# 필드 값 지우기 {#clear-field-values}

[데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) 좋긴 한데, 어떻게 지내세요 _제거_ 값을 완전히 삭제하시겠습니까? 좋은 질문입니다!

1. 흐름 단계에서 지울 필드를 선택하고 입력합니다 **NULL** (모두 대문자)을 **새 값**.

   ![](assets/image2015-3-19-10-3a6-3a14.png)

1. 붐! 넌 몰랐을 거야! 흐름 단계가 완료되면 선택한 필드의 값이 지워집니다.

   ![](assets/image2015-3-19-10-3a11-3a9.png)

   >[!CAUTION]
   >
   >새 값을 비워 두거나 단순히 SPACE를 입력해도 필드가 실제로 비어 있지 않습니다. NULL을 입력해야 합니다. 또한, 플로우 단계는 실행 후 실행 취소할 수 없습니다.

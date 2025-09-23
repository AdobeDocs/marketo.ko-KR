---
unique-page-id: 1147324
description: 필드 값 지우기 - Marketo 문서 - 제품 설명서
title: 필드 값 지우기
exl-id: cddc7697-4e8f-4a62-865c-efd451abea0c
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '92'
ht-degree: 6%

---

# 필드 값 지우기 {#clear-field-values}

[데이터 값 변경](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)은(는) 훌륭하지만 값을 _제거_&#x200B;하는 방법은 무엇입니까? 좋은 질문입니다!

1. 흐름 단계에서 지우려는 필드를 선택하고 **[!UICONTROL NULL]**(모두 대문자)을(를) **[!UICONTROL New Value]**(으)로 입력합니다.

   ![](assets/clear-field-values-1.png)

1. 흐름 단계가 완료되면 선택한 필드의 값이 지워집니다.

   ![](assets/clear-field-values-2.png)

   >[!CAUTION]
   >
   >새 값을 비워 두거나 단순히 SPACE를 입력해도 필드가 실제로 비어 있지 않습니다. NULL을 입력해야 합니다. 또한, 플로우 단계는 실행 후 실행 취소할 수 없습니다.

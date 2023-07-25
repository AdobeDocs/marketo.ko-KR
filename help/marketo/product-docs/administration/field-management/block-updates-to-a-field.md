---
unique-page-id: 2360291
description: 필드 업데이트 차단 - Marketo 문서 - 제품 설명서
title: 필드에 대한 업데이트 차단
exl-id: 763097a3-cfa0-4df7-bfd1-40332b8dda1e
feature: Field Management
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '171'
ht-degree: 0%

---

# 필드에 대한 업데이트 차단 {#block-updates-to-a-field}

필드 업데이트를 차단하면 필드에 한 번 쓴 다음 필드의 수명 동안 원래 값을 유지할 수 있습니다. 다음과 같은 필드에 유용합니다. [!UICONTROL 개인 소스].

>[!NOTE]
>
>**관리자 권한 필요**

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/block-updates-to-a-field-1.png)

1. 클릭 **[!UICONTROL 필드 관리]**.

   ![](assets/block-updates-to-a-field-2.png)

1. 필드를 찾아 선택한 다음 아래에 **[!UICONTROL 필드 작업]**, 클릭 **[!UICONTROL 필드 업데이트 차단]**.

   ![](assets/block-updates-to-a-field-3.png)

   >[!NOTE]
   >
   >에 대한 업데이트를 차단할 수 있습니다. [프로그램 멤버 사용자 정의 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md) 또한.

1. 다음 항목 선택 **[!UICONTROL 입력 소스]** 을(를) 차단한 다음 **[!UICONTROL 적용]**.

   ![](assets/block-updates-to-a-field-4.png)

   >[!CAUTION]
   >
   >목록 가져오기를 수행할 때 가져오기 미리 보기에서 차단되는 필드의 상태는 일치하는 필드의 이름을 기반으로 Marketo이 필드를 자동으로 인식하는 경우에만 표시됩니다 _정확하게_ (또는 별칭이 설정된 경우). Marketo 필드 드롭다운에서 필드를 수동으로 선택하는 경우 가져오기 미리보기에 차단된 상태가 표시되지 않지만 해당 필드에 대한 업데이트 차단은 여전히 구현됩니다.

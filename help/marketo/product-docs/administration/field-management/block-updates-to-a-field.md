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

필드 업데이트를 차단하면 필드에 한 번 쓴 다음 필드의 수명 동안 원래 값을 유지할 수 있습니다. 이 기능은 [!UICONTROL 개인 Source]와 같은 필드에 유용합니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. **[!UICONTROL 관리자]** 영역으로 이동합니다.

   ![](assets/block-updates-to-a-field-1.png)

1. **[!UICONTROL 필드 관리]**&#x200B;를 클릭합니다.

   ![](assets/block-updates-to-a-field-2.png)

1. 필드를 찾아 선택한 다음 **[!UICONTROL 필드 작업]**&#x200B;에서 **[!UICONTROL 필드 업데이트 차단]**&#x200B;을 클릭합니다.

   ![](assets/block-updates-to-a-field-3.png)

   >[!NOTE]
   >
   >[프로그램 구성원 사용자 지정 필드](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-fields.md)에 대한 업데이트도 차단할 수 있습니다.

1. 차단할 **[!UICONTROL 입력 원본]**&#x200B;을 선택하고 **[!UICONTROL 적용]**&#x200B;을 클릭합니다.

   ![](assets/block-updates-to-a-field-4.png)

   >[!CAUTION]
   >
   >목록 가져오기를 수행할 때 가져오기 미리 보기에서 차단된 필드의 상태는 필드가 _정확히_&#x200B;와(과) 일치하는 필드의 이름을 기반으로 Marketo에서 자동으로 인식되는 경우(또는 별칭이 설정된 경우)에만 표시됩니다. Marketo 필드 드롭다운에서 필드를 수동으로 선택하는 경우 가져오기 미리보기에 차단된 상태가 표시되지 않지만 해당 필드에 대한 업데이트 차단은 여전히 구현됩니다.

---
unique-page-id: 4719306
description: Marketo 동기화 - Marketo 문서 - 제품 설명서에서 Salesforce 필드 숨기기
title: Marketo 동기화에서 Salesforce 필드 숨기기
exl-id: 5d7229f0-43b0-4232-93ed-a9ca52ace401
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '167'
ht-degree: 1%

---

# Marketo 동기화에서 Salesforce 필드 숨기기 {#hide-a-salesforce-field-from-the-marketo-sync}

>[!NOTE]
>
>**관리자 권한 필요**

Salesforce의 모든 필드가 마케팅에 유용한 것은 아닙니다. 필요한 필드만 포함하여 동기화 성능을 최적화할 수 있습니다. 다음은 Marketo Engage에서 필드를 숨길 수 있는 방법입니다.

1. 이름 메뉴를 클릭하고 **[!UICONTROL 설정]**&#x200B;을 선택합니다.

   ![](assets/image2015-6-30-15-3a11-3a23.png)

1. 검색 창에 &quot;프로필&quot;을 입력하고 **[!UICONTROL 사용자 관리]**&#x200B;에서 **[!UICONTROL 프로필]**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a12-3a46.png)

1. 동기화 사용자의 프로필을 클릭합니다.

   ![](assets/image2015-6-30-15-3a17-3a38.png)

1. **[!UICONTROL 필드 수준 보안]** 섹션에서 대상 필드가 포함된 개체 옆의 **[!UICONTROL 보기]**&#x200B;를 클릭합니다.

   ![](assets/image2015-6-30-15-3a24-3a32.png)

1. **[!UICONTROL 편집]**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a25-3a42.png)

1. 숨기려는 필드 옆의 **[!UICONTROL 표시]** 확인란의 선택을 취소합니다. **[!UICONTROL 저장]**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a27-3a16.png)

   >[!NOTE]
   >
   >Salesforce에서 숨기는 필드가 이미 Marketo과 동기화된 경우 이 필드를 사용하지 않으려면 Marketo에서도 숨겨야 합니다.

   다 됐습니다! 다음 동기화가 완료되면 Marketo에서 이 필드가 더 이상 표시되지 않습니다.

   >[!MORELIKETHIS]
   >
   >[필드 숨기기 및 숨기기 취소](/help/marketo/product-docs/administration/field-management/hide-and-unhide-a-field.md){target="_blank"}

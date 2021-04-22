---
unique-page-id: 4719306
description: Marketo Sync - Marketo Docs - 제품 문서에서 Salesforce 필드 숨기기
title: Marketo 동기화에서 Salesforce 필드 숨기기
exl-id: 5d7229f0-43b0-4232-93ed-a9ca52ace401
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '166'
ht-degree: 0%

---

# Marketo 동기화에서 Salesforce 필드 숨기기 {#hide-a-salesforce-field-from-the-marketo-sync}

>[!NOTE]
>
>**관리자 권한 필요**

Salesforce의 모든 필드가 마케팅에 유용한 것은 아닙니다. 필요한 필드만 포함하여 동기화 성능을 최적화할 수 있습니다. Marketo에서 필드를 숨길 수 있는 방법은 다음과 같습니다.

1. 이름 메뉴를 클릭하고 **설정**&#x200B;을 선택합니다.

   ![](assets/image2015-6-30-15-3a11-3a23.png)

1. 검색 막대에 **프로필**&#x200B;을 입력하고 **사용자 관리**&#x200B;에서 **프로필**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a12-3a46.png)

1. 사용자 프로필 동기화를 클릭합니다.

   ![](assets/image2015-6-30-15-3a17-3a38.png)

1. **필드 수준 보안** 섹션에서 대상 필드가 포함된 개체 옆에 있는 **보기**&#x200B;를 클릭합니다.

   ![](assets/image2015-6-30-15-3a24-3a32.png)

1. **편집**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a25-3a42.png)

1. 숨길 필드 옆에 있는 **Visible** 확인란의 선택을 취소합니다. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2015-6-30-15-3a27-3a16.png)

   >[!NOTE]
   >
   >Salesforce에서 숨긴 필드가 Marketo과 이미 동기화된 경우 사용하지 않으려면 Marketo에서도 숨겨야 합니다.

   바로 그거야! 다음 동기화가 완료되면 Marketo에서 이 필드가 더 이상 표시되지 않습니다.

   >[!MORELIKETHIS]
   >
   >[필드 숨기기 및 숨김 취소](/help/marketo/product-docs/administration/field-management/hide-and-unhide-a-field.md)

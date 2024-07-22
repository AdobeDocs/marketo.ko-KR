---
unique-page-id: 2950617
description: 이메일에서 동적 콘텐츠 사용 - Marketo 문서 - 제품 설명서
title: 이메일에서 동적 콘텐츠 사용
exl-id: a1178f76-6760-4a4a-9510-f129ee6a9032
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 0%

---

# 이메일에서 동적 콘텐츠 사용 {#using-dynamic-content-in-an-email}

>[!PREREQUISITES]
>
>[세분화 만들기](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

이메일의 다이내믹 콘텐츠를 사용하여 잠재 고객을 타겟팅한 정보를 보냅니다.

>[!NOTE]
>
>이메일의 다이내믹 콘텐츠 내에서 변수를 사용하는 것은 트리거 캠페인을 사용할 때만 지원됩니다. 일괄 캠페인을 사용할 때 **지원되지 않음**&#x200B;입니다.

## 세분화 추가 {#add-segmentation}

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/login-marketing-activities.png)

1. 이메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/1.2.png)

1. 이 예제에서는 제목 줄을 동적으로 만듭니다. 제목 필드를 클릭한 다음 **동적으로 만들기** 단추를 클릭합니다.

   ![](assets/1.3.png)

   >[!NOTE]
   >
   >이메일 내의 요소를 동적으로 만들 수도 있습니다. 이렇게 하려면 영역을 선택하고 톱니바퀴 아이콘을 클릭한 다음 **동적으로 만들기**(또는 수행 중인 작업에 따라 [조각으로 바꾸기](/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet.md))를 선택합니다.

1. 세분화 이름을 입력하고 선택한 다음 **저장**&#x200B;을 클릭합니다.

   ![](assets/1.4.png)

   세그먼테이션과 해당 세그먼트는 오른쪽의 동적 탭 아래에 나타납니다.

   ![](assets/1.5.png)

## 다이내믹 콘텐츠 적용 {#apply-dynamic-content}

>[!CAUTION]
>
>허용되는 다이내믹 콘텐츠 요소 수는 제한이 없습니다. 특정 수 제한은 없지만(콘텐츠 조합에 따라 다를 수 있음) 다이내믹 콘텐츠를 과도하게 사용하면 이메일 성능에 부정적인 영향을 줄 수 있습니다. 이메일당 20개 미만에 사용된 다이내믹 콘텐츠 요소의 양을 유지하는 것이 좋습니다.

1. 세그먼트를 클릭하고 제목 줄을 추가합니다.

![](assets/2.1.png)

1. 각 세그먼트에 대해 이 작업을 반복합니다.

   ![](assets/2.2.png)

>[!TIP]
>
>다양한 세그먼트에 콘텐츠를 적용하기 전에 기본 이메일을 만듭니다.

>[!CAUTION]
>
>기본 세그먼트 콘텐츠 블록에 대한 변경 사항이 모든 세그먼트에 적용됩니다.

잘됐네! 이제 타겟 대상자에게 유연한 이메일을 보낼 수 있습니다.

>[!MORELIKETHIS]
>
>* [다이내믹 콘텐츠로 이메일 미리 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/preview-an-email-with-dynamic-content.md)
>* [랜딩 페이지에서 동적 콘텐츠 사용](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/use-dynamic-content-in-a-free-form-landing-page.md)

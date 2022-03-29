---
unique-page-id: 2950617
description: 이메일에서 동적 컨텐츠 사용 - Marketo 문서 - 제품 설명서
title: 이메일에서 동적 컨텐츠 사용
exl-id: a1178f76-6760-4a4a-9510-f129ee6a9032
source-git-commit: 076d781fc8d967ee6f63ed2023e75c94e5aa1e55
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# 이메일에서 동적 컨텐츠 사용 {#using-dynamic-content-in-an-email}

>[!PREREQUISITES]
>
>[세그멘테이션 만들기](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

이메일의 다이내믹 콘텐츠를 사용하여 리드에 타겟팅된 정보를 보냅니다.

>[!NOTE]
>
>이메일의 동적 콘텐츠 내에서 변수 사용은 트리거 캠페인을 사용할 때에만 지원됩니다. 그렇습니다 **not** 배치 캠페인을 사용할 때 지원됩니다.

## 세그멘테이션 추가 {#add-segmentation}

1. 이동 **마케팅 활동**.

   ![](assets/login-marketing-activities.png)

1. 이메일을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/1.2.png)

1. 이 예제에서는 제목 줄을 동적으로 만듭니다. 제목 필드를 클릭한 다음 **동적으로 만들기** 버튼을 클릭합니다.

   ![](assets/1.3.png)

   >[!NOTE]
   >
   >이메일 내에 요소를 동적으로 만들 수도 있습니다. 이렇게 하려면 영역을 선택하고 톱니바퀴 아이콘을 클릭한 다음, 을 선택합니다 **동적으로 만들기** 또는 [코드 조각으로 바꾸기](/help/marketo/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet.md), 원하는 내용에 따라 ).

1. 세그먼테이션 이름을 입력하고 선택한 다음 **저장**.

   ![](assets/1.4.png)

   세그먼테이션 및 해당 세그먼트가 오른쪽의 동적 탭 아래에 나타납니다.

   ![](assets/1.5.png)

## 동적 콘텐츠 적용 {#apply-dynamic-content}

>[!CAUTION]
>
>허용되는 동적 콘텐츠 요소의 수는 제한이 없습니다. 특정 숫자 제한이 없지만(콘텐츠 조합에 따라 다를 수 있음), 동적 콘텐츠를 과도하게 사용하면 전자 메일 성능에 부정적인 영향을 줄 수 있습니다. 이메일당 사용되는 동적 콘텐츠 요소의 양을 20개 미만으로 유지하는 것이 좋습니다.

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

달콤해! 이제 유연한 이메일을 타겟 대상자에게 보낼 수 있습니다.

>[!MORELIKETHIS]
>
>* [다이내믹 콘텐츠를 사용한 이메일 미리 보기](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/preview-an-email-with-dynamic-content.md)
>* [랜딩 페이지에서 동적 콘텐츠 사용](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/use-dynamic-content-in-a-free-form-landing-page.md)


---
solution: Marketo Engage
product: marketo
title: 조건부 콘텐츠
description: 이메일의 조건부 콘텐츠를 사용하여 수신자에 따라 콘텐츠를 동적으로 표시할 수 있습니다.
level: Beginner, Intermediate
feature: Email Designer
hide: true
hidefromtoc: true
source-git-commit: 40fdd38d8ec5b63568c8ed9beeab0ef50974b7fd
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 3%

---

# 조건부 콘텐츠 {#conditional-content}

조건부 콘텐츠를 사용하면 대상자에게 표시되는 콘텐츠를 동적으로 제어할 수 있습니다. 기존 세그먼트를 사용하여 미리 정의된 기준에 따라 수신자에게 표시되는 내용을 결정합니다.

>[!PREREQUISITES]
>
>하나 이상의 세분화 [생성](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md) 및 [승인](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/approve-a-segmentation.md)이 있습니다.

## 조건부 콘텐츠 추가 {#add-conditional-content}

1. 원하는 전자 메일을 열고 **전자 메일 콘텐츠 편집**&#x200B;을 클릭합니다.

   ![](assets/conditional-content-1.png){width="800" zoomable="yes"}

1. 조건을 지정할 콘텐츠를 선택합니다(이 예제에서는 헤더 이미지를 선택함). _조건부 콘텐츠 사용_ 아이콘을 클릭합니다.

   ![](assets/conditional-content-2.png)

1. 상자가 주황색으로 바뀝니다. 왼쪽의 _조건 선택 아이콘_()을 클릭하여 변형을 정의합니다.

   ![](assets/conditional-content-3.png)

1. 원하는 세그먼트를 선택하고 **선택**&#x200B;을 클릭합니다.

   ![](assets/conditional-content-4.png)

1. 변형에 대한 기존 이미지를 바꾸려면 _이미지 편집_ 아이콘을 클릭하십시오. 새 이미지의 소스를 선택합니다. 이 예제에서는 Marketo Engage 구독에서 _이미지 및 파일_ 라이브러리를 선택합니다.

   ![](assets/conditional-content-5.png)

1. 적용 가능한 이미지를 선택하고 **선택**&#x200B;을 클릭합니다.

   ![](assets/conditional-content-6.png)

1. 새 이미지가 나타납니다. 식별이 쉽도록 변형 이름을 바꾸는 것이 좋습니다.

   ![](assets/conditional-content-7.png)

1. 추가 변형(선택 사항)을 추가하려면 **변형 추가**&#x200B;를 클릭하고 동일한 단계를 수행합니다.

   ![](assets/conditional-content-8.png)

1. 완료되면 각 변형에 선택한 콘텐츠가 표시됩니다.

   ![](assets/conditional-content-9.gif)

1. 수신자는 각 세그먼트에 정의된 규칙에 따라 콘텐츠를 볼 수 있습니다. 위의 예에서는 Marketo Engage 필드 _좋아하는 스포츠_&#x200B;에 &quot;축구&quot;가 나열되어 있는 모든 사용자가 축구 이미지를 볼 수 있습니다.

>[!MORELIKETHIS]
>
>* [세그먼트 규칙 정의](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)
>* [Marketo에서 사용자 지정 필드 만들기](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md)

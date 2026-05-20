---
unique-page-id: 2359500
description: 세그먼테이션 순서 우선 순위 및 사용자가 속한 세그먼트를 결정하는 방법에 대해 알아봅니다. 데이터베이스의 세그먼트 순서를 편집하여 세그먼트 평가를 제어합니다.
title: 세분화 순서 우선순위
exl-id: c20d07c8-5e53-4f54-a7a3-2e1aa4fb0cdd
feature: Segmentation
TQID: https://experienceleague.adobe.com/wDvufJzxu0BFCSov4etUpEMxaol3-R5CePqllYyDeSc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
  - id: cdd4e0f6-e87e-453f-88ee-2ee54a7de272
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 140
ht-degree: 4%

---

# 세분화 순서 우선순위 {#segmentation-order-priority}

**order**&#x200B;이(가) 세분화에서 사용자의 평가 우선 순위를 설정하는 방법을 이해하는 것이 중요합니다.

>[!PREREQUISITES]
>
>[세분화 만들기](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)
>[세그먼트 규칙 정의](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)

>[!NOTE]
>
>초안 모드에서만 세그먼테이션을 편집할 수 있습니다.

1. **데이터베이스**(으)로 이동합니다.

   ![](assets/segmentation-order-priority-1.png)

1. **세그먼테이션**&#x200B;을 선택하세요. **[!UICONTROL Segmentation Actions]**&#x200B;에서 **[!UICONTROL Edit Segments]**&#x200B;을(를) 클릭합니다.

   ![](assets/segmentation-order-priority-2.png)

   이 화면에서 세그먼트의 순서를 확인하거나 편집할 수 있습니다.

   ![](assets/segmentation-order-priority-3.png)

>[!NOTE]
>
>* 세그먼트는 상호 배타적입니다. 한 번에 한 세그먼트만 멤버로 만들 수 있습니다.
>* 한 사람이 두 개의 세그먼트에 대한 자격이 되면 목록의 첫 번째 세그먼트에만 속하게 됩니다.
>* 어떤 세그먼트에도 적합하지 않은 사람은 기본 세그먼트의 구성원이 됩니다.

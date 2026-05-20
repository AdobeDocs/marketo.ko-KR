---
unique-page-id: 2359457
description: 다이내믹 콘텐츠 및 보고에 사용할 수 있도록 세그먼테이션을 승인하는 방법을 알아봅니다. 세그먼트 규칙을 정의한 후 데이터베이스 및 세분화 작업을 사용하여 승인합니다.
title: 세분화 승인
exl-id: c8b0fbe9-012c-47bf-8769-0167156b43d3
feature: Segmentation
TQID: https://experienceleague.adobe.com/hvFKybwLh1INYx2YWtOmdebJVYXOzhNMMncqeOoV8EU
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: c5f60233-d5ea-4453-a799-0ad258b4d399id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
subfeature_v2: id: a1d50dda-6d94-4e16-8c30-5eb7181c4650id: df8eb12b-4f82-491f-acbb-d74012ca5654
topic_v2: id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 246
ht-degree: 5%

---

# 세분화 승인 {#approve-a-segmentation}

세그먼테이션을 사용하려면 먼저 승인해야 합니다.

>[!PREREQUISITES]
>
>* [세분화 만들기](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)
>* [세그먼트 규칙 정의](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.md)

>[!NOTE]
>
>한 번에 최대 20개의 세그먼테이션을 승인할 수 있습니다.

1. **[!UICONTROL Database]**(으)로 이동합니다.

   ![](assets/approve-a-segmentation-1.png)

1. 세분화에서 **[!UICONTROL Segmentation Actions]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Approve]**&#x200B;을(를) 클릭합니다.

   ![](assets/approve-a-segmentation-2.png)

   >[!NOTE]
   >
   >승인이 진행되는 동안 상태가 _승인 중_(으)로 변경됩니다.

   >[!CAUTION]
   >
   >데이터베이스 크기에 따라 승인을 완료하는 데 몇 분에서 하루나 이틀 정도 걸릴 수 있습니다.

1. 승인되면 [!UICONTROL Status]이(가) [!UICONTROL Approving]에서 [!UICONTROL Approved]&#x200B;(으)로 변경됩니다.

   ![](assets/approve-a-segmentation-3.png)

   >[!TIP]
   >
   >각 세그먼트의 사람 수는 세그먼트 이름 옆에 대괄호로 표시됩니다.

1. 이제 **[!UICONTROL Segment]**&#x200B;의 **[!UICONTROL People]** 탭에 세그먼트에 대한 최종 사용자 목록이 표시됩니다.

   ![](assets/approve-a-segmentation-4.png)

>[!CAUTION]
>
>세그먼테이션에서 만들 수 있는 총 세그먼트 수는 사용된 필터의 수와 유형 및 세그먼트의 로직이 얼마나 복잡한지에 따라 다릅니다. 표준 필드를 사용하여 최대 100개의 세그먼트를 만들 수 있지만 다른 유형의 필터를 사용하면 복잡성이 증가하여 세그먼테이션이 승인되지 않을 수 있습니다. 일부 예는 사용자 정의 필드, 목록 멤버, 리드 소유자 필드 및 수익 단계입니다.
>
>승인 중에 오류 메시지가 표시되고 세분화의 복잡성을 줄이는 데 도움이 필요한 경우 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support)에 문의하십시오.

>[!MORELIKETHIS]
>
>[스마트 목록에서 세그먼트 필터 사용](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/use-segment-filters-in-a-smart-list.md)

---
unique-page-id: 2359449
description: 세그먼트 규칙 정의 - Marketo 문서 - 제품 설명서
title: 세그먼트 규칙 정의
exl-id: e6631848-aa8c-4709-b182-4c88abbd365b
source-git-commit: 55afdc537d0a5d0b6114f478c4dd2ded09c84e34
workflow-type: tm+mt
source-wordcount: '382'
ht-degree: 0%

---

# 세그먼트 규칙 정의 {#define-segment-rules}

세그먼트 규칙 정의를 사용하면 사람들을 서로 다른 상호 배타적인 그룹으로 분류할 수 있습니다.

>[!PREREQUISITES]
>
>[세그멘테이션 만들기](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md)

1. 로 이동합니다. **데이터베이스.**

   ![](assets/image2017-3-28-14-3a7-3a42.png)

1. 선택 **세그먼테이션** 트리에서 특정 **세그먼트**.

   ![](assets/image2017-3-28-14-3a11-3a15.png)

1. 클릭 **Smart List** 및 필터를 추가합니다.

   ![](assets/image2017-3-28-14-3a18-3a19.png)

   >[!CAUTION]
   >
   >현재 세그먼트는 지원되지 않습니다 _과거_ 및 _일정_  연산자 사용 변경 데이터 값이 기록될 때만 세그먼테이션이 업데이트를 확인하기 때문입니다. 이러한 값은 _not_ 공식 필드 및 날짜 등 자동으로 변경되는 항목을 위해 기록됩니다. 또한 상대적 날짜 범위가 있는 날짜 연산자는 데이터 값 변경 활동 시점이 아니라 세분화 승인 시 계산되므로 지원되지 않습니다.

   >[!NOTE]
   >
   >SFDC 유형 및 Microsoft 유형 필터는 현재 세그멘테이션 스마트 목록에서 지원되지 않습니다.

1. 필터에 적절한 값을 채웁니다.

   ![](assets/image2017-3-28-14-3a18-3a33.png)

   >[!CAUTION]
   >
   >계정 필드에 대한 활동 로깅 동작은 자격에 영향을 줄 수 있습니다. 따라서 세그먼트 규칙을 정의할 때 계정 필드를 사용하지 않는 것이 좋습니다.

1. 을(를) 클릭합니다. **사람(초안)** 탭하여 이 세그먼트의 구성원일 수 있는 사람을 볼 수 있습니다.

   ![](assets/image2017-3-28-14-3a20-3a15.png)

1. 이동 **세그먼테이션 작업**. 클릭 **승인**.

   ![](assets/image2014-9-15-11-3a36-3a7.png)

   >[!CAUTION]
   >
   >세그먼테이션에서 만들 수 있는 총 세그먼트 수는 사용된 필터의 수 및 유형과 세그먼트의 논리가 얼마나 복잡한지에 따라 다릅니다. 표준 필드를 사용하여 최대 100개의 세그먼트를 만들 수 있지만 다른 유형의 필터를 사용하면 복잡성이 높아지며 세그먼테이션을 승인하지 못할 수 있습니다. 예를 들면 다음과 같습니다. 사용자 정의 필드, 목록 멤버, 리드 소유자 필드 및 수익 단계.
   >
   >승인 중에 오류 메시지가 표시되고 세그멘테이션의 복잡도를 줄이는 데 도움이 필요한 경우 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).

1. 적용된 규칙과 파이 차트에 있는 세그먼트에 대한 간단한 개요를 보려면 대시보드를 확인하십시오.

   ![](assets/image2014-9-15-11-3a36-3a19.png)

잘했어! 이러한 세그먼트는 Marketo의 많은 곳에서 유용하게 사용될 것입니다.

>[!NOTE]
>
>사람은 다른 세그먼트에 대한 자격이 있을 수 있지만 결국 은(는) [세그먼트의 우선순위 순서](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md).

>[!NOTE]
>
>사람(초안) 화면에는 구성원이 될 자격이 있고 항상 최종 목록이 아닌 모든 사람이 표시됩니다. 최종 목록을 보려면 세그먼트를 승인하십시오.

>[!MORELIKETHIS]
>
>[세그멘테이션 승인](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/approve-a-segmentation.md)

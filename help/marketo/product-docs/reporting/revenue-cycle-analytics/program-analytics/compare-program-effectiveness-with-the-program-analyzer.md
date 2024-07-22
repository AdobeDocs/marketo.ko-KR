---
unique-page-id: 2360403
description: 프로그램 분석기와 프로그램 효율성 비교 - Marketo 설명서 - 제품 설명서
title: 프로그램 분석기와 프로그램 효율성 비교
exl-id: 6e54d0a4-3cff-46cf-be0d-1992a39d8c03
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '469'
ht-degree: 0%

---

# 프로그램 분석기와 프로그램 효율성 비교 {#compare-program-effectiveness-with-the-program-analyzer}

프로그램 분석기를 사용하여 프로그램 비용, 회원 확보, 파이프라인 및 매출을 비교하여 가장 효율적이고 가장 적은 프로그램을 식별합니다.

>[!PREREQUISITES]
>
>[프로그램 분석기 만들기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/create-a-program-analyzer.md)

1. **분석**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-17-18-3a50-3a30.png)

1. 프로그램 분석기를 선택합니다.

   ![](assets/image2014-9-17-18-3a50-3a37.png)

1. 보기를 프로그램별로 변경합니다.

   ![](assets/image2014-9-17-18-3a50-3a44.png)

1. 채널 필터를 사용하여 보기를 1~2개 채널로 축소할 수 있습니다. 지금은 Tradeshow 채널에서 프로그램을 살펴보겠습니다.

   ![](assets/image2014-9-17-18-3a51-3a2.png)

   >[!TIP]
   >
   >프로그램을 하나의 채널로만 필터링하는 빠른 방법은 **보기** > **채널별**&#x200B;을 선택하고 해당 채널의 버블을 클릭한 다음 팝업 대화 상자에서 채널 이름을 클릭하는 것입니다.

1. X축 드롭다운을 사용하여 가로 축에 대한 지표를 선택합니다. 프로그램 비용부터 시작하겠습니다.

   ![](assets/image2014-9-17-18-3a52-3a16.png)

1. Y축 드롭다운을 사용하여 세로 축에 대한 지표를 선택합니다. 새로운 잠재 고객을 포착하는 데 유용한 프로그램을 찾기 위해 새 이름을 선택하겠습니다.

   ![](assets/image2014-9-17-18-3a52-3a26.png)

1. 확대하려면 슬라이더를 켭니다.

   ![](assets/image2014-9-17-18-3a53-3a9.png)

   >[!TIP]
   >
   >또한 선형 스케일에서 로그 스케일로 변경하거나 그 반대로 변경하여 보기를 개선하려고 할 수도 있습니다. 맨 위에 있는 **크기 조정** 메뉴를 사용하십시오.

1. 결과 그래프를 살펴봅니다.

   ![](assets/image2014-9-17-18-3a53-3a49.png)

   이 예에서, 우리는 종이접기 엑스포가 새로운 이름을 포착할 때, 그리고 중간 비용으로 그 채널의 다른 모든 프로그램보다 훨씬 낫다는 것을 배웁니다. 하지만 그게 전부는 아니에요. 더 깊이 이해할 수 있도록 지표를 두 개 더 추가합니다.

1. 버블 크기 드롭다운을 사용하여 버블 크기로 비교할 지표를 선택합니다. 이 예제에서는 (FT) Revenue Won을 선택합니다.

   ![](assets/image2014-9-17-18-3a54-3a25.png)

   >[!NOTE]
   >
   >프로그램 분석기에서 선택할 수 있는 많은 지표는 FT(첫 번째 터치) 및 MT(다중 터치) 계산을 통해 사용할 수 있습니다. FT와 MT 속성의 [차이점](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md)을 이해하는 것이 중요합니다.

1. 그래프에서 거품의 크기가 변경되는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a54-3a57.png)

   **(FT) 매출 원**&#x200B;을 추가하면 Origami Expo가 많은 새 이름을 획득하는 동안 상대적으로 적은 매출을 얻습니다. 또한, 우리는 종이 축제 12 프로그램이 더 적은 수 있지만 더 나은 이름을 얻고 있다는 것을 볼 수 있습니다, 왜냐하면 그것은 더 많은 수익에 영향을 주기 때문입니다 (더 큰 거품).

1. 색상 드롭다운을 사용하여 네 번째 지표를 추가합니다. 우리는 투자에 대한 (FT) 매출을 살펴볼 것이다.

   ![](assets/image2014-9-17-18-3a55-3a33.png)

1. 그래프의 색상이 변하는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a55-3a47.png)

우리는 Paper Fest 12 프로그램이 더 많은 수익 (더 큰 거품)에 영향을 미칠 뿐만 아니라, 상대적으로 높은 프로그램 비용 (맨 오른쪽에 있음)에도 불구하고, 그것은 Tradeshow 채널에 있는 모든 프로그램 중 가장 좋은 투자 수익률 (가장 녹색 거품)을 가지고 있다는 것을 알 수 있습니다.

>[!TIP]
>
>한 채널의 프로그램을 다른 채널의 프로그램과 빠르게 비교할 수 있습니다. 더 많은 채널을 추가하려면 창 상단의 **채널 필터**&#x200B;를 사용하세요.

>[!MORELIKETHIS]
>
>* [프로그램 분석기를 사용하여 프로그램 및 채널 세부 정보 탐색](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/explore-program-and-channel-details-with-the-program-analyzer.md)
>* [프로그램 분석기와 채널 효율성 비교](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/compare-channel-effectiveness-with-the-program-analyzer.md)

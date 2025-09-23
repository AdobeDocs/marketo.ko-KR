---
unique-page-id: 2360403
description: 프로그램 분석기와 프로그램 효율성 비교 - Marketo 설명서 - 제품 설명서
title: 프로그램 분석기로 프로그램 효과 비교
exl-id: 6e54d0a4-3cff-46cf-be0d-1992a39d8c03
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '418'
ht-degree: 1%

---

# [!UICONTROL Program Analyzer]과(와) 프로그램 효율성 비교 {#compare-program-effectiveness-with-the-program-analyzer}

[!UICONTROL Program Analyzer]을(를) 사용하여 프로그램 비용, 회원 확보, 파이프라인 및 매출을 비교하여 가장 효과적이고 가장 적은 프로그램을 식별하십시오.

>[!PREREQUISITES]
>
>[[!UICONTROL Program Analyzer]](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/create-a-program-analyzer.md) 만들기

1. **[!UICONTROL Analytics]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-17-18-3a50-3a30.png)

1. 프로그램 분석기를 선택합니다.

   ![](assets/image2014-9-17-18-3a50-3a37.png)

1. 보기를 **[!UICONTROL By Program]**(으)로 변경합니다.

   ![](assets/image2014-9-17-18-3a50-3a44.png)

1. **[!UICONTROL Channel Filter]**&#x200B;을(를) 사용하여 보기를 하나 또는 두 개의 채널로 줄이십시오. 지금은 **[!UICONTROL Tradeshow]** 채널의 프로그램을 살펴봅니다.

   ![](assets/image2014-9-17-18-3a51-3a2.png)

   >[!TIP]
   >
   >프로그램을 한 개의 채널로만 필터링하는 빠른 방법은 **[!UICONTROL View]** > **[!UICONTROL By Channel]**&#x200B;을(를) 선택하고 해당 채널의 버블을 클릭한 다음 팝업 대화 상자에서 채널 이름을 클릭하는 것입니다.

1. **[!UICONTROL X Axis]** 드롭다운을 사용하여 가로 축에 대한 지표를 선택합니다. **[!UICONTROL Program Cost]**(으)로 시작합니다.

   ![](assets/image2014-9-17-18-3a52-3a16.png)

1. **[!UICONTROL Y Axis]** 드롭다운을 사용하여 세로 축에 대한 지표를 선택합니다. 새 잠재 고객을 포착하는 데 적합한 프로그램을 찾으려면 **[!UICONTROL New Names]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2014-9-17-18-3a52-3a26.png)

1. 확대하려면 슬라이더를 켭니다.

   ![](assets/image2014-9-17-18-3a53-3a9.png)

   >[!TIP]
   >
   >또한 선형 스케일에서 로그 스케일로 변경하거나 그 반대로 변경하여 보기를 개선하려고 할 수도 있습니다. 맨 위에 있는 **[!UICONTROL Scale]** 메뉴를 사용하십시오.

1. 결과 그래프를 살펴봅니다.

   ![](assets/image2014-9-17-18-3a53-3a49.png)

   이 예제에서는 [!DNL Origami Expo]이(가) 새 이름을 캡처할 때 중간 비용으로 해당 채널의 다른 모든 프로그램보다 훨씬 낫다는 것을 알아냈습니다. 하지만 그게 전부는 아니에요. 더 깊이 이해할 수 있도록 지표를 두 개 더 추가합니다.

1. **[!UICONTROL Bubble Size]** 드롭다운을 사용하여 거품의 크기로 비교할 지표를 선택합니다. 이 예제에서는 **[!UICONTROL (FT) Revenue Won]**&#x200B;을(를) 선택합니다.

   ![](assets/image2014-9-17-18-3a54-3a25.png)

   >[!NOTE]
   >
   >프로그램 분석기에서 선택할 수 있는 많은 지표는 FT(첫 번째 터치) 및 MT(다중 터치) 계산을 통해 사용할 수 있습니다. FT와 MT 속성의 [차이점](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md)을 이해하는 것이 중요합니다.

1. 그래프에서 거품의 크기가 변경되는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a54-3a57.png)

   **[!UICONTROL (FT) Revenue Won]**&#x200B;을(를) 추가하면 [!DNL Origami Expo]이(가) 많은 새 이름을 얻는 동안 상대적으로 적은 매출을 얻게 됩니다. 또한 [!DNL Paper Fest 12] 프로그램이 더 많은 수익(더 큰 거품)에 영향을 주므로 더 적지만 더 나은 이름이 되고 있습니다.

1. 색상 드롭다운을 사용하여 네 번째 지표를 추가합니다. **[!UICONTROL (FT) Revenue to Investment]**&#x200B;을(를) 살펴봅니다.

   ![](assets/image2014-9-17-18-3a55-3a33.png)

1. 그래프의 색상이 변하는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a55-3a47.png)

[!DNL Paper Fest 12] 프로그램이 더 많은 매출(거품)에 영향을 줄 뿐만 아니라 상대적으로 높은 프로그램 비용(맨 오른쪽에 있음)에도 불구하고 [!UICONTROL Tradeshow] 채널의 모든 프로그램 중 투자 수익률(가장 친환경적인 거품)이 가장 좋습니다.

>[!TIP]
>
>한 채널의 프로그램을 다른 채널의 프로그램과 빠르게 비교할 수 있습니다. 더 많은 채널을 추가하려면 창 상단의 **채널 필터**&#x200B;를 사용하세요.

>[!MORELIKETHIS]
>
>* [[!UICONTROL Program Analyzer]](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/explore-program-and-channel-details-with-the-program-analyzer.md)과(와) 함께 프로그램 및 채널 세부 정보 살펴보기
>* [채널 효과를 [!UICONTROL Program Analyzer]](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/compare-channel-effectiveness-with-the-program-analyzer.md)과(와) 비교

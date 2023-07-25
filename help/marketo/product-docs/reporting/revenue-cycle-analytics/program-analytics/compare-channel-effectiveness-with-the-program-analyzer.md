---
unique-page-id: 2360401
description: 프로그램 분석기와 채널 효율성 비교 - Marketo 문서 - 제품 설명서
title: 프로그램 분석기와 채널 효율성 비교
exl-id: bfe635a7-b077-4074-889d-fc2256102cd5
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '399'
ht-degree: 0%

---

# 프로그램 분석기와 채널 효율성 비교 {#compare-channel-effectiveness-with-the-program-analyzer}

프로그램 분석기를 사용하여 채널 비용, 회원 확보, 파이프라인, 매출 등을 비교하여 가장 효과적이고 가장 낮은 채널을 식별합니다.

>[!PREREQUISITES]
>
>[프로그램 분석기 만들기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/create-a-program-analyzer.md)

1. 클릭 **분석** 위치: **내 Marketo**.

   ![](assets/image2014-9-17-18-3a36-3a13.png)

1. 다음 항목 선택 **프로그램 분석기**.

   ![](assets/image2014-9-17-18-3a36-3a40.png)

1. 보기 변경 **채널별**.

   ![](assets/image2014-9-17-18-3a36-3a59.png)

1. 사용 **X 축** 드롭다운을 사용하여 가로 축에 대한 지표를 선택합니다. 다음으로 시작 **프로그램 비용**.

   ![](assets/image2014-9-17-18-3a37-3a7.png)

1. Y축 드롭다운을 사용하여 세로 축에 대한 지표를 선택합니다. 자, 같이 가자 **(FT) 파이프라인 생성됨**.

   ![](assets/image2014-9-17-18-3a37-3a50.png)

   >[!NOTE]
   >
   >프로그램 분석기에서 선택할 수 있는 많은 지표는 FT(첫 번째 터치) 및 MT(다중 터치) 계산을 통해 사용할 수 있습니다. 다음을 이해하는 것이 중요합니다. [FT와 MT 속성 간의 차이](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md).

1. 사용 **Y축** 드롭다운 선택 **(MT) 파이프라인 생성됨**.

   ![](assets/image2014-9-17-18-3a39-3a5.png)

   이 멀티 터치 속성 보기에서 웨비나 채널은 생성된 파이프라인에 더 많은 영향을 주고 트레이드쇼 및 온라인 광고 채널보다 비용이 적게 듭니다.

   이제 차원을 두 개 더 추가하겠습니다!

1. 사용 **거품 크기** 드롭다운을 사용하여 다음과 같이 추가 측정을 선택합니다. **새 이름**.

   ![](assets/image2014-9-17-18-3a39-3a36.png)

1. 그래프가 어떻게 변하는지 확인하십시오.

   ![](assets/image2014-9-17-18-3a39-3a55.png)

   로 측정하면 웨비나 채널이 축소됩니다. **새 이름**. 많은 회원을 보유하고 있지만, Tradeshow 채널보다 새로운 잠재 고객을 생성하는 데 더 효과적이지 못하다는 결론을 내릴 수 있습니다.

1. 마지막으로 색상 드롭다운을 사용하여 네 번째 차원을 추가합니다. 선택하겠습니다. **(FT) 수익(원)**.

   ![](assets/image2014-9-17-18-3a41-3a7.png)

1. 그래프의 색상이 변하는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a41-3a19.png)

   색상으로 부터 가장 녹색 버블인 Tradeshow 채널이 첫 번째 터치 속성으로 측정했을 때 가장 큰 수익 승수에 영향을 미쳤음을 알 수 있습니다.

1. 이제 색상 지표를 로 변경하면 **(MT) 수익 원**, 이제 가장 친환경적인 온라인 광고 채널이 웨비나와 트레이드쇼 채널보다 시간에 따라 더 많은 매출에 영향을 미쳤음을 알 수 있습니다.

   ![](assets/image2014-9-17-18-3a41-3a40.png)

이 예제에서 Tradeshow 채널은 첫 번째 터치로 만든 파이프라인을 측정할 때 가장 비싸고(오른쪽에서 가장 멀리 있음), 가장 성공적입니다(Y축에서 가장 높음). 이제 멀티 터치 속성으로 측정된 각 채널의 파이프라인을 생각해 보겠습니다.

>[!TIP]
>
>이 단계의 예제는 생성된 파이프라인을 기반으로 효과를 측정합니다. Y축 드롭다운을 사용하여 새 이름, 멤버, 성공당 비용 등과 같은 채널 효과를 측정하는 다른 방법을 선택합니다.

>[!MORELIKETHIS]
>
>* [프로그램 분석기를 사용하여 프로그램 및 채널 세부 정보 살펴보기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/explore-program-and-channel-details-with-the-program-analyzer.md)
>* [프로그램 분석기와 프로그램 효율성 비교](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/compare-program-effectiveness-with-the-program-analyzer.md)

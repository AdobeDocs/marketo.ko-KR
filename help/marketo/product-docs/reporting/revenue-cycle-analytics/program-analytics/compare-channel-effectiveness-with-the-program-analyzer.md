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

1. **내 Marketo**&#x200B;에서 **분석**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-17-18-3a36-3a13.png)

1. **프로그램 분석기**&#x200B;를 선택하십시오.

   ![](assets/image2014-9-17-18-3a36-3a40.png)

1. 보기를 **채널별**(으)로 변경합니다.

   ![](assets/image2014-9-17-18-3a36-3a59.png)

1. **X축** 드롭다운을 사용하여 가로 축에 대한 지표를 선택합니다. **프로그램 비용**(으)로 시작하겠습니다.

   ![](assets/image2014-9-17-18-3a37-3a7.png)

1. Y축 드롭다운을 사용하여 세로 축에 대한 지표를 선택합니다. **(FT) 파이프라인 생성됨** 상태로 이동합니다.

   ![](assets/image2014-9-17-18-3a37-3a50.png)

   >[!NOTE]
   >
   >프로그램 분석기에서 선택할 수 있는 많은 지표는 FT(첫 번째 터치) 및 MT(다중 터치) 계산을 통해 사용할 수 있습니다. FT와 MT 속성의 [차이점](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md)을 이해하는 것이 중요합니다.

1. **Y축** 드롭다운을 사용하여 **(MT) 파이프라인을 생성**&#x200B;하세요.

   ![](assets/image2014-9-17-18-3a39-3a5.png)

   이 멀티 터치 속성 보기에서 웨비나 채널은 생성된 파이프라인에 더 많은 영향을 주고 트레이드쇼 및 온라인 Advertising 채널보다 비용이 적게 듭니다.

   이제 차원을 두 개 더 추가하겠습니다!

1. **버블 크기** 드롭다운을 사용하여 **새 이름**&#x200B;과 같은 추가 측정값을 선택하십시오.

   ![](assets/image2014-9-17-18-3a39-3a36.png)

1. 그래프가 어떻게 변하는지 확인하십시오.

   ![](assets/image2014-9-17-18-3a39-3a55.png)

   **새 이름**&#x200B;으로 측정한 결과 웨비나 채널이 축소되었습니다. 많은 회원을 보유하고 있지만, Tradeshow 채널보다 새로운 잠재 고객을 생성하는 데 더 효과적이지 못하다는 결론을 내릴 수 있습니다.

1. 마지막으로 색상 드롭다운을 사용하여 네 번째 차원을 추가합니다. **(FT) 매출원**&#x200B;을(를) 선택하겠습니다.

   ![](assets/image2014-9-17-18-3a41-3a7.png)

1. 그래프의 색상이 변하는 것을 확인하십시오.

   ![](assets/image2014-9-17-18-3a41-3a19.png)

   색상으로 부터 가장 녹색 버블인 Tradeshow 채널이 첫 번째 터치 속성으로 측정했을 때 가장 큰 수익 승수에 영향을 미쳤음을 알 수 있습니다.

1. 이제 색상 지표를 **(MT) 매출원**(으)로 변경하면 현재 가장 녹색인 온라인 Advertising 채널이 웨비나 및 트레이드쇼 채널보다 시간에 따라 더 많은 매출에 영향을 미쳤습니다.

   ![](assets/image2014-9-17-18-3a41-3a40.png)

이 예제에서 Tradeshow 채널은 첫 번째 터치로 만든 파이프라인을 측정할 때 가장 비싸고(오른쪽에서 가장 멀리 있음), 가장 성공적입니다(Y축에서 가장 높음). 이제 멀티 터치 속성으로 측정된 각 채널의 파이프라인을 생각해 보겠습니다.

>[!TIP]
>
>이 단계의 예제는 생성된 파이프라인을 기반으로 효과를 측정합니다. Y축 드롭다운을 사용하여 새 이름, 멤버, 성공당 비용 등과 같은 채널 효과를 측정하는 다른 방법을 선택합니다.

>[!MORELIKETHIS]
>
>* [프로그램 분석기를 사용하여 프로그램 및 채널 세부 정보 탐색](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/explore-program-and-channel-details-with-the-program-analyzer.md)
>* [프로그램 분석기와 프로그램 효율성 비교](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/compare-program-effectiveness-with-the-program-analyzer.md)

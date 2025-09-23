---
unique-page-id: 3571886
description: 성공 경로 분석기 사용 - Marketo 문서 - 제품 설명서
title: 성공 경로 분석기 사용
exl-id: f816b7ac-a158-46bd-9d00-09ef4cc8b381
feature: Reporting, Revenue Cycle Analytics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 3%

---

# 성공 경로 분석기 사용 {#using-the-success-path-analyzer}

성공 경로 분석기를 사용하여 [수익 주기 모델](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md)의 단계를 통해 사람들의 흐름(금액)과 속도(일 단위 속도)를 모두 반영하는 특정 세부 정보를 살펴보십시오.

>[!PREREQUISITES]
>
>[성공 경로 분석기 만들기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/create-a-success-path-analyzer.md)

1. **[!UICONTROL Analytics]**(으)로 이동하여 **성공 경로 분석기**&#x200B;를 선택하십시오.

   ![](assets/image2015-6-12-17-3a23-3a53.png)

   오른쪽의 차트는 왼쪽의 선택한 단추에 있는 데이터를 반영합니다. 기본적으로 **[!UICONTROL Balance]**&#x200B;입니다.

1. **[!UICONTROL In Flow]**&#x200B;을(를) 클릭하여 선택한 기간 동안 단계에 들어간 사람 수를 그래프로 표시합니다.

   ![](assets/image2015-6-12-17-3a30-3a52.png)

   * **[!UICONTROL Out Flow]**&#x200B;을(를) 클릭하여 스테이지를 종료한 사람 수를 그래프로 표시합니다.
   * **[!UICONTROL Conv %]**&#x200B;을(를) 클릭하여 이 단계에서 다음 단계로의 전환율을 그래프로 표시합니다.
   * **[!UICONTROL Avg Time]**&#x200B;을(를) 클릭하여 사람들이 다음 단계로 이동하기 전에 이 단계에서 보낸 시간을 확인합니다.

1. 데이터를 동일한 길이의 다른 시간대와 비교하려면 **[!UICONTROL Chart Actions]** > **[!UICONTROL Compare Period]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-6-12-17-3a39-3a15.png)

1. 비교 기간의 **[!UICONTROL From]** 날짜를 선택하십시오.

   ![](assets/image2015-6-12-17-3a43-3a49.png)

   **[!UICONTROL To]** 날짜는 원래 기간의 길이와 일치하도록 자동으로 설정됩니다.

1. **[!UICONTROL Compare]**&#x200B;를 클릭합니다.

   ![](assets/image2015-6-12-17-3a44-3a8.png)

1. 차트는 비교 기간 동안 녹색 단위의 겹치는 데이터로 업데이트됩니다.

   ![](assets/image2015-6-12-17-3a46-3a16.png)

1. 차트의 시간 배율을 변경하려면 **[!UICONTROL Graph by]** 단추 중 하나를 클릭합니다(매일(기본값), 매주 및 매월).

   ![](assets/image2015-6-12-17-3a46-3a55.png)

1. SLA(서비스 수준 계약)가 있는 단계의 경우 **[!UICONTROL Chart Actions]** > **[!UICONTROL Show SLA Due]**&#x200B;을(를) 클릭하여 지정된 기간 내에 SLA 대상을 놓친 모든 사용자를 표시합니다.

   ![](assets/image2015-6-12-17-3a49-3a23.png)

1. 차트는 주황색으로 각 노드에 예정된 SLA 수를 반영하도록 업데이트됩니다.

   ![](assets/image2015-6-12-17-3a50-3a16.png)

   주황색으로 표시된 사용자가 *이거나*&#x200B;되지 않을 수 있습니다. 여전히 SLA 단계에 있습니다.

1. **[!UICONTROL Chart Actions]** > **[!UICONTROL Show SLA Past Due]**&#x200B;을(를) 클릭하여 지정된 기간이 끝날 때 아직 SLA 단계에 있는 만료된 SLA 대상 사용자를 모두 표시합니다.

   ![](assets/image2015-6-12-17-3a51-3a39.png)

1. 차트는 주황색으로 각 노드에서 얼마나 많은 SLA가 지연되었는지 반영하도록 업데이트됩니다.

   ![](assets/image2015-6-12-17-3a52-3a17.png)

1. 특정 노드(날짜)에 있는 데이터 포인트의 특정 세부 사항을 읽으려면 버블 위로 마우스를 가져갑니다.

   ![](assets/image2015-6-12-17-3a52-3a49.png)

1. 차트를 인쇄하려면 **[!UICONTROL Chart Actions]** > **[!UICONTROL Print Chart]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-6-12-17-3a53-3a34.png)

분석기는 모델을 통한 움직임을 이해하는 데 도움이 됩니다. 고급 기능이 추가되면 마케팅 활동을 전략화하는 데 매우 중요한 역할을 하게 됩니다.

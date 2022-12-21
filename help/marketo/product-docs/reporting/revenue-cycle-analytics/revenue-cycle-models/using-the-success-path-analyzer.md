---
unique-page-id: 3571886
description: 성공 경로 분석기 사용 - Marketo 문서 - 제품 설명서
title: 성공 경로 분석기 사용
exl-id: f816b7ac-a158-46bd-9d00-09ef4cc8b381
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '373'
ht-degree: 0%

---

# 성공 경로 분석기 사용 {#using-the-success-path-analyzer}

성공 경로 분석기를 사용하여 단계에 따라 사람의 흐름(양)과 속도(일 기준 속도)를 모두 반영하는 특정 세부 정보를 탐색합니다 [매출 주기 모델](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md).

>[!PREREQUISITES]
>
>[성공 경로 분석기 만들기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/create-a-success-path-analyzer.md)

1. 이동 **Analytics** 그리고 **성공 경로 분석기**.

   ![](assets/image2015-6-12-17-3a23-3a53.png)

   오른쪽에 있는 차트는 왼쪽의 선택한 단추에 있는 데이터를 반영합니다. 기본적으로 잔액(Balance)입니다.

1. 클릭 **흐름 중** 선택한 기간 동안 스테이지에 입장한 사람 수를 그래프로 표시합니다.

   ![](assets/image2015-6-12-17-3a30-3a52.png)

   * 단계 흐름 을 클릭하여 단계를 종료한 사람을 그래프로 표시합니다.
   * 전환 % 를 클릭하여 전환율을 이 단계에서 다음 단계로 그래프로 표시합니다.
   * 평균 시간 을 클릭하여 다음 단계로 이동하기 전에 이 단계에서 사람들이 보낸 시간을 확인합니다.

1. 클릭 **차트 작업** > 기간 비교 를 통해 데이터를 동일한 길이의 다른 시간대와 비교합니다.

   ![](assets/image2015-6-12-17-3a39-3a15.png)

1. 을(를) 선택합니다 **From** 비교 기간의 일자.

   ![](assets/image2015-6-12-17-3a43-3a49.png)

   다음 **종료** 날짜가 원래 기간의 길이와 일치하도록 자동으로 설정됩니다.

1. 클릭 **비교**.

   ![](assets/image2015-6-12-17-3a44-3a8.png)

1. 차트가 비교 기간 동안 겹치는 데이터로 녹색으로 업데이트됩니다.

   ![](assets/image2015-6-12-17-3a46-3a16.png)

1. 차트의 시간 비율을 변경하려면 **그래프 기준** 버튼: 일별(기본값), 주별 및 월별

   ![](assets/image2015-6-12-17-3a46-3a55.png)

1. SLA(Service-Level Agreements)를 갖는 단계에 대해 **차트 작업** > **SLA 기한 표시** 지정된 기간 내에 SLA 타겟을 지키지 않은 모든 사용자를 표시합니다.

   ![](assets/image2015-6-12-17-3a49-3a23.png)

1. 차트가 업데이트되어 각 노드에서 몇 SLA가 이행되었는지 주황색으로 표시됩니다.

   ![](assets/image2015-6-12-17-3a50-3a16.png)

   오렌지색으로 표시된 사람들은 *또는* 여전히 SLA 단계에 있습니다.

1. 클릭 **차트 작업** > **기한 경과에 대한 SLA 표시** 지정된 기간이 끝날 때 여전히 SLA 단계에 있는 만료된 SLA 타겟을 가진 모든 사람을 표시합니다.

   ![](assets/image2015-6-12-17-3a51-3a39.png)

1. 주황색으로 표시된 각 노드에서 SLA가 지연된 횟수를 반영하도록 차트가 업데이트됩니다.

   ![](assets/image2015-6-12-17-3a52-3a17.png)

1. 특정 노드(날짜)에서 데이터 포인트의 특정 세부 정보를 읽으려면 버블 위로 마우스를 가져갑니다.

   ![](assets/image2015-6-12-17-3a52-3a49.png)

1. 차트를 인쇄하려면 **차트 작업** > **차트 인쇄**.

   ![](assets/image2015-6-12-17-3a53-3a34.png)

모델을 통한 이동을 이해하는 데 도움이 되는 분석기가 여기에 있습니다. 더 발전할수록 마케팅 활동을 전략적으로 활용하는 것이 매우 중요합니다.

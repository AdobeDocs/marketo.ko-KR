---
unique-page-id: 7504676
description: 기간 비용 이해 - Marketo 문서 - 제품 설명서
title: 기간 원가 이해
exl-id: 99f50eaf-28cf-4a8b-8ebd-89a4beef986a
feature: Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# 기간 원가 이해 {#understanding-period-costs}

## 개요 {#overview}

기간비는 특정 달에 프로그램에 지출하는 금액을 의미합니다.

>[!NOTE]
>
>**예**
>
>만약 여러분이 1000달러를 들여 7월에 출시되는 eBook의 일러스트레이터를 고용한다면, eBook 프로그램은 7월에 1000달러의 기간 비용이 들 것이다.
>
>Google Adwords에 매달 200달러를 지출하는 경우 Google Adwords 프로그램의 기간 비용은 $200입니다 **매달**.

>[!NOTE]
>
>[프로그램 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[프로그램 멤버십 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## 기간 비용 계산 방법 {#how-period-costs-are-calculated}

3월에 발생하는 웨비나와 같은 이벤트를 상상해 보십시오. 1월과 2월에 광고를 하여 새로운 사람을 미리 획득합니다. 사람들이 4월과 5월 달에 웨비나를 다운로드할 때 이벤트 후 새로운 연락처도 획득됩니다.

1. 3월로 인한 단일 기간 비용 발생...

   ![](assets/graph1.png)

   ...다음 달 전후에 추가된 연락처 *전용* 3월을 기약하다.

   ![](assets/graph2.png)

1. 기간 비용이 1월, 2월, 3월로 인한 경우...

   ![](assets/graph3.png)

   ...3월 이후 몇 달에만 추가된 연락처는 3월까지 카운트됩니다.

   ![](assets/graph4.png)

1. 기간 비용이 1월과 4월로 인한 경우...

   ![](assets/graph5.png)

   ...1월부터 3월까지 몇 달 동안 추가된 연락처는 1월에 계산됩니다. 4월과 5월 사이에 추가된 연락처는 4월이 됩니다.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >요약하면 - 정의된 기간 비용이 없는 월은 정의된 마지막 월로 &quot;이전&quot;으로 롤링됩니다. 이전 기간 비용이 없는 경우 월은 정의된 다음 기간으로 &quot;앞으로&quot; 롤링됩니다. 기간 비용이 다음에 대해 정의되지 않은 경우 _임의_ 개월 동안 프로그램에 대해 RCE로 보고할 수 없습니다.

   >[!MORELIKETHIS]
   >
   >* [프로그램에서 기간 원가 사용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.md)
   >* [기간 원가별로 프로그램 보고서 필터링](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)

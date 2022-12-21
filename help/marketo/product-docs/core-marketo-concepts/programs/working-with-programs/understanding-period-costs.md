---
unique-page-id: 7504676
description: 기간 비용 이해 - Marketo 문서 - 제품 설명서
title: 기간 원가 이해
exl-id: 99f50eaf-28cf-4a8b-8ebd-89a4beef986a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# 기간 원가 이해 {#understanding-period-costs}

## 개요 {#overview}

기간 비용은 프로그램에서 특정 월에 사용하는 돈을 의미합니다.

>[!NOTE]
>
>**예**
>
>7월에 시작되는 eBook의 삽화가를 위해 1000달러를 사용한다면, eBook 프로그램은 7월에 1000달러의 기간 비용이 들 것이다.
>
>Google Adwords에 월 200달러를 사용하는 경우 - Google Adwords 프로그램에 200달러의 기간 비용이 발생합니다 **매월**.

>[!NOTE]
>
>[프로그램 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[프로그램 멤버십 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## 기간 원가를 계산하는 방법 {#how-period-costs-are-calculated}

웨비나 같은 3월에 일어나는 사건을 상상해 보세요. 새로운 사람들은 1월과 2월에 광고로 미리 취득된다. 행사 후 4월과 5월에 웨비나를 다운로드할 때도 새 연락처를 획득합니다.

1. 3월...

   ![](assets/graph1.png)

   ...다음 시기 이전 및 이후에 추가된 연락처 *전용* 3월을 세다.

   ![](assets/graph2.png)

1. 기간 원가가 1월, 2월, 3월로 인한 경우..

   ![](assets/graph3.png)

   ...3월 이후 몇 달에만 추가된 연락처는 3월에 계산됩니다.

   ![](assets/graph4.png)

1. 기간 비용이 1월과 4월에 속하는 경우

   ![](assets/graph5.png)

   ...1월부터 3월까지 달에 추가된 연락처는 1월까지 계산됩니다. 4월과 5월에 추가된 연락처는 4월에 계산됩니다.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >요약 - 정의된 기간 비용이 없는 달은 정의된 마지막 비용으로 &quot;뒤로&quot; 롤업됩니다. 이전 기간 비용이 없는 경우 달은 정의된 다음 기간 원가로 &quot;앞으로&quot;됩니다. 기간 원가가 정의되지 않은 경우 _임의_ 몇 달 동안 프로그램에 RCE에서 보고를 사용할 수 없습니다.

   >[!MORELIKETHIS]
   >
   >* [프로그램에서 기간 원가 사용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.md)
   >* [기간 원가로 프로그램 보고서 필터링](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)


---
unique-page-id: 7504676
description: 기간 비용 이해 - 마케팅 문서 - 제품 문서
title: 기간 비용 이해
translation-type: tm+mt
source-git-commit: 07f713ece9832b7696451001f61c6a3b45b4a94a
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---


# 기간 비용 이해 {#understanding-period-costs}

## 개요 {#overview}

기간 비용은 프로그램에서 특정 월에 지출한 금액을 말합니다.

>[!NOTE]
>
>**예**
>
>7월에 시작되는 eBook을 위해 일러스트레이터를 고용하기 위해 1000달러를 지출하는 경우, eBook 프로그램은 7월에 1000달러의 기간 비용이 들 것이다.
>
>Google Adwords에 월 $200를 지출하는 경우 - Google Adwords 프로그램은 월&#x200B;**에 $200의**&#x200B;을(를) 사용할 수 있습니다.

>[!NOTE]
>
>[프로그램 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[프로그램 회원 이해](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## 기간 비용을 계산하는 방법 {#how-period-costs-are-calculated}

웨비나와 같은 이벤트가 3월에 발생한다고 가정해 보십시오. 신인은 1월과 2월의 광고로부터 사전에 취득된다. 또한 사람들이 4월과 5월에 웨비나를 다운로드하는 행사 후에 새로운 연락처가 획득됩니다.

1. 3월...에 대해 단일 기간 비용이 발생합니다.

   ![](assets/graph1.png)

   ...이전 및 후 달에 추가된 연락처는 *만 3월에 계산됩니다.*

   ![](assets/graph2.png)

1. 기간 비용은 1월, 2월, 3월에 귀속됩니다.

   ![](assets/graph3.png)

   ...3월 이후 몇 달에만 추가된 연락처는 3월에 계산됩니다.

   ![](assets/graph4.png)

1. 기간 비용은 1월과 4월에 귀속되며..

   ![](assets/graph5.png)

   ...1월부터 3월까지 달에 추가된 연락처는 1월에 계산됩니다. 4월과 5월에 추가된 연락처는 4월에 계산됩니다.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >요약 - 기간 비용이 정의되지 않은 달은 정의된 마지막 달로 &quot;뒤로&quot; 롤업됩니다. 이전 기간 비용이 없는 경우 달은 정의된 다음 기간으로 &quot;앞으로&quot;됩니다. _임의의_&#x200B;개월 동안 기간 비용이 정의되지 않은 경우 프로그램에 대해 RCE 보고를 사용할 수 없습니다.

   >[!MORELIKETHIS]
   >
   >* [프로그램에서 기간 비용 사용](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.md)
   >* [기간 원가로 프로그램 보고서 필터링](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)


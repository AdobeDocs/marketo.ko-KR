---
unique-page-id: 7504676
description: 기간 비용 이해 - 마케팅 문서 - 제품 설명서
title: 기간 비용 이해
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '278'
ht-degree: 0%

---


# 기간 비용 이해 {#understanding-period-costs}

## 개요 {#overview}

기간 비용은 프로그램에서 특정 월에 쓴 비용을 의미합니다.

>[!NOTE]
>
>**예**
>
>7월에 시작되는 eBook용 일러스트레이터를 사용하기 위해 1000달러를 지출하는 경우, eBook 프로그램은 7월에 1000달러의 기간 비용이 들 것입니다.
>
>만약 여러분이 구글 애드워스에 매달 200달러를 쓴다면, 구글 애드워즈 프로그램은 **매달** 200달러의 기간 비용이 들 것이다.

>[!NOTE]
>
>**딥 다이브**
>
>[프로그램 이해](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[프로그램 회원 이해](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## 기간 비용을 계산하는 방법 {#how-period-costs-are-calculated}

웨비나와 같은 이벤트가 3월에 발생한다고 상상해 보십시오. 신인은 1월과 2월에 광고로부터 사전에 취득된다. 또 4월과 5월 사이에 사람들이 웨비나를 다운로드하는 행사를 연 후에 새로운 연락처가 획득됩니다.

1. 3월...

   ![](assets/graph1.png)

   ...계약 전후 월에 추가된 연락처는 3월에만 ** 계산됩니다.

   ![](assets/graph2.png)

1. 1월, 2월, 3월에 발생한 기간 비용은

   ![](assets/graph3.png)

   ...3월 이후 몇 달에만 추가된 연락처는 3월로 카운트됩니다.

   ![](assets/graph4.png)

1. 기간 비용은 1월과 4월..

   ![](assets/graph5.png)

   ...1월부터 3월까지 달에 추가된 연락처는 1월로 카운트됩니다. 4월과 5월에 추가된 연락처는 4월로 계산됩니다.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >요약하면 - 정의된 기간 비용이 없는 달은 정의된 마지막 비용으로 &quot;뒤로&quot; 롤업됩니다. 이전 기간 비용이 없는 경우 달은 정의된 다음 기간으로 &quot;앞으로&quot; 롤포워드됩니다. 기간 비용이 *어느* 달 동안 정의되지 않은 경우 프로그램에 대해 RCE 보고를 사용할 수 없습니다.

   >[!NOTE]
   >
   >**관련 문서**
   >
   >    
   >    
   >    * [프로그램에서 기간 비용 사용](using-period-costs-in-a-program.md)
   >    * [기간 원가로 프로그램 보고서 필터링](../../../../product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)



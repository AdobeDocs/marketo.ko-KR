---
unique-page-id: 7514149
description: 속성 예 3 - Marketo 문서 - 제품 설명서
title: 속성 예 3
exl-id: d8ca63a2-58de-4cde-b915-ff7f2e6468d9
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '175'
ht-degree: 0%

---

# 속성 예 3 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Steve 다운로드 (콘텐츠) - 성공
* 4월 22일 | 영업 기회가 $3,000에 생성됨(Steve와 Jason 모두 역할 보유)
* 4월 25일 | Jason이 참석함(웨비나) - 성공
* 4월 30일 | 영업 기회는 비공개

| 속성 지표 | (컨텐츠) | (웨비나) |
|---|---|---|
| (MT) 옵션 생성됨 | `<pre>1</pre>` | `<pre>0</pre>` |
| (MT) 파이프라인 생성됨 | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (MT) Opty 원 | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) 수익 원 | `<pre>$1,500</pre>` | `<pre>$1,500</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>기여도 분석 규칙 #3 사항을 기억하십시오. Jason은 파티가 만들어진 후 프로그램 성공을 거두었습니다. 따라서 웨비나는 영업 기회 창출에 대한 크레딧을 받을 수 없습니다. Opty에 대한 크레딧만.
>
>따라서 (Content)는 Opty 생성 및 파이프라인에 대해서는 100%의 크레딧이 있지만, Opty 원화에 대해서는 50%의 크레딧만 제공합니다.

>[!NOTE]
>
>**속성 규칙**
>
>1. 크레딧이 균등하게 분할됩니다.
>1. 획득한 것보다 더 많은 크레딧을 줄 수는 없습니다
>1. 과거에 일어난 일에 대해서는 칭찬할 수 없다

모든 예를 시도해 보십시오. 그러면 기여도 분석 전문가가 됩니다!

>[!MORELIKETHIS]
>
>* [속성 예 1](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [속성 예 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)

---
unique-page-id: 7514146
description: 속성 예 2 - Marketo 문서 - 제품 설명서
title: 속성 예 2
exl-id: 8f00abb5-85f8-4f05-874e-57aa6442548c
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# 속성 예 2 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | 청구서 인수 주체 (Tradeshow)
* 4월 15일 | Joan은 (웨비나)에 의해 획득됩니다.
* 4월 22일 | (영업 기회 1) $6,000에 생성됨
* 4월 24일 | (영업 기회 2) $10,000에 생성됨
* 4월 25일 | Bill과 Joan은 **둘 다** 옵션에 역할과 연결되어 있습니다.
* 4월 29일 | (영업 기회 1)이 마감되었습니다.

| 프로그램 이름 | (박람회) | (웨비나) |
|---|---|---|
| (FT) 옵션 생성됨 | `<pre>1</pre>` | `<pre>1</pre>` |
| (FT) 파이프라인 생성됨 | `<pre>$8,000</pre>` | `<pre>$8,000</pre>` |
| (FT) Opty 원 | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (FT) 수익(원) | `<pre>$3,000</pre>` | `<pre>$3,000</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>Bill과 Joan은 모두 **BOTH** 기회에 대한 역할과 연결되어 있으므로(규칙에 따라) 시스템에서 크레딧을 균등하게 분배합니다.
>
>각 프로그램($8,000)에 대해 생성된 파이프라인은 크레딧으로 제공할 수 있는 총($16,000)의 절반입니다.

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
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)

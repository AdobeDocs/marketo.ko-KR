---
unique-page-id: 7514146
description: 속성 예 2 - Marketo 문서 - 제품 설명서
title: 속성 예 2
exl-id: 8f00abb5-85f8-4f05-874e-57aa6442548c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '162'
ht-degree: 0%

---

# 속성 예 2 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Bill 은 (Tradeshow)에 의해 인수됩니다.
* 4월 15일 | Joan이 (웨비나)에 의해 인수됩니다.
* 4월 22일 | (Opportunity 1) $6,000에 대해 생성
* 4월 24일 | (Opportunity 2) $10,000에 대해 생성
* 4월 25일 | Bill과 Joan은 **둘 다** 옵티스
* 4월 29일 | (Opportunity 1) Closed-Won

| 프로그램 이름 | (트레이드쇼) | (웨비나) |
|---|---|---|
| (FT) 작성된 속성 | `<pre>1</pre>` | `<pre>1</pre>` |
| (FT) 생성된 파이프라인 | `<pre>$8,000</pre>` | `<pre>$8,000</pre>` |
| (FT) 옵티원 | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (FT) 수입 원 | `<pre>$3,000</pre>` | `<pre>$3,000</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>빌과 조안 둘 다 **둘 다** 기회에서는 시스템(규칙에 따라)이 크레딧을 균등하게 분할합니다.
>
>각 프로그램($8,000)에 대해 생성된 파이프라인은 크레딧으로 제공할 수 있는 총 ($16,000)의 절반입니다.

>[!NOTE]
>
>**속성 규칙**
>
>1. 크레딧은 균등하게 분할됩니다
>1. 당신이 받은 것보다 더 많은 공을 줄 수 없습니다
>1. 과거에 일어났던 일에 대해 너는 신용을 줄 수 없다


모든 예제를 사용해 보십시오. 그러면 속성 전문가가 됩니다!

>[!MORELIKETHIS]
>
>* [속성 예 1](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)


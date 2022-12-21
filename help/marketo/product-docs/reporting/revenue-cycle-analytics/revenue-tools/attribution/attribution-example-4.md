---
unique-page-id: 7514151
description: 속성 예 4 - Marketo 문서 - 제품 설명서
title: 속성 예 4
exl-id: 98cd7401-3bc7-40a1-b88d-7174a3027d4e
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# 속성 예 4 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Michelle 다운로드 e-Book(컨텐츠) - 성공
* 4월 15일 | John이 참석함(웨비나) - 성공
* 4월 22일 | (Opportunity 1) $3,000에 대해 생성
* 4월 24일 | (Opportunity 2) $5,000에 대해 생성
* 4월 25일 | John과 Michelle은 **둘 다** 옵티스
* 4월 29일 | [Opty 1] 닫힘

| 프로그램 이름 | (콘텐츠) | (웨비나) |
|---|---|---|
|  | (정당 1) | (정당 2) | (정당 1) | (정당 2) |
| (MT) 작성된 파티 | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) 파이프라인 생성됨 | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` |
| (MT) 옵티원 | `<pre>0.5</pre>` | `<pre>0</pre>` | `<pre>0.5</pre>` | `<pre>0</pre>` |
| (MT) 매출 원 | `<pre>$1,500</pre>` | `<pre>$0</pre>` | `<pre>$1,500</pre>` | `<pre>$0</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>여러 기회가 있고 프로그램 성공을 가진 여러 사람이 있는 경우 사람과 프로그램 간에 크레딧을 나눠야 합니다. 그러나 기회 1과 2에 대한 크레딧은 결합되지 않습니다. 각각 개별적인 신용 평가입니다.
>
>많은 사람들이 관련되어 있을 때, Marketo은 자동으로 크레딧을 제공할 기회의 차이를 계산합니다.

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
>* [속성 예 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)


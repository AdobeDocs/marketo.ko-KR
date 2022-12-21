---
unique-page-id: 7514149
description: 속성 예 3 - Marketo 문서 - 제품 설명서
title: 속성 예 3
exl-id: d8ca63a2-58de-4cde-b915-ff7f2e6468d9
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '161'
ht-degree: 0%

---

# 속성 예 3 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Steve 다운로드(컨텐츠) - 성공
* 4월 22일 | Opportunity 가 3,000달러(Steve와 Jason의 역할 모두 포함)에 대해 작성됩니다.
* 4월 25일 | Jason이 참가함(웨비나) - 성공
* 4월 30일 | Opportunity 가 Closed-Won

| 속성 지표 | (콘텐츠) | (웨비나) |
|---|---|---|
| (MT) 작성된 파티 | `<pre>1</pre>` | `<pre>0</pre>` |
| (MT) 파이프라인 생성됨 | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (MT) 옵티원 | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) 매출 원 | `<pre>$1,500</pre>` | `<pre>$1,500</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>속성 규칙 #3. 제이슨은 AFTER the opity가 만들어진 후 프로그램 성공을 거두었다. 따라서 웨비나는 기회 생성에 대한 크레딧을 받을 수 없습니다. 오직 당원의 신용만.
>
>따라서 (컨텐츠)는 속성 생성 및 파이프라인에 대한 크레딧의 100%를 가지지만, 광학 원에 대해서는 50%만 크레딧을 받습니다.

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
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)


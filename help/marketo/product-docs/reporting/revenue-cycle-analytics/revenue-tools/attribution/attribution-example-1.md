---
unique-page-id: 7514126
description: 속성 예 1 - Marketo 문서 - 제품 설명서
title: 속성 예 1
exl-id: 851cbad3-0f6d-4ea0-857f-8b15337c7540
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---

# 속성 예 1 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Fred는 (Tradeshow)에 의해 인수됩니다.
* 4월 15일 | Margo에 참가(웨비나) - 성공
* 4월 22일 | Fred는 영업 기회에 (역할)을 연관시킵니다
* 4월 22일 | 3,000달러에 대한 영업 기회 창출

| 프로그램 이름 | (트레이드쇼) | (웨비나) |
|---|---|---|
| (FT) 작성된 속성 | `<pre>1</pre>` | `<pre>0</pre>` |
| (FT) 생성된 파이프라인 | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (FT) 옵티원 | `<pre>0</pre>` | `<pre>0</pre>` |
| (FT) 수입 원 | `<pre>0</pre>` | `<pre>0</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>먼저 일부 유형은 COUNTS이고 다른 유형은 CURRENCY임을 이해하는 것입니다. Created는 정수인 수입니다. 파이프라인은 통화입니다. Marketo에서 통화는 관리자 로케일 설정을 따릅니다.
>
>Tradeshow가 모든 크레딧을 받은 이유는 Margo가 Opportunity에서 역할과 연관되지 않았기 때문입니다. 역할 없음, 크레딧이 없음.

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
>* [속성 예 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)


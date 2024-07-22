---
unique-page-id: 7514126
description: 속성 예 1 - Marketo 문서 - 제품 설명서
title: 속성 예 1
exl-id: 851cbad3-0f6d-4ea0-857f-8b15337c7540
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# 속성 예 1 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Fred는 (Tradeshow)에 의해 획득됩니다.
* 4월 15일 | Margo 참석(웨비나) - 성공
* 4월 22일 | Fred가 영업 기회에 연관됨(역할)
* 4월 22일 | 영업 기회가 3,000달러에 생성됨

| 프로그램 이름 | (박람회) | (웨비나) |
|---|---|---|
| (FT) 옵션 생성됨 | `<pre>1</pre>` | `<pre>0</pre>` |
| (FT) 파이프라인 생성됨 | `<pre>$3,000</pre>` | `<pre>$0</pre>` |
| (FT) Opty 원 | `<pre>0</pre>` | `<pre>0</pre>` |
| (FT) 수익(원) | `<pre>0</pre>` | `<pre>0</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>첫 번째는 일부 유형은 COUNTS이고 다른 유형은 CURRENCY임을 이해하는 것입니다. Opty Created 는 정수 입니다. 파이프라인이 통화입니다. Marketo에서 통화는 관리자 로케일 설정을 따릅니다.
>
>Tradeshow가 모든 크레딧을 받은 이유는 Margo가 Opportunity에서 역할과 관련이 없기 때문입니다. 역할, 크레딧 없음.

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
>* [속성 예 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)
>* [속성 예 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)

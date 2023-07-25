---
unique-page-id: 7514151
description: 속성 예 4 - Marketo 문서 - 제품 설명서
title: 속성 예 4
exl-id: 98cd7401-3bc7-40a1-b88d-7174a3027d4e
feature: Reporting, Revenue Cycle Analytics
source-git-commit: d20a9bb584f69282eefae3704ce4be2179b29d0b
workflow-type: tm+mt
source-wordcount: '181'
ht-degree: 0%

---

# 속성 예 4 {#attribution-example}

다음 시나리오를 읽고 그리드에 있어야 하는 숫자를 결정하십시오.

* 4월 11일 | Michelle 다운로드 e-Book (콘텐츠) - 성공
* 4월 15일 | John이 참석함(웨비나) - 성공
* 4월 22일 | (Opportunity 1) 이 $3,000에 대해 생성됨
* 4월 24일 | (Opportunity 2) 가 $5,000에 대해 생성됨
* 4월 25일 | John과 Michelle은 **모두** 옵티스
* 4월 29일 | [옵션 1] 은(는) 비공개 원입니다.

| 프로그램 이름 | (콘텐츠) | (웨비나) |
|---|---|---|
|   | (옵션 1) | (옵션 2) | (옵션 1) | (옵션 2) |
| (MT) 옵션 생성됨 | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` | `<pre>0.5</pre>` |
| (MT) 파이프라인 생성됨 | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` | `<pre>$1,500</pre>` | `<pre>$2,500</pre>` |
| (MT) Opty 원 | `<pre>0.5</pre>` | `<pre>0</pre>` | `<pre>0.5</pre>` | `<pre>0</pre>` |
| (MT) 수익 원 | `<pre>$1,500</pre>` | `<pre>$0</pre>` | `<pre>$1,500</pre>` | `<pre>$0</pre>` |

**답변 표시**

>[!NOTE]
>
>**설명**
>
>여러 기회와 프로그램 성공을 거둔 사람이 여러 명일 경우 해당 사람과 프로그램 간에 크레딧을 분할해야 합니다. 단, 기회 1과 2에 대한 크레딧은 결합되지 않습니다. 각각은 고유한 신용 평가입니다.
>
>많은 사람들이 참여하면 Marketo은 크레딧을 제공할 기회의 일부를 자동으로 계산합니다.

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
>* [속성 예 3](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-3.md)

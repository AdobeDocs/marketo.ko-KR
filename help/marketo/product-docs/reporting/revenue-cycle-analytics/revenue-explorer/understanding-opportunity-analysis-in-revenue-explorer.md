---
unique-page-id: 2951884
description: Revenue Explorer의 Opportunity Analysis 이해 - Marketo 문서 - 제품 설명서
title: Revenue Explorer의 Opportunity Analysis 이해
exl-id: 2ef45d3e-7640-4c47-86ae-d7ae45ed1dd4
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '899'
ht-degree: 4%

---

# Revenue Explorer의 Opportunity Analysis 이해 {#understanding-opportunity-analysis-in-revenue-explorer}

Revenue Explorer의 Opportunity Analysis를 사용하면 보다 심층적인 수준에서 기회를 검사할 수 있습니다. 리드 소스, 업계 또는 지역과 같은 리드/회사 속성을 기반으로 데이터를 분류합니다. 이름, 단계 또는 확률에 따라 기회 생성 및 닫기 분석 파이프라인에 대한 마케팅 기여도를 확인하십시오.

## 분석 예 {#example-analysis}

다음은 Opportunity Analysis 영역에서 생성할 수 있는 몇 가지 보고서입니다.

1. 생성된 기회에 대한 마케팅 영향

   귀사 회사의 파이프라인의 몇 퍼센트가 마케팅 프로그램에 영향을 받았습니까? 이 보고서가 답을 준다. 다음 원형 차트는 마케팅 프로그램에서 획득한 모든 기회의 수와 기회 금액의 백분율을 보여줍니다.

   ![](assets/image2015-7-21-16-3a21-3a4.png)

1. 마케팅이 영업 기회의 종전과 원점에 미치는 영향.

   이 보고서는 수 및 금액별로 마케팅의 획득 및 영향을 받은 정도를 보여줍니다.

   ![](assets/image2015-7-21-16-3a41-3a55.png)

1. 가망 고객 출처로 마감된 기회

   이 보고서는 리드 소스에 의해 종료되는 모든 기회를 분류하고 작동 중인 소스와 그렇지 않은 소스에 대한 명확한 개요를 제공합니다.

   ![](assets/image2015-7-21-10-3a34-3a50.png)

1. 소스별 종료 시간

   이 보고서는 영업 기회를 마감하기 위한 평균 일 수와 리드 소스의 관계를 보여줍니다.

   ![](assets/image2015-7-21-10-3a35-3a3.png)

1. 영업 기회 및 단계 열기

   이 보고서는 각 매출 주기 단계에서 열려 있는 기회를 보여줍니다.

   ![](assets/image2015-7-21-10-3a35-3a32.png)

1. 업종별 연도별 기회 수

   이 보고서는 다음과 같은 질문에 답합니다. &quot;우리는 매년 특정 산업에서 점점 더 혹은 더 적은 기회를 얻고 있는가?&quot;

   ![](assets/image2015-7-21-10-3a35-3a45.png)

## 기회 분석 Dimension 및 측정 {#opportunity-analysis-dimensions-and-measures}

Opportunity Analysis를 통해 모든 Lead, Company 및 Opportunity 관련 차원 및 Opportunity 관련 Measurement에 액세스할 수 있습니다. 이 기회 분석 차원 및 측정값을 사용하여 보고서의 특정 질문에 답변합니다.

1. 회사 속성

   | 치수 | 설명 |
   |---|---|
   | 연간 수익 | 회사의 연간 매출 |
   | 시 | 회사가 있는 도시 |
   | 국가 | 회사가 있는 주 |
   | 산업 | 그 회사가 속한 산업 |
   | 회사명 | 회사 이름 |
   | 직원 수 | 회사의 직원 수 |
   | 우편 번호 | 회사의 우편 번호 |
   | SIC 코드 | 회사의 SIC 코드 |
   | 주 | 회사가 있는 주 |

1. 리드 속성

   | 치수 | 설명 |
   |---|---|
   | 차단 목록에 추가된 | 납은 차단 목록에 추가된입니다 |
   | Converted to Opportunity | 리드가 기회로 변환됩니다 |
   | 이메일이 잘못되었습니다. | 리드에 유효한 이메일 주소가 있는지 여부 |
   | 마케팅 중단 | 리드가 마케팅 이메일에서 일시 중단됩니까 |
   | 이메일 주소 | 리드의 이메일 주소 |
   | 직위 | 리드의 직함 |
   | 전체 이름 | 리드의 전체 이름 |
   | 원본 소스 유형 | 리드의 원래 소스 유형 |
   | 소스 유형 등록 | 리드의 등록된 소스 유형 |
   | 리드 소유자 이메일 주소 | 리드 소유자의 이메일 주소 |
   | 리드 소유자 직책 | 리드 소유자의 직함 |
   | 리드 소유자 이름 | 리드 소유자 이름 |
   | 잠재 고객 소스 | 리드 소스 |
   | 잠재 고객 상태 | 리드 상태 |

1. 리드 생성 일정

   | 치수 | 설명 |
   |---|---|
   | Lead Created Year | 리드가 만들어지는 연도 |
   | 리드 생성 분기 | 리드가 만들어지는 분기입니다 |
   | 만든 리드 월 | 리드가 생성된 월입니다 |
   | 만든 리드 주 | 리드가 만들어지는 주 |
   | 리드 생성 날짜 | 리드가 만들어지는 날짜입니다 |

1. 기회 속성

   | 치수 | 설명 |
   |---|---|
   | 영업 기회 종료 | 영업 기회가 종료되었습니까 |
   | 기회 예측 범주 | 기회 예측 범주 |
   | 영업 기회 이름 | 영업 기회 이름 |
   | 영업 기회 단계 | 기회 단계 |
   | 영업 기회 유형 | 영업 기회 유형 |
   | 기회 원점 | 이 기회가 종료되어 승리합니까 |
   | 마케팅 영향 기회 | 이 플래그는 모든 마케팅 프로그램에서 리드/연락처를 획득했는지 아니면 획득되었는지 여부를 나타냅니다. 기간 원가가 정의된 프로그램만 고려합니다. |

1. 영업 기회 마감 일정

   | 치수 | 설명 |
   |---|---|
   | 영업 기회 마감 연도 | 기회가 종료되는 연도 |
   | 영업 기회 마감 분기 | 기회가 종료되는 분기입니다 |
   | 영업 기회 마감 월 | 기회가 종료되는 달 |
   | 영업 기회 마감 주 | 기회가 종료되는 주 |
   | 영업 기회 마감 날짜 | 기회가 종료되는 날짜 |

1. 영업 기회 생성 일정

   | 치수 | 설명 |
   |---|---|
   | Opportunity Created Year | 기회가 생성된 연도 |
   | 영업 기회 생성 분기 | 기회가 생성된 분기입니다 |
   | Opportunity Created Month | 기회가 생성된 월입니다 |
   | Opportunity Created Week | 기회가 생성된 주 |
   | 기회 생성 날짜 | 기회가 생성된 날짜입니다 |

1. 측정

   | 측정 | 설명 |
   |---|---|
   | 영업 기회 종료에 필요한 평균 일 수 | 영업 기회를 마감할 평균 일 수 |
   | Avg Days to Close Opportunity(손실) | 영업 기회 손실까지의 평균 일 수 |
   | Avg Days to Close Opportunity (Won) | 원점 기회의 평균 일 수 |
   | 모든 기회 수 | 모든 기회의 총 수 |
   | 영업 기회 수(마감) | 마감된 총 기회(원 또는 손실) 수 |
   | 기회 수(손실) | 손실된 총 기회 수 |
   | 기회 수(개설) | 아직 개설된 총 기회 수 |
   | 기회 수(원) | 획득된 총 기회 수 |
   | 기회 금액 | 총 기회 금액. 두 개 이상의 리드가 Opportunity 와 연결된 경우 할당 금액은 Lead 점수에 따라 결정됩니다. |
   | 기회 금액(손실) | 손실된 기회에 대한 총 금액입니다. 두 개 이상의 리드가 Opportunity 와 연결된 경우 할당 금액은 Lead 점수에 따라 결정됩니다. |
   | 기회 금액(개설) | 개설 기회에 대한 총 금액. 두 개 이상의 리드가 Opportunity 와 연결된 경우 할당 금액은 Lead 점수에 따라 결정됩니다. |
   | 기회 금액(원) | 원화의 기회 총액. 두 개 이상의 리드가 Opportunity 와 연결된 경우 할당 금액은 Lead 점수에 따라 결정됩니다. |

>[!MORELIKETHIS]
>
>* [매출 탐색기 보고서 만들기](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/create-a-revenue-explorer-report.md)
>* [매출 탐색기 보고서에 필드 추가](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/adding-fields-to-a-revenue-explorer-report.md)
>* [매출 탐색기 보고서 구독](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-explorer/subscribe-to-a-revenue-explorer-report.md)


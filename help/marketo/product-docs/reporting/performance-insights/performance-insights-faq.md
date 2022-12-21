---
unique-page-id: 12979858
description: 성능 통찰력 FAQ - Marketo 문서 - 제품 설명서
title: 성능 통찰력 FAQ
exl-id: cee791c3-1845-4fca-b803-c0dc1c644549
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '1357'
ht-degree: 0%

---

# 성능 통찰력 FAQ {#performance-insights-faq}

## 참여 탭에서 &quot;성공&quot;에 대한 정의란 무엇입니까? {#what-is-the-definition-of-success-in-the-engagement-tab}

성공은 Marketo에서 의미 있는 상호 작용을 측정하는 것입니다. 프로그램의 목적은 개인 또는 잠재 고객과 의미 있는 상호 작용을 만드는 것이다. 사용자가 해당 목표를 달성하는 상태에 도달하면 성공이 표시됩니다. 웨비나에 참석하거나, 이메일에서 링크를 클릭하거나, 웹 양식을 채울 수 있습니다. 성공은 프로그램 채널에 따라 다릅니다.

>[!NOTE]
>
>웨비나 프로그램에는 다음과 같은 여러 상태가 있을 수 있습니다. 초대, 등록 및 참석 사람들이 실제로 웨비나를 보지 않기 때문에 초대 또는 등록은 의미 있는 상호 작용이 아닙니다. 이 경우에는 참석이 성공으로 간주된다.

## MPI가 CRM에서 작동합니까? {#will-mpi-work-with-any-crm}

예. 기술적으로, MPI는 데이터 동기화를 위해 CRM과 직접 상호 작용하지 않습니다. MPI는 Marketo Analytics Data Warehouse에 저장된 데이터를 사용합니다. CRM 동기화는 리드 관리 애플리케이션에서 발생하므로 리드 관리 애플리케이션과 통합된 Marketo 지원 CRM에 데이터가 올바르게 표시됩니다. 그러나 CRM 기회 필드를 Marketo 기회 필드에 올바르게 매핑해야 합니다.

## 다른 Marketing Analytics 제품(ARB, RCE, RCA, 프로그램 분석)이 없습니다. MPI가 작동합니까? {#i-do-not-have-any-other-marketing-analytics-products-arb-rce-rca-program-analysis-will-mpi-work-for-me}

MPI는 리드 관리 응용 프로그램에 대한 독립적인 추가 기능입니다. 다른 분석 제품을 사용할 필요가 없습니다.

## RCA는 프로그램 성능 데이터도 보여줍니다. MPI와 RCA에 표시된 데이터 간에 차이가 있습니까? {#rca-shows-me-program-performance-data-as-well-is-there-a-difference-between-the-data-shown-in-mpi-and-rca}

아니요. MPI는 RCA와 동일한 데이터 웨어하우스에서 데이터를 제공합니다. 따라서 두 데이터 간의 데이터 차이점은 표시되지 않습니다. RCA를 사용하여 신속하게 고유한 보고서를 만들 수 있습니다. MPI를 통해 이해하기 쉬운 시각적 대시보드에 액세스할 수 있습니다.

## 일부 프로그램(예: 작동)이 MPI에 표시되는 것을 원하지 않습니다. 특정 프로그램의 가시성을 제어하려면 어떻게 합니까? {#i-don-t-want-some-of-my-programs-e-g-operational-to-show-up-in-mpi-how-do-i-control-the-visibility-of-specific-programs}

프로그램의 Analytics 동작을 Operational로 설정하여 프로그램의 가시성을 제어할 수 있습니다. 이렇게 하면 프로그램이 분석 계산에서 제외됩니다.

>[!NOTE]
>
>분석 동작 설정에 대해 자세히 알아보기 [여기](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/edit-analytics-behavior-settings.md).

## 새로운 제품 시작을 위한 멀티채널 캠페인을 실행하고 있습니다. 한 위치에서 모든 다른 채널에서 이 캠페인의 성과를 보려면 어떻게 해야 합니까? {#i-am-running-a-multi-channel-campaign-for-a-new-product-launch-how-can-i-view-the-performance-for-this-campaign-across-all-the-different-channels-in-one-place}

캠페인의 일부 프로그램의 경우 프로그램 태그를 사용하는 것이 좋습니다. 프로그램 태그는 자동으로 MPI에 동기화되며, 모든 MPI 대시보드에서 필터링하여 다중 채널 캠페인 성능을 볼 수 있습니다.

## RCA가 없는 경우 속성 설정에 액세스할 수 있습니까? {#will-i-have-access-to-attribution-settings-if-i-do-not-have-rca}

RCA가 있는지 여부에 관계없이 MPI가 있는 경우 속성 설정에 액세스할 수 있습니다.

## 로그인하면 내 속성 설정이 잘못되었음을 알리는 MPI가 표시됩니다. 왜 그래? {#i-get-an-alert-in-mpi-when-i-log-in-telling-me-that-my-attribution-settings-are-incorrect-what-s-wrong}

MPI는 모든 기회가 분석에 포함되는지 여부를 계산합니다. 그렇지 않으면 더 많은 기회를 포함하도록 속성 설정(명시적, 암시적, 하이브리드)을 변경하는 것을 고려하라는 메시지가 표시됩니다.

프로그램에서 프로그램 비용이 누락되어 기회가 누락될 수도 있습니다. 프로그램의 Analytics 동작을 검토하십시오. 다음 항목을 지정할 수 있습니다.

1. 기본값 - 기본 동작은 0 달러가 지정된 기간 비용이 하나 이상인 경우에만 MPI에 프로그램이 포함됩니다.

1. 포함 - 이 옵션은 기간 비용을 포함했는지 여부에 관계없이 MPI에서 프로그램을 사용할 수 있도록 합니다.

1. [운영](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs.md#operational-programs) - 이 옵션을 선택하면 프로그램이 MPI에 표시되지 않습니다.

>[!NOTE]
>
>기간 원가 **has** 참여 대시보드에서 성공 및 새 이름 보고에 대해 설정할 수 있습니다. 이 대시보드는 성공 및 새 이름을 집계하기 위해 기간 원가 데이터를 사용합니다. 기간 비용을 설정하지 않으면 위의 Analytics 동작 설정에 관계없이 참여 대시보드가 올바르게 보고되지 않습니다.

## MPI에 기회가 없는 이유는 무엇입니까? {#why-am-i-missing-some-opportunities-in-mpi}

MPI에서 영업 기회를 놓쳤을 수 있는 두 가지 주요 이유는 다음과 같습니다.

1. 속성 설정이 명시됨으로 설정되어 있지만 영업 기회에 담당자 역할이 할당되지 않았습니다
1. 기간 비용은 프로그램에 포함되지 않습니다

MPI는 모든 기회가 분석에 포함되는지 여부를 계산합니다. 그렇지 않으면 더 많은 기회를 포함하도록 속성 설정(명시적, 암시적, 하이브리드)을 변경하는 것을 고려하라는 메시지가 표시됩니다.

프로그램에서 프로그램 비용이 누락되어 기회가 누락될 수도 있습니다. 경고 메시지가 표시되지만 비용이 없는 프로그램이 표시됩니다. 모든 프로그램과 기회가 MPI에 포함되어 있는지 확인하기 위해 비용을 포함하도록 프로그램 설정을 검토하십시오.

## 참여 대시보드에 사용자 지정 필드, 기회 유형 및 ABM 필터가 표시되지 않는 이유는 무엇입니까? {#why-do-i-not-see-custom-fields-opportunity-type-and-abm-filters-on-the-engagement-dashboard}

사용자 정의 필드, 기회 유형 및 ABM 필터는 영업 기회에 관련된 모든 속성입니다. 참여 대시보드를 사용하면 참여 및 리드 획득이 기회와 연관되어 있는지 여부를 측정할 수 있습니다. Engagement 대시보드에는 Custom Fields, Opportunity Type 및 ABM Filters가 적용되지 않습니다.

## 표준 Salesforce Opportunity Amount 필드 대신 수익 보고를 위해 사용자 정의 Salesforce Opportunity 필드를 사용하려고 합니다. MPI를 통해 가능합니까? {#i-want-to-use-a-custom-salesforce-opportunity-field-for-revenue-reporting-instead-of-the-standard-salesforce-opportunity-amount-field-will-mpi-allow-me-to-do-that}

예. [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support) 필드 유형이 통화인 경우 Marketo의 Opportunity Amount 필드를 사용자 정의 Salesforce Opportunity 필드에 다시 매핑할 수 있습니다. MPI가 Marketo Opportunity 금액 필드를 가리키므로 MPI는 다시 매핑된 사용자 지정 Salesforce 필드의 데이터를 사용할 수 있습니다.

>[!NOTE]
>
>다시 매핑하면 MPI가 앞으로 데이터를 표시합니다. 역사적 액수는 변하지 않을 것이다.

## 기회를 사용하지 않는 경우에도 MPI를 사용할 수 있습니까? {#if-i-don-t-use-opportunities-can-i-still-use-mpi}

MPI는 단계 맨 위에서 수익 효과까지 프로그램 성능을 측정할 수 있도록 설계되었습니다. 기회를 사용하지 않더라도 다음 작업을 수행할 수 있습니다.

* 대상 참여를 위한 교육 프로그램의 성과를 봅니다.
* 리드 획득 프로그램의 성과를 봅니다.
* 프로그램 태그를 통해 멀티채널 캠페인의 성과를 볼 수 있습니다.
* 지난 12개월 동안의 대상 참여 트렌드를 참조하십시오.
* PowerPoint에서 성능 데이터를 저장하고 내보냅니다.

## MPI에서 계정 기반 전략의 성공을 측정할 수 있습니까? {#can-i-measure-the-success-of-account-based-strategies-in-mpi}

예. MPI 통합 [Marketo TAM](https://docs.marketo.com/display/DOCS/Account+Based+Marketing+Overview) ABM 계정 목록을 MPI로 원활하게 가져올 수 있습니다. ABM 계정 목록 필터를 사용하여 원하는 ABM 목록을 선택하여 데이터를 필터링할 수 있습니다.

## MPI를 구입할 때 속성을 즉시 사용할 수 있습니까? {#is-attribution-instantly-available-when-i-purchase-mpi}

Marketo 속성 기능은 고객이 MPI를 구입할 때 사용할 수 있습니다. 하지만, [적절한 설정](/help/marketo/product-docs/reporting/performance-insights/setting-up-performance-insights.md) 기회와 프로그램 데이터가 MPI에 올바르게 전달되도록 하려면 가 필요합니다.

## 속성을 설정하려면 어떻게 해야 합니까? {#what-do-i-have-to-do-to-set-up-attribution}

1. 기회 설정

   1. CRM과 영업 기회를 동기화합니다
   1. 속성 설정이 명시됨으로 설정된 경우 기회에 대한 연락처 역할이 채워졌는지 확인하십시오
   1. 속성 설정을 Hybrid로 변경하는 것이 좋습니다
   1. 프로그램 설정

      1. 프로그램에 프로그램 비용 포함
      1. 분석 동작을 검토하여 프로그램을 analytics에 포함해야 하는지 여부를 지정합니다
      1. 보유한 모든 채널에 대한 성공 기준을 설정합니다
      1. 사람을 프로그램에 연결

         1. 첫 번째 터치 속성이 작동하려면 데이터베이스의 각 사용자에 대해 획득 프로그램 및 획득 날짜가 설정되었는지 확인하십시오.
         1. 프로그램이 데이터베이스의 사용자에 대한 성공 상태를 설정하는지 확인합니다

>[!TIP]
>
>필요한 모든 설정 단계는 [이 문서](/help/marketo/product-docs/reporting/performance-insights/setting-up-performance-insights.md).

## MPI와 프로그램 분석기의 차이점은 무엇입니까? {#whats-the-difference-between-mpi-and-the-program-analyzer}

프로그램 분석기를 사용하면 네 가지 방법으로 프로그램을 비교할 수 있습니다. MPI를 사용하면 성공, 새로운 기회 생성 등과 같이 선택한 지표에 대한 채널 및 프로그램 기여도를 분석할 수 있습니다. 또한 선택한 특정 지표를 기반으로 12개월 채널 트렌드를 볼 수도 있습니다.

## MPI와 고급 Report Builder 간의 차이점은 무엇입니까? {#whats-the-difference-between-mpi-and-the-advanced-report-builder}

고급 Report Builder(RCE라고도 함)는 셀프 서비스(또는 애드혹) 보고용으로 설계되었으며, 일반적으로 마케팅 작업에서 수행됩니다. MPI는 마케팅 리더 및 마케터가 한 번의 클릭으로 성능 분석에 액세스할 수 있도록 설계되었습니다. 최소 설정이 필요합니다.

## 기여도 날짜 필터의 &quot;이전 연도&quot; 선택 사항이 어떻게 되었습니까? {#what-happened-to-the-previous-year-option-in-contributions-date-filter}

&quot;이전 연도&quot; 항목을 일시적으로 제거했습니다. 사용자 지정 날짜 범위 선택 사항을 사용하여 전체 연도의 성능 데이터를 볼 수 있는 옵션이 있습니다.

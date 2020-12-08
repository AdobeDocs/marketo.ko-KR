---
unique-page-id: 12979858
description: 성능 통찰력 FAQ - 마케팅 문서 - 제품 설명서
title: 성능 통찰력 FAQ
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '1404'
ht-degree: 0%

---


# 성능 통찰력 FAQ {#performance-insights-faq}

## 참여 탭에서 &quot;성공&quot;의 정의는 무엇입니까? {#what-is-the-definition-of-success-in-the-engagement-tab}

성공은 Marketing To에서 의미 있는 상호 작용을 측정하는 것입니다. 프로그램의 목적은 개인 또는 잠재 고객과 의미 있는 상호 작용을 만드는 것입니다. 성공을 나타내는 것은 한 사람이 그 목표를 이루는 상태에 도달할 때 표시됩니다. 웨비나에 참석하고, 이메일에 있는 링크를 클릭하거나, 웹 양식을 채울 수 있습니다. 성공은 프로그램 채널에 따라 다릅니다.

>[!NOTE]
>
>**예**
>
>웨비나 프로그램에서는 다음과 같은 여러 상태가 있을 수 있습니다.초대, 등록 및 참석. 사람들이 실제로 웨비나를 보지 않기 때문에 초대받거나 등록된 것은 의미 있는 상호 작용이 아닙니다. 이 경우에는 참석한 것이 성공으로 간주된다.

## MPI가 CRM과 연동됩니까? {#will-mpi-work-with-any-crm}

네 기술적으로 MPI는 데이터 동기화를 위해 CRM과 직접 상호 작용하지 않습니다. MPI는 마케팅 분석 Data Warehouse에 저장된 데이터를 활용합니다. CRM 동기화는 리드 관리 응용 프로그램에서 발생하므로 리드 관리 응용 프로그램과 통합된 Marketing-supported CRM에 데이터가 올바르게 표시됩니다. 그러나 CRM 기회 필드는 Marketing To 기회 필드에 올바르게 매핑해야 합니다.

## 다른 마케팅 분석 제품(ARB, RCE, RCA, 프로그램 분석)이 없습니다. MPI가 제대로 작동합니까? {#i-do-not-have-any-other-marketing-analytics-products-arb-rce-rca-program-analysis-will-mpi-work-for-me}

MPI는 리드 관리 응용 프로그램에 대한 독립적인 추가 기능입니다. 다른 분석 제품은 사용하지 않아도 됩니다.

## RCA는 프로그램 성능 데이터도 보여줍니다. MPI와 RCA에 표시된 데이터 간에 차이가 있습니까? {#rca-shows-me-program-performance-data-as-well-is-there-a-difference-between-the-data-shown-in-mpi-and-rca}

아뇨 MPI 소스 데이터는 RCA와 동일한 데이터 웨어하우스의 데이터입니다. 따라서 두 데이터 간의 데이터 차이는 나타나지 않습니다. RCA를 사용하여 신속하게 자체 보고서를 만들 수 있습니다. MPI를 사용하면 이해하기 쉬운 시각적 대시보드에 액세스할 수 있습니다.

## 내 프로그램(예: 작동)이 MPI에 표시되는 것을 원하지 않습니다. 특정 프로그램의 가시성을 제어하려면 어떻게 해야 합니까? {#i-don-t-want-some-of-my-programs-e-g-operational-to-show-up-in-mpi-how-do-i-control-the-visibility-of-specific-programs}

프로그램의 Analytics 동작을 Operational으로 설정하여 프로그램의 가시성을 제어할 수 있습니다. 이로 인해 프로그램이 분석 계산에서 제외됩니다.

>[!NOTE]
>
>분석 행동 설정에 대한 자세한 내용을 [살펴보십시오](http://docs.marketo.com/display/public/DOCS/Edit+Analytics+Behavior+Settings).

## 새 제품 출시에 대한 멀티채널 캠페인을 실행하고 있습니다. 여러 채널에서 한 곳에서 이 캠페인의 성과를 어떻게 볼 수 있습니까? {#i-am-running-a-multi-channel-campaign-for-a-new-product-launch-how-can-i-view-the-performance-for-this-campaign-across-all-the-different-channels-in-one-place}

이러한 캠페인의 일부 프로그램의 경우 프로그램 태그를 사용하는 것이 좋습니다. 프로그램 태그는 자동으로 MPI에 동기화되고, 모든 MPI 대시보드에서 필터링하여 다중 채널 캠페인 성과를 볼 수 있습니다.

## RCA가 없는 경우 속성 설정에 액세스할 수 있습니까? {#will-i-have-access-to-attribution-settings-if-i-do-not-have-rca}

RCA가 있는지 여부에 관계없이 MPI가 있는 경우 속성 설정에 액세스할 수 있습니다.

## 로그인하면 내 속성 설정이 잘못되었다고 알려주는 MPI에 경고가 표시됩니다. 무슨 일이야? {#i-get-an-alert-in-mpi-when-i-log-in-telling-me-that-my-attribution-settings-are-incorrect-what-s-wrong}

MPI는 모든 기회가 분석에 포함되는지 여부를 계산합니다. 그렇지 않은 경우 더 많은 기회를 포함하도록 속성 설정(명시적, 암시적, 하이브리드)을 변경하는 것을 고려하라는 메시지가 표시됩니다.

프로그램에 프로그램 비용이 누락되어 기회를 놓치고 있을 수도 있습니다. 프로그램의 분석 동작을 검토하십시오. 이러한 기능은 다음과 같습니다.

1. 기본값 - 기본 동작은 최소 하나의 기간 비용이 할당되고, 1개의 기간 비용이 할당되는 경우 프로그램이 MPI ONLY에 포함됩니다.
1. 포함 - 이 옵션은 기간 비용을 포함했는지 여부에 관계없이 프로그램을 MPI에서 사용할 수 있도록 합니다.
1. [작동](http://docs.marketo.com/display/DOCS/Best+Practice%3A+How+to+Organize+your+Programs#BestPractice:HowtoOrganizeyourPrograms-OperationalPrograms) - 이 옵션을 선택하면 프로그램이 MPI에 표시되지 않습니다.

>[!NOTE]
>
>계약 대시보드에서 성공 및 새 이름 보고에 대해 기간 비용 **을** 설정해야 합니다. 이 대시보드는 기간 비용 데이터를 사용하여 성공 및 새 이름을 집계합니다. 기간 비용이 설정되지 않은 경우 위의 Analytics 동작 설정에 관계없이 관여 대시보드가 올바르게 보고되지 않습니다.

## MPI에 기회가 없는 이유는 무엇입니까? {#why-am-i-missing-some-opportunities-in-mpi}

MPI에서 기회가 없을 수 있는 두 가지 주요 원인은 다음과 같습니다.

1. 속성 설정이 [명시적]으로 설정되지만 기회는 연락처 역할을 할당하지 않습니다.
1. 기간 비용은 프로그램에 포함되지 않습니다.

MPI는 모든 기회가 분석에 포함되는지 여부를 계산합니다. 그렇지 않은 경우 더 많은 기회를 포함하도록 속성 설정(명시적, 암시적, 하이브리드)을 변경하는 것을 고려하라는 메시지가 표시됩니다.

프로그램에 프로그램 비용이 누락되어 기회를 놓치고 있을 수도 있습니다. 경고 메시지가 나타날 예정이지만 비용이 많이 들지 않는 프로그램을 가리킬 필요는 없다. 모든 프로그램과 기회가 MPI에 포함되어 있는지 확인하려면 프로그램 설정을 검토하십시오.

## 관여 대시보드에 사용자 지정 필드, 기회 유형 및 ABM 필터가 표시되지 않는 이유는 무엇입니까? {#why-do-i-not-see-custom-fields-opportunity-type-and-abm-filters-on-the-engagement-dashboard}

사용자 지정 필드, 기회 유형 및 ABM 필터는 기회와 관련된 모든 속성입니다. 관여 대시보드에서는 관여 및 리드 획득이 기회와 연관되어 있는지 여부를 측정할 수 있습니다. 관여 대시보드에서는 기회를 고려하지 않으므로 사용자 지정 필드, 기회 유형 및 ABM 필터가 적용되지 않습니다.

## 표준 Salesforce 기회 금액 필드가 아닌 매출 보고를 위해 맞춤형 Salesforce 기회 필드를 사용하려고 합니다. MPI를 통해 가능합니까? {#i-want-to-use-a-custom-salesforce-opportunity-field-for-revenue-reporting-instead-of-the-standard-salesforce-opportunity-amount-field-will-mpi-allow-me-to-do-that}

네 [Marketing](http://docs.marketo.com/cdn-cgi/l/email-protection#b5c6c0c5c5dac7c1f5d8d4c7ded0c1da9bd6dad8) Support는 필드 유형이 통화인 경우 Marketing To의 Opportunity Amount 필드를 사용자 지정 Salesforce Opportunity 필드에 다시 매핑할 수 있습니다. MPI가 마케팅 기회 금액 필드를 가리키므로 MPI는 리매핑된 사용자 지정 Salesforce 필드의 데이터를 사용할 수 있습니다.

>[!NOTE]
>
>다시 매핑 후 MPI는 앞으로 데이터를 표시합니다. 역사적 액수는 변하지 않을 것이다.

## 기회를 사용하지 않는다면 MPI를 사용할 수 있습니까? {#if-i-don-t-use-opportunities-can-i-still-use-mpi}

MPI는 깔때기 아래쪽에서 매출 영향에 이르기까지 프로그램 성과를 측정할 수 있도록 설계되었습니다. 기회를 사용하지 않으면 다음과 같은 이점을 얻을 수 있습니다.

* 고객 참여를 위한 교육 프로그램의 성과를 확인할 수 있습니다.
* 리드 획득 프로그램의 성능을 확인합니다.
* 프로그램 태그를 통해 멀티채널 캠페인의 성과를 확인할 수 있습니다.
* 지난 12개월 동안 고객 참여 트렌드를 살펴보십시오.
* PowerPoint에서 성능 데이터를 저장하고 내보낼 수 있습니다.

## MPI에서 계정 기반 전략의 성공을 측정할 수 있습니까? {#can-i-measure-the-success-of-account-based-strategies-in-mpi}

네 MPI는 Marketing [to ABM과](http://docs.marketo.com/display/DOCS/Account+Based+Marketing+Overview) 통합되므로 ABM 계정 목록을 MPI로 원활하게 가져올 수 있습니다. ABM 계정 목록 필터를 사용하여 원하는 ABM 목록을 선택하여 데이터를 필터링할 수 있습니다.

## MPI를 구입할 때 속성 기능을 즉시 사용할 수 있습니까? {#is-attribution-instantly-available-when-i-purchase-mpi}

Marketing To 속성 기능은 고객이 MPI를 구입할 때 사용할 수 있습니다. 그러나 기회와 프로그램 데이터가 MPI에 올바로 [들어오도록 하려면 적절한 설정이](http://docs.marketo.com/x/mRPG) 필요합니다.

## 속성을 설정하려면 어떻게 해야 합니까? {#what-do-i-have-to-do-to-set-up-attribution}

1. 기회 설정

   1. CRM과 기회 동기화
   1. 기여도 설정이 명시됨으로 설정된 경우 기회에 대한 연락처 역할을 채워야 합니다
   1. 속성 설정을 하이브리드 설정으로 변경하는 것이 좋습니다.
   1. 프로그램 설정

      1. 프로그램에 프로그램 비용 포함
      1. 분석 동작을 검토하여 프로그램이 분석에 포함되어야 하는지 여부 표시
      1. 모든 채널에 대한 성공 기준 설정
      1. 프로그램에 사람 연결

         1. 첫 번째 터치 속성이 작동하도록 데이터베이스의 각 사용자에 대해 획득 프로그램 및 획득 날짜가 설정되어 있는지 확인하십시오.
         1. 프로그램이 데이터베이스의 사용자에 대한 성공 상태를 설정하는지 확인

>[!TIP]
>
>필요한 모든 설정 단계는 [이 문서에 자세히 설명되어 있습니다](http://docs.marketo.com/x/mRPG).

## MPI와 프로그램 분석기의 차이점은 무엇입니까? {#whats-the-difference-between-mpi-and-the-program-analyzer}

프로그램 분석기를 사용하면 네 가지 측정값을 통해 프로그램을 비교할 수 있습니다. MPI를 사용하면 성공, 새로운 기회 창출 등과 같은 선택된 지표에 대한 채널 및 프로그램 기여도를 분석할 수 있습니다. 또한 선택한 특정 지표를 기반으로 12개월 채널 트렌드를 볼 수도 있습니다.

## MPI와 고급 Report Builder의 차이점은 무엇입니까? {#whats-the-difference-between-mpi-and-the-advanced-report-builder}

고급 Report Builder(때로 RCE라고도 함)는 셀프 서비스(또는 애드혹) 보고를 위해 설계되었으며, 일반적으로 마케팅 작업에서 수행됩니다. MPI는 마케팅 리더 및 마케터가 한 번의 클릭으로 성능 분석에 액세스할 수 있도록 설계되었습니다. 최소 설정이 필요합니다.

## 기여도 날짜 필터에서 &quot;이전 연도&quot; 옵션은 어떻게 되었습니까? {#what-happened-to-the-previous-year-option-in-contributions-date-filter}

&quot;전년도&quot; 항목을 일시적으로 제거했습니다. 사용자 지정 날짜 범위 선택을 사용하여 전체 연도의 성능 데이터를 보는 옵션이 여전히 있습니다.

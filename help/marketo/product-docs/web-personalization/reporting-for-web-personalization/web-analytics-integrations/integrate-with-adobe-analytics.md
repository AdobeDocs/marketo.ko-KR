---
unique-page-id: 2949160
description: Adobe Analytics - Marketo 문서 - 제품 설명서와 통합
title: Adobe Analytics과 통합
exl-id: 6ea35811-6f3d-4dc8-91aa-877d613f8e93
feature: Web Personalization
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '1130'
ht-degree: 0%

---

# Adobe Analytics과 통합 {#integrate-with-adobe-analytics}

## 소개 {#intro}

Adobe Analytics 계정 내에서 조직, 업계 및 Marketo RTP(Real-Time Personalization) 캠페인 데이터를 보고 B2B 관점에서 웹 분석을 분석합니다.

이 문서를 사용하면 Marketo 실시간 개인화(RTP)와 Adobe Adobe Analytics 간의 통합을 사용할 수 있습니다. RTP의 데이터를 사용하면 사이트를 방문하는 모든 업계 세그먼트 및 조직의 트렌드를 감지하고 분석하고 RTP 캠페인의 효과를 측정하여 최적의 결과를 얻을 수 있는 통찰력과 분석을 제공할 수 있습니다.

각 세그먼트의 신규 방문자 수와 재방문자 수 등의 지표를 보고, 캠페인에 대한 클릭률을 분석하고, 최고의 전환 리드를 생성한 업계 및 사용자 정의 세그먼트와 실시간 캠페인을 발견하여 이를 달성할 수 있습니다. 이 기능을 활용하여 RTP 계정의 최대 이점을 얻으십시오.

## RTP AUDIENCE ANALYTICS {#rtp-audience-analytics}

RTP - AA 통합을 사용하면 웹 분석 인터페이스 내에 새 차원이 있습니다. RTP는 다음을 통해 웹 분석 대시보드를 자동으로 향상시킵니다.

1. 조직 및 업계 데이터
1. 사용자 지정된 RTP 세그먼트
1. 명명된 계정 목록(Account-Based Marketing)

이렇게 하면 B2B 데이터가 향상되고, 다음을 최적화하여 관련 방문자에 집중할 수 있습니다.

1. 아웃바운드 채널
1. 콘텐츠
1. 재타겟팅

## 채널 보고서 {#channel-report}

![](assets/image2014-11-29-12-3a0-3a26.png)

RTP 대시보드는 세로 및 RTP 세그먼트에 따른 방문자 분류를 이해하는 데 도움이 됩니다. 업종에 따른 방문자 실적과 해당 업종과 관련된 다양한 마케팅 캠페인(유료, 유기, 소셜)을 볼 수 있습니다. 또한 대시보드는 방문자가 업계 유형에 따라 보고 있는 사이트 섹션에 대한 높은 수준의 개요를 제공합니다.

## 동작 보고서 {#behavioral-report}

조직, 업계 및 RTP 세그먼트 데이터를 기반으로 Adobe Analytics에서 다양한 동작 보고서를 만들 수 있습니다. 이러한 흐름 보고서는 방문자가 한 페이지 또는 이벤트에서 다음 페이지로 이동하는 경로를 시각화합니다. 이 보고서는 방문자가 사이트에 계속 참여할 수 있는 콘텐츠를 찾는 데 도움이 될 수 있습니다.

## RTP 성능 {#rtp-performance}

Adobe Analytics의 사용자 지정 링크에서 RTP 캠페인 노출 횟수 및 전환을 봅니다.

이 사용자 지정 링크 보고서는 다음 이름 지정 형식으로 캠페인의 노출 횟수 및 변환 횟수를 보여줍니다.

* 노출 ISegment: [RTP 세그먼트 이름], ICampaign: [RTP 캠페인 이름]
* 전환 세그먼트: [RTP 세그먼트 이름], ICampaign: [RTP 캠페인 이름]

![](assets/custom-links-report.png)

## Adobe Analytics에서 설정 {#set-up-in-adobe-analytics}

통합에서는 Adobe Analytics이 제공하는 JavaScript API를 사용합니다. 사용자 지정 전환 변수(eVar), 사용자 지정 이벤트(이벤트) 및 트래픽 변수가 통합에 사용됩니다. 모든 은(는) AA 관리자 내에서 활성화되어야 합니다. RTP에서 전환 변수, 사용자 지정 이벤트 및 트래픽 변수를 설정해야 합니다. 그렇지 않으면 RTP에서 데이터를 활성화하더라도 세트에서 데이터를 볼 수 없습니다.

다음 단계를 완료하여 AA에서 이러한 변수를 설정합니다.

1. 다음으로 이동 **관리 도구** AA 계정에서.
1. 다음 항목 선택 **보고서 세트** 통합에 사용됩니다.
1. 아래 **설정 편집**&#x200B;로 이동합니다. **전환** 및 선택 **[전환 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Edit_conversion_variables)**.\
   다음 항목 선택 [전환 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Conversion_Variables_eVar) 번호(권장):

   1. 업계 사용자 정의 전환용 Evar # 20
   1. 조직 사용자 정의 전환에 대한 Evar # 21

   >[!NOTE]
   >
   >이 #을 사용하는 경우 사용 가능한 다른 숫자를 선택하십시오. 이 숫자를 RTP 계정 설정의 슬롯 번호에 맞춥니다.

   1. 상태를 다음으로 변경 _활성화됨_.

      1. 이름 변경 대상 **업계** 및 **조직**. (이것이 보고서 세트에 표시되는 방식입니다.)

      1. 다음 시기 이후에 만료 필드를 다음으로 변경 **방문**.

1. 아래 **설정 편집** 다음으로 이동 **전환** 및 선택 **[성공 이벤트](https://microsite.omniture.com/t2/help/en_US/reference/#Configure_success_events)**.

   1. 사용자 지정 성공 이벤트 이벤트 이벤트 번호를 선택합니다(권장).

      1. RTP 캠페인용 event20
      1. rtp 세그먼트에 대한 event21

      >[!NOTE]
      >
      >이 #을 사용하는 경우 사용 가능한 다른 숫자를 선택하십시오. 이 숫자를 RTP 계정 설정의 슬롯 번호에 맞춥니다.

      1. 두 이벤트 이름을 다음으로 변경 **RTP 캠페인** 및 **RTP 세그먼트**. 보고서 세트에 표시되는 이름입니다.

   1. 다음이 될 유형 필드 선택 **카운터(하위 관계 없음)**

1. 아래 **설정 편집** 다음으로 이동 **[트래픽](https://microsite.omniture.com/t2/help/en_US/reference/#Traffic_Variable)** 및 선택 **[트래픽 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Enable_traffic_variable_reports)**.

   1. 트래픽 변수 속성 번호 를 선택합니다(권장).

      1. 속성 # 20 - 이름: RTP 세그먼트 조직
      1. 속성 # 21 - 이름: RTP 세그먼트 업계
      1. 속성 # 25 - 이름: 캠페인 조직
      1. 속성 # 26 - 이름: RTP Campaign 업계

      >[!NOTE]
      >
      >이 #을 사용하는 경우 사용 가능한 다른 숫자를 선택하십시오. 이 숫자를 RTP 계정 설정의 슬롯 번호에 맞춥니다.)

      1. 4개의 속성 이름을 변경합니다. 보고서 세트에 표시되는 이름입니다.

   1. 활성화 필드 선택 **활성화됨**.

   1. 경로 보고서 필드 선택 **활성화됨**.

## Marketo Real-Time Personalization (RTP)에서 설정 {#set-up-in-marketo-real-time-personalization-rtp}

1. RTP 플랫폼에서 로 이동합니다. **계정 설정**.

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. 아래 **계정 설정**, 클릭 **도메인**.
1. 아래 **Analytics, 클릭** **Adobe Analytics**.
1. 회전 **날짜** 전환, 사용자 지정 및 트래픽 변수가 전환됩니다.
1. 전환, 이벤트 및 트래픽 변수 할당 **슬롯 번호** AA에서 생성된 슬롯 번호와 일치
1. 클릭 **저장**.

![](assets/image2014-11-29-12-3a24-3a42.png)

>[!NOTE]
>
>권장되는 슬롯 설정은 다음과 같습니다.
>
>**전환 변수**
>
>* 업계 맞춤형 전환 - 슬롯 20
>* 조직 사용자 지정 전환 - 슬롯 21
>
>**사용자 지정 이벤트**
>
>* Campaign 사용자 지정 이벤트 - 슬롯 20
>* 세그먼트 사용자 지정 이벤트 - 슬롯 21
>
>**트래픽 변수**
>
>* 세그먼트 조직 트래픽 변수 - 슬롯 20
>* 세그먼트 업계 트래픽 변수 - 슬롯 21
>* 캠페인 조직 트래픽 변수 - 슬롯 22
>* 캠페인 산업 트래픽 변수 - 슬롯 23
>
>**이러한 슬롯 번호가 AA에서 생성된 변수 및 이벤트 번호와 일치하는지 확인하십시오.**

## 보고서 {#reports}

조직 이름, 업계 및 RTP 세그먼트 및 실시간 캠페인 데이터에 따라 향상된 SiteAdobe Analytics 보고서를 만듭니다.

AA의 맞춤화된 보고서 및 대시보드의 예는 다음과 같습니다.

* 업계 또는 정의된 세그먼트별 성능(계정 기반 명명 목록)
* KPI 성능별 업계 분류
* 조직당 본 페이지 수
* 조직, 업계, 세그먼트에 따른 마케팅 채널 성과

**-보고서 예-**

**주요 업계 보고서**

![](assets/top-industries-report.png)

**조직 보고서**

![](assets/image2014-11-29-12-3a29-3a42.png)

**RTP 대시보드 만들기**

만들기 [새 대시보드](https://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add.html), 호출됨 **RTP 대시보드**. 이 대시보드는 세로 및 RTP 세그먼트에 따른 방문자 분류를 이해하는 데 도움이 됩니다.

1. 클릭 **대시보드,** 클릭 **대시보드 추가**.

1. 대시보드 이름 지정 **RTP 대시보드**.

1. 다음 항목 선택 **대시보드 크기** 3 x 2, 2 x 2.

1. 만들기 [리포트릿](https://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add_report.html#task_EC3AFBBAA51C45CEBAF632F841C305B3) 및 추가 [대시보드에 컨텐츠](https://docs.marketo.com/Add%2520content%2520to%2520a%2520dashboard).

대시보드에 업계 Reportlet 추가

1. 다음으로 이동 **사용자 지정 전환**, 클릭 **업계**.

1. 그래프 구성 대상 **파이 차트**.

1. 클릭 **대시보드**, 추가 **리포트릿**.

1. 보고서 이름 지정 **주요 업종**.

1. 대시보드에 배치 **RTP 대시보드**.

1. 만들기 **신규**.

대시보드에 세그먼트 Reportlet 추가

1. 다음으로 이동 **사이트 지표**. 클릭 **사용자 지정 이벤트**, **세그먼트**.

1. 그래프 구성 대상 **세로 막대**.

1. 클릭 **대시보드**, 추가 **리포트릿**.

1. 보고서 이름 지정 **상위 세그먼트**.

1. 대시보드에 배치 **RTP 대시보드**.

1. 만들기 **신규**.

reportlet이 대시보드에 표시됩니다.

## Adobe Analytics에서 노출 횟수 및 클릭 수(전환) 보기 {#view-impressions-and-clicks-conversions-in-adobe-analytics}

1. 클릭 **사용자 지정 링크**.

   ![](assets/sitecatalyst1-1.png)

1. 캠페인 노출 횟수를 나타내는 세그먼트 및 캠페인 이름을 보려면 노출 횟수를 검색합니다.\
   ![](assets/sitecatalyst1.png)

1. 캠페인 클릭 수를 나타내는 세그먼트 및 캠페인 이름을 보기 위해 전환을 검색합니다.

   ![](assets/sitecatalyst2.png)

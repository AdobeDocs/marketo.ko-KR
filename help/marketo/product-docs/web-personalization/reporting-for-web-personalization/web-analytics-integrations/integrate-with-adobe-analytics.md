---
unique-page-id: 2949160
description: Adobe Analytics과 통합 - Marketo 문서 - 제품 설명서
title: Adobe Analytics과 통합
exl-id: 6ea35811-6f3d-4dc8-91aa-877d613f8e93
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '1130'
ht-degree: 0%

---

# Adobe Analytics과 통합 {#integrate-with-adobe-analytics}

## 인트로 {#intro}

Adobe Analytics 계정 내에서 조직, 업계 및 Marketo RTP(실시간 개인화) 캠페인 데이터를 확인하여 B2B 관점에서 웹 분석을 분석합니다.

이 문서에서는 Marketo RTP(실시간 개인화)와 Adobe Adobe Analytics 간의 통합을 활성화합니다. RTP의 데이터를 사용하면 사이트를 방문하는 모든 업계 세그먼트 및 조직의 트렌드를 감지하고 분석하고 RTP 캠페인의 효과를 측정하며, 통찰력과 분석을 제공하여 최적의 결과를 얻을 수 있습니다.

각 세그먼트의 새 방문자와 재방문자 수 등의 지표를 보고, 캠페인의 클릭률을 분석하고, 전환율이 가장 높은 업계 및 사용자 지정된 세그먼트와 실시간 캠페인을 확인하여 이를 달성할 수 있습니다. 이 기능을 활용하여 RTP 계정의 최대 이점을 얻을 수 있습니다.

## RTP Audience Analytics {#rtp-audience-analytics}

RTP - AA 통합을 사용하면 웹 분석 인터페이스 내에 새 차원이 있습니다. RTP는 다음을 사용하여 웹 분석 대시보드를 자동으로 향상시킵니다.

1. 조직 및 업계 데이터
1. 사용자 지정된 RTP 세그먼트
1. 명명 계정 목록(Account-Based Marketing)

이를 통해 B2B 데이터가 향상되며 다음을 최적화하여 관련 방문자에 집중할 수 있습니다.

1. 아웃바운드 채널
1. 콘텐츠
1. 재타겟팅

## 채널 보고서 {#channel-report}

![](assets/image2014-11-29-12-3a0-3a26.png)

RTP 대시보드는 일반적인 세그먼트와 RTP 세그먼트에 따라 방문자의 분류를 이해하는 데 도움이 됩니다. 해당 산업과 관련된 업계 및 다양한 마케팅 캠페인(유료, 유기, 소셜)에 따라 방문자 성과를 볼 수 있습니다. 또한 대시보드는 방문자가 업계 유형에 따라 보고 있는 사이트 섹션에 대한 높은 수준의 개요를 제공합니다.

## 행동 보고서 {#behavioral-report}

조직, 업계 및 RTP 세그먼트 데이터를 기반으로 하여 Adobe Analytics에서 다양한 동작 보고서를 만들 수 있습니다. 이러한 흐름 보고서는 방문자가 한 페이지 또는 이벤트에서 다음 페이지로 이동하는 경로를 시각화합니다. 이 보고서를 통해 방문자가 사이트에 계속 참여하는 콘텐츠를 확인할 수 있습니다.

## RTP 성능 {#rtp-performance}

Adobe Analytics의 사용자 지정 링크에서 RTP 캠페인 노출 횟수 및 전환을 봅니다.

이 사용자 지정 링크 보고서는 다음 이름 지정 형식으로 캠페인의 노출 횟수 및 전환을 보여줍니다.

* 노출 ISgment: [RTP 세그먼트 이름], ICampaign: [RTP 캠페인 이름]
* 변환 ISegment: [RTP 세그먼트 이름], ICampaign: [RTP 캠페인 이름]

![](assets/custom-links-report.png)

## Adobe Analytics에서 설정 {#set-up-in-adobe-analytics}

통합은 Adobe Analytics이 제공하는 JavaScript API를 사용합니다. 사용자 지정 전환 변수(eVar), 사용자 지정 이벤트(이벤트) 및 트래픽 변수가 통합에서 사용됩니다. 관리자 내에서 모두 를 활성화해야 합니다. Adobe에서 전환 변수, 사용자 지정 이벤트 및 트래픽 변수를 설정해야 합니다. 그렇지 않으면 RTP에서 데이터를 활성화한 경우에도 세트에서 데이터를 볼 수 없습니다.

다음 단계를 완료하여 AA에서 이러한 변수를 설정합니다.

1. 이동 **관리 도구** ( AA 계정)에 보관하십시오.
1. 을(를) 선택합니다 **보고서 세트** 와 함께 사용할 수 있습니다.
1. 아래 **설정 편집**, 이동 **전환** 을(를) 선택합니다. **[전환 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Edit_conversion_variables)**.\
   을(를) 선택합니다 [전환 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Conversion_Variables_eVar) 번호(권장됨):

   1. 업계 사용자 지정 전환용 Evar # 20
   1. 조직 사용자 지정 전환용 Evar # 21

   >[!NOTE]
   >
   >이 번호를 가져올 경우 다른 사용 가능한 번호를 선택하십시오. 이 숫자를 RTP 계정 설정의 슬롯 번호와 맞춥니다.

   1. 상태 변경 _활성화됨_.

      1. 이름 변경 **업계** 및 **조직**. (보고서 세트에 표시되는 방식입니다.)

      1. 다음 시기 이후에 만료 필드를 다음으로 변경 **방문**.


1. 아래 **설정 편집** 이동 **전환** 을(를) 선택합니다. **[성공 이벤트](https://microsite.omniture.com/t2/help/en_US/reference/#Configure_success_events)**.

   1. 사용자 지정 성공 이벤트 이벤트 번호를 선택합니다(권장).

      1. rtp 캠페인용 event20
      1. rtp 세그먼트에 대한 event21

      >[!NOTE]
      >
      >이 번호를 가져올 경우 다른 사용 가능한 번호를 선택하십시오. 이 숫자를 RTP 계정 설정의 슬롯 번호와 맞춥니다.

      1. 두 이벤트 이름을 **RTP 캠페인** 및 **RTP 세그먼트**. 보고서 세트에 표시되는 이름입니다.
   1. 표시할 유형 필드를 선택합니다 **카운터(하위 관계 없음)**



1. 아래 **설정 편집** 이동 **[트래픽](https://microsite.omniture.com/t2/help/en_US/reference/#Traffic_Variable)** 을(를) 선택합니다. **[트래픽 변수](https://microsite.omniture.com/t2/help/en_US/reference/#Enable_traffic_variable_reports)**.

   1. 트래픽 변수 속성 번호를 선택합니다(권장).

      1. 속성 번호 20 - 이름: RTP 세그먼트 조직
      1. 속성 번호 21 - 이름: RTP 세그먼트 업계
      1. 속성 번호 25 - 이름: 캠페인 조직
      1. 속성 번호 26 - 이름: RTP Campaign 업계

      >[!NOTE]
      >
      >이 번호를 가져올 경우 다른 사용 가능한 번호를 선택하십시오. 이 번호를 RTP 계정 설정의 슬롯 번호와 맞춥니다.

      1. 4개의 속성 이름을 변경합니다. 보고서 세트에 표시되는 이름입니다.
   1. 사용할 수 있는 필드 선택 **활성화됨**.

   1. 경로 보고서 필드를 선택하여 **활성화됨**.



## Marketo 실시간 개인화(RTP)에서 설정 {#set-up-in-marketo-real-time-personalization-rtp}

1. RTP 플랫폼에서 **계정 설정**.

   ![](assets/image2014-11-29-11-3a27-3a7.png)

1. 아래 **계정 설정**&#x200B;를 클릭합니다. **도메인**.
1. 아래 **Analytics에서** **Adobe Analytics**.
1. 회전 **설정** 전환, 사용자 지정 및 트래픽 변수가 토글됩니다.
1. 전환, 이벤트 및 트래픽 변수 할당 **슬롯 번호** AA에서 생성된 슬롯 번호와 일치시키기
1. 클릭 **저장**.

![](assets/image2014-11-29-12-3a24-3a42.png)

>[!NOTE]
>
>권장되는 슬롯 설정은 다음과 같습니다
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
>* 캠페인 업계 트래픽 변수 - 슬롯 23
>
>**이러한 슬롯 번호가 AA에서 만든 변수 및 이벤트 번호와 일치하는지 확인합니다.**

## 보고서 {#reports}

조직 이름, 업계 및 RTP 세그먼트 및 실시간 캠페인 데이터에 따라 향상된 SiteAdobe Analytics 보고서를 만듭니다.

AA에서 사용자 지정된 보고서 및 대시보드의 예는 다음과 같습니다.

* 업계 또는 정의된 세그먼트별 성과(계정 기반 명명된 목록)
* KPI 성능당 업계 분류
* 조직당 본 페이지
* 조직, 업계, 세그먼트에 따른 마케팅 채널 성과

**-보고서 예 -**

**상위 산업 보고서**

![](assets/top-industries-report.png)

**조직 보고서**

![](assets/image2014-11-29-12-3a29-3a42.png)

**RTP 대시보드 만들기**

만들기 [새 대시보드](https://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add.html), 호출됨 **RTP 대시보드**. 이 대시보드는 일반적인 세그먼트와 RTP 세그먼트에 따라 방문자의 분류를 이해하는 데 도움이 됩니다.

1. 클릭 **대시보드,** click **대시보드 추가**.

1. 대시보드 이름을 지정합니다 **RTP 대시보드**.

1. 을(를) 선택합니다 **대시보드 크기** 3 x 2, 2 x 2

1. 만들기 [리포트릿](https://microsite.omniture.com/t2/help/en_US/sc/user/t_dashboard_add_report.html#task_EC3AFBBAA51C45CEBAF632F841C305B3) 및 추가 [대시보드에 컨텐츠](https://docs.marketo.com/Add%2520content%2520to%2520a%2520dashboard).

대시보드에 업계 Reportlet 추가

1. 이동 **사용자 지정 전환**&#x200B;를 클릭하고 **업계**.

1. 그래프 구성 대상 **파이 차트**.

1. 클릭 **대시보드**, 추가 **Reportlet**.

1. 보고서 이름을 지정합니다 **상위 업종**.

1. 대시보드에 배치 **RTP 대시보드**.

1. 만들기 **새로 만들기**.

대시보드에 세그먼트 Reportlet 추가

1. 이동 **사이트 지표**. 클릭 **사용자 지정 이벤트**, **세그먼트**.

1. 그래프 구성 대상 **세로 막대**.

1. 클릭 **대시보드**, 추가 **Reportlet**.

1. 보고서 이름을 지정합니다 **상위 세그먼트**.

1. 대시보드에 배치 **RTP 대시보드**.

1. 만들기 **새로 만들기**.

reportlet이 대시보드에 표시됩니다.

## Adobe Analytics에서 노출 횟수 및 클릭 수(전환) 보기 {#view-impressions-and-clicks-conversions-in-adobe-analytics}

1. 클릭 **사용자 지정 링크**.

   ![](assets/sitecatalyst1-1.png)

1. 노출 횟수를 검색하여 세그먼트와 캠페인에 대한 노출 횟수를 나타내는 캠페인 이름을 봅니다.\
   ![](assets/sitecatalyst1.png)

1. 전환을 검색하여 보기 세그먼트와 캠페인 클릭 수를 나타내는 캠페인 이름을 봅니다.

   ![](assets/sitecatalyst2.png)

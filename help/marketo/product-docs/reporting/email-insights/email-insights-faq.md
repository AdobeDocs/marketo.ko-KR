---
unique-page-id: 10100257
description: 이메일 통찰력 FAQ - Marketo 문서 - 제품 설명서
title: 이메일 통찰력 FAQ
exl-id: de3aca5a-08b4-4af8-ab92-675cb46dcbb2
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---

# 이메일 통찰력 FAQ {#email-insights-faq}

## 이메일 인사이트 포함 비율 지표와 다른 Marketo 이메일 보고 간에 차이가 있습니까? {#are-there-any-differences-between-ratio-metrics-with-email-insights-and-other-marketo-email-reporting}

예. 이메일 인사이트는 참여 지표 비율(열기 비율, 클릭으로 열기 비율, 가입 해지 비율)을 계산할 때 전송된 동일한 이메일에 대한 해당 게재 지표와 상호 연관됩니다. 예를 들어 이메일 인사이트에서 클릭대 오픈율의 일별 분류로 지난 주 동안의 시계열 차트를 볼 때 이제 해당 게재 지표를 기반으로 공개/클릭/구독 취소 이벤트의 실제 상관 관계가 있는 비율을 표시합니다. 이는 모든 것을 요약하는 Revenue Explorer의 동작과 대조적입니다. 이메일 인사이트는 참여 비율에 대한 보다 정확한 보기를 제공합니다.

## 이메일 인사이트가 10개의 사용자 지정 Dimension만 지원하는 이유는 무엇입니까? {#why-does-email-insights-only-support-custom-dimensions}

많은 사용 사례의 경우, 10개의 추가 사용자 지정 차원으로 기본 시스템 차원을 확장하는 것은 적절하지 않으며, 세그먼테이션이나 프로그램 태그를 기반으로 하는 사용자 지정 차원을 포함합니다. 향후 고객이 허용된 사용자 지정 Dimension 수를 늘릴 수 있도록 할 계획입니다.

## 사용자 지정 Dimension 슬롯이 지정된 후 다시 사용할 수 없는 이유는 무엇입니까? {#why-cant-i-re-use-custom-dimensions-slots-after-theyve-been-assigned}

주어진 사용자 지정 Dimension 슬롯이 할당되면 다시 매핑되면 새로운 의미와 블렌드될 때 이전 데이터가 오류를 생성합니다. 이로 인해 사용자 정의 Dimension 슬롯이 다시 사용되지 않을 수 있습니다. 이 동작은 Google Analytics과 같은 다른 지표 분석 도구의 동작 과 일치합니다.

## 이메일 인사이트가 Marketo Sales Insight 이메일을 지원합니까? {#does-email-insights-support-marketo-sales-insight-emails}

예. Marketo Sales Insights를 통해 전송되는 모든 이메일은 이메일 인사이트에 포함됩니다.

## 이메일 인사이트가 운영 이메일을 지원합니까? {#does-email-insights-support-operational-emails}

예. 기본적으로 운영 이메일은 보기 및 쿼리로부터 숨겨집니다. 그러나 개인 설정 패널에서 이 설정을 변경할 수 있습니다.

## 이메일 인사이트는 반복 예약된 반복 또는 스마트 캠페인 이메일 흐름 단계를 다시 실행합니까? {#does-email-insights-capture-recurring-scheduled-or-re-run-smart-campaign-email-flow-steps}

예, 아니요. 이메일 인사이트의 초기 릴리스를 사용하면 모든 이메일 이벤트가 캡처되고 반복 예약되거나 다시 실행하는 스마트 캠페인에 대해 액세스할 수 있습니다. 하지만 스마트 캠페인의 다른 실행을 구별할 수는 없습니다. 차별화하기 위해 다음 릴리스에서 열기, 클릭 및 가입 해지 이벤트에 대한 Smart Campaign 실행 정보를 캡처할 수 있는 지원을 추가하고 있습니다.

## 장치 유형 또는 장치 OS별로 필터링할 때 지표가 0으로 표시되는 이유는 무엇입니까? {#why-do-many-metrics-show-zero-when-i-filter-by-device-type-or-device-os}

클릭대 오픈율, 열기, 클릭 수 및 가입 해지 이외의 다른 모든 지원 지표는 게재 이벤트에서 파생된 게재 이벤트 또는 비율입니다. 장치 유형 및 장치 OS는 참여 지표에만 적용되므로 표시할 정보가 없습니다. 예를 들어, Marketo은 기본 게재 및 보낸 이벤트에 대한 참여 지표를 수신하지 않았으므로 장치 유형 = 모바일로 필터링되면 배달 속도를 요청하도록 정의되지 않은 쿼리입니다. 참여 지표와 게재 지표 모두에 포함된 비율에 대해 참여 지표에서 장치 유형 및 장치 OS를 적용하는 방법을 모색하고 있습니다.

## 특정 이메일 클라이언트가 이미지를 차단할 때 이메일 인사이트는 어떻게 수행됩니까? {#what-does-email-insights-do-when-certain-email-clients-block-images}

일반적인 업계 문제는 점차 많은 이메일 클라이언트가 기본적으로 이미지를 비활성화하고 있다는 것입니다. 이미지 로드는 [열기]가 기록되는 방식을 기반으로 합니다. 사용자가 이미지가 차단된 이메일을 받을 수 있지만 텍스트 및 링크가 완전히 읽을 수 있습니다. 사용자가 이를 경험하고 해당 이메일의 링크를 클릭한 경우 클릭 이벤트의 시나리오가 표시되지만 해당 이메일에 대한 해당 열기 이벤트는 표시되지 않습니다. Marketo 이메일 인사이트는 누락된 이벤트를 자동으로 생성합니다. 논리는 Marketo이 이메일 성과 보고서에 대해 이 작업을 수행하는 방법과 매출 탐색기의 이메일 분석 영역과 동일합니다.

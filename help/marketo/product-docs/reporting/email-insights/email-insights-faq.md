---
unique-page-id: 10100257
description: 이메일 인사이트 FAQ - Marketo 문서 - 제품 설명서
title: 이메일 인사이트 FAQ
exl-id: de3aca5a-08b4-4af8-ab92-675cb46dcbb2
feature: Reporting
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '602'
ht-degree: 0%

---

# 이메일 인사이트 FAQ {#email-insights-faq}

## 이메일 인사이트와 다른 Marketo 이메일 보고의 비율 지표 간에 차이가 있습니까? {#are-there-any-differences-between-ratio-metrics-with-email-insights-and-other-marketo-email-reporting}

예. 이메일 인사이트 는 참여 지표 비율 (열기 비율, 클릭에서 열기 비율, 구독 취소 비율)을 계산할 때 전송되는 동일한 이메일에 대해 참여 지표를 해당 게재 지표와 상호 연관시킵니다. 예를 들어 이메일 인사이트에서 클릭률/오픈율에 대한 일일 분류가 있는 지난 주 시계열 차트를 보면 이제 해당 게재 지표를 기반으로 열기/클릭/구독 취소 이벤트의 실제 상관 관계 비율을 보여 줍니다. 이는 단순히 모든 것을 요약하는 매출 탐색기의 동작과 대조됩니다. 이메일 인사이트는 참여 비율을 보다 정확하게 보여 줍니다.

## 이메일 인사이트는 왜 10개의 사용자 지정 Dimension만 지원합니까? {#why-does-email-insights-only-support-custom-dimensions}

많은 사용 사례에서 10개의 추가 사용자 지정 차원으로 기본 시스템 차원을 확장하는 것은 적절하지 않으며 세그먼트화나 프로그램 태그를 기반으로 하는 사용자 지정 차원을 포함합니다. 향후 고객이 허용된 사용자 정의 Dimension 수를 늘릴 수 있도록 허용할 계획입니다.

## 사용자 지정 Dimension 슬롯이 할당된 후 다시 사용할 수 없는 이유는 무엇입니까? {#why-cant-i-re-use-custom-dimensions-slots-after-theyve-been-assigned}

주어진 사용자 지정 Dimension 슬롯이 할당되면 다시 매핑하면 새 의미와 혼합될 때 이전 데이터에 오류가 발생합니다. 이러한 이유로 사용자 정의 Dimension 슬롯은 재사용되지 않을 수 있습니다. 이 동작은 Google Analytics과 같은 다른 지표 분석 도구의 동작과 일치합니다.

## 이메일 인사이트는 Marketo Sales Insight 이메일을 지원합니까? {#does-email-insights-support-marketo-sales-insight-emails}

예. Marketo Sales Insights 를 통해 전송된 모든 이메일은 이메일 인사이트에 포함됩니다.

## 이메일 인사이트는 작동 중인 이메일을 지원합니까? {#does-email-insights-support-operational-emails}

예. 기본적으로 운영 이메일은 보기 및 쿼리에서 숨겨집니다. 그러나 개인 설정 패널에서 이 설정을 변경할 수 있습니다.

## 이메일 인사이트는 반복되는 예약된 또는 다시 실행되는 스마트 Campaign 이메일 흐름 단계를 캡처합니까? {#does-email-insights-capture-recurring-scheduled-or-re-run-smart-campaign-email-flow-steps}

예, 아니요. 이메일 인사이트의 초기 릴리스에서는 모든 이메일 이벤트가 캡처되어 반복 예약된 또는 다시 실행되는 Smart Campaign에 대해 액세스할 수 있습니다. 그러나 스마트 캠페인의 다양한 실행을 구별할 수는 없습니다. 차별화하기 위해 다음 릴리스에서 열기, 클릭 및 구독 취소 이벤트에 대한 스마트 Campaign 실행 정보를 캡처하는 지원을 추가하고 있습니다.

## 장치 유형 또는 장치 OS별로 필터링할 때 많은 지표가 0으로 표시되는 이유는 무엇입니까? {#why-do-many-metrics-show-zero-when-i-filter-by-device-type-or-device-os}

클릭률-열기, 클릭 수, 구독 취소 를 제외하고 지원되는 다른 모든 지표는 배달 이벤트 또는 배달 이벤트에서 파생된 비율입니다. 장치 유형 및 장치 OS는 참여 지표에만 적용되므로 표시할 정보가 없습니다. 예를 들어, Marketo은 기본 배달 및 전송된 이벤트에 대한 참여 지표를 받지 못했을 것이므로 디바이스 유형 = 모바일로 필터링될 때 배달 속도를 묻는 것은 정의되지 않은 쿼리입니다. 참여 및 게재 지표로 구성된 비율에 대한 참여 지표에서 장치 유형 및 장치 OS를 적용하는 방법을 살펴보고 있습니다.

## 특정 이메일 클라이언트가 이미지를 차단할 때 이메일 인사이트는 어떻게 합니까? {#what-does-email-insights-do-when-certain-email-clients-block-images}

일반적인 업계 문제는 기본적으로 이미지를 사용하지 않는 이메일 클라이언트가 증가하고 있다는 것입니다. 이미지 로드는 열림 수를 기록하는 방법의 기초입니다. 사용자가 이미지와 텍스트 및 링크를 완전히 읽을 수 없는 상태로 이메일을 수신할 수 있습니다. 사용자가 이를 경험하고 해당 이메일의 링크를 클릭한 경우 해당 이메일에 해당하는 열기 이벤트가 없는 클릭 이벤트의 시나리오가 표시됩니다. Marketo 이메일 인사이트는 누락된 모든 이벤트를 자동으로 생성합니다. 논리는 Marketo이 이메일 성능 보고서 및 매출 탐색기의 이메일 분석 영역에 대해 이 작업을 수행하는 방법과 동일합니다.

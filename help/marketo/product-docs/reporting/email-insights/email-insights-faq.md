---
unique-page-id: 10100257
description: 이메일 인사이트 FAQ - 마케팅 문서 - 제품 설명서
title: 이메일 인사이트 FAQ
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '600'
ht-degree: 0%

---


# 이메일 인사이트 FAQ {#email-insights-faq}

## 이메일 인사이트와 기타 마케팅 이메일 보고 간의 비율 지표 간에는 차이가 있습니까? {#are-there-any-differences-between-ratio-metrics-with-email-insights-and-other-marketo-email-reporting}

네 이메일 인사이트는 참여 지표 비율을 계산할 때 보낸 동일한 이메일에 대한 해당 전달 지표와 참여 지표(개방 비율, 클릭대 열기 비율, 가입 취소 비율)를 상관 관계가 있습니다. 예를 들어, 이메일 인사이트에서 클릭률 일일 분류와 함께 지난 주 동안의 시간 시리즈 차트를 볼 때, 이제 해당 전달 지표를 기반으로 열린/클릭/구독 취소 이벤트의 진정한 상관 관계가 있는 비율이 표시됩니다. 이는 모든 것을 요약하는 매출 탐색기의 동작과 대조적입니다. 이메일 인사이트는 참여 비율을 보다 정확하게 보여줍니다.

## 이메일 인사이트는 왜 10개의 사용자 지정 Dimension만 지원합니까? {#why-does-email-insights-only-support-custom-dimensions}

많은 사용 사례의 경우, 10개의 추가 사용자 지정 차원으로 기본 시스템 차원을 확장하면 적절하지 않으며, 세그먼테이션 또는 프로그램 태그를 기반으로 사용자 지정 차원을 포함합니다. 앞으로 고객이 허용된 사용자 정의 Dimension 수를 늘릴 수 있도록 할 계획입니다.

## 할당된 사용자 정의 Dimension 슬롯을 다시 사용할 수 없는 이유는 무엇입니까? {#why-cant-i-re-use-custom-dimensions-slots-after-theyve-been-assigned}

지정된 사용자 지정 Dimension 슬롯이 할당되면 다시 매핑하면 새 의미와 혼합될 때 이전 데이터가 오류가 발생합니다. 이로 인해 사용자 정의 Dimension 슬롯이 다시 사용되지 않을 수 있습니다. 이 동작은 Google Analytics과 같은 다른 지표 분석 도구의 동작과 동일합니다.

## 이메일 인사이트는 Marketing to Sales Insight 이메일을 지원합니까? {#does-email-insights-support-marketo-sales-insight-emails}

네 Marketing to Sales Insights를 통해 전송되는 모든 이메일이 이메일 인사이트에 포함됩니다.

## 이메일 인사이트는 운영 이메일을 지원합니까? {#does-email-insights-support-operational-emails}

네 기본적으로 작업 이메일은 보기 및 쿼리로부터 숨겨집니다. 그러나 개인 설정 패널에서 이 설정을 변경할 수 있습니다.

## 이메일 인사이트는 주기적으로 예약되거나 스마트 캠페인 이메일 흐름 단계를 다시 실행합니까? {#does-email-insights-capture-recurring-scheduled-or-re-run-smart-campaign-email-flow-steps}

예 및 아니요. 이메일 인사이트의 초기 릴리스에서는 모든 이메일 이벤트가 캡처되고 반복 예약된 캠페인 또는 다시 실행되는 스마트 캠페인에 액세스할 수 있습니다. 하지만 해당 스마트 캠페인의 다른 실행 수를 구별할 수는 없습니다. 다음 릴리스에서 지원을 추가하여 열기, 클릭 및 가입 해지 이벤트에 대한 스마트 캠페인 실행 정보를 캡처하여 구별할 수 있습니다.

## 장치 유형 또는 장치 OS별로 필터링할 때 지표가 0으로 표시되는 이유는 무엇입니까? {#why-do-many-metrics-show-zero-when-i-filter-by-device-type-or-device-os}

클릭대 열기 비율, 열기, 클릭 수 및 가입 취소를 제외한 다른 모든 지표는 배달 이벤트나 배달 이벤트에서 파생된 비율입니다. 장치 유형 및 장치 OS는 참여 지표에만 적용되므로 표시할 정보가 없습니다. 예를 들어 Marketing to가 기본 배달 및 전송 이벤트에 대한 참여 지표를 받지 못했을 것이므로 장치 유형 = 모바일로 필터링된 경우 배달 비율을 묻는 것은 정의되지 않은 쿼리입니다. 참여 지표와 전달 지표 모두로 구성된 비율에 대해 참여 지표에서 장치 유형 및 장치 OS를 적용하는 방법을 모색하고 있습니다.

## 특정 이메일 클라이언트가 이미지를 차단할 때 이메일 인사이트는 어떤 역할을 합니까? {#what-does-email-insights-do-when-certain-email-clients-block-images}

일반적인 업계 문제는 점점 더 많은 이메일 클라이언트가 기본적으로 이미지를 비활성화하고 있다는 것입니다. 이미지를 로딩하는 것은 [열기]가 기록된 방법의 기초가 됩니다. 사용자는 이미지가 차단되었지만 텍스트와 링크가 완전히 읽을 수 있는 상태로 이메일을 수신할 수 있습니다. 사용자가 이러한 상황을 경험하고 해당 이메일의 링크를 클릭했을 경우, 클릭 이벤트의 시나리오가 나타나지만 해당 이메일에 해당하는 열기 이벤트는 없을 것입니다. Marketing to Email Insights는 누락된 모든 이벤트를 자동으로 생성합니다. 논리는 Marketing To가 이메일 성과 보고서 및 매출 탐색기에서 이메일 분석 영역을 수행하는 방법과 동일합니다.

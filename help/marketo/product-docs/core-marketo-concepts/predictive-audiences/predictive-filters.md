---
description: 예측 필터 - Marketo 문서 - 제품 설명서
title: 예측 필터
exl-id: 27736b80-cd8b-455d-9d73-c17d492d0906
feature: Predictive Audiences
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 0%

---

# 예측 필터 {#predictive-filters}

예측 대상의 일부로 Marketo은 스마트 캠페인 내의 스마트 목록에서 AI/ML 기반 필터 그룹을 제공합니다.

![이미지 하나](assets/predictive-filters-1.png)

>[!NOTE]
>
>&quot;참석할 가능성이 있음&quot; 및 &quot;등록할 가능성이 있음&quot; 필터는 이벤트 프로그램에서만 사용할 수 있습니다. &quot;구독 취소 가능성&quot;, &quot;프로그램 멤버 유사&quot; 및 &quot;스마트 목록 멤버 유사&quot;는 모든 프로그램 유형에서 사용할 수 있습니다.

## 참석 가능성 {#likelihood-to-attend}

이 필터는 대상자의 범위를 효과적으로 좁히는 데 사용됩니다. 이렇게 하면 웨비나 이벤트에 **참석**&#x200B;할 가능성이 더 높은 잠재 고객을 타겟팅하고 초대할 수 있습니다. 귀하의 &quot;프로그램에 참석할 가능성&quot;은 귀하의 현재 이벤트 프로그램입니다.

![이미지 2](assets/predictive-filters-2.png)

## 등록 가능성 {#likelihood-to-register}

_참석할 가능성_ 필터와 마찬가지로 이 필터를 사용하여 웨비나 또는 이벤트에 대해 **등록**&#x200B;할 가능성이 더 높은 대상 및 잠재 고객을 좁힐 수 있습니다.

![이미지 3](assets/predictive-filters-3.png)

## 구독 취소 가능성 {#likelihood-to-unsubscribe}

이렇게 하면 다음 2주 동안 구독을 취소할 가능성이 높은지 또는 낮은지로 대상이 필터링됩니다. 이를 사용하여 피로도 리드가 높은 리드를 다르게 더 효과적으로 타깃팅할 수 있습니다. 구독 취소 임계값은 데이터베이스의 리드 타임 및 리드 활동을 포함한 여러 속성을 고려하는 AI 모델에 의해 동적으로 결정됩니다.

![이미지 4](assets/predictive-filters-4.png)

>[!NOTE]
>
>참석/등록/구독 취소 필터는 다른 표준 필터와 함께 사용해야 합니다.

## 프로그램 멤버 유사/스마트 목록 멤버 유사 {#lookalike-of-members}

이 두 필터는 다른 프로그램 또는 Smart List의 멤버와 유사한 추가 리드를 타겟팅하여 현재 대상을 확장하는 데 도움이 됩니다. 유사 항목 필터는 잠재 고객 속성, 이메일 활동, 웹 활동 및 참여를 포함한 50개 이상의 요인을 고려합니다.

**[!UICONTROL Add Constraint]**&#x200B;을(를) 클릭하여 선택한 프로그램의 구성원에 대한 성공 기준을 선택합니다.

여러 프로그램/스마트 목록을 하나의 필터에 쉽게 추가하려면 **+** 아이콘을 클릭하십시오.

![이미지 5](assets/predictive-filters-5.png)

## 참고할 사항 {#things-to-note}

* 예측 필터가 활성화되기 전에 상위 프로그램이 만들어지는 경우에도 예측 필터를 스마트 캠페인에 적용할 수 있습니다.
* 예측 필터는 트리거 캠페인에 사용할 수 없습니다.
* 예측 필터가 포함된 캠페인을 복제하거나 이동할 수 없습니다.
* 스마트 목록에서 최대 5개의 예측 필터를 사용할 수 있습니다.
* Marketo Engage에서 예측 필터 평가에 오류가 발생하면 캠페인 실행이 자동으로 중단되고 Marketo 알림 센터에서 알림을 받게 됩니다.
* 예측 필터에는 현재 100만 명의 자격이 있는 사람의 입력 제한이 있습니다.
* 예측 필터가 있는 활성 프로그램을 최대 50개까지 가질 수 있습니다.

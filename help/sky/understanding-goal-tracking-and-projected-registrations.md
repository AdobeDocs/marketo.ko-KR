---
title: 목표 추적 및 예상 등록 이해
description: 목표 추적 및 예상 등록 이해
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '969'
ht-degree: 0%

---


# 목표 추적 및 예상 등록 이해

<br> 

이벤트 [목표를](/help/sky/setting-event-goals.md)설정하고 [스마트한 캠페인](/help/sky/create-a-smart-campaign.md)을 통해 초대장을 보낸 후 목표 진행 상황을 추적하고 Marketing의 예측을 이해하는 방법을 소개합니다.

>[!NOTE]
>
>Marketing To Classic 경험에 이벤트 프로그램이 만들어지면 현재 이벤트 시작 날짜는 이벤트 생성 날짜로 설정됩니다. 예상 등록은 이벤트 시작 날짜 전 시간을 고려하므로 시작 날짜 및 생성 날짜가 동일한 경우(의도적으로 설정하지 않은 경우) 이러한 수가 정확하지 않을 수 있습니다.

## 목표 추적 및 예상 등록

1. 이벤트 프로그램의 **[!UICONTROL Reports]** 탭에서 목표 추적 세부 사항을 확인할 수 있습니다. 이 특정 예에서는 지금까지 200(75%)의 목표에 반해서 150명의 등록된 구성원이 있습니다.

   ![이미지 원](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-1.png)

등록도 **[!UICONTROL Projected]** 표시됩니다. 정보 아이콘 위로 마우스를 가져가면 이 수의 분류가 Adobe Target 세그먼트별로 표시됩니다.

![이미지 2](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-2.png)

>[!NOTE]
>
>[참석자] 및 [상위] 차트는 이벤트 날짜까지 비어 있게 됩니다.

1. 등록 가능성으로 멤버 분류로 전환하려면 차트 토글을 클릭합니다. 이전 프로그램에서 해당 세그먼트의 평균 비율과 비교하여 각 세그먼트에 대한 현재 등록 비율이 표시됩니다.

   ![이미지 3](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-3.png)

모든 구성원(등록했지만 아직 등록되지 않음)은 등록 가능성에 따라 분류됩니다. 정보 아이콘 위로 마우스를 가져가면 이러한 가능성 카테고리가 정의된 방식을 확인할 수 있습니다.

![이미지 4](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-4.png)

>[!NOTE]
>
>예측 번호는 이벤트 날짜까지 24시간마다 업데이트됩니다. 처리(Processing)_로_&#x200B;나열된 모든 구성원은 다음 계산 주기에 포함됩니다.

## 유사 프로그램

과거에 얼마나 유사한 프로그램이 수행되었는지를 확인하여 현재 이벤트에 대한 인사이트를 얻을 수 있습니다. 이 섹션에서는 지난 6개월 동안 등록한 구성원 수/백분율과 함께 최대 5개의 유사한 프로그램을&#x200B;_보여_ 줍니다.

유사한 프로그램을 계산할 때 다음과 같은 요소가 포함됩니다.

* 프로그램 유형
* 프로그램 채널
* 고객 규모
* 프로그램 태그
* 이벤트 생성에서 이벤트 시작까지의 기간
* 이벤트 기간

   ![이미지 5](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-5.png)

## Recommendations

보고서 페이지 상단에서 진행 상황을 기준으로 AI/ML 기반 권장 사항을 찾을 수 있습니다. 유용한 팁과 인사이트를 정기적으로 확인하시기 바랍니다.

![이미지 6](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-6.png)

## 개인 수준 예측

모든 프로그램 구성원을 보려면&#x200B;**[!UICONTROL Members]** 탭을 클릭합니다. 비율을 정확히 **[!UICONTROL Registration Likelihood]** 표시하거나 **[!UICONTROL Attendance Likelihood]** 범주를 마우스로 가리켜서 분류할 수 있습니다. 그런 다음 특정 카테고리(예: &quot;가능성이 적은&quot; 모든 구성원이 카테고리를 등록하도록 함)의 멤버에 대해 조치를 취하여 특정 멤버를 타깃팅하여 잠재적으로 등록 번호를 높일 수 있습니다.

![이미지 7](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-7.png)

>[!NOTE]
>
>개별 가능성은 프로필 속성, 개인 활동, 과거 초대된/등록/참석 활동 등 40명 이상의 개인 요소를 고려합니다.

## FAQ

**Q:세그먼트가 무엇입니까?**

A:등록할 가능성이 있는 값은 0부터 100까지입니다. 이벤트 프로그램의 멤버라면 0에서 100 사이의 가능성 값을 받게 됩니다.

가능성 값을 세 개의 세그먼트에 넣습니다.

* 등록 가능성 > 50% = 매우 가능성 있는 세그먼트
* 등록 가능성: 25% ~ &lt;50% = 가능한 세그먼트
* 등록 가능성: &lt;25% = 가능성이 낮은 세그먼트

한 사람이 등록 가능성을 갖게 되면 이러한 세그먼트 중 하나에 예측이 몰릴 것입니다(프로그램 회원이 된 모든 사람은 해당 세그먼트 중 하나에 속하게 됩니다). 예를 들어, 이벤트 프로그램에 예측 기준으로 1000명의 구성원이 있는 경우, 이러한 1000명이 _가능성이 높은_&#x200B;세그먼트, _가능성이_&#x200B;낮은 _세그먼트_ 로배포됩니다.

따라서 가능성이 높은 세그먼트에 속하는 사람은 이벤트에 등록할 가능성이 높습니다.

등록으로의 전환 = 세그먼트에 속하는 사용자 수로 등록된 세그먼트의 사람 수(예: 100명이 매우 가능성이 높은 세그먼트에 속해 있고 60명이 등록한 경우 전환율은 60%).

등록할 전환 비율은 다음 패턴을 따릅니다.가능성이 높은 > 가능성 > 가능성이 낮음.

**Q:인사이트를 사용하는 방법**

A:모범 사례에는 다음이 포함됩니다.

i.프로그램을 만든 다음 스마트 캠페인이 &quot;X보다 큼&quot;이 있는 예측 필터를 사용하여 일정 인원(예: 1000명)이 발생하고 캠페인을 실행합니다.

ii. 24시간 후 [!UICONTROL Reports] 탭에서 현재 초대된 모든 사람의 값을 등록할 수 있는 가능성을 기준으로 계산된 예상 등록을 볼 수 있습니다.

iii. 예상 등록이 목표보다 적은 경우 더 많은 사람을 초대해야 합니다. 이 시점에서, 여러분은 과거의 프로그램에서 작동하는 한계점이 무엇인지 알려주는 통찰력을 볼 수 있습니다.

![이미지 8](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-8.png)

iv. 해당 임계값을 사용하여 더 많은 사람을 초대하는 새 스마트 캠페인을 만들 수 있습니다.

v. 예상 숫자가 표시되는 이유를 이해하려는 경우 언제든지 전환하여 세그먼트 간 대상 분포, 과거 전환 비율을 확인하고 현재 대상자에게 해당 전환율을 적용할 수 있습니다(아래 스크린샷 참조).

**Q:등록별 세그먼트 그래프는 무엇입니까?**

A:세 개의 막대가 있으며 각 막대는 세그먼트를 나타냅니다(가능성이 높고 가능성이 낮음).

**자주색 점선:** 과거 유사한 프로그램을 기준으로 해당 세그먼트에서 등록하기 위한 평균 대화율입니다.

**파란색 막대:** 해당 세그먼트에 있는 모든 사람의 등록 백분율입니다.

![이미지 9](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-9.png)

예를 들어 등록된 100명 중 50% 이상, 60명이 등록할 가능성이 있다고 가정해 봅시다. 전환 가능성이 높은 경우 따라서 프로그램에 추가된 모든 구성원은 값을 등록할 가능성을 얻게 되면 세그먼트에 삽입되고 각 세그먼트 전환율에 등록된 사람의 수에 따라 계산됩니다.

**Q:&quot;등록 및 이상&quot;이란 무엇을 의미합니까?**

A:등록됨으로 나열된 사람 또는 같은 단계 또는 더 높은 상태의 모든 사람.

이벤트 프로그램에 대해 새 진행 상태를 만들 수 있지만 표준 상태에 해당 상태를 매핑할 수 있습니다. 초대받은 사람을 다시 상기하도록 이동하는 경우 등록보다 높은 단계를 고려합니다. 이 사람도 등록으로 간주되어 목표 추적에 표시됩니다.

![이미지 10](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-10.png)

**Q:예상 등록은 어떻게 계산됩니까?**

A:아래를 참조하십시오.

![이미지 일레븐](/help/sky/assets/predictive-audiences/understanding-goal-tracking-and-projected-registrations/understanding-goal-tracking-and-projected-registrations-11.png)

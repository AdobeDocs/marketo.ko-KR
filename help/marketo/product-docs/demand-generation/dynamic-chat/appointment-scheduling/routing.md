---
description: 라우팅 - Marketo 문서 - 제품 설명서
title: 라우팅
hide: true
hidefromtoc: true
source-git-commit: 0ca537b46247eef1e7200180d7c1516465910dac
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 1%

---

# 라우팅 {#routing}

Dynamic Chat에서 예약된 모임을 두 가지 방법으로 라우팅할 수 있습니다. 라운드 로빈 또는 사용자 지정 규칙을 사용합니다.

라운드 로빈: 모임이 순차적으로 에이전트에 할당됩니다. 그래서 당신이 5명의 에이전트들과 3명의 요원이 마지막 회의를 가졌다면, 4명의 요원은 다음 1명을 얻고, 그 다음에 5명의 요원을 차례로 얻고, 그리고 나서 1의 에이전트로 돌아갑니다.

사용자 지정 규칙: 선택한 특성에 따라 모임을 수신할 특정 에이전트를 선택할 수 있습니다.

## 사용자 지정 규칙 만들기 {#create-a-custom-rule}

이 예에서는 CA, OR의 추론된 상태에서 John 요원에게 모든 모임을 보내고 있습니다.

1. Dynamic Chat에서 **라우팅**.

   ![](assets/routing-1.png)

1. 을(를) 클릭합니다. **사용자 지정 규칙** 탭.

   ![](assets/routing-2.png)

1. 클릭 **규칙 만들기**.

   ![](assets/routing-3.png)

1. 규칙에 이름을 지정하고 **다음**.

   ![](assets/routing-4.png)

1. 원하는 에이전트를 선택합니다.

   ![](assets/routing-5.png)

1. 원하는 속성 위로 드래그합니다.

   ![](assets/routing-6.png)

1. 원하는 값을 찾아 선택합니다.

   ![](assets/routing-7.png)

1. 원하는 값을 모두 선택한 경우 **저장**.

   ![](assets/routing-8.png)

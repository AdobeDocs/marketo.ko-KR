---
description: 라우팅 - Marketo 문서 - 제품 설명서
title: 라우팅
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: ea9e02d9ad52991757f137c7c2b549b98f139ba5
workflow-type: tm+mt
source-wordcount: '148'
ht-degree: 1%

---

# 라우팅 {#routing}

Dynamic Chat에서 예약된 회의는 두 가지 방법으로 라우팅될 수 있습니다. 라운드 로빈 또는 사용자 지정 규칙 사용.

라운드 로빈: 모임이 에이전트에 순차적으로 할당됩니다. 그래서 당신이 5명의 요원들과 3번 요원이 마지막 회의를 가졌다면, 4번 요원이 다음 회의를 가질 것이고, 5번 요원이 그 후에 1번 요원으로 돌아갈 것입니다.

사용자 지정 규칙: 선택한 속성에 따라 회의를 수신할 특정 에이전트를 선택할 수 있습니다.

## 사용자 지정 규칙 만들기 {#create-a-custom-rule}

이 예에서는 유추한 CA, OR 및 WA 상태의 모든 회의를 John 에이전트에게 보냅니다.

1. Dynamic Chat에서 **라우팅**.

   ![](assets/routing-1.png)

1. 다음을 클릭합니다. **사용자 지정 규칙** 탭.

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
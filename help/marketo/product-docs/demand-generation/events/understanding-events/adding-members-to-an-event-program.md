---
unique-page-id: 37355758
description: 이벤트 프로그램에 멤버 추가 - Marketo 문서 - 제품 설명서
title: 이벤트 프로그램에 멤버 추가
exl-id: 05bd4807-3ab8-452d-a389-b22477cf7445
feature: Events
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '177'
ht-degree: 0%

---

# 이벤트 프로그램에 멤버 추가 {#adding-members-to-an-event-program}

이 문서는 이벤트 상한 또는 이벤트 목표를 활용하는 사용자에게만 적용됩니다.

>[!CAUTION]
>
>사용자 목록을 이벤트 프로그램으로 직접 가져오면 해당 레코드가 목표 추적 보고서와 이벤트 상한 진행률 보고서의 실제 등록에서 계산되지 않습니다. 아래 지침에 따라 기록이 계산되는지 확인합니다.

1. 만들기 및 [정적 목록에 사람 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/create-a-static-list.md).

1. [스마트 캠페인 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

1. 2단계에서 만든 스마트 캠페인의 스마트 목록에서 를 찾아 추가합니다. **목록 구성원** 필터.

   ![](assets/three.png)

1. 1단계에서 생성한 목록을 찾아 선택합니다.

   ![](assets/four.png)

1. 플로우에서 를 찾아 추가합니다. **프로그램 상태 변경** 흐름 단계.

   ![](assets/five.png)

1. 이벤트 프로그램을 찾아 선택합니다.

   ![](assets/six.png)

1. 원하는 상태를 선택합니다.

   ![](assets/seven.png)

1. 예약 탭에서 다음을 클릭합니다. **한 번 실행**.

   ![](assets/eight.png)

1. 선택 **지금 실행** 및 클릭 **실행**.

   ![](assets/nine.png)

1. 스마트 캠페인이 실행되면 멤버가 프로그램에 추가되고, 목표 추적 및 이벤트 상한 진행률 계산에 포함됩니다.

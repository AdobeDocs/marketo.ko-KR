---
unique-page-id: 2359947
description: 참여 스트림 간 사람 전환 - Marketo 문서 - 제품 설명서
title: 참여 스트림 간 사람 전환
exl-id: 2367852c-3dcf-4188-a50c-7c6f0b0ff7bc
feature: Engagement Programs
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 0%

---

# 참여 스트림 간 사람 전환 {#transition-people-between-engagement-streams}

참여 프로그램에는 두 개 이상의 스트림이 있을 수 있습니다. [스트림을 추가](/help/marketo/product-docs/email-marketing/drip-nurturing/creating-an-engagement-program/add-a-stream.md)하면 사람들이 한 스트림에서 다른 스트림으로 이동하는 방법을 정의하게 됩니다. 이를 **전환 규칙**&#x200B;이라고 합니다.

1. **마케팅 활동**(으)로 이동합니다.

   ![](assets/ma.png)

1. 멀티스트리밍된 참여 프로그램을 선택하고 **Streams**(으)로 이동합니다.

   ![](assets/multistream.jpg)

1. 다른 스트림에서 가져올 스트림에 대해 **전환 규칙**&#x200B;을 클릭한 다음 **전환 규칙 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-15-18-3a10-3a18.png)

   >[!NOTE]
   >
   >전환 규칙은 스트림으로 가져옵니다. 항상 가져올 스트림에 규칙을 정의합니다.

   전환 규칙 창이 열리면 선택한 트리거를 찾아 드래그합니다. 이 경우 기회가 추가되면 사람들을 중간 단계로 이동하려고 합니다.

   ![](assets/image2014-9-15-18-3a10-3a46.png)

1. 추가된 기회에 대해 사람들이 이동할 수 있도록 연산자를 **is any**(으)로 설정해 보겠습니다.

   ![](assets/image2014-9-15-18-3a11-3a14.png)

   >[!TIP]
   >
   >전환 규칙에 여러 트리거와 필터를 추가할 수 있지만 전환 규칙에서는 모든 필터를 사용합니다(모든 필터를 사용하는 것이 유일한 옵션). 전환 규칙에서 OR을 사용해야 하는 경우 대신 외부 스마트 캠페인을 설정하는 것이 좋습니다.

1. Click **Close**.

   ![](assets/image2014-9-15-18-3a11-3a23.png)

   잘됐네! 이제 참여 프로그램에서 영업 기회에 추가된 모든 사람이 중간 단계 스트림으로 이동됩니다.

   ![](assets/image2014-9-15-18-3a11-3a29.png)

   >[!NOTE]
   >
   >*do* 위에 설명된 단계는 [일시 중지](/help/marketo/product-docs/email-marketing/drip-nurturing/using-engagement-programs/pause-people-in-an-engagement-program.md)를 사용하는 사용자에게도 적용됩니다.

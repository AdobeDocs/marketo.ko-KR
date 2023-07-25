---
unique-page-id: 9438139
description: 개인 차단 목록에 추가하다 추가 - Marketo 문서 - 제품 설명서
title: 차단 목록에 추가하다 Person 추가
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---

# 차단 목록에 추가하다 Person 추가 {#add-person-to-blocklist}

차단 목록에 사람들을 추가하면 그들은 당신의 서신을 받지 못하게 됩니다.

>[!NOTE]
>
>Marketo은 우리 제품의 블랙리스트 및 허용 목록에 추가하다와 차단 목록에 추가하다에 대한 화이트 리스트 등의 용어를 변경 중입니다. 이 업데이트 중에 UI 및 설명서 스크린샷에서 이전 용어를 보고 설명서 텍스트에서 새 용어를 볼 수 있습니다. 착오가 있었다면 죄송합니다.

1. [새 기본 프로그램 만들기](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) 이름을 지정합니다. **차단 목록에 추가하다 추가**.

1. 클릭 **신규** 및 선택 **새 로컬 자산**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. 목록 이름을 지정하고 **만들기**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. 모든 사용자를 다음에 추가 **스마트 목록** 차단 목록에 추가하다에 추가하려는 경우

   >[!NOTE]
   >
   >차단 목록 중인 사용자는 운영 이메일을 받지 않습니다.

   ![](assets/three-6.png)

1. 클릭 **신규** 및 선택 **새 스마트 캠페인**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. 이름 지정 **새 스마트 캠페인**. Click **Create**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. 드래그 앤 드롭 **스마트 목록의 구성원**.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. 방금 만든 스마트 목록을 선택합니다.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. 드래그 앤 드롭 **데이터 값 변경**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. 의 경우 **플로우**, 입력 **차단 목록** 대상: **속성** 및 설정 **새 값** 끝 **true**.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. 다음에서 **예약** 탭, 선택 **한 번 실행**.

   ![](assets/ten.png)

1. 선택 **지금 실행** 및 클릭 **실행**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   예이! 이러한 사용자는 더 이상 이메일을 받지 않습니다.

   >[!TIP]
   >
   >만들기 [스마트 캠페인 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) 사용 **데이터 값 변경** 포함 **나열된 블록이 true입니다.** 미래의 모든 사람들은 차단 목록에 추가하다가 가능한 속성을 가지고 있습니다.

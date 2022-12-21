---
unique-page-id: 9438139
description: 개인 추가 차단 목록에 추가하다 - Marketo 문서 - 제품 설명서
title: 에 차단 목록에 추가하다 개인 추가
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '216'
ht-degree: 0%

---

# 에 차단 목록에 추가하다 개인 추가 {#add-person-to-blocklist}

사용자를에 차단 목록에 추가하다 추가하면 해당 사용자가 서신을 수신하지 못합니다.

>[!NOTE]
>
>Marketo은 블랙리스트 및 화이트리스트와 같은 용어를 Adobe 제품차단 목록에 추가하다의 및 허용 목록에 추가하다 게시로 변경하는 중입니다. 이 업데이트 중에 UI 및 설명서 스크린샷에 이전 용어가 표시되고 설명서 텍스트에 새 용어가 표시될 수 있습니다. 혼동을 사과드립니다

1. [새 기본 프로그램 만들기](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) 이름을 지정합니다 **에 차단 목록에 추가하다 추가**.

1. 클릭 **새로 만들기** 을(를) 선택합니다. **새 로컬 자산**.

   ![](assets/image2015-8-14-11-3a0-3a46.png)

1. 목록에 이름을 지정하고 을(를) 클릭합니다 **만들기**.

   ![](assets/image2015-8-14-11-3a2-3a26.png)

1. 모든 사용자를 **Smart List** 을에 차단 목록에 추가하다 추가하려는 경우

   >[!NOTE]
   >
   >에 차단 목록에 추가하다 있는 사람은 운영 이메일을 받지 않습니다.

   ![](assets/three-6.png)

1. 클릭 **새로 만들기** 을(를) 선택합니다. **새로운 스마트 캠페인**.

   ![](assets/image2015-8-14-11-3a12-3a35.png)

1. 이름을 로 지정합니다 **새로운 스마트 캠페인**. Click **Create**.

   ![](assets/image2015-8-14-11-3a13-3a36.png)

1. 드래그 앤 드롭 **스마트 목록의 구성원**.

   ![](assets/image2015-8-14-11-3a16-3a34.png)

1. 방금 만든 스마트 목록을 선택합니다.

   ![](assets/image2015-8-14-11-3a17-3a5.png)

1. 드래그 앤 드롭 **데이터 값 변경**.

   ![](assets/image2015-8-14-11-3a18-3a41.png)

1. 대상 **흐름**, 입력 **나열된 블록** 대상 **속성** 및 설정 **새 값** to **true**.

   ![](assets/image2015-8-14-11-3a21-3a1.png)

1. 설정 **예약** 탭, 선택 **한 번 실행**.

   ![](assets/ten.png)

1. 선택 **지금 실행** 을(를) 클릭합니다. **실행**.

   ![](assets/image2015-8-14-11-3a24-3a50.png)

   예이! 이 사람들은 더 이상 이메일을 받지 않습니다.

   >[!TIP]
   >
   >만들기 [스마트 캠페인 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) 사용 **데이터 값 변경** with **나열된 블록이 true입니다.** 가능 속성을 가진 차단 목록에 추가하다 모든 사람에게 적용됩니다.

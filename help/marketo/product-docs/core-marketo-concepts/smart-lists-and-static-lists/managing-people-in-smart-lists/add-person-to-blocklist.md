---
unique-page-id: 9438139
description: 개인 차단 목록에 추가하다 추가 - Marketo 문서 - 제품 설명서
title: 차단 목록에 추가하다 Person 추가
exl-id: e4543bf9-11e9-42df-a31e-e2cebe24ad4a
feature: Smart Lists
source-git-commit: cc87ecb8d3245734ec0ce984eeccf742833a85d2
workflow-type: tm+mt
source-wordcount: '184'
ht-degree: 1%

---

# 차단 목록에 추가하다 Person 추가 {#add-person-to-blocklist}

차단 목록에 사람들을 추가하면 그들은 당신의 서신을 받지 못하게 됩니다.

1. [새 기본 프로그램 만들기](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/create-a-program.md) 이름을 지정합니다. **차단 목록에 추가하다 추가**.

1. 클릭 **신규** 및 선택 **새 로컬 자산**.

   ![](assets/add-person-to-blocklist-1.png)

1. 선택 **스마트 목록**.

   ![](assets/add-person-to-blocklist-2.png)

1. 목록 이름을 지정하고 **만들기**.

   ![](assets/add-person-to-blocklist-3.png)

1. 모든 사용자를 다음에 추가 **스마트 목록** 차단 목록에 추가하다에 추가하려는 경우

   ![](assets/add-person-to-blocklist-4.png)

   >[!NOTE]
   >
   >차단 목록 중인 사용자는 운영 이메일을 받지 않습니다.

1. 프로그램으로 돌아갑니다.

   ![](assets/add-person-to-blocklist-5.png)

1. 클릭 **신규** 및 선택 **새 스마트 캠페인**.

   ![](assets/add-person-to-blocklist-6.png)

1. 이름 지정 **새 스마트 캠페인**. Click **Create**.

   ![](assets/add-person-to-blocklist-7.png)

1. 드래그 앤 드롭 **스마트 목록의 구성원**.

   ![](assets/add-person-to-blocklist-8.png)

1. 방금 만든 스마트 목록을 선택합니다.

   ![](assets/add-person-to-blocklist-9.png)

1. 다음을 클릭합니다. **플로우** 탭. 을(를) 끌어다 놓습니다. **데이터 값 변경** 흐름 작업.

   ![](assets/add-person-to-blocklist-10.png)

1. 다음에서 **속성** 드롭다운 선택 **차단 목록** 및 설정 **새 값** 끝 **true**.

   ![](assets/add-person-to-blocklist-11.png)

1. 다음을 클릭합니다. **예약** 탭하고 선택 **한 번 실행**.

   ![](assets/add-person-to-blocklist-12.png)

1. 선택 **지금 실행** 및 클릭 **실행**.

   ![](assets/add-person-to-blocklist-13.png)

1. 클릭 **실행** 다시.

   ![](assets/add-person-to-blocklist-14.png)

이러한 사용자는 더 이상 이메일을 받지 않습니다.

>[!TIP]
>
>만들기 [스마트 캠페인 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md) 사용 **데이터 값 변경** 포함 **나열된 블록이 true입니다.** 미래의 모든 사람들은 차단 목록에 추가하다가 가능한 속성을 가지고 있습니다.

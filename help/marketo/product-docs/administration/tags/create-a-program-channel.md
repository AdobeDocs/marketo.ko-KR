---
unique-page-id: 2950682
description: 프로그램 채널 만들기 - Marketo 문서 - 제품 설명서
title: 프로그램 채널 만들기
exl-id: 7b4e15db-c221-45a9-9588-99eb2510cde7
feature: Tags
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '428'
ht-degree: 0%

---

# 프로그램 채널 만들기 {#create-a-program-channel}

프로그램은 하나의 특정 마케팅 이니셔티브입니다. 이 채널은 웨비나 후원 또는 온라인 광고와 같은 게재 메커니즘으로 설계되었습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>자세히 알아보기 [프로그램](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md): Marketo에서 가장 중요한 요소입니다.

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/create-a-program-channel-1.png)

1. 클릭 **[!UICONTROL 태그]**.

   ![](assets/create-a-program-channel-2.png)

   >[!NOTE]
   >
   >태그를 사용해야 하는 이유 채널은 다른 태그와 마찬가지로 프로그램을 설명하는 방법입니다. 이 채널에는 특별한 기능이 있습니다.

1. 다음을 클릭합니다. **+** 다음 옆에 서명 [!UICONTROL 채널] 기존 채널을 확장하여 봅니다.

   ![](assets/create-a-program-channel-3.png)

1. 아래 **[!UICONTROL 신규]**, 클릭 **[!UICONTROL 새 채널]**.

   ![](assets/create-a-program-channel-4.png)

   >[!NOTE]
   >
   >**예**
   >
   >채널: 빌보드
   >
   >* 적용 대상: 기본값
   >* 진행: 멤버, 참여(확실하지 않은 경우 제대로 작동함)
   >* 성공: 참여
   >
   >채널: 파티
   >
   >* 적용 대상: 이벤트
   >* 진행: 초대됨, 등록됨, 표시 없음 및 참석됨
   >* 성공: 출석함
   >
   >기존 채널의 진행 상황을 확인하여 사용 방법에 대한 아이디어를 얻을 수 있습니다.

1. 파티 채널 예를 살펴보겠습니다. 새 이름 지정 **채널** 적용할 프로그램 유형을 선택합니다.

   ![](assets/create-a-program-channel-5.png)

   >[!NOTE]
   >
   >무엇을 적용하시겠습니까? 프로그램에는 몇 가지 유형이 있습니다. 채널을 적절한 유형에 일치시키십시오. 확실하지 않은 경우 다음을 선택하십시오. **[!UICONTROL 기본값]**.

   >[!NOTE]
   >
   >사용 시[!UICONTROL 웨비나를 사용하는 이벤트],&quot; 시스템 매핑은 웨비나 통합에 필요한 경우 잠기고 편집할 수 없습니다.

1. 처음 두 프로그램의 상태 이름을 입력한 다음 **[!UICONTROL 단계 추가]**.

   ![](assets/create-a-program-channel-6.png)

1. 다른 프로그램 입력 **[!UICONTROL 상태]** 및 **[!UICONTROL 단계]** 번호를 누른 후 클릭 **[!UICONTROL 단계 추가]**.

   ![](assets/create-a-program-channel-7.png)

   >[!TIP]
   >
   >다음 **[!UICONTROL 단계]** number 는 프로그램 상태를 정렬하는 데 사용됩니다. 이러한 진행 단계에서 사람들이 뒤로 갈 수 없다는 점을 명심하십시오. 상태를 더 높거나 동일한 값 상태로만 변경할 수 있습니다. 상태가 진행이 아니라 앞뒤로 전환되어야 하는 경우 동일한 값을 사용합니다.

1. 마지막 프로그램 입력 **[!UICONTROL 상태]** 및 **[!UICONTROL 단계]** 숫자.

   ![](assets/create-a-program-channel-8.png)

   >[!NOTE]
   >
   >유형 사용 시[!UICONTROL 이벤트]등록됨, 대기자 명단 등록됨 및 참석됨 상태에 대한 &quot; 시스템 매핑이 필요합니다. 따라서 이러한 상태는 숨길 수 없습니다.

1. 을(를) 선택합니다 **[!UICONTROL 모바일 체크인 상태]** 대상 **[!UICONTROL 등록됨]**.

   ![](assets/create-a-program-channel-9.png)

1. 을(를) 선택합니다 **[!UICONTROL 모바일 체크인 상태]** 대상 **[!UICONTROL 출석함]**.

   ![](assets/create-a-program-channel-10.png)

   >[!NOTE]
   >
   >**[!UICONTROL 모바일 체크인 상태]** 옵션은 이벤트 프로그램에 채널이 사용되는 경우에만 사용할 수 있습니다.

   >[!NOTE]
   >
   >이(가) 있는 사용자만 **[!UICONTROL 모바일 체크인 상태]** / **[!UICONTROL 등록됨]** 및 **[!UICONTROL 출석함]** 다음에서 볼 수 있습니다. [모바일 체크인 앱](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/event-check-in-overview.md).

   >[!TIP]
   >
   >모바일 체크인 앱에서 새로운 인물을 생성하면 이벤트 프로그램에서 등록됨으로 설정됩니다. 앱에서 이벤트에 체크 인된 경우 이벤트 프로그램에서 참석으로 설정됩니다.

1. 다음 항목 선택 **[!UICONTROL 성공]** 프로그램 상태를 확인한 다음 **[!UICONTROL 만들기]**.

   ![](assets/create-a-program-channel-11.png)

   잘했어! 해당 유형의 새 프로그램을 만들 때 이 새 채널이 선택 사항 중 하나가 됩니다.

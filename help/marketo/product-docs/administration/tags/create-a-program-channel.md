---
unique-page-id: 2950682
description: 프로그램 유형, 성공 상태 및 이벤트에 대한 모바일 체크인 옵션을 포함하여 상태 및 진행 단계로 프로그램 채널을 만드는 단계입니다.
title: 프로그램 채널 만들기
exl-id: 7b4e15db-c221-45a9-9588-99eb2510cde7
feature: Tags
TQID: https://experienceleague.adobe.com/Ficlv7OfEScqLRVbOfc2hc-S3cQ2YjriiKWnbS1Op9A
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
subfeature_v2:
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 390
ht-degree: 4%

---

# 프로그램 채널 만들기 {#create-a-program-channel}

프로그램은 하나의 특정 마케팅 이니셔티브입니다. 이 채널은 웨비나 후원 또는 온라인 광고와 같은 게재 메커니즘으로 설계되었습니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!NOTE]
>
>Marketo에서 가장 중요한 요소인 [프로그램](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)에 대해 자세히 알아보세요.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/create-a-program-channel-1.png)

1. **[!UICONTROL Tags]**&#x200B;를 클릭합니다.

   ![](assets/create-a-program-channel-2.png)

   >[!NOTE]
   >
   >태그를 사용해야 하는 이유 채널은 다른 태그와 마찬가지로 프로그램을 설명하는 방법입니다. 이 채널에는 특별한 추가 기능이 있습니다.

1. [!UICONTROL Channel] 옆에 있는 **+** 기호를 클릭하여 확장하고 기존 채널을 확인합니다.

   ![](assets/create-a-program-channel-3.png)

1. **[!UICONTROL New]**&#x200B;에서 **[!UICONTROL New Channel]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-program-channel-4.png)

   >[!NOTE]
   >
   >**예**
   >
   >채널: 빌보드
   >
   >* 적용 대상: 기본값
   >* 승급: 멤버, 참여(적합한 기본값)
   >* 성공: 참여
   >
   >채널: 파티
   >
   >* 적용 대상: 이벤트
   >* 진행: 초대됨, 등록됨, 표시 없음 및 참석됨
   >* 성공: 출석함
   >
   >기존 채널의 진행 상황을 검토하여 사용 방법에 대한 지침을 확인하십시오.

1. 파티 채널을 예로 들면 새 **[!UICONTROL Channel]**&#x200B;의 이름을 지정하고 적용할 프로그램 유형을 선택하십시오.

   ![](assets/create-a-program-channel-5.png)

   >[!NOTE]
   >
   >프로그램에는 몇 가지 유형이 있습니다. 채널을 적절한 유형에 일치시키십시오. 확실하지 않은 경우 **[!UICONTROL Default]**&#x200B;을(를) 선택하십시오.

   >[!NOTE]
   >
   >&quot;[!UICONTROL Event with Webinar]&quot;을(를) 사용하는 경우 시스템 매핑이 잠기고(웨비나 통합에 필요한 경우) 편집할 수 없습니다.

1. 처음 두 프로그램 상태 이름을 입력한 다음 **[!UICONTROL Add Step]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-program-channel-6.png)

1. 다른 프로그램 **[!UICONTROL Status]** 및 **[!UICONTROL Step]** 번호를 입력한 다음 **[!UICONTROL Add Step]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-program-channel-7.png)

   >[!TIP]
   >
   >**[!UICONTROL Step]** 숫자는 프로그램 상태를 정렬하는 데 사용됩니다. 이러한 진행 단계에서 뒤로 이동할 수 없습니다. 상태를 더 높거나 동일한 값 상태로만 변경할 수 있습니다. 상태가 진행이 아니라 앞뒤로 전환되어야 하는 경우 동일한 값을 사용합니다.

1. 마지막 프로그램 **[!UICONTROL Status]** 및 **[!UICONTROL Step]** 번호를 입력하십시오.

   ![](assets/create-a-program-channel-8.png)

   >[!NOTE]
   >
   >&quot;[!UICONTROL Event]&quot; 유형을 사용하는 경우 등록됨, 대기자 명단 및 참석됨 상태에 대한 시스템 매핑이 필요합니다. 따라서 이러한 상태는 숨길 수 없습니다.

1. **[!UICONTROL Registered]**&#x200B;에 대해 **[!UICONTROL Mobile Check-in Status]**&#x200B;을(를) 선택하십시오.

   ![](assets/create-a-program-channel-9.png)

1. **[!UICONTROL Attended]**&#x200B;에 대해 **[!UICONTROL Mobile Check-in Status]**&#x200B;을(를) 선택하십시오.

   ![](assets/create-a-program-channel-10.png)

   >[!NOTE]
   >
   >이벤트 프로그램에 채널이 사용되는 경우에만 **[!UICONTROL Mobile Check-in Status]** 옵션을 사용할 수 있습니다.

   >[!NOTE]
   >
   >**[!UICONTROL Mobile Check-in Status]**/**[!UICONTROL Registered]** 및 **[!UICONTROL Attended]**&#x200B;을(를) 가진 사람만 [모바일 체크인 앱](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/event-check-in-overview.md)에 표시됩니다.

   >[!TIP]
   >
   >모바일 체크인 앱에서 새 사용자를 만들면 이벤트 프로그램에서 [!UICONTROL Registered]&#x200B;(으)로 설정됩니다. 사용자가 앱에서 이벤트에 체크 인되면 이벤트 프로그램에서 [!UICONTROL Attended]&#x200B;(으)로 설정됩니다.

1. **[!UICONTROL Success]** 프로그램 상태를 선택한 다음 **[!UICONTROL Create]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-a-program-channel-11.png)

   해당 유형의 새 프로그램을 만들 때 이 새 채널이 선택 사항 중 하나가 됩니다.

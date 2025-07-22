---
description: Adobe Experience Platform 세그먼트를 Marketo 정적 목록에 푸시 - Marketo 문서 - 제품 설명서
title: Adobe Experience Platform 세그먼트를 Marketo 정적 목록에 푸시
exl-id: 8df11bf4-06f4-4927-8dfb-954414fce6dc
feature: Static Lists
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '601'
ht-degree: 0%

---

# Adobe Experience Platform 세그먼트를 Marketo 정적 목록에 푸시 {#push-an-adobe-experience-platform-segment-to-a-marketo-static-list}

이 기능을 사용하면 Adobe Experience Platform에 있는 세그먼트를 정적 목록의 형태로 Marketo Engage에 푸시할 수 있습니다.

>[!PREREQUISITES]
>
>* [API 역할을 편집](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md#edit-an-existing-role){target="_blank"}하여 API 액세스 드롭다운에 있는 **사람 읽기-쓰기** 권한이 있는지 확인하세요.
>* Marketo에서 [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"}.
>* **[!UICONTROL Admin]** > **[!UICONTROL Launchpoint]**(으)로 이동합니다. 방금 만든 역할의 이름을 찾아 **[!UICONTROL View Details]**&#x200B;을(를) 클릭합니다. 7단계에 필요할 수 있으므로 **[!UICONTROL Client ID]** 및 **[!UICONTROL Client Secret]**&#x200B;의 정보를 복사하여 저장하십시오.
>* Marketo에서 정적 목록을 만들거나 이미 만든 목록을 찾아 선택합니다. 신분증이 필요합니다.

1. [Adobe Experience Platform](https://experience.adobe.com/){target="_blank"}에 로그인합니다.

   ![](assets/push-an-adobe-experience-platform-segment-1.png)

1. 격자 아이콘을 클릭하고 **[!UICONTROL Experience Platform]**&#x200B;을(를) 선택합니다.

   ![](assets/push-an-adobe-experience-platform-segment-2.png)

1. 왼쪽 탐색에서 **[!UICONTROL Destinations]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-3.png)

1. **[!UICONTROL Catalog]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-4.png)

1. Marketo Engage 타일을 찾아 **[!UICONTROL Activate]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-5.png)

1. **[!UICONTROL Configure New Destination]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-6.png)


1. [계정 유형]에서 [기존 계정] 또는 [새 계정] 라디오 단추를 선택합니다. 이 예제에서는 **[!UICONTROL Existing Account]**&#x200B;을(를) 선택합니다. 계정 선택 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-7.png)

   >[!NOTE]
   >
   >새 계정을 선택하는 경우 **[!UICONTROL Admin]** > **[!UICONTROL Munchkin]**(로그인한 후 Marketo URL의 일부임)로 이동하여 Munchkin ID를 찾을 수 있습니다. 이 문서의 맨 위에 있는 사전 요구 사항을 따르지 않을 클라이언트 ID/암호입니다.

1. 대상 계정을 선택하고 **[!UICONTROL Select]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-8.png)

1. 대상 **[!UICONTROL Name]** 및 선택적 설명을 입력하십시오. 개인 만들기 드롭다운을 클릭하고 &quot;기존 Marketo 사용자와 Marketo에서 누락된 사용자 만들기&quot; _또는_ &quot;기존 Marketo 사용자에게만 일치&quot;를 선택합니다(이 예제에서는 전자를 선택함). **[!UICONTROL Workspace]**&#x200B;도 선택해야 합니다.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

   >[!NOTE]
   >
   >&quot;[!UICONTROL Match Existing Marketo People Only]&quot;을(를) 선택하는 경우 전자 메일 및/또는 ECID만 매핑하면 되므로 13-16단계를 건너뛸 수 있습니다.

1. 이 섹션은 선택 사항입니다. 건너뛰려면 **[!UICONTROL Create]**&#x200B;을(를) 클릭하십시오.

   ![](assets/push-an-adobe-experience-platform-segment-10.png)

1. 만든 대상을 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-11.png)

1. Marketo으로 보낼 세그먼트를 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-12.png)

   >[!NOTE]
   >
   >여러 세그먼트를 선택하는 경우 [!UICONTROL Segment Schedule] 탭에서 각 세그먼트를 지정된 정적 목록에 매핑해야 합니다.

   >[!IMPORTANT]
   >
   >세그먼트가 Marketo 대상에 처음 활성화되면 Marketo 대상을 활성화하기 전에 세그먼트에 이미 있는 프로필을 다시 채우는 데 _최대 24시간_&#x200B;이 걸릴 수 있습니다. 앞으로 프로필이 세그먼트에 추가될 때마다 Marketo에 즉시 추가됩니다.

1. **[!UICONTROL Add New Mapping]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-13.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-14.png)

1. 원하는 특성을 선택하고 **[!UICONTROL Select]**&#x200B;을(를) 클릭합니다. 이 예제에서는 이름, 성 및 이메일 주소를 선택합니다.

   ![](assets/push-an-adobe-experience-platform-segment-15.png)

   >[!NOTE]
   >
   >Experience Platform의 속성을 조직이 Marketo Engage에서 액세스할 수 있는 모든 속성에 매핑할 수 있습니다. [API 요청 설명](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/lead-database#describe){target="_blank"}을(를) 사용하여 조직에서 액세스할 수 있는 특성 필드를 검색합니다.

1. **[!UICONTROL Add New Mapping]**&#x200B;을(를) 다시 클릭하고 15단계를 두 번 반복하여 **[!UICONTROL lastName]**&#x200B;을(를) 선택한 다음 **[!UICONTROL companyName]**&#x200B;을(를) 선택하여 성 및 회사 이름을 매핑합니다.

   ![](assets/push-an-adobe-experience-platform-segment-16.png)

1. 이제 이메일 주소를 매핑할 차례입니다. **[!UICONTROL Add New Mapping]**&#x200B;을(를) 다시 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-17.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-18.png)

1. ID 네임스페이스 선택 라디오 단추를 클릭하고 **[!UICONTROL Email]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Select]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-19.png)

   >[!IMPORTANT]
   >
   >**[!UICONTROL Identity Namespace]** 탭의 전자 메일 및/또는 ECID 매핑은 해당 사용자가 Marketo에서 일치하는지 확인하기 위해 수행하는 가장 중요한 작업입니다. 이메일 매핑은 가장 높은 일치율을 보장합니다.

1. 이제 소스 필드를 선택할 차례입니다. 이메일의 경우 커서 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-20.png)

1. ID 네임스페이스 선택 라디오 단추를 클릭하고 **[!UICONTROL Email]**&#x200B;을(를) 찾아 선택한 다음 **[!UICONTROL Select]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-21.png)

1. 회사명 출처 필드를 선택하려면 해당 행에서 커서 아이콘을 누릅니다.

   ![](assets/push-an-adobe-experience-platform-segment-22.png)

1. 속성 선택 라디오 단추를 선택된 상태로 둡니다. &quot;회사&quot;를 검색하고 **[!UICONTROL companyName]**&#x200B;을(를) 선택한 다음 **[!UICONTROL Select]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-23.png)

1. 각 이름에 대한 커서 아이콘을 클릭하고 23단계를 두 번 반복하여 **[!UICONTROL lastName]**&#x200B;을(를) 선택한 다음 **[!UICONTROL firstName]**&#x200B;을(를) 선택하여 성 및 이름에 대한 소스 필드를 매핑합니다.

   ![](assets/push-an-adobe-experience-platform-segment-24.png)

1. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-25.png)

1. 변경 내용을 검토하고 **[!UICONTROL Finish]**&#x200B;을(를) 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-26.png)

---
description: Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시 - Marketo 문서 - 제품 설명서
title: Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시
exl-id: 8df11bf4-06f4-4927-8dfb-954414fce6dc
source-git-commit: 0dd8059a43bfb37cdcb6b36cc73d82538263245e
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시 {#push-an-adobe-experience-platform-segment-to-a-marketo-static-list}

이 기능을 사용하면 Adobe Experience Platform에 있는 세그먼트를 정적 목록 형태로 Marketo에 푸시할 수 있습니다.

>[!PREREQUISITES]
>
>* [API 역할 편집](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md#edit-an-existing-role) 그 안에 **읽기-쓰기 사람** 권한(액세스 API 드롭다운에서 찾음)
>* [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) Marketo.
>* 이동 **관리** > **Launchpoint**. 방금 만든 역할의 이름을 찾아 **세부 사항 보기**. 정보를 복사하여 저장합니다 **클라이언트 ID** 및 **클라이언트 암호** 7단계에 필요한 경우
>* Marketo에서 정적 목록을 만들거나 이미 만든 정적 목록을 찾아 선택합니다. ID가 필요합니다.


1. 에 로그인합니다. [Adobe Experience Platform](https://experience.adobe.com/).

   ![](assets/push-an-adobe-experience-platform-segment-1.png)

1. 격자 아이콘을 클릭하고 를 선택합니다 **Experience Platform**.

   ![](assets/push-an-adobe-experience-platform-segment-2.png)

1. 왼쪽 탐색 메뉴에서 **대상**.

   ![](assets/push-an-adobe-experience-platform-segment-3.png)

1. 클릭 **카탈로그**.

   ![](assets/push-an-adobe-experience-platform-segment-4.png)

1. Marketo Engage 타일을 찾고 **활성화**.

   ![](assets/push-an-adobe-experience-platform-segment-5.png)

1. 클릭 **새 대상 구성**.

   ![](assets/push-an-adobe-experience-platform-segment-6.png)


1. 계정 유형에서 기존 또는 새 계정 라디오 단추를 선택합니다(이 예에서는 다음과 같이 선택합니다 **기존 계정**). 계정 선택 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-7.png)

   >[!NOTE]
   >
   >새 계정을 선택하는 경우 다음 위치로 이동하여 Munchkin ID를 찾을 수 있습니다 **관리** > **Munchkin** (한 번 로그인하면 Marketo URL의 일부입니다.) 클라이언트 ID/비밀번호는 이 문서의 맨 위에 있는 사전 요구 사항을 따라야 합니다.

1. 대상 계정을 선택하고 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-8.png)

1. 대상 입력 **이름** 및 선택적 설명. 개인 만들기 드롭다운을 클릭하고 &quot;Match Existing Marketo People and Create Missing People in Marketo&quot;을 선택합니다. _또는_ &quot;기존 Marketo 사용자만 일치&quot;합니다. 이 예에서는 이전 항목을 선택합니다.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

   >[!NOTE]
   >
   >기존 Marketo 사용자만 일치 를 선택하는 경우 이메일 및/또는 ECID만 매핑하면 되므로 13~16단계를 건너뛸 수 있습니다.

1. 이 섹션은 선택 사항입니다. 클릭 **만들기** 을 클릭하여 건너뜁니다.

   ![](assets/push-an-adobe-experience-platform-segment-10.png)

1. 만든 대상을 선택하고 을(를) 클릭합니다 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-11.png)

1. Marketo에 보낼 세그먼트를 선택하고 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-12.png)

   >[!NOTE]
   >
   >여러 세그먼트를 선택하는 경우, 세그먼트 예약 탭에서 지정된 정적 목록에 각 세그먼트를 매핑해야 합니다.

   >[!IMPORTANT]
   >
   >세그먼트가 Marketo 대상에 처음으로 활성화되면 Marketo 대상 활성화 전에 세그먼트에 이미 있었던 프로필을 다시 채울 수 있습니다 **최대 24시간**. 앞으로는 언제든지 프로필이 세그먼트에 추가되면 즉시 Marketo에 추가됩니다.

1. 클릭 **새 매핑 추가**.

   ![](assets/push-an-adobe-experience-platform-segment-13.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-14.png)

1. 을 선택하여 이름 매핑 **firstName** 및 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-15.png)

1. 을 클릭하여 성 및 회사 이름 매핑 **새 매핑 추가** 다시 15단계를 두 번 반복하여 **lastName** 그리고 **companyName**.

   ![](assets/push-an-adobe-experience-platform-segment-16.png)

1. 이제 이메일 주소를 매핑할 차례입니다. 클릭 **새 매핑 추가** 다시 한 번

   ![](assets/push-an-adobe-experience-platform-segment-17.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-18.png)

1. Select Identity Namespace 라디오 단추를 클릭하고  **이메일**&#x200B;를 클릭한 다음 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-19.png)

   >[!IMPORTANT]
   >
   >에서 이메일 및/또는 ECID 매핑 **ID 네임스페이스** 탭은 Marketo에서 사람이 일치하는지 확인하기 위해 가장 중요한 작업입니다. 이메일을 매핑하면 가장 높은 일치율을 보장합니다.

1. 이제 소스 필드를 선택할 차례입니다. 전자 메일의 경우 커서 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-20.png)

1. ID 네임스페이스 선택 라디오 단추를 클릭하고 을 찾아 선택합니다 **이메일**&#x200B;를 클릭한 다음 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-21.png)

1. 회사 이름 출처 필드를 선택하려면 해당 행에서 커서 아이콘을 누릅니다.

   ![](assets/push-an-adobe-experience-platform-segment-22.png)

1. 속성 선택 라디오 단추를 선택된 상태로 두십시오. &quot;company&quot;를 검색하고 선택합니다. **companyName**&#x200B;를 클릭한 다음 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-23.png)

1. 각각에 대한 커서 아이콘을 클릭하고 23단계를 두 번 반복하여 성 및 이름에 대한 소스 필드를 매핑합니다. **lastName** 그리고 **firstName**.

   ![](assets/push-an-adobe-experience-platform-segment-24.png)

1. 클릭 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-25.png)

1. 이제 목록의 ID가 필요합니다. 브라우저에서 Marketo 정적 목록이 있는 탭을 클릭하거나 새 탭을 열고 원하는 정적 목록을 선택합니다.

   ![](assets/push-an-adobe-experience-platform-segment-26.png)

   >[!NOTE]
   >
   >최상의 결과를 얻으려면 빈 Marketo Engage 목록을 사용하십시오.

1. URL 끝에 있는 목록 ID를 강조 표시하고 복사합니다.

   ![](assets/push-an-adobe-experience-platform-segment-27.png)

1. 매핑 ID 아래에 방금 복사한 ID를 붙여넣고 를 클릭합니다 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-28.png)

1. 클릭 **완료**.

   ![](assets/push-an-adobe-experience-platform-segment-29.png)

---
description: Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시 - Marketo 문서 - 제품 설명서
title: Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시
exl-id: 8df11bf4-06f4-4927-8dfb-954414fce6dc
source-git-commit: 5d26aff392d5749941ad93e351c454249662cd72
workflow-type: tm+mt
source-wordcount: '514'
ht-degree: 0%

---

# Marketo 정적 목록에 Adobe Experience Platform 세그먼트 푸시 {#push-an-adobe-experience-platform-segment-to-a-marketo-static-list}

이 기능을 사용하면 Adobe Experience Platform에 있는 세그먼트를 정적 목록 형태로 Marketo에 푸시할 수 있습니다.

>[!PREREQUISITES]
>
>* [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) Marketo.
>* 그런 다음 **관리** > **Launchpoint**. 방금 만든 역할의 이름을 찾아 **세부 사항 보기**. 정보를 복사하여 저장합니다 **클라이언트 ID** 및 **클라이언트 암호**&#x200B;을 가리키도록 업데이트하는 것이 좋습니다.


1. 에 로그인합니다. [Adobe Experience Platform](https://experience.adobe.com/).

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-1.png)

1. 격자 아이콘을 클릭하고 를 선택합니다 **Experience Platform**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-2.png)

1. 왼쪽 탐색 메뉴에서 **대상**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-3.png)

1. 클릭 **카탈로그**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-4.png)

1. Marketo Engage 타일을 찾고 **세그먼트 활성화**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-5.png)

1. 클릭 **새 대상 구성**.


1. 계정 유형에서 **새 계정** 라디오 단추입니다. Marketo 자격 증명을 입력하고 **대상에 연결**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-6.png)

   >[!NOTE]
   >
   >Munchkin ID는 **관리** > **Munchkin** (한 번 로그인하면 Marketo URL의 일부입니다.) 클라이언트 ID/비밀번호는 이 문서의 맨 위에 있는 사전 요구 사항을 따라야 합니다.

1. &quot;연결됨&quot;은 자격 증명 아래에 표시됩니다. 클릭 **다음** 오른쪽 상단 모서리에서

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-7.png)

1. 을(를) 입력합니다. **이름** 그리고 _옵션_ 설명. 클릭 **대상 만들기**.

   >[!NOTE]
   >
   >마케팅 작업에서 항목을 선택하는 것도 선택 사항입니다. Marketo은 현재 해당 정보를 활용하지 않지만 곧 이용할 수 있습니다.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-8.png)

1. 클릭 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-9.png)

1. 원하는 세그먼트를 선택하고 을(를) 클릭합니다 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-10.png)

   >[!NOTE]
   >
   >정적 목록에 대한 세그먼트는 1:1입니다. 여기에서 여러 세그먼트를 선택하는 경우, 세그먼트 예약 탭에서 지정된 정적 목록에 각 세그먼트를 매핑해야 합니다.

1. 클릭 **새 매핑 추가**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-11.png)

1. 커서 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-12.png)

1. 다음 중 하나를 선택합니다 **속성 선택** 또는 **ID 네임스페이스 선택** 라디오 단추(이 예에서는 속성 선택)

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-13.png)

   >[!NOTE]
   >
   >선택한 경우 **ID 네임스페이스 선택**&#x200B;을 선택한 후 15단계로 이동합니다.

1. 사용자를 식별하는 이메일 주소가 포함된 관련 필드를 선택합니다. 클릭 **선택** 완료 시.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-14.png)

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-15.png)

   >[!NOTE]
   >
   >선택한 예는 선택한 예제와 많이 다를 수 있습니다.

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-16.png)

1. 선택 **ID 네임스페이스 선택**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-17.png)

   >[!IMPORTANT]
   >
   >매핑 속성은 선택 사항입니다. 에서 이메일 및/또는 ECID 매핑 **ID 네임스페이스** 탭은 Marketo에서 사람이 일치하는지 확인하기 위해 가장 중요한 작업입니다. 이메일을 매핑하면 가장 높은 일치율을 보장합니다.

1. ECID 또는 이메일 중에서 선택합니다. 이 예제에서는 **이메일**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-18.png)

1. 클릭 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-19.png)

   >[!NOTE]
   >
   >ID는 Marketo에서 일치 항목을 찾는 데 사용됩니다. 일치하는 항목이 있으면 해당 사람이 정적 목록에 추가됩니다. 일치하는 항목을 찾을 수 없으면 해당 사람이 삭제됩니다(즉, Marketo에서 만들지 않음).

1. _Marketo에서_&#x200B;정적 목록을 만들거나 이미 만든 목록을 찾아 선택합니다. URL의 끝에서 매핑 ID를 복사합니다.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-20.png)

   >[!NOTE]
   >
   >최상의 결과를 얻으려면 Marketo에서 참조하는 목록이 비어 있는지 확인하십시오.

1. Adobe Experience Platform으로 돌아가서 방금 복사한 ID를 입력합니다. 시작 날짜를 선택합니다. 사람들은 선택한 종료 날짜까지 계속 동기화됩니다. 무기한 동기화하려면 종료 날짜를 비워 둡니다. 클릭 **다음** 완료 시.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-21.png)

1. 변경 내용을 확인하고 를 클릭합니다 **완료**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-22.png)

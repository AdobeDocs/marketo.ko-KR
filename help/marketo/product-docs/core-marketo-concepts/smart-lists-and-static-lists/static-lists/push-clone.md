---
description: 푸시 복제 - Marketo 문서 - 제품 설명서
title: 푸시 복제
hide: true
hidefromtoc: true
source-git-commit: 8920bc525075923b32e7330da20debb7b8f47b06
workflow-type: tm+mt
source-wordcount: '467'
ht-degree: 0%

---

# 푸시 복제 {#push-clone}

이 기능을 사용하면 Adobe Experience Platform에 있는 세그먼트를 정적 목록 형태로 Marketo에 푸시할 수 있습니다.

>[!PREREQUISITES]
>
>* [API 사용자 만들기](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) Marketo.
>* 그런 다음 **관리** > **Launchpoint**. 방금 만든 역할의 이름을 찾아 **세부 사항 보기**. 정보를 복사하여 저장합니다 **클라이언트 ID** 및 **클라이언트 암호**&#x200B;을 가리키도록 업데이트하는 것이 좋습니다.


1. 에 로그인합니다. [Adobe Experience Platform](https://experience.adobe.com/).

   ![](assets/push-an-adobe-experience-platform-segment-1.png)

1. 격자 아이콘을 클릭하고 를 선택합니다 **Experience Platform**.

   ![](assets/push-an-adobe-experience-platform-segment-2.png)

1. 왼쪽 탐색 메뉴에서 **대상**.

   ![](assets/push-an-adobe-experience-platform-segment-3.png)

1. 클릭 **카탈로그**.

   ![](assets/push-an-adobe-experience-platform-segment-4.png)

1. Marketo Engage 타일을 찾고 **세그먼트 활성화**.

   ![](assets/push-an-adobe-experience-platform-segment-5.png)

1. 클릭 **새 대상 구성**.

   ![](assets/push-an-adobe-experience-platform-segment-6.png)


1. 계정 유형에서 기존 또는 새 계정 라디오 단추를 선택합니다(이 예에서는 다음과 같이 선택합니다 **기존 계정**). 계정 선택 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-7.png)

1. 대상 계정을 선택하고 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-8.png)

다음으로 기존 Marketo 사용자만 일치시킬 것인지 아니면 기존 Marketo 사람을 일치시킬 것인지 선택하고 Marketo에서 누락된 사람을 만들어야 합니다. 다음은 각 방법을 요약한 섹션입니다.

## Marketo에서 기존 Marketo 사람 일치 및 실종된 사람 만들기 {#match-existing-marketo-people-create-missing-people}

위의 단계 1-8을 수행한 후...

1. 대상 입력 **이름** 및 선택적 설명. 개인 생성 드롭다운을 클릭하고 을 선택합니다 **Marketo에서 기존 Marketo 사람 일치 및 실종된 사람 만들기**.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

1. 이 섹션은 선택 사항입니다. 클릭 **만들기** 을 클릭하여 건너뜁니다.

   ![](assets/push-an-adobe-experience-platform-segment-10.png)

1. 만든 대상을 선택하고 을(를) 클릭합니다 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-11.png)

1. Marketo에 보낼 세그먼트를 선택하고 **다음**.

   ![](assets/push-an-adobe-experience-platform-segment-12.png)

1. 클릭 **새 매핑 추가**.

   ![](assets/push-an-adobe-experience-platform-segment-13.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-14.png)

1. 을 선택하여 이름 매핑 **firstName** 및 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-15.png)

1. 을 클릭하여 성 및 회사 이름을 매핑합니다 **새 매핑 추가** 다시 7단계를 두 번 반복하여 lastName을 선택하고 companyName을 선택합니다.

   ![](assets/push-an-adobe-experience-platform-segment-16.png)

1. 이제 이메일 주소를 매핑할 차례입니다. 클릭 **새 매핑 추가** 다시 한 번

   ![](assets/push-an-adobe-experience-platform-segment-17.png)

1. 매핑 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-18.png)

1. Select Identity Namespace 라디오 단추를 클릭하고  **이메일**&#x200B;를 클릭한 다음 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-19.png)

1. 이제 소스 필드를 선택할 차례입니다. 전자 메일의 경우 커서 아이콘을 클릭합니다.

   ![](assets/push-an-adobe-experience-platform-segment-20.png)

1. ID 네임스페이스 선택 라디오 단추를 클릭하고 을 찾아 선택합니다 **이메일**&#x200B;를 클릭한 다음 **선택**.

   ![](assets/push-an-adobe-experience-platform-segment-21.png)

모리이

## 기존 Marketo 사용자만 일치 {#match-existing-marketo-people-only}

>[!NOTE]
>
>ID는 Marketo에서 일치 항목을 찾는 데 사용됩니다. 일치하는 항목이 있으면 해당 사람이 정적 목록에 추가됩니다. 일치하는 항목을 찾을 수 없으면 해당 사람이 삭제됩니다(즉, Marketo에서 만들지 않음).

1. _Marketo에서_&#x200B;정적 목록을 만들거나 이미 만든 목록을 찾아 선택합니다. URL의 끝에서 매핑 ID를 복사합니다.

PICC

>[!NOTE]
>
>최상의 결과를 얻으려면 Marketo에서 참조하는 목록이 비어 있는지 확인하십시오.

1. Adobe Experience Platform으로 돌아가서 방금 복사한 ID를 입력합니다. 시작 날짜를 선택합니다. 사람들은 선택한 종료 날짜까지 계속 동기화됩니다. 무기한 동기화하려면 종료 날짜를 비워 둡니다. 클릭 **다음** 완료 시.

PICC

1. 변경 내용을 확인하고 를 클릭합니다 **완료**.

PICC

---
description: 이메일 보트 활동 필터링 - Marketo 문서 - 제품 설명서
title: 전자 메일 보트 활동 필터링
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
source-git-commit: a64c499f6972e94adfecbe164d86f7db1b1447aa
workflow-type: tm+mt
source-wordcount: '168'
ht-degree: 0%

---

# 전자 메일 보트 활동 필터링 {#filtering-email-bot-activity}

경우에 따라 이메일 보트 활동이 이메일 열기 및 데이터 클릭 수를 잘못 부풀릴 수 있습니다. 이를 수정하는 방법은 다음과 같습니다.

>[!NOTE]
>
>사용 [IAB/ABC International Spiders and Bots List](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/), 해당 목록에 있는 모든 것과 일치하는 IP 또는 사용자 에이전트가 있는 모든 열기/클릭 활동은 보트 활동으로 식별되고 Marketo에 로그인되지 않습니다.

1. 클릭 **관리**.

   ![](assets/filtering-email-bot-activity-1.png)

1. 클릭 **이메일**.

   ![](assets/filtering-email-bot-activity-2.png)

1. 을(를) 클릭합니다. **보트 활동** 탭.

   ![](assets/filtering-email-bot-activity-3.png)

1. 슬라이더를 클릭하여 활성화합니다 **보트 활동 필터링**.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>보트 활동을 기록할지 여부를 별도로 선택할 수 있습니다. 선택하지 않으면 잘못된 숫자가 필터링되어 이메일이 열리고 클릭 수가 줄어들 수 있습니다.

**옵션 단계**: 피쳐를 비활성화하려면 슬라이더를 선택 해제하면 됩니다. 비활성화하면 &quot;최근 90일 동안의 보트 활동&quot; 데이터가 수행됩니다 **not** 재설정

>[!TIP]
>
>보트 활동인지 부울(예/아니요) 또는 적용 가능한 필터/트리거 제한을 통해 스마트 목록의 보트 활동 데이터를 활용하십시오.

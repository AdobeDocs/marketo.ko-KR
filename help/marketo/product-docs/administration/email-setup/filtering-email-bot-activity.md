---
description: 이메일 보트 활동 필터링 - Marketo 문서 - 제품 설명서
title: 전자 메일 보트 활동 필터링
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
source-git-commit: 91e04b4282f18f8074d0192fae42e62dfe5ebb80
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 0%

---

# 전자 메일 보트 활동 필터링 {#filtering-email-bot-activity}

경우에 따라 이메일 보트 활동이 이메일 열기 및 데이터 클릭 수를 잘못 부풀릴 수 있습니다. 아래 절차에 따라 이 문제를 해결하십시오.

두 개의 별도 메서드를 사용하여 보트 활동을 확인합니다.

* 일치 [Interactive Advertising Bureau 보트 목록](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/){target=&quot;_blank&quot;}: IAB UA/IP(사용자 에이전트/IP 주소) 목록에 있는 무엇과도 일치하는 활동은 보트로 표시됩니다.
* 근접 패턴과 일치: 두 개 이상의 활동이 동시에(초 이내)발생하면 보트로 식별됩니다.

이메일 링크 클릭 및 이메일 열기 활동에 대해 새 속성은 아래 값으로 채워집니다.

* 보트로 식별되는 활동에는 &quot;보트 활동&quot;이 &quot;True&quot;로 설정되고, &quot;보트 활동 패턴&quot;이 식별된 패턴/메서드로 사용됩니다
* 보트가 아닌 것으로 식별되는 활동에는 &quot;보트 활동&quot;이 &quot;False&quot;로 표시되고, &quot;보트 활동 패턴&quot;은 &quot;N/A&quot;로 표시됩니다
* 이러한 속성을 도입하기 전에 발생한 활동의 &quot;보트 활동&quot;은 &quot; (비어 있음) &quot;으로 표시되고, &quot;보트 활동 패턴&quot;은 &quot; &quot; (비어 있음)로 표시됩니다

1. 클릭 **관리**.

   ![](assets/filtering-email-bot-activity-1.png)

1. 클릭 **이메일**.

   ![](assets/filtering-email-bot-activity-2.png)

1. 을(를) 클릭합니다. **보트 활동** 탭.

   ![](assets/filtering-email-bot-activity-3.png)

1. 선택 **IAB 목록과 일치**, **근접 패턴과 일치**&#x200B;또는 둘 다 사용할 수 있습니다. 보트 활동을 기록할지 여부를 선택합니다 _또는_ 보트 활동을 필터링합니다.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>보트 활동 필터링 을 선택하는 경우 잘못된 활동이 제외되므로 이메일 열기 및 클릭 수가 줄어들 수 있습니다.

**옵션 단계**: 이 기능을 비활성화하려면 슬라이더를 선택 취소하면 됩니다. 비활성화하면 데이터가 재설정되지 않습니다.

>[!TIP]
>
>&quot;Clicked Link in Email&quot; 및 &quot;Open Email&quot; 필터에서 &quot;Is Bot Activity&quot; 부울(예/아니요) 및 &quot;보트 활동 패턴&quot; 을 통해 Smart List에서 보트 활동 데이터를 활용하고 &quot;Click Link in Email&quot; 및 &quot;Open Email&quot; 트리거를 사용합니다.

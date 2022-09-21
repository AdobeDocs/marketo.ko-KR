---
unique-page-id: 10096681
description: 웨비나 프로그램 상태 이해 - Marketo 문서 - 제품 설명서
title: 웨비나 프로그램 상태 이해
exl-id: ef0b1b94-a612-4aa8-9b4a-aa7ef0e2abaa
source-git-commit: 0c6c119f5be6e2ac3db7d99f7e8623d8aaa3555c
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 0%

---

# 웨비나 프로그램 상태 이해 {#understanding-webinar-program-statuses}

프로그램 상태는 개인이 이벤트의 구성원으로 진행하는 다양한 이벤트 상태를 나타냅니다. 이러한 시퀀스는 채널 유형에 연결됩니다. Marketo에는 **웨비나**. 배치 및 트리거 캠페인 모두에서 상태를 사용할 수 있습니다.

사람들은 프로그램 상태를 선형 방식으로 이동하며 상태로 돌아가지 않습니다. 예를 들어, 상태가 **참석함** 다시 이동할 수 없음 **등록**.

다음은 웨비나 채널과 관련된 프로그램 상태에 대한 간략한 설명입니다.

>[!TIP]
>
>상태를 수동으로 업데이트하려면  **웨비나 공급자에서 새로 고침** 에서 **이벤트 작업** 드롭다운.

![](assets/image2015-12-17-13-3a52-3a39.png)

**프로그램에 없음** - 이 상태를 사용하여 이벤트에서 사용자를 제거합니다.

**초대** - 이 상태를 사용하여 이벤트에 사람을 추가합니다.

**승인 보류 중** - 이 상태를 사용하여 확인 이메일 전송을 중단합니다. 자세한 내용은 의 &quot;수동으로 등록 승인&quot;을 참조하십시오. [ON24 이벤트 등록 업데이트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md)자세한 내용은 {target=&quot;_blank&quot;} 를 참조하십시오.

**대기 목록** - 이 상태를 사용하여 추가 좌석이 마련될 때까지 일부 사용자가 대기하도록 합니다.

**거부됨** - 이 상태를 사용하여 이벤트에 대한 개인 등록을 거부합니다.

**등록** - 이 상태는 ON24 통합을 사용할 때 사용자를 ON24로 푸시합니다. ON24가 개인이 성공적으로 등록되었다고 응답하면 개인 상태가 업데이트됩니다.

**등록 오류** - 이 상태는 사용자가 이벤트에 등록하려고 할 때 오류가 발생했음을 나타냅니다.

>[!NOTE]
>
>등록 오류가 발생하면 프로그램의 멤버 탭에서 상태 이유 열을 보고 해당 사용자에 대한 추가 정보를 얻을 수 있습니다. 오류가 수정되면 수동으로 사용자의 프로그램 상태를 Marketo 내에서 등록됨으로 변경할 수 있습니다.

**참석함** - 웨비나가 끝나면 ON24에 참석한 사람 목록이 반환됩니다. 이 상태는 자동으로 Marketo으로 가져옵니다.

**주문형 참석** - 보관된 웨비나 버전에 참석한 사람이 이 상태를 받습니다.

**표시 안 함** - 웨비나가 끝나고 ON24에서 참가 데이터를 가져온 후 등록했지만 참석하지 않은 사용자의 상태가 [표시 안 함]으로 업데이트됩니다. ON24에서 최종 참석 정보를 준비하고 Marketo에서 사용할 수 있도록 하려면 30분에서 3시간 정도 걸릴 수 있습니다.

>[!NOTE]
>
>Marketo에서 표시 안 함 상태를 가져오려면 사람이 등록되어 있어야 합니다 *Marketo*. On24 데이터 피드에서 나오는 표시 횟수를 캡처할 수 없습니다.

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target=&quot;_blank&quot;}

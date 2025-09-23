---
unique-page-id: 10096681
description: 웨비나 프로그램 상태 이해 - Marketo 문서 - 제품 설명서
title: 웨비나 프로그램 상태 이해
exl-id: ef0b1b94-a612-4aa8-9b4a-aa7ef0e2abaa
feature: Events
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 1%

---

# 웨비나 프로그램 상태 이해 {#understanding-webinar-program-statuses}

프로그램 상태는 개인이 이벤트의 멤버로 진행하는 다양한 이벤트 상태를 나타냅니다. 채널 유형에 연결됩니다. Marketo에는 **웨비나**&#x200B;라는 기본 제공 채널 형식이 있습니다. 상태는 일괄 처리와 트리거 캠페인 모두에서 사용할 수 있습니다.

직원들은 프로그램 상태를 직선으로 이동하고 상태로 돌아가지 않습니다. 예를 들어 상태가 **참석함**&#x200B;인 사용자는 **등록됨**(으)로 돌아갈 수 없습니다.

다음은 웨비나 채널과 관련된 프로그램 상태에 대한 간략한 설명입니다.

>[!TIP]
>
>상태를 수동으로 업데이트하려면 **이벤트 작업** 드롭다운에서 **웨비나 공급자에서 새로 고침**&#x200B;을 클릭하세요.

![](assets/image2015-12-17-13-3a52-3a39.png)

**프로그램에 없음** - 이 상태를 사용하여 이벤트에서 사람을 제거하십시오.

**초대됨** - 이 상태를 사용하여 이벤트에 사용자를 추가하십시오.

**승인 보류 중** - 이 상태를 사용하여 사람들에게 확인 전자 메일을 보내는 것을 보류하세요. 자세한 내용은 [ON24 이벤트 등록 업데이트](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md){target="_blank"}의 &quot;수동으로 등록자 승인&quot;을 참조하십시오.

**대기 목록** - 추가 좌석이 생길 때까지 일부 직원을 대기시키려면 이 상태를 사용하십시오.

**거부됨** - 이 상태를 사용하여 이벤트에 대한 사용자 등록을 거부합니다.

**등록됨** - 이 상태는 ON24 통합을 사용할 때 ON24로 사용자를 푸시합니다. ON24에서 개인이 성공적으로 등록되었다고 응답하면 개인의 상태가 업데이트됩니다.

**등록 오류** - 이 상태는 사용자가 이벤트에 등록하려고 할 때 오류가 발생했음을 나타냅니다.

>[!NOTE]
>
>등록 오류가 발생하면 프로그램의 구성원 탭에서 상태 사유 열을 확인하여 해당 사용자에 대한 추가 정보를 얻을 수 있습니다. 오류가 해결되면 사용자의 프로그램 상태를 수동으로 Marketo 내에 등록됨으로 변경할 수 있습니다.

**참석함** - 웨비나가 끝나면 ON24에서 참석한 사람 목록을 반환합니다. 이 상태는 자동으로 Marketo으로 가져옵니다.

**요청 시 참석함** - 보관된 웨비나 버전에 참석한 사람들에게 이 상태가 표시됩니다.

**표시 안 함** - 웨비나가 끝날 때 및 ON24에서 출석 데이터를 가져온 후 등록했지만 출석하지 않은 사람의 상태가 [표시 안 함]으로 업데이트됩니다. ON24는 최종 참석 정보를 작성해서 Marketo에서 이용할 수 있도록 30분에서 3시간 정도 소요될 수 있습니다.

>[!NOTE]
>
>Marketo에서 표시 안 함 상태를 가져오려면 해당 사용자가 *Marketo*&#x200B;에 등록되어 있어야 합니다. On24 데이터 피드에서 발생하는 No Show를 캡처할 수 없습니다.

>[!MORELIKETHIS]
>
>[Marketo ON24 어댑터 이벤트 이해](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}

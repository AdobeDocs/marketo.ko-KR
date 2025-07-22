---
unique-page-id: 10617431
description: 인앱 메시지 대상 설정 - Marketo 문서 - 제품 설명서
title: 인앱 메시지 대상자 설정
exl-id: 696ae5b6-7063-41bc-bcef-27879182ff1e
feature: Mobile Marketing
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '266'
ht-degree: 1%

---

# 인앱 메시지 대상자 설정 {#set-your-in-app-message-audience}

첫 번째 단계는 인앱 메시지를 수신할 사용자를 결정하는 것입니다. 스마트 목록을 설정해야 합니다.

1. **[!UICONTROL Edit Smart List]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2016-5-9-15-3a15-3a7.png)

1. Smart List에서 **[!UICONTROL Has Mobile App Activity]** 트리거가 자동으로 채워집니다. 드롭다운을 클릭하고 메시지를 넣을 앱을 선택합니다.

   ![](assets/image2016-5-9-15-3a18-3a10.png)

   >[!NOTE]
   >
   >현재 인앱 메시지 프로그램에서는 모바일 앱 필드에 대한 여러 값이 지원되지 않습니다.

1. **[!UICONTROL App Open]**&#x200B;은(는) 기본 작업 설정이지만 이미 설정한 사용자 지정 이벤트를 선택할 수 있습니다.

   ![](assets/image2016-5-9-15-3a20-3a23.png)

   >[!NOTE]
   >
   >개발자가 코드에 추가한 기본 트리거([!UICONTROL App Open]) 및 모든 사용자 지정 트리거는 [!UICONTROL Action] 선택기에 자동으로 표시됩니다. 사용자 지정 이벤트가 누락된 경우 개발자에게 문의하여 앱에 사용자 지정 이벤트를 추가했는지 확인하십시오. 사용자 지정 이벤트 코딩 및 승인 프로세스를 완료하는 데 시간이 걸릴 수 있습니다. 자세한 내용은 [이 문서](/help/marketo/product-docs/mobile-marketing/admin/before-you-create-push-notifications-and-in-app-messages.md)를 참조하십시오.

1. 필요한 경우 **[!UICONTROL Has Mobile App Activity]** 트리거에 제약 조건을 사용할 수 있습니다.

   ![](assets/image2016-5-9-15-3a22-3a27.png)

1. 스마트 목록에 필터를 추가하여 인앱 메시지를 받는 사람을 제한할 수 있습니다. 이 예에서는 **[!UICONTROL Acquisition Date]** 필터를 사용하여 2016년 6월 9일에 획득한 사람에게만 인앱 메시지가 전송됩니다.

   ![](assets/image2016-5-9-15-3a26-3a2.png)

1. 인앱 메시지 Campaign 컨트롤 패널으로 돌아갑니다. 드롭다운에서 표시 제한을 설정합니다.

   ![](assets/image2016-5-9-15-3a30-3a35.png)

   >[!NOTE]
   >
   >기본 표시 제한은 **[!UICONTROL Once per session]**&#x200B;입니다. 받는 사람이 응답한 후 메시지 표시를 중지하려면 **[!UICONTROL Every time until tapped]**&#x200B;을(를) 선택합니다. 매번 표시되어야 하는 경우 받는 사람이 무엇을 하든 관계없이 **[!UICONTROL Every time]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2016-5-9-15-3a32-3a6.png)

수고하셨습니다! 대상을 설정했습니다. 파란색 막대와 녹색 확인 표시를 획득했습니다.

[인앱 메시지 선택](/help/marketo/product-docs/mobile-marketing/in-app-messages/sending-your-in-app-message/select-your-in-app-message.md)할 시간!

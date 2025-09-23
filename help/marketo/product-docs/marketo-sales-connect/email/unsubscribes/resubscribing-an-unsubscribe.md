---
unique-page-id: 14746177
description: 구독 취소 다시 구독 - Marketo 문서 - 제품 설명서
title: 구독 취소 및 재구독
exl-id: 1c451ff7-c56f-477e-b287-898c359aedcf
feature: Marketo Sales Connect
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '186'
ht-degree: 1%

---

# [!UICONTROL Unsubscribe] 다시 구독 중 {#resubscribing-an-unsubscribe}

경우에 따라 사람들은 이메일 수신을 다시 옵트인하고 싶어합니다. 구독 취소 메시지를 다시 받을 수 있도록 하는 방법을 소개합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!CAUTION]
>
>다른 사람을 다시 구독하기 전에 다시 구독할 수 있는 권한이 문서화되고 적용 가능한 모든 법률을 준수하는지 입증할 수 있어야 합니다.

>[!NOTE]
>
>구독 취소 동기화를 설정한 경우 ToutApp에서 구독 취소를 제거하고 개인 레코드가 다시 동기화되지 않도록 [!DNL Salesforce]에서 옵트아웃을 선택 취소해야 합니다.

1. [웹 응용 프로그램](https://toutapp.com/login)&#x200B;(으)로 이동하여 **[!UICONTROL People]**&#x200B;을(를) 클릭합니다.

1. 개인 세부 정보 보기를 열 개인을 선택합니다.

   ![](assets/two.png)

1. 개인 세부 정보 보기에서 세 점을 클릭하고 **[!UICONTROL Remove Unsubscribe]**&#x200B;을(를) 선택합니다.

   ![](assets/three.png)

1. 전자 메일을 받도록 해당 사용자가 다시 옵트인되는 이유를 선택한 다음 **[!UICONTROL Remove Unsubscribe]**&#x200B;을(를) 클릭합니다.

   ![](assets/four.png)

>[!NOTE]
>
>구독 취소 동기화가 켜져 있는 경우 Salesforce의 레코드에서도 옵트아웃 상자의 선택을 취소해야 합니다. 그렇지 않으면 야간 동기화에서 [!DNL Sales Connect]의 사용자에 대한 구독을 다시 취소하게 됩니다. [!DNL Salesforce]에서 해당 사용자가 옵트아웃되었음을 감지하게 됩니다. 레코드 중 하나가 옵트아웃/구독 취소되면 동기화에서 연결된 레코드를 이와 같이 표시합니다.

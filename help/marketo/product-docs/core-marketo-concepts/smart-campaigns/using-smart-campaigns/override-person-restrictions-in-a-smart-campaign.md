---
unique-page-id: 1147066
description: Smart Campaign에서 개인 제한을 재정의하는 방법을 알아봅니다. 사람들이 통신 제한에 도달하더라도 실행할 수 있도록 허용합니다.
title: 스마트 캠페인에서 개인 제한 재정의
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/GUIwrHBCrtl5NONZAqCY9sXt1FaLfjBwe3N3t1u98a4
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: a7170d27-32ab-462b-a333-269abc654483id: c5f60233-d5ea-4453-a799-0ad258b4d399id: d1d0a9cd-295d-4976-8c39-ddae266f240e
topic_v2: id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 141
ht-degree: 9%

---

# 스마트 캠페인에서 개인 제한 재정의 {#override-person-restrictions-in-a-smart-campaign}

Marketo Engage을 사용하면 Smart Campaign에 사용할 수 있는 최대 사용자 수를 설정할 수 있습니다. 이렇게 하면 전체 데이터베이스에 실수로 이메일을 보내는 것을 방지할 수 있습니다. 이 제한을 _재정의_&#x200B;하려는 경우 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>Marketo 관리자의 [스마트 캠페인에 대한 개인 제한 사용](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md){target="_blank"}을 확인하세요.

1. **[!UICONTROL Marketing Activities]**&#x200B;에서 스마트 캠페인으로 이동하여 **[!UICONTROL Schedule]**&#x200B;을(를) 클릭합니다.

   ![](assets/override-person-restrictions-in-a-smart-campaign-1.png)

1. 스마트 캠페인 설정에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >기본 제한은 Admin에 설정된 제한입니다.

1. 새 한도를 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/override-person-restrictions-in-a-smart-campaign-3.png)

   자격 조건을 갖춘 사람 수가 설정된 제한을 초과할 경우 스마트 캠페인이 실행되지 않습니다.

   >[!CAUTION]
   >
   >이 기능을 주의해서 실수로 너무 많은 사람을 포함하지 않도록 하십시오.

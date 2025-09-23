---
unique-page-id: 1147066
description: 스마트 캠페인에서 개인 제한 재정의 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에서 개인 제한 재정의
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
feature: Smart Campaigns
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '132'
ht-degree: 10%

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

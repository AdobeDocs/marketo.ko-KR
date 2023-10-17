---
unique-page-id: 1147066
description: 스마트 캠페인에서 개인 제한 재정의 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에서 개인 제한 재정의
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
feature: Smart Campaigns
source-git-commit: fec5219c599c805328d77797d2636e549e489ca5
workflow-type: tm+mt
source-wordcount: '139'
ht-degree: 0%

---

# 스마트 캠페인에서 개인 제한 재정의 {#override-person-restrictions-in-a-smart-campaign}

Marketo Engage을 사용하면 Smart Campaign의 자격을 가질 수 있는 최대 인원을 설정할 수 있습니다. 이렇게 하면 전체 데이터베이스에 실수로 이메일을 보내는 것을 방지할 수 있습니다. 원하는 경우 _재정의_ 이 제한, 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>다음을 확인합니다. [스마트 캠페인에 대한 개인 제한 활성화](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md){target="_blank"} Marketo 관리에서.

1. 마케팅 활동에서 Smart Campaign으로 이동하고 **예약**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-1.png)

1. 스마트 캠페인 설정에서 **[!UICONTROL 편집]**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >기본 제한은 Admin에 설정된 제한입니다.

1. 새 한도를 입력한 다음 을(를) 클릭합니다. **[!UICONTROL 저장]**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-3.png)

   자격 조건을 갖춘 사람 수가 설정된 제한을 초과할 경우 스마트 캠페인이 실행되지 않습니다.

   >[!CAUTION]
   >
   >이 기능을 주의해서 실수로 너무 많은 사람을 포함하지 않도록 하십시오.

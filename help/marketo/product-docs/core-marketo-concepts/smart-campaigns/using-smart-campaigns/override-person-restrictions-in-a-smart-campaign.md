---
unique-page-id: 1147066
description: 스마트 캠페인에서 개인 제한 무시 - Marketo 문서 - 제품 설명서
title: 스마트 캠페인에서 개인 제한 무시
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
source-git-commit: bb628e5211601bd8b424c78cae887c2eeb0614cf
workflow-type: tm+mt
source-wordcount: '138'
ht-degree: 0%

---

# 스마트 캠페인에서 개인 제한 무시 {#override-person-restrictions-in-a-smart-campaign}

Marketo을 사용하면 스마트 캠페인에 적합한 최대 사용자 수를 설정할 수 있습니다. 이렇게 하면 실수로 전체 데이터베이스를 이메일로 보내는 것을 방지할 수 있습니다. 원한다면 _재정의_ 이 한계, 방법이 있습니다.

>[!PREREQUISITES]
>
>반드시 다음을 수행하십시오 [스마트 캠페인에 대한 개인 제한 활성화](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md) Marketo Admin에 로그인되어 있는지 확인하십시오.

1. 마케팅 활동에서 스마트 캠페인으로 이동하여 를 클릭합니다 **예약**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-1.png)

1. 스마트 캠페인 설정에서 **편집**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >기본 제한은 관리자에 설정된 것입니다.

1. 새 제한을 입력한 다음 **저장.**

   ![](assets/override-person-restrictions-in-a-smart-campaign-3.png)

   자격이 있는 사람 수가 설정된 제한을 초과하는 경우 스마트 캠페인이 실행되지 않습니다.

   >[!CAUTION]
   >
   >실수로 너무 많은 사람을 포함하지 않도록 이 기능을 주의하십시오.

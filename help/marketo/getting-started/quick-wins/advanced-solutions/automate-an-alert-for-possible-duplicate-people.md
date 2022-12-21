---
unique-page-id: 7513680
description: 가능한 중복 사람에 대한 경고 자동화 - Marketo 문서 - 제품 설명서
title: 가능한 중복 사람에 대한 경고 자동화
exl-id: 596c03f4-7a84-4564-bbe1-e7bc0d22a616
source-git-commit: 50fc46312d2c7c25556994fad4e118c01cf92fc0
workflow-type: tm+mt
source-wordcount: '178'
ht-degree: 0%

---

# 가능한 중복 사람에 대한 경고 자동화 {#automate-an-alert-for-possible-duplicate-people}

가능한 중복 사용자가 생성될 때마다 알림을 받으려는 경우? 다음은 스마트 캠페인을 설정하여 수행하는 방법입니다.

1. [새 스마트 캠페인 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md){target=&quot;_blank&quot;}. 다음 스마트 목록을 정의합니다.

* 트리거: **사람이 생성됨**
* 필터: **필드가 중복되었습니다.** 필드 이름 **전체 이름**

   ![](assets/automate-an-alert-1.png)

   >[!TIP]
   >
   >창의적이 되어라. 다양한 필드를 실험하여 필터링 결과를 얻을 수 있습니다.

1. 흐름 단계에서 [경고 보내기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md){target=&quot;_blank&quot;} 흐름 작업.

   ![](assets/automate-an-alert-2.png)

   >[!TIP]
   >
   >사용 [경고 정보 토큰 보내기](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md)CRM에 있는 사람에 대한 링크를 포함하도록 {target=&quot;_blank&quot;}.

   >[!CAUTION]
   >
   >큰 목록을 가져올 경우 이러한 경고를 한꺼번에 받을 수 있습니다.
   >
   >또한, 같은 이름을 가진 두 사람이 자동적으로 같은 사람이라는 것을 의미하지는 않는다.

1. 에서 캠페인을 활성화합니다 **예약** 탭.

   ![](assets/automate-an-alert-3.png)

됐습니다. 이 스마트 캠페인은 Marketo에서 기존 전체 이름을 가진 새 사람을 만들 때마다 트리거됩니다.

>[!MORELIKETHIS]
>
>[중복 사람 찾기 및 병합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md){target=&quot;_blank&quot;}

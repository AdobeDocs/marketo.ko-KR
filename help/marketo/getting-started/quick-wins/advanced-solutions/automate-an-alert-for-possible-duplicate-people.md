---
unique-page-id: 7513680
description: 가능한 중복 사람에 대한 경고 자동화 - Marketing To Docs - 제품 설명서
title: 가능한 중복 사람에 대한 경고 자동화
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '170'
ht-degree: 0%

---


# 가능한 중복 사람에 대한 경고 자동화 {#automate-an-alert-for-possible-duplicate-people}

중복 사용자가 생성될 때마다 경고를 설정하시겠습니까? 스마트 캠페인을 설정하는 방법은 다음과 같습니다.

1. [새로운 스마트 캠페인을 만듭니다](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md). 다음 스마트 목록을 정의합니다.

* 트리거: **사람이 만들어짐**
* 필터: **중복 필드.** 필드 이름 **이 전체 이름입니다.**

   ![](assets/image2017-3-27-8-3a22-3a4.png)

   >[!TIP]
   >
   >창의적인 아이디어 표현 여러 필드를 실험해 보면서 필터링 결과를 얻을 수 있습니다.

1. 흐름 단계에서 경고 [흐름](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) 전송 작업을 선택합니다.

   ![](assets/image2017-3-27-8-3a24-3a8.png)

   >[!TIP]
   >
   >CRM [에 있는](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) 사람에 대한 링크를 포함하려면 [알림 정보 보내기] 토큰을 사용합니다.

   >[!CAUTION]
   >
   >큰 목록을 가져오면 이러한 경고가 한꺼번에 많이 표시될 수 있습니다.
   >
   >또한, 이름이 같은 두 사람이 자동으로 같은 사람임을 의미하지는 않습니다.

1. 예약 탭에서 **캠페인을** 활성화합니다.

   ![](assets/image2017-3-27-8-3a24-3a37.png)

바로 그거야! 이 스마트 캠페인은 Marketing에서 기존 전체 이름을 가진 새 사람을 만들 때마다 트리거됩니다.

>[!MORELIKETHIS]
>
>[중복 인물 찾기 및 병합](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md)

---
unique-page-id: 7513680
description: 가능한 중복 사람에 대한 경고 자동화 - Marketing To Docs - 제품 설명서
title: 가능한 중복 사람에 대한 경고 자동화
translation-type: tm+mt
source-git-commit: 3c24395e55c756184615941327e15e050fa7d0ac
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 0%

---


# 가능한 중복 사람에 대한 경고 자동화 {#automate-an-alert-for-possible-duplicate-people}

가능한 중복 사용자가 생성될 때마다 경고를 설정하시겠습니까? 스마트 캠페인을 설정하는 방법은 다음과 같습니다.

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

1. [새로운 스마트 캠페인을 만듭니다](../../../product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md). 다음 스마트 목록을 정의합니다.

   * 트리거: **사람이 만들어짐**
   * 필터:**중복 필드. **필드 이름 **은** 전체 **이름입니다**.

   ![](assets/image2017-3-27-8-3a22-3a4.png)

   >[!TIP]
   >
   >창의적인 아이디어 표현 여러 필드를 실험해 보고 더 나은 필터링 결과를 얻을 수 있습니다.

1. 흐름 단계에서 경고 [흐름](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) 전송 작업을 선택합니다.

   ![](assets/image2017-3-27-8-3a24-3a8.png)

   >[!TIP]
   >
   >CRM에 있는 [사람에 대한 링크를 포함하려면 알림 정보 전송 토큰을](../../../product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) 사용하십시오.

   >[!CAUTION]
   >
   >큰 목록을 가져오면 여러 개의 경고가 한꺼번에 나타날 수 있습니다.
   >
   >
   >또한, 같은 이름을 가진 두 사람이 자동으로 같은 사람이라는 의미는 아닙니다.

1. 예약 **탭에서 캠페인을** 활성화합니다.

   ![](assets/image2017-3-27-8-3a24-3a37.png)

바로 그거야! 이 스마트 캠페인은 Marketing To에서 기존 전체 이름을 가진 새 사람을 만들 때마다 트리거됩니다.

>[!MORELIKETHIS]
>
>* [중복 사용자 찾기 및 병합](../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md)


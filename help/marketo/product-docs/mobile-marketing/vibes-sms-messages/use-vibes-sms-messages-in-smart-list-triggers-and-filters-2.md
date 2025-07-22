---
description: 스마트 목록 트리거 및 필터 - Marketo 문서 - 제품 설명서에서 Vibes SMS 메시지 사용
title: 스마트 목록 트리거 및 필터에서 SMS 메시지 보기 사용
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 0%

---

# 스마트 목록 트리거 및 필터에서 SMS 메시지 보기 사용 {#use-vibes-sms-messages-in-smart-list-triggers-and-filters}

[Vibes SMS 메시지를 만들고](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-a-vibes-sms-message.md){target="_blank"} 나면 Smart Campaign 내의 Smart List 트리거 및 필터를 사용하여 혜택을 얻을 수 있습니다. 방법은 다음과 같습니다.

1. 내 Marketo에서 **[!UICONTROL Marketing Activities]**&#x200B;을(를) 클릭합니다.

   ![](assets/use-vibes-sms-messages-in-smart-list-triggers-and-filters-1.png)

1. SMS 자산을 사용할 스마트 캠페인을 선택합니다. 트리거 위로 드래그합니다. 이 예제에서는 **양식 작성**&#x200B;을 사용합니다.

   ![](assets/fills-out-form-pull-over.jpg)

## SMS 트리거 {#sms-triggers}

사용할 수 있는 다른 SMS 트리거가 있습니다. SMS 트리거는 Vibes 서비스가 활성화된 경우에만 표시됩니다.

SMS 메시지 보내기:

* 마케팅 활동 > 새 스마트 캠페인 선택
   * 스마트 목록 > 비디오 목록 선택 필터 및 올바른 논리 > 비디오 목록: 드롭다운에서 목록 선택(Vibes 플랫폼에서 동기화되는 모바일 데이터베이스 목록)
      * 세분화를 수행하고 하나의 캠페인 내에서 SMS 및 이메일 필터와 트리거를 활용할 수 있음
      * 비디오 필터: 비디오 목록과 비디오 목록 구성원 비교 - 로직이 이메일과 일치함
         * Vibes 목록 구독 - 현재 구독 취소되었더라도 해당 Vibes 목록에 등록한 적이 있는 참가자.  - 크로스 채널 마케팅 활동에 주로 활용됨
            * 참고: Vibes 모바일 데이터베이스 목록에 없는 경우 구독을 취소한 사용자에게는 SMS 메시지가 전송되지 않습니다
         * 바이브 목록 구성원 - 활성, 확인된 구독자
         * 목록에 추가됨 - 비디오 목록이 이 필터로 채워지지 않습니다. Marketo 목록용입니다.

![](assets/new-sms-search2.png)

다음은 몇 가지 예입니다.

**SMS 메시지 반송** 트리거는 SMS 메시지가 반송될 때 전자 메일 전송과 같은 흐름을 시작합니다.

![](assets/sms-message-bounces-real.jpg)

**[!UICONTROL Subscribes to Vibes List]** 트리거는 사용자가 구독할 때 흐름을 시작합니다.

![](assets/subscribes-to-vibes-list-real.jpg)

**[!UICONTROL Clicks Link in SMS Message]** 트리거는 사용자가 SMS 메시지의 링크를 클릭하면 흐름을 시작합니다.

![](assets/clicks-link-in-sms-message.jpg)

## SMS 필터 {#sms-filters}

스마트 목록에서 바이브 필터를 사용할 수도 있습니다. **[!UICONTROL Subscribed to Vibes List]** 필터는 *ever*&#x200B;을(를) 구독하는 모든 사용자를 찾습니다. 삭제된 사람이 흐름에서 생략되더라도 여기에는 구독 취소자와 삭제된 사람이 모두 포함됩니다. 이 필터는 보고에 가장 적합합니다.

![](assets/subscribed-to-vibes-list-filter-real.jpg)

반대로 **Vibes 목록 구성원** 필터는 현재 Vibes를 구독한 _모든 사용자_&#x200B;를 찾아 스마트 캠페인이나 목록에서 사용하기에 가장 적합합니다.

![](assets/image001.png)

>[!NOTE]
>
>모든 SMS 필터에는 기본적으로 **[!UICONTROL Date of Activity]** 제약 조건이 포함됩니다.

스마트 목록에서 Vibes 트리거 및 필터를 설정한 후에는 [흐름을 정의](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/add-a-flow-step-for-sms.md)할 수 있습니다.

>[!MORELIKETHIS]
>
>* [스마트 캠페인용 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [스마트 목록에 필터 찾기 및 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)

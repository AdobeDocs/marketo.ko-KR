---
description: 스마트 목록 트리거 및 필터 - Marketo 문서 - 제품 설명서에서 SMS 옵션 사용
title: 스마트 목록 트리거 및 필터의 SMS 옵션 사용
hide: true
hidefromtoc: true
feature: Mobile Marketing
source-git-commit: 8e56b571a34451d6b0436dc041efaf0fd575db36
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 0%

---

# 스마트 목록 트리거 및 필터의 SMS 옵션 사용 {#use-sms-options-in-smart-list-triggers-and-filters}

새 문서

이후 [sms 메시지 만들기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-an-sms-message.md){target="_blank"}, 스마트 캠페인 내의 스마트 목록 트리거 및 필터를 사용하여 이점을 얻고자 합니다.

>[!PREREQUISITES]
>
>SMS 트리거/필터는 [Vibes 서비스가 활성화되었습니다.](/help/marketo/product-docs/mobile-marketing/admin/add-vibes-as-a-launchpoint-service.md).

## SMS 트리거 {#sms-triggers}

<table>
  <tr>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-1.png"></td>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-2.png"></td>
  </tr>
</table>

다음은 몇 가지 예입니다.

다음 **SMS 메시지 반송** 트리거는 SMS 메시지가 반송될 때 이메일 전송과 같은 흐름을 시작합니다.

다음 **비디오 구독 목록** 트리거는 사용자가 구독할 때 흐름을 시작합니다.

다음 **SMS 메시지의 링크 클릭** 트리거는 사용자가 SMS 메시지의 링크를 클릭하면 흐름을 시작합니다.

## SMS 필터 {#sms-filters}

<table>
  <tr>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-3.png"></td>
    <td><img src="assets/use-sms-options-in-smart-list-triggers-and-filters-4.png"></td>
  </tr>
</table>

스마트 목록에서 바이브 필터를 사용할 수도 있습니다. 다음 **구독 중인 비디오 목록** 다음 권한이 있는 모든 사람을 찾습니다. *이제까지* 비디오 구독 중. 삭제된 사람이 흐름에서 생략되더라도 여기에는 구독 취소자와 삭제된 사람이 모두 포함됩니다. 이 필터는 보고에 가장 적합합니다.

그와 대조적으로 **바이브 목록 멤버** 필터 찾기 _모든 사용자_ 현재 Vibes를 구독하고 있으며 스마트 캠페인 또는 목록에서 사용하기에 가장 적합합니다.

>[!NOTE]
>
>모든 SMS 필터에는 **활동 날짜** 기본적으로 제약 조건.

Smart List에서 Vibes 트리거 및 필터를 설정한 후 다음을 수행할 수 있습니다. [플로우 정의](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/add-a-flow-step-for-sms.md).

>[!MORELIKETHIS]
>
>* [SMS 메시지 보내기](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/send-an-sms-message.md)
>* [스마트 캠페인을 위한 스마트 목록 정의 | 트리거](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [스마트 목록 필터 찾기 및 추가](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)

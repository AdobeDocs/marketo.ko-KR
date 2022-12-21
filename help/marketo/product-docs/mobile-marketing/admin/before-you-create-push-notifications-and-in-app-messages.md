---
unique-page-id: 11376159
description: 푸시 알림 및 인앱 메시지를 만들기 전에 - Marketo 문서 - 제품 설명서
title: 푸시 알림 및 인앱 메시지를 만들기 전에
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '352'
ht-degree: 0%

---

# 푸시 알림 및 인앱 메시지를 만들기 전에 {#before-you-create-push-notifications-and-in-app-messages}

푸시 알림 및 인앱 메시지를 만드는 것은 어렵지 않지만, 시작하려면 먼저 모든 것을 준비해야 합니다. Marketo 관리자 및 모바일 앱 개발자는 아래 단계에 따라 필요한 통합을 준비해야 합니다.

1. 먼저, Marketo 관리자 [모바일 앱 추가](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md).

1. 그러면 Marketo 관리자 [코드 조각을 개발자에게 보냅니다.](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. 개발자는 SDK를 다운로드하고 다음을 위한 코드 조각 및 기타 메서드를 포함합니다. [Android](https://developers.marketo.com/documentation/mobile/installation-instructions-on-android/) 또는 [iOS](https://developers.marketo.com/documentation/mobile/installation-instructions-on-ios/).

1. 기본적으로 인앱 메시지는 앱이 열릴 때 트리거됩니다. 특정 페이지를 보거나 특정 단추를 누르는 경우와 같이 다른 이벤트에 대한 메시지를 트리거하려면 개발자가 사용자 지정 이벤트를 코드에 추가해야 합니다(참조) [인앱 메시지에 대한 사용자 지정 이벤트](#CustomEvents) 아래에 표시됩니다.

1. 개발자 [android용 서버 API 키 및 프로젝트 번호 생성](https://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-android/) 또는 [iOS용 인증 및 암호](https://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-ios/) 및에서 Marketo 관리자에게 전송합니다.

1. Marketo 관리자는 푸시 알림 액세스를 구성합니다 [서버 API 키(Android)와 함께 사용](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) 또는 [인증서 사용(iOS)](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md).

>[!TIP]
>
>Marketo 관리자는 푸시 구성이 확인되었는지 확인하기 쉽습니다. 그냥 가 [여기](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md).

## 인앱 메시지에 대한 사용자 지정 이벤트 {#custom-events-for-in-app-messages}

인앱 메시지의 경우 디스플레이 트리거가 **앱 열기** 기본적으로 제공됩니다. 사용자 지정 이벤트를 사용하여 인앱 메시지 표시를 트리거하려는 경우(예: **장바구니에 추가 클릭**, **보기 설정 페이지**)를 클릭하여 원하는 이벤트 목록을 만들어 모바일 앱 개발자에게 제공합니다. 그러면 개발자가 사용자 지정 이벤트를 코드에 추가합니다. 승인되면 대상을 설정할 때 디스플레이 트리거로 표시됩니다. **주의**: 사용자 지정 이벤트 코딩 승인 프로세스를 완료하는 데 시간이 걸릴 수 있습니다.

인앱 메시지 및 푸시 알림에 대한 모든 준비를 마쳤으면 지금이 바로 시작할 적기입니다!

>[!MORELIKETHIS]
>
>* [인앱 메시지 만들기](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [푸시 알림 만들기](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)


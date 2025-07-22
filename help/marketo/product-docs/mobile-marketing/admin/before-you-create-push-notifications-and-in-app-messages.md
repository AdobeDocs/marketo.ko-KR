---
unique-page-id: 11376159
description: 푸시 알림 및 인앱 메시지를 만들기 전에 - Marketo 문서 - 제품 설명서
title: 푸시 알림 및 인앱 메시지를 만들기 전에
exl-id: c7e24338-387b-4c6f-bb29-7f7e6a1a7de5
feature: Mobile Marketing
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 0%

---

# 푸시 알림 및 인앱 메시지를 만들기 전에 {#before-you-create-push-notifications-and-in-app-messages}

푸시 알림 및 인앱 메시지를 만드는 것은 어렵지 않지만 시작하려면 먼저 모든 준비가 되어 있어야 합니다. Marketo 관리 및 모바일 앱 개발자는 아래 단계에 따라 필요한 통합을 준비해야 합니다.

1. 먼저 Marketo 관리자 [이(가) 모바일 앱을 추가합니다](/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md).

1. 그런 다음 Marketo 관리자는 [개발자에게 코드 조각을 보냅니다](/help/marketo/product-docs/mobile-marketing/admin/send-sdk-code-to-a-developer.md).

1. 개발자는 SDK을 다운로드하고 [Android](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) 또는 [iOS](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-ios)에 대한 코드 조각 및 기타 메서드를 포함합니다.

1. 기본적으로 인앱 메시지는 앱이 열릴 때 트리거됩니다. 특정 페이지를 보거나 특정 단추를 누르는 경우와 같이 다른 이벤트에 대한 메시지를 트리거하려면 개발자가 사용자 지정 이벤트를 코드에 추가해야 합니다(아래 [인앱 메시지에 대한 사용자 지정 이벤트](#CustomEvents) 참조).

1. 개발자 [Android에 대한 서버 API 키 및 프로젝트 번호](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/mobile/installation#how-to-install-marketo-sdk-on-android) 또는 [iOS에 대한 인증 및 암호](https://experienceleague.adobe.com/ko/docs/marketo-developer/marketo/mobile/installation#install-marketo-sdk-on-ios)를 생성하여 Marketo 관리자에게 보냅니다.

1. Marketo 관리자는 푸시 알림 액세스 [서버 API 키(Android)로 ](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-android-push-access.md) 또는 [인증서(iOS)로 ](/help/marketo/product-docs/mobile-marketing/admin/configure-mobile-app-ios-push-access.md)을(를) 구성합니다.

>[!TIP]
>
>Marketo 관리자는 푸시 구성이 확인되었는지 쉽게 확인할 수 있습니다. [여기](/help/marketo/product-docs/mobile-marketing/admin/verify-push-configuration.md)로 이동하세요.

## 인앱 메시지에 대한 사용자 지정 이벤트 {#custom-events-for-in-app-messages}

인앱 메시지의 경우 기본적으로 표시 트리거가 **[!UICONTROL App Open]**(으)로 설정됩니다. 사용자 지정 이벤트를 사용하여 인앱 메시지 표시를 트리거하려면(예: **장바구니에 추가 클릭**, **설정 페이지 보기**) 원하는 이벤트 목록을 만들어 모바일 앱 개발자에게 제공하십시오. 그런 다음 개발자는 사용자 지정 이벤트를 코드에 추가합니다. 승인된 후에는 대상을 설정할 때 표시 트리거로 표시됩니다. **주의**: 사용자 지정 이벤트 코딩 승인 프로세스를 완료하는 데 시간이 걸릴 수 있습니다.

인앱 메시지 및 푸시 알림에 대한 모든 준비가 완료되면 시작할 수 있습니다.

>[!MORELIKETHIS]
>
>* [인앱 메시지 만들기](/help/marketo/product-docs/mobile-marketing/in-app-messages/creating-in-app-messages/create-an-in-app-message.md)
>
>* [푸시 알림 만들기](/help/marketo/product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)

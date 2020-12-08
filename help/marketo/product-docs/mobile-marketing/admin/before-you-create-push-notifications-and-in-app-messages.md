---
unique-page-id: 11376159
description: 푸시 알림 및 인앱 메시지를 만들기 전에 - Marketing Docs - 제품 설명서
title: 푸시 알림 및 인앱 메시지를 만들기 전
translation-type: tm+mt
source-git-commit: d88fb92a00e4c20509617e6ef8b2e51b66cc085b
workflow-type: tm+mt
source-wordcount: '362'
ht-degree: 0%

---


# 푸시 알림 및 인앱 메시지를 만들기 전 {#before-you-create-push-notifications-and-in-app-messages}

푸시 알림 및 인앱 메시지를 만드는 것은 어렵지 않지만 시작하기 전에 모든 것을 준비해야 합니다. Marketing To Admin 및 모바일 앱 개발자는 필요한 통합을 준비하려면 아래 단계를 따라야 합니다.

1. 먼저, 마케팅 관리자가 모바일 앱 [을 추가합니다](add-a-mobile-app.md)
1. 그런 다음 마케팅 관리자가 코드 조각을 개발자에게 [보냅니다](send-sdk-code-to-a-developer.md)
1. 개발자는 SDK를 다운로드하고 Android [또는](http://developers.marketo.com/documentation/mobile/installation-instructions-on-android/) [iOS용 코드 조각 및 기타 메서드를 포함합니다](http://developers.marketo.com/documentation/mobile/installation-instructions-on-ios/)
1. 기본적으로 인앱 메시지는 앱이 열릴 때 트리거됩니다. 특정 페이지를 보거나 특정 단추를 누르는 등 다른 이벤트에 대한 메시지를 트리거하려면 개발자가 사용자 지정 이벤트를 코드에 추가해야 합니다(아래 [인앱 메시지에 대한 사용자 지정 이벤트 참조](#CustomEvents) )
1. 개발자는 [Android용 서버 API 키와 프로젝트 번호](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-android/) 또는 iOS용 인증 및 암호 [를 생성하여 Marketing](http://developers.marketo.com/documentation/mobile/enabling-push-notifications-on-ios/) Admin으로 전송합니다
1. 마케팅 관리자는 서버 API 키(Android) [또는 인증서(iOS)](configure-mobile-app-android-push-access.md) [를 사용하여 푸시 알림 액세스 권한을 구성합니다.](configure-mobile-app-ios-push-access.md)

>[!TIP]
>
>Marketing To 관리자는 푸시 구성이 확인되었는지 확인하는 것이 쉽습니다. 그냥 [여기](verify-push-configuration.md)가세요

## 인앱 메시지에 대한 사용자 지정 이벤트 {#custom-events-for-in-app-messages}

인앱 메시징의 경우 기본적으로 디스플레이 트리거가 **앱** 열기를 설정합니다. 사용자 지정 이벤트를 사용하여 인앱 메시지 표시(예: 장바구니에 추가, **보기 설정 페이지******)를 트리거하려면 원하는 이벤트 목록을 만들어 모바일 앱 개발자에게 제공합니다. 그러면 개발자는 사용자 지정 이벤트를 코드에 추가합니다. 승인되면 대상을 설정할 때 표시 트리거로 표시됩니다. **주의**:사용자 지정 이벤트 코딩 승인 프로세스를 완료하는 데 시간이 걸릴 수 있습니다.

인앱 메시지 및 푸시 알림에 대한 모든 준비가 완료되면 시작할 때입니다!

>[!NOTE]
>
>**관련 문서**
>
>* [인앱 메시지 만들기](http://docs.marketo.com/display/docs/create+an+in-app+message)
   >
   >
* [푸시 알림 만들기](../../../product-docs/mobile-marketing/push-notifications/create-a-push-notification.md)

>




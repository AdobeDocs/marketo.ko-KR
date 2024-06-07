---
unique-page-id: 7512454
description: 모바일 푸시 알림 구성 - Marketo 문서 - 제품 설명서
title: 모바일 푸시 알림 구성
exl-id: 10368b13-40c9-435a-847c-68aaa5a892ea
feature: Mobile Marketing
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '466'
ht-degree: 0%

---

# 모바일 푸시 알림 구성 {#configure-mobile-push-notification}

1. 로 이동 **마케팅 활동** 영역입니다.

![](assets/2fbf1ab6-2247-40c8-980d-be56b9d94890.png)

1. 푸시 에셋을 선택하고 **초안 편집**.

   ![](assets/image2016-8-23-16-3a49-3a48.png)

1. 다음으로 이동 **설정**.

   ![](assets/image2016-8-23-16-3a51-3a56.png)

1. 원하는 앱을 선택합니다. Android 및 Apple 플랫폼은 기본적으로 활성화되어 있습니다.

   ![](assets/image2016-8-23-16-3a53-3a33.png)

1. 푸시 메시지가 한 플랫폼(예: iPhone의 경우)에만 적용되는 경우 해당 선택기를 비활성화로 밀어 다른 플랫폼을 제외할 수 있습니다.

   ![](assets/image2016-8-23-16-3a41-3a48.png)

1. 클릭 **다음**.

   ![](assets/image2016-8-23-16-3a43-3a28.png)

1. 메시지 텍스트를 입력하거나 토큰 아이콘을 선택하여 토큰을 추가합니다. 그런 다음 을 선택합니다. **탭 작업**.

   ![](assets/image2015-9-14-16-3a7-3a43.png)

   >[!NOTE]
   >
   >플랫폼이 활성화되면 휴대폰 화면 디스플레이의 왼쪽에 표시됩니다. 선택하면 색상으로 표시됩니다.

   >[!NOTE]
   >
   >세 가지 유형의 탭 작업이 있습니다.
   >
   >**앱 실행** - **이 앱** 알림을 탭하면 앱의 홈 페이지가 열립니다. **사용자 정의** 는 딥링크를 사용하여 앱의 다른 영역 또는 링크가 있는 다른 앱을 엽니다(참조) [딥링크 URI](#Deeplink) (자세한 내용은 아래 참조).
   >
   >**랜딩 페이지** - 지정된 Marketo 랜딩 페이지로 이동합니다.
   >
   >**외부 URL** - Marketo이 아닌 랜딩 페이지로 이동합니다.

1. 사용자 지정 탭 작업에 대한 딥 링크를 삽입하려면 사용자 지정 을 클릭하고 [딥링크 URI](#Deeplink) 필드에서.

   ![](assets/image2016-7-28-16-3a19-3a13.png)

1. 토큰을 삽입하려면 토큰을 선택하고 기본값을 입력한 다음 삽입을 클릭합니다.

   >[!NOTE]
   >
   >텍스트 상자에 커서를 놓은 위치에 토큰이 나타납니다. 두 개 이상의 토큰을 사용할 수 있습니다.

   ![](assets/image2015-8-10-14-3a48-3a52.png)

   >[!NOTE]
   >
   >메시지 및 탭 작업은 두 플랫폼에서 동일하게 표시됩니다.

1. iOS의 경우에만 확인란을 선택하여 메시지가 도착할 때 앱에서 사운드를 재생하도록 합니다. Android는 자동으로 사운드를 재생합니다.

   ![](assets/ios-tap-and-notification-hand.png)

1. 다른 플랫폼 미리 보기 및 클릭 **완료**.

   ![](assets/image2015-9-14-16-3a12-3a34.png)

1. 클릭 **승인 및 닫기**.

   ![](assets/323dda12-0543-4558-8562-563eed5fa0e0.png)

축하합니다! 이제 푸시 알림을 전송할 준비가 되었습니다.

## 딥링크 URI {#deep-link-uris}

구독자가 푸시 메시지의 버튼을 클릭하면 앱의 홈 페이지로 이동하거나 앱 내의 특정 페이지로 바로 이동할 수 있습니다. 딥링크는 앱의 특정 페이지에 대한 고유 참조이며 웹 사이트 링크와 매우 유사합니다.

딥링크 URI는 스키마 이름, 경로 및 식별자의 세 부분으로 구성됩니다. 아래 예에서 &quot;myappname&quot;은 체계입니다. &quot;products&quot;가 경로이고 &quot;purple-shirt&quot;가 식별자입니다. 고객이 탭하면 앱의 제품 페이지 내에 있는 보라색 셔츠 항목으로 특별히 이동합니다.

![](assets/image2016-7-29-12-3a49-3a1.png)

즉, 앱의 딥링크 구조는 위의 예와 다를 수 있습니다. 개발자는 딥링크 URI를 정의하는 데 여러 가지 옵션을 사용할 수 있으므로 개발자에게 사용하려는 페이지의 URI(링크)를 보내도록 요청하십시오. 이렇게 하면 푸시 메시지에 입력한 URI가 올바른 위치를 가리킵니다. 개발자는 [여기에서 추가 정보 찾기](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mobile/enabling-deep-links-in-your-app).

>[!MORELIKETHIS]
>
>[모바일 푸시 알림 보내기](/help/marketo/product-docs/mobile-marketing/push-notifications/send-a-mobile-push-notification.md)

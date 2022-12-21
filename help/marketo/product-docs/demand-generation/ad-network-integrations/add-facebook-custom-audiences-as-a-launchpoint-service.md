---
unique-page-id: 4720257
description: LaunchPoint Service로 Facebook 사용자 지정 대상 추가 - Marketo 문서 - 제품 설명서
title: facebook 사용자 지정 대상을 LaunchPoint 서비스로 추가
exl-id: 5c5b5c80-fd0f-482a-8163-6eef3dbcb236
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '324'
ht-degree: 0%

---

# facebook 사용자 지정 대상을 LaunchPoint 서비스로 추가 {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**관리 권한 필요**

이 통합을 통해 Marketo 정적 및 스마트 목록에서 대상 데이터를 Facebook으로 전송하여 Facebook 광고 캠페인에서 사용자 지정 대상으로 사용할 수 있습니다. 설정 방법은 다음과 같습니다.

1. Marketo으로 이동 **관리**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. 이동 **LaunchPoint**&#x200B;를 클릭하고 **새로 만들기** 을(를) 선택합니다. **새 서비스**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. 을(를) 입력합니다. **표시 이름** 서비스에 대해 을(를) 선택하고 을(를) 선택합니다. **Facebook 사용자 지정 대상** 서비스 제공 **서비스** 드롭다운.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. 동일한 브라우저에서 새 탭을 열고 다음 위치로 이동합니다. [facebook.com](https://www.facebook.com/). 통합에 사용할 계정을 사용하여 Facebook에 로그인합니다.

   >[!CAUTION]
   >
   >Marketo이 여러 Ad Manager 계정에 걸쳐 대상을 전송하려면 다음 단계에서 승인하는 Facebook 사용자는 액세스 권한이 있어야 합니다 *모두* 이 두 가지 계정이 있습니다.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. facebook에 로그인하고 나면 Marketo으로 돌아갑니다. 클릭 **권한 부여**.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >사용자 _반드시_ 사용자 지정 대상 통합이 작동하려면 Facebook Business Manager 계정을 사용하십시오. Business Manager 계정을 설정하는 방법에 대해 알아보려면 [Facebook 도움말](https://www.facebook.com/business/help/1710077379203657).

1. 메시지가 표시되면 을 클릭합니다 **확인** facebook에 Marketo 앱 설치를 수락하려면 다음을 수행하십시오.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. 이제 권한이 있습니다! 일치 모드를 선택하고 를 클릭합니다 **만들기**.

   >[!NOTE]
   >
   >**기본 일치** 은 이메일 주소만 사용합니다. **고급 일치** 에서는 더 많은 전환을 위해 일치율을 높이는 7개의 추가 필드를 사용합니다. 하지만 회사의 개인정보 처리방침에서 추가 필드 공유를 허용하지 않거나 데이터에 추가 필드가 포함되지 않은 경우 기본 일치를 선택합니다.

   ![](assets/fb-custom-adv-matching-hands.png)

   잘했어요! 이제 Marketo의 모든 정적 또는 스마트 목록으로 이동한 후 대상 데이터를 Facebook으로 보낼 수 있습니다.

   >[!CAUTION]
   >
   >오, 가기 전에 [facebook의 사용자 지정 대상 약관에 동의합니다](https://www.facebook.com/ads/manage/customaudiences/tos.php) facebook 계정 내에서 사용할 수 있습니다. 이렇게 하지 않으면 대상 업데이트가 실패합니다.

>[!MORELIKETHIS]
>
>* [facebook에서 사용자 지정 대상 만들기](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md)
>
>* [facebook 리드 광고 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)


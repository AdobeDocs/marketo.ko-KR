---
unique-page-id: 4720257
description: facebook 사용자 지정 대상을 LaunchPoint 서비스로 추가 - Marketo 문서 - 제품 설명서
title: facebook 사용자 지정 대상을 LaunchPoint Service로 추가
exl-id: 5c5b5c80-fd0f-482a-8163-6eef3dbcb236
feature: Integrations
source-git-commit: bebf61037f37a06b40b4d9c1df872f1cf62a1403
workflow-type: tm+mt
source-wordcount: '315'
ht-degree: 0%

---

# facebook 사용자 지정 대상을 LaunchPoint Service로 추가 {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**관리자 권한 필요**

이 통합을 통해 Marketo Engage 정적 및 스마트 목록의 대상 데이터를 Facebook으로 전송하여 Facebook 광고 캠페인에서 사용자 지정 대상으로 사용할 수 있습니다. 설정 방법은 다음과 같습니다.

1. Marketo **[!UICONTROL 관리자]**(으)로 이동합니다.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. **[!UICONTROL LaunchPoint]**(으)로 이동하고 **[!UICONTROL 새로 만들기]**&#x200B;를 클릭한 다음 **[!UICONTROL 새 서비스]**&#x200B;를 선택하십시오.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. 서비스에 대한 **[!UICONTROL 표시 이름]**&#x200B;을(를) 입력하고 **[!UICONTROL 서비스]** 드롭다운에서 **[!UICONTROL Facebook 사용자 지정 대상]** 서비스를 선택합니다.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. 같은 브라우저에서 새 탭을 열고 [facebook.com](https://www.facebook.com/){target="_blank"}(으)로 이동합니다. 통합에 사용할 계정을 사용하여 Facebook에 로그인합니다.

   >[!CAUTION]
   >
   >Marketo에서 여러 Ad Manager 계정에 대상자를 보내려면 다음 단계에서 권한을 부여한 Facebook 사용자가 이러한 계정의 *모두*&#x200B;에 액세스할 수 있어야 합니다.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. facebook에 로그인한 후 Marketo으로 돌아갑니다. **[!UICONTROL 승인]**&#x200B;을 클릭합니다.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >사용자 지정 대상 통합이 작동하려면 _반드시_ Facebook Business Manager 계정을 사용해야 합니다. Business Manager 계정을 설정하는 방법은 [Facebook 도움말](https://www.facebook.com/business/help/1710077379203657){target="_blank"}을 참조하세요.

1. 메시지가 표시되면 **[!UICONTROL 확인]**&#x200B;을 클릭하여 Facebook에 Marketo 앱 설치를 수락합니다.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. 이제 권한이 부여되었습니다! 일치하는 모드를 선택하고 **[!UICONTROL 만들기]**&#x200B;를 클릭합니다.

   >[!NOTE]
   >
   >**기본 일치**&#x200B;에서는 전자 메일 주소만 사용합니다. **고급 일치**&#x200B;에서는 7개의 추가 필드를 사용하므로 더 많은 전환을 위해 일치율이 증가합니다. 그러나 회사 개인정보 처리방침에서 추가 필드 공유를 허용하지 않거나 데이터에 포함되지 않은 경우 기본 일치를 선택합니다.

   ![](assets/fb-custom-adv-matching-hands.png)

   좋습니다! 이제 Marketo의 모든 정적 또는 스마트 목록으로 이동하여 대상 데이터를 Facebook으로 보낼 수 있습니다.

   >[!CAUTION]
   >
   >오가기 전에 Facebook 계정에서 [Facebook의 사용자 지정 대상 약관에 동의](https://www.facebook.com/ads/manage/customaudiences/tos.php){target="_blank"}하세요! 이렇게 하지 않으면 대상자 업데이트가 실패합니다.

>[!MORELIKETHIS]
>
>* [Facebook에서 사용자 지정 대상 만들기](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md){target="_blank"}
>
>* [Facebook 리드 광고 설정](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md){target="_blank"}

---
unique-page-id: 7513865
description: Microsoft Dynamics 2015에서 Marketo Sales Insight 설치 및 구성 - Marketo 설명서 - 제품 설명서
title: Microsoft Dynamics 2015에 Marketo Sales Insight 설치 및 구성
exl-id: 26c1f02c-c910-445d-8560-0b37961eadcb
feature: Marketo Sales Insights
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '370'
ht-degree: 4%

---

# [!DNL Marketo Sales Insight]에서 [!DNL Microsoft Dynamics 2015] 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight은 영업 팀에 마케팅 팀이 보유한 풍부한 데이터를 &quot;창&quot;으로 전달할 수 있는 환상적인 도구입니다. [!DNL Microsoft Dynamics 2015]에서 설치하고 구성하는 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>[&#x200B; 버전에 대해 &#x200B;](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md)올바른 솔루션을 다운로드하십시오[!DNL Microsoft Dynamics CRM].

## 솔루션 가져오기 {#import-solution}

이제 [!DNL Marketo Sales Insight] 솔루션을 [!DNL Microsoft Dynamics]&#x200B;(으)로 가져올 차례입니다. 방법은 다음과 같습니다.

1. [!UICONTROL Microsoft Dynamics CRM]에서 **[!UICONTROL Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. [!UICONTROL SETTINGS]에서 **[!UICONTROL Customizations]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-29-14-3a22-3a1.png)

1. **[!UICONTROL Solutions]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >계속 진행하기 전에 Marketo 솔루션을 이미 설치 및 구성했어야 합니다.

1. **[!UICONTROL Import]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 **[!UICONTROL Browse]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. 위에서 다운로드한 솔루션을 찾아 선택합니다.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. 솔루션이 업로드됩니다. 원한다면 패키지 콘텐츠를 볼 수 있습니다. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. 상자를 선택한 상태로 두고 **[!UICONTROL Import]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 언제든지 로그 파일을 다운로드한 다음 **[!UICONTROL Close]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 멋지다! 이제 해결 방법을 확인해야 합니다. 없는 경우 화면을 새로 고칩니다.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Marketo 및 Sales Insight 연결 {#connect-marketo-and-sales-insight}

Marketo 인스턴스를 [!DNL Sales Insight]의 [!DNL Dynamics]에 연결합니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>관리자 권한이 필요합니다.

1. Marketo에 로그인한 다음 **[!UICONTROL Admin]** 섹션으로 이동합니다.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. [!UICONTROL Sales Insight] 섹션 아래에서 **[!UICONTROL Edit API Configuration]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 이후 단계에서 사용할 **[!UICONTROL Marketo Host]**, **[!UICONTROL API URL]** 및 **[!UICONTROL API User Id]**&#x200B;을(를) 복사합니다. 원하는 API 비밀 키를 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!CAUTION]
   >
   >API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >*이(가) 작동하려면*&#x200B;리드 및 연락처[!DNL Sales Insight]에 대해 다음 필드를 Marketo과 동기화해야 합니다.
   >
   >* 우선순위
   >* 긴급도
   >* 상대 스코어
   >
   >이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 [이 절차](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md)를 수행하십시오.

1. [!DNL Microsoft Dynamics]&#x200B;(으)로 돌아가서 **[!UICONTROL Settings]**(으)로 이동합니다.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. **[!UICONTROL Settings]**&#x200B;에서 **[!UICONTROL Marketo API Config]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. **[!UICONTROL New]**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. 이전에 Marketo에서 가져온 정보를 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## 사용자 액세스 설정 {#set-user-access}

마지막으로, Marketo Sales Insight을 사용하려면 특정 사용자에게 액세스 권한을 부여해야 합니다.

1. **[!UICONTROL Settings]**(으)로 이동합니다.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. **[!UICONTROL Security]**(으)로 이동합니다.

   ![](assets/image2015-4-29-14-3a56-3a33.png)

1. **[!UICONTROL Users]**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. [!DNL Sales Insight]에게 액세스 권한을 부여할 사용자를 선택하고 **[!UICONTROL Manage Roles]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. [!DNL Marketo Sales Insight] 역할을 선택하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 넌 다 끝내야 해! 마지막으로 테스트하려면 [!DNL Dynamics]에 액세스할 수 있는 사용자로 [!DNL Marketo Sales Insight]에 로그인한 다음 잠재 고객 또는 연락처를 확인하십시오.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

이제 영업 팀에 대한 [!DNL Marketo Sales Insight]의 기능을 잠금 해제했습니다.

>[!MORELIKETHIS]
>
>[잠재 고객/연락처 레코드에 대한 별과 불꽃놀이 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

---
unique-page-id: 3571735
description: Microsoft Dynamics 2011 - Marketo 설명서 - 제품 설명서에서 Marketo Sales Insight 설치 및 구성
title: Microsoft Dynamics 2011에서 Marketo Sales Insight 설치 및 구성
exl-id: 40622dcc-7129-4392-95dc-ca829c15c3a6
feature: Marketo Sales Insights
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 2%

---

# [!DNL Marketo Sales Insight]에서 [!DNL Microsoft Dynamics 2011] 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

[!DNL Marketo Sales Insight]은(는) 영업팀에게 훌륭한 도구입니다. 다음은 [!DNL Microsoft Dynamics 2011] 온-프레미스에서 설치 및 구성 방법에 대한 단계별 지침입니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>[ CRM 버전에 대해 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md)올바른 솔루션을 다운로드하십시오[!DNL Microsoft Dynamics].

## 솔루션 가져오기 {#import-solution}

1. [!DNL Microsoft Dynamics] CRM에 로그인합니다. 왼쪽 아래 메뉴에서 **[!UICONTROL Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. 트리에서 **[!UICONTROL Solutions]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. **가져오기**( ![](assets/image2015-5-4-10-3a45-3a44.png))를 클릭합니다.

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >계속 진행하기 전에 이미 Marketo 솔루션을 [설치 및 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md)해야 합니다.

1. **[!UICONTROL Browse]**&#x200B;을(를) 클릭합니다. [!DNL Marketo Sales Insight]다운로드한[에서 ](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) 솔루션을 선택합니다. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. 솔루션의 세부 정보를 확인하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. SDK 메시지 옵션이 선택되어 있는지 확인합니다. **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. 이제 가져오기가 완료될 때까지 기다립니다.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. **[!UICONTROL Close]**&#x200B;을(를) 클릭합니다.

   ![](assets/crmhand.png)

1. [!DNL Marketo Sales Insight]이(가) 이제 솔루션 목록에 표시됩니다. 예이!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. [!DNL Marketo Sales Insight]을(를) 선택하고 **모든 사용자 지정 게시**( ![](assets/image2015-5-4-11-3a7-3a8.png))를 클릭합니다.

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Marketo 및 Sales Insight 연결  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketo에 로그인하고 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. **[!UICONTROL Sales Insight]** 섹션 아래에서 **[!UICONTROL Edit API Configuration]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 이후 단계에서 사용할 **[!UICONTROL Marketo Host]**, **[!UICONTROL API URL]** 및 **[!UICONTROL API User Id]**&#x200B;을(를) 복사합니다. 선택한 **[!UICONTROL API Secret Key]**&#x200B;을(를) 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   >[!CAUTION]
   >
   >API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >Sales Insight이 작동하려면 _리드 및 연락처_&#x200B;를 위해 다음 필드를 Marketo과 동기화해야 합니다.
   >
   >* 우선순위
   >* 긴급도
   >* 상대 스코어
   >
   >이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 [이 절차](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md)를 수행하십시오.

1. Dynamics로 돌아가서 **[!UICONTROL Settings]**&#x200B;을(를) 선택합니다.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. 트리에서 **[!UICONTROL Marketo API Config]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. **[!UICONTROL Default Configuration]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. 이전에 Marketo에서 가져온 정보를 입력하십시오.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a28-3a13.png)

## 사용자 액세스 설정 {#set-user-access}

특정 사용자에게 [!DNL Sales Insight]에 대한 액세스 권한을 부여할 사용자 역할을 설정하십시오.

1. **[!UICONTROL Settings]**&#x200B;를 선택합니다.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. 트리에서 **[!UICONTROL Administration]**&#x200B;을(를) 선택하십시오.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. **[!UICONTROL Users]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. 액세스 권한을 부여할 사용자를 선택하고 **[!UICONTROL Manage Roles]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. **[!UICONTROL Marketo Sales Insight]** 역할을 선택하고 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   다 됐습니다! 이제 액세스 권한이 있는 모든 사용자가 잠재 고객/연락처 세부 정보 보기에서 판매 insight 섹션을 볼 수 있습니다.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   축하합니다. 이제 [!DNL Marketo Sales Insight]의 기능을 해제했습니다.

>[!MORELIKETHIS]
>
>[잠재 고객/연락처 레코드에 대한 별과 불꽃놀이 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)

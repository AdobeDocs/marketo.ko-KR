---
unique-page-id: 12983390
description: Azure에 앱을 등록하여 클라이언트 ID/앱 ID 획득 - Marketo 문서 - 제품 설명서
title: Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 얻습니다.
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '294'
ht-degree: 0%

---

# Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 얻습니다. {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory는 온-프레미스 디렉터리를 클라우드로 확장하여 온-프레미스 ADFS 인증을 사용하는 [!DNL MS Dynamics 365] CRM을 지원합니다.

## 새 앱 등록 {#registering-a-new-app}

1. 관리자 권한이 있는 계정을 사용하여 Microsoft Azure 관리 포털에 [로그인](https://login.microsoftonline.com/){target="_blank"}합니다. 왼쪽 탐색 창에서 **[!UICONTROL Admin]** 항목을 확장하고 **[!UICONTROL Azure AD]**&#x200B;을(를) 선택하여 Office 365 관리 센터를 통해 Microsoft Azure 포털에 액세스할 수도 있습니다.

   >[!CAUTION]
   >
   >앱을 등록할 계정과 동일한 [!DNL Office 365] 구독의 계정을 사용해야 합니다.

   >[!NOTE]
   >
   >Azure 계정이 없는 경우 [등록](https://azure.microsoft.com/en-us/free/){target="_blank"}할 수 있습니다. 자세한 내용은 Microsoft 설명서를 참조하거나 Microsoft 담당자에게 문의하십시오. Azure 계정을 만든 후에는 아래 설명된 절차를 사용하여 하나 이상의 앱을 등록할 수 있습니다.
   >
   >
   >Azure 계정이 있지만 Azure 구독에서 [!DNL Office 365]의 [!DNL Microsoft Dynamics 365] 구독을 사용할 수 없는 경우 [다음 지침](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription){target="_blank"}에 따라 두 계정을 연결하세요.

1. 왼쪽 탐색 창에서 **[!UICONTROL Azure Active Directory]**&#x200B;을(를) 찾아 클릭합니다.

   ![](assets/two.png)

1. [!UICONTROL Manage]에서 **[!UICONTROL App registrations]**&#x200B;을(를) 클릭합니다.

   ![](assets/three.png)

1. 페이지 맨 위에서 **[!UICONTROL New registration]**&#x200B;을(를) 클릭합니다.

   ![](assets/four.png)

1. 앱 이름을 입력하고 적용 가능한 계정 유형을 선택한 다음 리디렉션 URL을 입력합니다. 그런 다음 페이지 하단의 **[!UICONTROL Register]**&#x200B;을(를) 클릭합니다.

   ![](assets/five.png)

1. 이제 앱이 **[!UICONTROL App registrations]** 탭에 표시됩니다.

   ![](assets/six.png)

## 앱 권한 구성 {#configuring-app-permissions}

1. Active Directory의 **[!UICONTROL App registrations]** 탭에서 권한을 구성할 앱을 클릭합니다.

   ![](assets/seven.png)

1. [!UICONTROL Manage]에서 **[!UICONTROL API permissions]**&#x200B;을(를) 클릭합니다.

   ![](assets/eight.png)

1. **[!UICONTROL Add a permission]** 단추를 클릭합니다.

   ![](assets/nine.png)

1. **[!UICONTROL Dynamics CRM]**&#x200B;을(를) 선택하십시오.

   ![](assets/ten.png)

1. **[!UICONTROL Access Common Data Service as organization users]** 상자를 선택한 다음 **[!UICONTROL Add permissions].**&#x200B;을(를) 클릭합니다

   ![](assets/eleven.png)

1. 권한이 성공적으로 추가되면 10초 이상 기다리십시오.

   ![](assets/twelve.png)

1. **[!UICONTROL Grant admin consent]** 단추를 클릭합니다.

   ![](assets/thirteen.png)

1. **[!UICONTROL Yes]**&#x200B;을(를) 클릭하여 확인합니다.

   ![](assets/fourteen.png)

   넌 끝났어!

   ![](assets/fifteen.png)

---
unique-page-id: 12983390
description: Azure에 앱을 등록하여 클라이언트 ID/앱 ID 획득 - Marketo 문서 - 제품 설명서
title: Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 얻습니다.
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
feature: Microsoft Dynamics
source-git-commit: 821d69736b1cbeac0c80718c58a7a3c471387545
workflow-type: tm+mt
source-wordcount: '346'
ht-degree: 0%

---

# Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 얻습니다. {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory는 온-프레미스 디렉터리를 클라우드로 확장하여 온-프레미스 ADFS 인증을 사용하는 MS Dynamics 365 CRM을 지원합니다.

## 새 앱 등록 {#registering-a-new-app}

1. [로그인](https://login.microsoftonline.com/){target="_blank"} 관리자 권한이 있는 계정을 사용하여 Microsoft Azure 관리 포털에 연결합니다. 또한 Office 365 관리 센터를 통해 다음을 확장하여 Microsoft Azure 포털에 액세스할 수 있습니다. **[!UICONTROL 관리자]** 왼쪽 탐색 창의 항목 및 선택 **[!UICONTROL Azure AD]**.

   >[!CAUTION]
   >
   >앱을 등록할 계정과 동일한 Office 365 구독의 계정을 사용해야 합니다.

   >[!NOTE]
   >
   >Azure 계정이 없는 경우 다음을 수행할 수 있습니다. [등록](https://azure.microsoft.com/en-us/free/){target="_blank"} 한 명이요. 자세한 내용은 Microsoft 설명서를 참조하거나 Microsoft 담당자에게 문의하십시오. Azure 계정을 만든 후에는 아래 설명된 절차를 사용하여 하나 이상의 앱을 등록할 수 있습니다.
   >
   >
   >Azure 계정이 있지만 Microsoft Dynamics 365를 사용하는 Office 365 구독을 Azure 구독에서 사용할 수 없는 경우 다음을 참조하세요. [이 지침](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription){target="_blank"} 두 계정을 연결합니다.

1. 찾기 및 클릭 **[!UICONTROL Azure Active Directory]** 왼쪽 탐색 창에서 을 클릭합니다.

   ![](assets/two.png)

1. 관리에서 **[!UICONTROL 앱 등록]**.

   ![](assets/three.png)

1. 클릭 **[!UICONTROL 새 등록]** 을 클릭합니다.

   ![](assets/four.png)

1. 앱 이름을 입력하고 적용 가능한 계정 유형을 선택한 다음 리디렉션 URL을 입력합니다. 그런 다음 **[!UICONTROL 등록]** 페이지 하단에 있습니다.

   ![](assets/five.png)

1. 이제 앱이에 표시됩니다. **[!UICONTROL 앱 등록]** 탭.

   ![](assets/six.png)

## 앱 권한 구성 {#configuring-app-permissions}

1. 아래 **[!UICONTROL 앱 등록]** active Directory에서 권한을 구성할 앱을 클릭합니다.

   ![](assets/seven.png)

1. 관리에서 **[!UICONTROL API 권한]**.

   ![](assets/eight.png)

1. 다음을 클릭합니다. **[!UICONTROL 권한 추가]** 단추를 클릭합니다.

   ![](assets/nine.png)

1. 선택 **[!UICONTROL Dynamics CRM]**.

   ![](assets/ten.png)

1. 다음 확인: **[!UICONTROL 조직 사용자로 Common Data Service 액세스]** 상자를 클릭한 다음 **[!UICONTROL 권한 추가]**.

   ![](assets/eleven.png)

1. 권한이 성공적으로 추가되면 10초 이상 기다리십시오.

   ![](assets/twelve.png)

1. 다음을 클릭합니다. **[!UICONTROL 관리자 동의 부여]** 단추를 클릭합니다.

   ![](assets/thirteen.png)

1. 클릭 **[!UICONTROL 예]** 확인할 수 있습니다.

   ![](assets/fourteen.png)

   넌 끝났어!

   ![](assets/fifteen.png)

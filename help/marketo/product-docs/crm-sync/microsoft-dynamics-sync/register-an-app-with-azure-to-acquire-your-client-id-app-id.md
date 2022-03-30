---
unique-page-id: 12983390
description: Azure에 앱을 등록하여 클라이언트 ID/앱 ID 획득 - Marketo 문서 - 제품 설명서
title: Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 확보하십시오
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
source-git-commit: 6ad418c8f4056b9a2fb31b0ac995692f0c618795
workflow-type: tm+mt
source-wordcount: '349'
ht-degree: 0%

---

# Azure에 앱을 등록하여 클라이언트 ID/앱 ID를 확보하십시오 {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory는 온-프레미스 디렉터리를 클라우드로 확장하여 온-프레미스 ADFS 인증을 통해 MS Dynamics 365 CRM에 대한 지원을 제공합니다.

## 새 앱 등록 {#registering-a-new-app}

1. [로그인](https://azure.microsoft.com/en-us/account/) 관리자 권한이 있는 계정을 사용하여 Microsoft Azure 관리 포털로 이동합니다. Office 365 관리 센터를 통해 Office Azure 포털에서 **관리** 왼쪽 탐색 창의 항목과 선택 **Azure AD**.

   >[!CAUTION]
   >
   >앱을 등록하려는 계정과 동일한 Office 365 구독의 계정을 사용해야 합니다.

   >[!NOTE]
   >
   >Azure 계정이 없는 경우 다음 작업을 수행할 수 있습니다 [등록](https://azure.microsoft.com/en-us/free/) 1명. 자세한 내용은 Microsoft 설명서를 참조하거나 Microsoft 담당자에게 문의하십시오. Azure 계정을 만든 후에는 아래 요약된 절차를 사용하여 하나 이상의 앱을 등록할 수 있습니다.
   >
   >
   >Azure 계정이 있지만 Microsoft Dynamics 365의 Office 365 구독을 Azure 구독에서 사용할 수 없는 경우 다음을 수행하십시오 [이러한 지침은](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription) 두 계정을 연관시키려면

1. 찾기 및 클릭 **Azure Active Directory** 왼쪽 탐색 창에서 클릭합니다.

   ![](assets/two.png)

1. 관리에서 **앱 등록**.

   ![](assets/three.png)

1. 클릭 **새 등록** 를 클릭합니다.

   ![](assets/four.png)

1. 앱의 이름을 입력하고 적용 가능한 계정 유형을 선택한 다음 리디렉션 URL을 입력합니다. 그런 다음 **등록** 를 클릭합니다.

   ![](assets/five.png)

1. 이제 앱이 **앱 등록** 탭.

   ![](assets/six.png)

## 앱 권한 구성 {#configuring-app-permissions}

1. 아래에 **앱 등록** 탭에서 권한을 구성할 앱을 클릭합니다.

   ![](assets/seven.png)

1. 관리에서 **API 권한**.

   ![](assets/eight.png)

1. 을(를) 클릭합니다. **권한 추가** 버튼을 클릭합니다.

   ![](assets/nine.png)

1. 선택 **Dynamics CRM**.

   ![](assets/ten.png)

1. 을(를) 확인합니다. **조직 사용자로 일반 데이터 서비스에 ****** 상자를 클릭한 다음 **권한 추가.**

   ![](assets/eleven.png)

1. 권한이 성공적으로 추가되면 10초 이상 기다립니다.

   ![](assets/twelve.png)

1. 을(를) 클릭합니다. **관리자 동의 부여** 버튼을 클릭합니다.

   ![](assets/thirteen.png)

1. 클릭 **예** 확인합니다.

   ![](assets/fourteen.png)

   넌 끝났어!

   ![](assets/fifteen.png)

---
unique-page-id: 12983390
description: Azure에 앱을 등록하여 클라이언트 ID/앱 ID - Marketing Docs - 제품 설명서
title: Azure에 앱을 등록하여 클라이언트 ID/앱 ID 받기
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '346'
ht-degree: 0%

---


# Azure에 앱을 등록하여 클라이언트 ID/앱 ID 받기 {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory는 온-프레미스 디렉터리를 클라우드로 확장하여 온-프레미스 ADFS 인증을 통해 MS Dynamics 365 CRM에 대한 지원을 제공합니다.

## 새 앱 등록 {#registering-a-new-app}

1. [관리자 권한이](http://manage.windowsazure.com/) 있는 계정을 사용하여 Microsoft Azure 관리 포털에 로그인합니다. 왼쪽 탐색 창에서 **관리** 항목을 확장하고 **Azure AD를 선택하여 Office 365 관리 센터를 통해 Microsoft Azure 포털에 액세스할 수도 있습니다**.

   >[!CAUTION]
   >
   >앱을 등록하려는 계정과 동일한 Office 365 구독의 계정을 사용해야 합니다.

   >[!NOTE]
   >
   >Azure 계정이 없는 경우 [등록할](https://azure.microsoft.com/en-us/free/) 수 있습니다. 자세한 내용은 Microsoft 설명서를 참조하거나 Microsoft 담당자에게 문의하십시오. Azure 계정을 만든 후에는 아래 설명된 절차를 사용하여 하나 이상의 앱을 등록할 수 있습니다.
   >
   >
   >Azure 계정이 있지만 Microsoft Dynamics 365와의 Office 365 구독을 Azure 구독에서 사용할 수 없는 경우 [다음 지침에 따라 두 계정을 연결합니다](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription) .

1. 왼쪽 탐색 창에서 **Azure Active** Directory를 찾아 클릭합니다.

   ![](assets/two.png)

1. 관리에서 **앱 등록을 클릭합니다**.

   ![](assets/three.png)

1. 페이지 맨 위에서 **새 등록 **을 클릭합니다.

   ![](assets/four.png)

1. 앱 이름을 입력하고 해당 계정 유형을 선택한 다음 리디렉션 URL을 입력합니다. 그런 다음 **페이지** 아래쪽에 있는 등록을 클릭합니다.

   ![](assets/five.png)

1. 이제 **앱 등록** 탭에 앱이 표시됩니다.

   ![](assets/six.png)

## 앱 권한 구성 {#configuring-app-permissions}

1. Active Directory의 **앱 등록** 탭에서 권한을 구성할 앱을 클릭합니다.

   ![](assets/seven.png)

1. 관리에서 **API 권한을 클릭합니다**.

   ![](assets/eight.png)

1. 권한 **추가** 단추를 클릭합니다.

   ![](assets/nine.png)

1. Dynamics **CRM을 선택합니다**.

   ![](assets/ten.png)

1. 일반 **데이터 서비스에 조직 사용자로 액세스***** 상자를 선택한 다음 권한 **추가를 클릭합니다.**

   ![](assets/eleven.png)

1. 권한이 추가되면 최소 10초 동안 기다립니다.

   ![](assets/twelve.png)

1. 관리자 **동의 부여** 단추를 클릭합니다.

   ![](assets/thirteen.png)

1. 예를 **클릭하여** 확인합니다.

   ![](assets/fourteen.png)

   이제 모든 작업이 끝났습니다.

   ![](assets/fifteen.png)


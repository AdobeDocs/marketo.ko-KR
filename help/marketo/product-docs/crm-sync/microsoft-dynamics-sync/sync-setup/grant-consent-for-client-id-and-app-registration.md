---
description: 클라이언트 ID 및 앱 등록에 대한 동의 부여 - Marketo 문서 - 제품 설명서
title: 클라이언트 ID 및 앱 등록에 대한 동의 부여
exl-id: d0c851d7-24a1-4b17-9daa-f0ceed39d040
source-git-commit: 8b4d86f2dd5f19abb56451403cd2638b1a852d79
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# 클라이언트 ID 및 앱 등록에 대한 동의 부여 {#grant-consent-for-client-id-and-app-registration}

## 동기화 사용자에 대한 위임된 사용자 권한 부여 {#grant-delegated-user-permissions-for-the-sync-user}

1. 아래 텍스트를 붙여넣고 client_id, redirect_uri 및 stae 값을 대체하여 인증을 위한 URI(Uniform Resource Identifier)를 만들려면 클린 텍스트 프로그램(Windows용 메모장, Mac용 텍스트 편집)을 사용합니다.

   ```
   https://login.microsoftonline.com/common/oauth2/authorize?
   client_id='xxxxxx-xxxx-xxxx-xxxx-xxxxxxxx'
   &response_type='code'
   &redirect_uri='https://www.<ourdomain>.com'
   &response_mode='query'
   &state='SOME_UNIQUE_UID'
   client_id value should be the client_id generated in App Registration process
   redirect_uri value should be same as value entered at the time of App registration-> Redirect URIs
   state value can be any ID (e.g.,12345)
   ```

   <table> 
    <colgroup> 
     <col> 
     <col> 
    </colgroup> 
    <tbody> 
     <tr> 
      <td><strong>client_id 값</strong></td> 
      <td>는 앱 등록 프로세스에서 생성된 client_id여야 합니다</td> 
     </tr> 
     <tr> 
      <td><strong>redirect_uri 값</strong></td> 
      <td>는 앱 등록 &gt; 리디렉션 URI 시 입력한 값과 동일해야 합니다.</td> 
     </tr> 
     <tr> 
      <td><strong>상태 값</strong></td> 
      <td>모든 ID(예: 12345)일 수 있습니다</td> 
     </tr> 
    </tbody> 
   </table>

   최종 URL은 다음과 같이 표시되어야 합니다. `https://login.microsoftonline.com/common/oauth2/authorize?client_id=xxxxxx-xxxx-xxxx-xxxx-xxxxxxxx&response_type=code&redirect_uri=https://www.marketo.com&response_mode=query&state=12345`

1. 브라우저에서 만든 URI를 엽니다.

   ![](assets/grant-consent-for-client-id-app-registration-1.png)

1. 권한을 부여하는 동기화 사용자로 로그인합니다.

   ![](assets/grant-consent-for-client-id-app-registration-2.png)

   >[!NOTE]
   >
   >다른 탭에서 관리자로 Azure에 이미 로그인되어 있는 경우 다른 브라우저나 Incognito 모드를 사용하여 동기화 사용자로 로그인해야 합니다.

1. 클릭 **수락**.

   ![](assets/grant-consent-for-client-id-app-registration-3.png)

## 모든 사용자에 대한 동의 부여 {#grant-consent-for-all-users}

관리자는 임차인에 있는 모든 사용자를 대신하여 애플리케이션의 위임된 권한에 동의할 수도 있습니다. 관리자 동의는 테넌트의 모든 사용자에 대해 동의 대화 상자가 표시되지 않도록 하며 관리자 역할을 가진 사용자가 Azure 포털에서 수행할 수 있습니다. 어떤 관리자 역할을 수행할 수 있는지 알아봅니다. [여기에서 위임된 권한에 대한 동의](https://docs.microsoft.com/en-us/azure/active-directory/roles/permissions-reference).

1. Azure 포털에서 애플리케이션 홈페이지로 이동합니다.

1. 관리에서 **API 권한**.

   ![](assets/grant-consent-for-client-id-app-registration-4.png)

1. 을(를) 클릭합니다. **관리자 동의 부여** (임차인) 단추.

   ![](assets/grant-consent-for-client-id-app-registration-5.png)

1. 클릭 **예** 확인합니다.

   ![](assets/grant-consent-for-client-id-app-registration-6.png)

>[!MORELIKETHIS]
>
>[On-prem용 Microsoft Dynamics CRM 앱 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/set-up-oauth-authentication-for-dynamics/set-up-microsoft-dynamics-crm-app-for-on-prem.md)

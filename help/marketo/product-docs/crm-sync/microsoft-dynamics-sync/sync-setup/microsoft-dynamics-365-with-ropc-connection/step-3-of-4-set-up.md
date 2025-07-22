---
description: 3단계/4단계 - MS [!DNL Dynamics]  - Marketo 문서 - 제품 설명서에서 클라이언트 앱 설정
title: 3단계/4단계 - MS [!DNL Dynamics]에서 클라이언트 앱 설정
exl-id: e7897174-3303-4c3b-8832-3e10f34fca96
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '296'
ht-degree: 0%

---

# 3단계/4단계: MS [!DNL Dynamics]에서 클라이언트 앱 설정 {#step-3-of-4-set-up-client-app-ms-dynamics-ropc}

>[!PREREQUISITES]
>
>* [4단계 중 1단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설치](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md){target="_blank"}
>* [2단계/4단계: 리소스 소유자 암호 제어 연결을 사용하여 Marketo 솔루션 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}

1. 이 [Microsoft 문서](https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory#create-an-application-registration){target="_blank"}(으)로 이동합니다.

1. 모든 단계를 따르십시오. 3단계의 경우 관련 응용 프로그램 이름(예: &quot;[!DNL Marketo Integration]&quot;)을 입력하십시오. 지원되는 계정 유형에서 이 조직 디렉터리에서만 계정을 선택합니다.

1. 애플리케이션 ID(ClientId)를 기록합니다. 나중에 Marketo에서 입력해야 합니다.

1. [이 문서](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/grant-consent-for-client-id-and-app-registration.md){target="_blank"}의 단계에 따라 관리자 동의를 부여합니다.

1. **[!UICONTROL Certificates & secrets]**&#x200B;을(를) 클릭하여 관리 센터에서 클라이언트 암호를 생성합니다.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-1.png)

1. **[!UICONTROL New client secret]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-2.png)

1. 클라이언트 암호 설명을 추가하고 **[!UICONTROL Add]**&#x200B;을(를) 클릭합니다.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-3.png)

   >[!CAUTION]
   >
   >클라이언트 암호 값(아래 스크린샷에 표시됨)은 나중에 필요하므로 기록해 두십시오. 한 번만 표시되며 다시 검색할 수 없습니다.

   ![](assets/step-3-of-4-set-up-client-app-ms-dynamics-ropc-4.png)

## [!DNL Azure AD]이(가) [!DNL AD FS On-prem]&#x200B;(으)로 연결됨 {#azure-ad-federated-with-ad-fs-on-prem}

[!DNL Azure] AD를 [!DNL ADFS Onprem]&#x200B;(으)로 페더레이션하려면 특정 응용 프로그램에 대한 홈 영역 검색 정책을 만들어야 합니다. 이 정책을 사용하면 [!DNL Azure] AD에서 인증 요청을 페더레이션 서비스에 리디렉션합니다. 이에 대해 [!DNL AD Connect]에서 암호 해시 동기화를 사용하도록 설정해야 합니다. 자세한 내용은 [[!DNL OAuth] 함께 [!DNL ROPC]](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth-ropc) 및 [응용 프로그램에 대한 hrd 정책 설정](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/configure-authentication-for-federated-users-portal#example-set-an-hrd-policy-for-an-application)을 참조하세요.

추가 참조 [이(가) 여기에 있습니다](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-all-sign-ins#:~:text=Interactive%20user%20sign%2Dins%20are,as%20the%20Microsoft%20Authenticator%20app.&text=이%20report%20also%20includes%20federated, are%20federated%20to%20Azure%20AD.){target="_blank"}.

## 4단계로 진행하기 전에 {#before-proceeding-to-step-4}

* 동기화하는 레코드 수를 제한하려면 [사용자 지정 동기화 필터를 설정](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md)하세요.
* [유효성 검사 [!DNL Microsoft Dynamics] 동기화](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) 프로세스를 실행합니다. 초기 설정이 올바르게 수행되었는지 확인합니다.
* [!DNL Microsoft Dynamics] CRM의 Marketo 동기화 사용자에 로그인합니다.

>[!MORELIKETHIS]
>
>* [4단계 중 4단계: 리소스 소유자 암호 제어 연결과 Marketo 솔루션 연결](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-4-of-4-connect.md){target="_blank"}
